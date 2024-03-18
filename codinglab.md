# Menghitung luas dan keliling lingkaran

```c++
#include <iostream>

// Deklarasi fungsi
double menghitungluaspersegipanjang(double panjang, double lebar);
double menghitungkelilingpersegipanjang(double panjang, double lebar);

int main() {
    // Meminta pengguna memasukkan panjang, lebar persegi panjang
    double panjang;
    std::cout << "Masukkan panjang persegi panjang: ";
    std::cin >> panjang;

    double lebar;
    std::cout << "Masukkan lebar persegi panjang: ";
    std::cin >> lebar;

    // Memanggil fungsi untuk menghitung luas dan keliling lingkaran
    double luas = menghitungluaspersegipanjang(panjang,lebar);
    double keliling = menghitungkelilingpersegipanjang(panjang,lebar);

    //menampilkan hasil
    std::cout << "luas persegi panjang: "<<luas<<std::endl;
    std::cout << "keliling persegi panjang: "<<keliling<<std::endl;
    
    return 0;
}

// implementasi fungsi menghitung keliling lingkaran
    double menghitungluaspersegipanjang(double panjang, double lebar){
        return panjang*lebar;
    }

// Implementasi fungsi menghitung keliling lingkaran
    double menghitungkelilingpersegipanjang(double panjang, double lebar){
        return 2*(panjang+lebar);
    }
```
# capture hasil running

![Screenshot (1)](https://github.com/euisjulianingsih/TugasAlpro/assets/156889234/97fee5cf-9c77-4238-94be-32becd21cfba)
