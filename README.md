# Soma-em-C
Exercício da faculdade
#include <stdio.h>
int main (){
    int num1, num2;
    int soma,subtracao,mutiplicacao,divisao;
    
    printf("***Calculadora modelo1***\n");
    printf("digite o primeiro número: ");
    scanf("%d", & num1);
    
    printf("digite o segundo número: ");
    scanf("%d", & num2);
    
    soma= num1 + num2;
    subtracao= num1 - num2;
    mutiplicacao= num1 * num2;
    divisao= num1 / num2;
    
    printf("num1: %d\n", num1);
    printf("num2: %d\n", num2);
    printf("soma: %d\n", soma);
    printf("subtracao entre num1 e num2 %d\n", subtracao);
    printf("mutiplicacao: %d\n",mutiplicacao);
    printf("divisao entre num1 e num2 %d\n", divisao);
    printf("divisao: %d\n", divisao);    
    return 0;
}
