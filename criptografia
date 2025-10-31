#include <stdio.h>
#include <string.h>

    int main() {
    char alfa[26] = { 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z' };
    char cifra[26];
    int shift = 0;
    char palavra[15];  
    int i;
    int j = 0;
    
    printf("digite a palavra: "); 
        scanf("%s", &palavra); 
        
    printf("digite o shift: "); 
        scanf("%d", &shift); 
    
    for (int i = shift; i < 26; i++) {
    cifra[j] = alfa[i];
    j++;
}

    for (i = 0; i < shift; i++) {
    cifra[j] = alfa[i];
    j++;
}

printf("Palavra cifrada: ");
    for (i = 0; i < strlen(palavra); i++) { //strlen retorna para a variavel o tamanho da string.
        char letra = palavra[i];
        
        for (j = 0; j < 26; j++) {
            if (letra == alfa[j]) {
                printf("%c", cifra[j]);
                break;
            }
        }
    }
    printf("\n");

    return 0; 
}
