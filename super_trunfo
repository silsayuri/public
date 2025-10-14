#include <stdio.h>
#include <string.h>

struct Carta {
    char estado;
    char codigo[4];
    char cidade[50];
    int populacao;
    float area;
    float pib;
    int pontos_turisticos;
};

int main() {
    struct Carta carta1, carta2;
    printf("SUPER TRUNFO\n");

    // Leitura da Carta 1
    printf("digitar carta 1:\n");
    printf("Estado (A-H): ");
    scanf(" %c", &carta1.estado);
    printf("codigo (ex:A01): ");
    scanf("%3s", carta1.codigo); 
    printf("nome da cidade: ");
    getchar();
    fgets(carta1.cidade, sizeof(carta1.cidade), stdin);
    carta1.cidade[strcspn(carta1.cidade, "\n")] = 0; 
    printf("populacao: ");
    scanf("%d", &carta1.populacao);
    printf("tamanho da area (km²): ");
    scanf("%f", &carta1.area);
    printf("PIB: ");
    scanf("%f", &carta1.pib);
    printf("Pontos Turisticos: ");
    scanf("%d", &carta1.pontos_turisticos);
    printf("\n");

    // Leitura da Carta 2
    printf("digitar carta 2:\n");
    printf("Estado (A-H): ");
    scanf(" %c", &carta2.estado);
    printf("codigo (ex:B02): ");
    scanf("%3s", carta2.codigo);
    printf("nome da cidade: ");
    getchar();
    fgets(carta2.cidade, sizeof(carta2.cidade), stdin);
    carta2.cidade[strcspn(carta2.cidade, "\n")] = 0;
    printf("populacao: ");
    scanf("%d", &carta2.populacao);
    printf("area (km²): ");
    scanf("%f", &carta2.area);
    printf("PIB: ");
    scanf("%f", &carta2.pib);
    printf("Pontos Turisticos: ");
    scanf("%d", &carta2.pontos_turisticos);
    printf("\n");

    // Comparar atributos - ex area
    if (carta1.area > carta2.area) {
        printf("carta1 tem área maior\n");
    } else if (carta1.area < carta2.area) {
        printf("carta2 tem área maior\n");
    } else {
        printf("As cartas têm área igual\n");
    }

    
    return 0;
}
