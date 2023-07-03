#include <stdio.h>

int main() {
    int t1, t2, t3;
    float total_time;

    // Введення значень t1, t2, t3
    printf("Введіть значення t1, t2, t3: ");
    scanf("%d %d %d", &t1, &t2, &t3);

    // Обчислення загального часу
    total_time = (float)(t1 + t2 + t3);

    // Виведення результату з округленням до 2 знаків після коми
    printf("Загальний час: %.2f год\n", total_time);

    return 0;
}
