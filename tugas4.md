coding
```c++
#include <iostream>
#include <vector>

using namespace std;

// Fungsi untuk menjumlahkan dua matriks
vector<vector<int>> tambahMatriks(const vector<vector<int>>& A, const vector<vector<int>>& B) {
    int m = A.size();
    int n = A[0].size();
    vector<vector<int>> C(m, vector<int>(n, 0));

    for (int i = 0; i < m; ++i) {
        for (int j = 0; j < n; ++j) {
            C[i][j] = A[i][j] + B[i][j];
        }
    }

    return C;
}

int main() {
    // Matriks A
    vector<vector<int>> A = {{1, 2}, {3, 4}};

    // Matriks B
    vector<vector<int>> B = {{5, 6}, {7, 8}};

    // Jumlahkan dua matriks
    vector<vector<int>> hasil = tambahMatriks(A, B);

    // Tampilkan hasil
    for (const auto& row : hasil) {
        for (int elem : row) {
            cout << elem << " ";
        }
        cout << endl;
    }

    return 0;
}
```
# capture hasil running
![Screenshot (5)](https://github.com/euisjulianingsih/TugasAlpro/assets/156889234/902e89b4-57e7-4318-ac6e-c36240155dca)


