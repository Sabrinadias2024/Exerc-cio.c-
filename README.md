#include <stdio.h>

int main()
{
    printf("Hello World");

    return 0;
}
   
   int main() {
    int mes;

    printf("Digite um numero: ");
    scanf("%d", &mes);

    switch(mes) {
    case 1:
        printf("\nJaneiro\n");
        break;
    case 2:
        printf("\nFevereiro\n");
        break;
    case 3:
        printf("\nMarco\n");
        break;
    case 4:
        printf("\nAbril\n");
        break;
    case 5:
        printf("\nMaio\n");
        break;
    case 6:
        printf("\nJunho\n");
        break;
    case 7:
        printf("\nJulho\n");
        break;
    case 8:
        printf("\nAgosto\n");
        break;
    case 9:
        printf("\nSetembro\n");
        break;
    case 10:
        printf("\nOutubro\n");
        break;
    case 11:
        printf("\nNovembro\n");
        break;
    case 12:
        printf("\nDezembro\n");
        break;
    default:
        printf("\nValor nao corresponde a nenhum mes!\n");
    }
}
