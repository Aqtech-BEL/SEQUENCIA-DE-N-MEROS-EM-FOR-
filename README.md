

Escreva um programa em C que leia uma sequência de 10 números inteiros fornecidos
pelo usuário e conte quantos desses números são pares. em C


    #include <stdio.h>
    
    int main() {
        int num, contador = 0, i;

   
    for (int i = 1; i <= 10; i++) {
        printf("Digite o %dº número: ", i);
        scanf("%d", &num);

        
        if (num % 2 == 0) {
            contador++;  
        }
    }

   
    printf("Quantidade de números pares: %d\n", contador);

    return 0;
    }
