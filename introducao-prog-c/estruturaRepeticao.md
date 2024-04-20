# Estruturas de Repetição #

## Ementa ##
1. While  - Enquanto
2. Do..while - Repita até
3. For - Para

## Comando while - Enquanto ##

```
int main (){
printf("Hello world!");
return 0;
}
```

* Faça um programa que leia um valor do operador e apresente em ordem crescente esse valor até 100 usando o laço do..while
```
  #include <stdio.h>
int main()
{
    int valor;
    printf("Digite um valor: ");
    scanf("%d", &valor);
    do{
        printf("O valor é %d \n ", valor);
        valor = valor+1;
    } while (valor <= 100);

    return 0;
}
```

## Atividade para ser realizada ##

1. Desenvolva um programa em linguagem c que calcule a soma dos numeros de 0 a 100
2. Desenvolva um programa em linguagem c que calcule a média da soma dos números de 50 a 100
3. Desenvolva um programa em linguagem c que apresente a tabuada do numero 99 (Considere os valor multiplicado de 1 a 10 )
4. Desenvolva um programa em linguagem c que leia um numero do usuário e apresente a sua tabuada (Considere os valor multiplicado de 1 a 10 )
5. Desenvolva um programa em linguagem c que leia um numero do usuário e calcule e apresente o seu fatorial. (O fatorial de um numero é o produto de todos os inteiros positivos menores que esse numero)




