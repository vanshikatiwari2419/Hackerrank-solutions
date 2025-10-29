char* twoArrays(int k, int A_count, int* A, int B_count, int* B) {

    for (int i = 0; i < A_count - 1; i++) {
        for (int j = i + 1; j < A_count; j++) {
            if (A[i] > A[j]) {
                int temp = A[i];
                A[i] = A[j];
                A[j] = temp;
            }
        }
    }

    for (int i = 0; i < B_count - 1; i++) {
        for (int j = i + 1; j < B_count; j++) {
            if (B[i] < B[j]) {
                int temp = B[i];
                B[i] = B[j];
                B[j] = temp;
            }
        }
    }

    for (int i = 0; i < A_count; i++) {
        if (A[i] + B[i] < k) {
            static char result[] = "NO";
            return result;
        }
    }

    static char result[] = "YES";
    return result;
}
