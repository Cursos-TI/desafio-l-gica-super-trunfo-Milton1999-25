#include <stdio.h>

int main() {
    // Dados da carta 1 - Brasil
    char pais1[] = "Brasil";
    int populacao1 = 214000000;
    float area1 = 8515767;
    float pib1 = 2000000000000.0;
    int pontosTuristicos1 = 20;
    float densidade1 = populacao1 / area1;

    // Dados da carta 2 - Canadá
    char pais2[] = "Canadá";
    int populacao2 = 38000000;
    float area2 = 9984670;
    float pib2 = 1900000000000.0;
    int pontosTuristicos2 = 25;
    float densidade2 = populacao2 / area2;

    int opcao;

    // Menu interativo
    printf("=== SUPER TRUNFO: COMPARAÇÃO DE PAÍSES ===\n");
    printf("Escolha o atributo para comparação:\n");
    printf("1 - População\n");
    printf("2 - Área\n");
    printf("3 - PIB\n");
    printf("4 - Pontos Turísticos\n");
    printf("5 - Densidade Demográfica\n");
    printf("Digite sua opção (1 a 5): ");
    scanf("%d", &opcao);

    printf("\n");

    switch(opcao) {
        case 1:
            printf("Comparação: População\n");
            printf("%s: %d\n", pais1, populacao1);
            printf("%s: %d\n", pais2, populacao2);
            if (populacao1 > populacao2) {
                printf("Resultado: %s venceu!\n", pais1);
            } else if (populacao2 > populacao1) {
                printf("Resultado: %s venceu!\n", pais2);
            } else {
                printf("Resultado: Empate!\n");
            }
            break;

        case 2:
            printf("Comparação: Área\n");
            printf("%s: %.2f km²\n", pais1, area1);
            printf("%s: %.2f km²\n", pais2, area2);
            if (area1 > area2) {
                printf("Resultado: %s venceu!\n", pais1);
            } else if (area2 > area1) {
                printf("Resultado: %s venceu!\n", pais2);
            } else {
                printf("Resultado: Empate!\n");
            }
            break;

        case 3:
            printf("Comparação: PIB\n");
            printf("%s: R$ %.2f\n", pais1, pib1);
            printf("%s: R$ %.2f\n", pais2, pib2);
            if (pib1 > pib2) {
                printf("Resultado: %s venceu!\n", pais1);
            } else if (pib2 > pib1) {
                printf("Resultado: %s venceu!\n", pais2);
            } else {
                printf("Resultado: Empate!\n");
            }
            break;

        case 4:
            printf("Comparação: Pontos Turísticos\n");
            printf("%s: %d\n", pais1, pontosTuristicos1);
            printf("%s: %d\n", pais2, pontosTuristicos2);
            if (pontosTuristicos1 > pontosTuristicos2) {
                printf("Resultado: %s venceu!\n", pais1);
            } else if (pontosTuristicos2 > pontosTuristicos1) {
                printf("Resultado: %s venceu!\n", pais2);
            } else {
                printf("Resultado: Empate!\n");
            }
            break;

        case 5:
            printf("Comparação: Densidade Demográfica\n");
            printf("%s: %.4f hab/km²\n", pais1, densidade1);
            printf("%s: %.4f hab/km²\n", pais2, densidade2);
            if (densidade1 < densidade2) {
                printf("Resultado: %s venceu!\n", pais1);
            } else if (densidade2 < densidade1) {
                printf("Resultado: %s venceu!\n", pais2);
            } else {
                printf("Resultado: Empate!\n");
            }
            break;

        default:
            printf("Opção inválida! Por favor, execute o programa novamente.\n");
    }

    return 0;
}
