#include<stdio.h>

int main(){
    int dia;
    
    printf("Digite um número de 1 a 5: ");
    scanf("%d", &dia);
    
switch (dia) {
    case 1:
        printf("segunda-feira");
        break;
    case 2:
        printf("terça-feira");
        break;
    case 3:
        printf("quarta-feira");
        break;
    case 4:
        printf("quinta-feira");
        break;
    case 5:
        printf("sexta-feira");
        break;
    default:
        printf("Entrada inválida");
    
}

}
