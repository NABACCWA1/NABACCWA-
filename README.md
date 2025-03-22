#include <stdio.h>

int main() {
    int balance = 50000;
    int withdrawal = 20000;

    printf("Initial balance: %d\n", balance);
    
    if (withdrawal <= balance) {
        balance -= withdrawal;
        printf("You have withdrawn: %d\n", withdrawal);
        printf("Remaining balance: %d\n", balance);
    } else {
        printf("Insufficient balance.\n");
    }

    return 0;
}

