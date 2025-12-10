#include <stdio.h>
#include <math.h>

int main() {
    const float PI = 3.14;
    float S, R, D, L;
    
    // Ввод площади круга
    printf("Введите площадь круга S: ");
    scanf("%f", &S);
    
    // Вычисление радиуса из площади
    R = sqrt(S / PI);
    
    // Вычисление диаметра
    D = 2 * R;
    
    // Вычисление длины окружности
    L = 2 * PI * R;
    
    // Вывод результатов
    printf("\nРезультаты:\n");
    printf("Радиус круга: %.2f\n", R);
    printf("Диаметр круга D: %.2f\n", D);
    printf("Длина окружности L: %.2f\n", L);
    
    return 0;
}
