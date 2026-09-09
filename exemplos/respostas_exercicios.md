# Respostas dos exercícios

## Exercício 1 — Soma

```c
# include <stdio.h>

int main() {

    int numero1, numero2, soma;

    scanf("%d %d", \&numero1, \&numero2);

    soma = numero1 + numero2;	

    printf("Soma: %d\\n", soma);

    return 0;

}
```

## Exercício 2 - Par ou ímpar
```c
#include <stdio.h>

int main() {

    int numero;

    scanf("%d", \&numero);

    if (numero % 2 == 0) {

    printf("Par\\n");

    } else {

        printf("Impar\\n");

    }

    return 0;

}
```
## Execício 3 - Contagem
```c
#include <stdio.h>

int main() {

    for (int i = 1; i <= 10; i++) {
    
        printf("%d\\n", i);

    }

    return 0;

}
```
