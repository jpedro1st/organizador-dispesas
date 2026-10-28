#include <stdio.h>

#define TAM 10

int main(void) {
    // Array com os valores de 10 despesas pessoais.
    float despesas[TAM] = {
        150.00, 45.90, 320.00, 89.50, 210.75,
        35.00, 500.00, 120.00, 75.25, 180.00
    };

    float temp;
    int i, j;

    printf("====================================\n");
    printf("   ORGANIZADOR DE DESPESAS PESSOAIS\n");
    printf("====================================\n");

    // Exibe as despesas antes da ordenacao.
    printf("\nDespesas antes da ordenacao:\n");

    for (i = 0; i < TAM; i++) {
        printf("Despesa %d: R$ %.2f\n", i + 1, despesas[i]);
    }

    // Bubble Sort em ordem decrescente.
    // O laco externo controla as passagens pelo array.
    for (i = 0; i < TAM - 1; i++) {

        // O laco interno compara elementos adjacentes.
        for (j = 0; j < TAM - 1 - i; j++) {

            // Se o elemento atual for menor que o proximo,
            // os valores sao trocados para ordenar do maior
            // para o menor.
            if (despesas[j] < despesas[j + 1]) {
                temp = despesas[j];
                despesas[j] = despesas[j + 1];
                despesas[j + 1] = temp;
            }
        }
    }

    // Exibe as despesas depois da ordenacao.
    printf("\nDespesas apos a ordenacao:\n");
    printf("Criterio: ordem decrescente "
           "(maior para o menor)\n\n");

    for (i = 0; i < TAM; i++) {
        printf("%d. R$ %.2f\n", i + 1, despesas[i]);
    }

    // Identifica o maior e o menor gasto.
    printf("\nMaior despesa: R$ %.2f\n", despesas[0]);
    printf("Menor despesa: R$ %.2f\n", despesas[TAM - 1]);

    printf("\nOrdenacao concluida com sucesso!\n");

    return 0;
}
