# nascimento-
Data em dias mes e ano

#include <stdio.h>
int dias,mes,ano;

int main() {
printf("Digite a quantidade de dias: ");
    scanf("%d",&dias);
    printf("\n********Idade em dia,mes e ano********\n");
ano=dias/365;
mes=(dias % 365)/30;
dias = (dias % 365) % 30;

printf("\n......%d ano(s)\n.......%d mes(es)\n........%d dia(as)",ano,mes,dias);




    return 0;
}
