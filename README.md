#include <stdio.h>

int main() {
    // ===== MOVIMENTO DA TORRE =====
    // A torre se move em linha reta. Vamos simular 5 casas para a direita usando FOR.
    int i; // Variável de controle do loop
    int casasTorre = 5;

    printf("Movimento da Torre:\n");
    for (i = 1; i <= casasTorre; i++) {
        printf("Direita\n");
    }

    printf("\n"); // Linha em branco para separar os movimentos

    // ===== MOVIMENTO DO BISPO =====
    // O bispo se move na diagonal. Vamos simular 5 casas para cima e à direita usando WHILE.
    int j = 1; // Inicializa a variável de controle
    int casasBispo = 5;

    printf("Movimento do Bispo:\n");
    while (j <= casasBispo) {
        printf("Cima Direita\n");
        j++;
    }

    printf("\n"); // Linha em branco para separar os movimentos

    // ===== MOVIMENTO DA RAINHA =====
    // A rainha pode se mover em todas as direções. Vamos simular 8 casas para a esquerda usando DO-WHILE.
    int k = 1; // Inicializa a variável de controle
    int casasRainha = 8;

    printf("Movimento da Rainha:\n");
    do {
        printf("Esquerda\n");
        k++;
    } while (k <= casasRainha);

    return 0;
}
