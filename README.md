#include <stdint.h>

int main() {

    int numero;

    do {

        printf("Digite um numero par para sair do progama");
        scanf("%d", &numero);
        
        if(numero % 2 == 0){
            printf("%d é par!", numero);
        } else {
            printf("%d é impar!", numero);
        }

    } while (numero % 2 != 0);
    
    printf("Voce digitou um numero par, saindo do programa...");
    
    

    return 0;
}
