# supertrunfo.c
#include<stdio.h>

int main() {

//carta 1;
char estado2 = 'B';
char estado = '1';

char codigo2[5]="B02";
char codigo[5]="A01";

char nome[20] ="Rio de Janeiro";
char nome2[20] ="Minas Gerais";

float area = 325.900;
float area2= 225.350;

float pib=73;
float pib2=355;

int populacao = 350.000;
int populacao2 = 550.000;

int pontosturisticos = 15;
int pontosturisticos2 = 20;

float densidade = 0;
float densidade2 = 0;

float pibpercapita = 0;
float pibpercapita2 =0;

densidade = populacao/area;
pib = populacao/pib;
densidade2 = populacao2/area2;
pib2 = populacao2/pib2;

    printf("Cartas super trunfo\n");
    printf("Imprimir carta 1\n");
    printf("Estado: %c\n",estado);

    printf("Nome da cidade: %s\n",nome);
    printf("Codigo: %s\n", codigo);
    printf("Area em KM²: %2.fKM²\n", area);
    printf("pib: %3f bilhoes\n", pib);
    printf("Populacao: %d\n", populacao);
    printf("Pontos turisticos: %d\n", pontosturisticos);
    printf("Densidade populacional: %fkm²\n", densidade);
    printf("PIB per capita: %f mil\n", pibpercapita);
        printf("\n");

        

        printf("Imprimir carta 2\n");
        printf("Estado: %c\n",estado2);

    printf("Nome da cidade: %s\n",nome2);
    printf("Codigo: %s\n", codigo2);
    printf("Area em KM²: %2.fKM²\n", area2);
    printf("pib: %3f bilhoes\n", pib2);
    printf("Populacao: %d\n", populacao2);
    printf("Pontos turisticos: %d\n", pontosturisticos2);
    printf("Densidade populacional: %fkm²\n", densidade2);
    printf("PIB per capita: %f mil\n", pibpercapita2);


    return 0;










}
