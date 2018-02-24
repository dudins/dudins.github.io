## quem sou eu?  
Maria Eduarda,  
IFRN- programação de jogos digitais,  
Natal-RN.

## mapa de influências
![](https://github.com/dudins/dudins.github.io/blob/master/map%20influence.png?raw=true)  

## meus jogos  
[Fit Food](https://mrbtrzmoraes.github.io/FitFood)  
![](https://github.com/dudins/dudins.github.io/blob/master/fitfood.png?raw=true)    
"Fit Food" é um, jogo que trata de um personagem chamado Florisvaldo que está com problemas de saúde devido ao seu peso. Portanto, neste jogo o usuário deve alimentar Florisvaldo apenas com comidas saudáveis.

[BFR](https://thaynanmedeiros.github.io/BFR/)  
![](https://github.com/dudins/dudins.github.io/blob/master/bfr.png?raw=true)    
"Black Friday Run" é um jogo que trata sobre a cultura da black friday. O objetivo é conseguir coletar o máximo de moedas e cupons de descontos para levar as compras.

[Quizz Potengi](https://mrbtrzmoraes.github.io/Quiz1/)  
![](https://github.com/dudins/dudins.github.io/blob/master/potengi.png?raw=true)  
"Quizz Potengi", é um jogo de perguntas e respostas e conhecimento a cerca do rio Potengi
  
## projetos e eventos  
EXPOTEC campus ceará-mirim(2017), expositora do projeto jogos e o conhecimento da cultura budista.  

## extras  
![](https://github.com/dudins/dudins.github.io/blob/master/Coralineoficial1.jpg?raw=true)  
Projeto de design gráfico- cartaz minimalista  

'
#include <stdio.h>//biblioteca de entrada e saida 
#include <stdlib.h> //incluso todos os comandos do sistema 
main (){ //função "int" 
 
	//abertura do jogo 
	printf ("BATALHA NAVAL \n"); 

	//Preparando o argumento 
	printf ("ACERTE O MAIOR NUMERO DE BARCOS \n"); 

	//declarando matrizes 
//começa do 1 
	char inimigos[10][10]={{5, 0, 5, 1, 1, 0, 2, 0, 0, 0}, 
		      { 3, 0, 0, 5, 5, 5, 4, 1, 0, 0}, 
		      { 2, 0, 4, 5, 0, 5, 0, 5, 0, 5}, 
		      { 0, 5, 0, 5, 1, 1, 0, 0, 3, 5}, 
		      { 0, 5, 0, 0, 3, 0, 0, 2, 2, 5}, 
		      { 2, 5, 0, 5, 5, 3, 0, 0, 1, 0}, 
		      { 2, 0, 4, 5, 5, 5, 5, 0, 0, 0}, 
	              { 0, 5, 1, 0, 1, 0, 5, 2, 0, 0}, 
		      { 4, 0, 2, 0, 5, 5, 5, 5, 0, 0}, 
		      { 5, 5, 0, 3, 0, 0, 4, 2, 5, 5}}; 

	//matriz para o tabuleiro 10x10 	 
	char tabuleiro[10][10]; 

	//foi adicionado varios contadores, um para cada barco mais um para o número de tiros 
	int l, c, contx=0, fim=0; 

 //INICIANDO O LAÇO FOR ele informa como sera a matriz 
for(l=1; l<11; l++){ 
	for(c=1; c<11; c++){ tabuleiro[l][c] = '.';  
} printf("\n"); 
} 

while (5>=fim){ // o jogo continua ate terminar as tentativas 

for(l=1; l<11; l++){ 
	for(c=1; c<11; c++){ 
if (tabuleiro [l][c]=='.') { 
	printf("."); } 
else if (tabuleiro [l][c]=='A') { //a dif. if 1x1 if else so 1 
	printf("A"); } 
else if (tabuleiro [l][c]=='N') { 
	printf("N"); } 
else if (tabuleiro [l][c]=='S') { 
	printf("S"); } 
else if (tabuleiro [l][c]=='P') { 
	printf("P"); } 
else if (tabuleiro [l][c]=='H') { 
	printf("H"); } 
else if (tabuleiro [l][c]=='B') { 
	printf("B"); } 
} 
printf("\n"); 
} 


//o usuario informa a linha 
printf("Informe a Linha (1 a 10): "); 
scanf("%d", &l); 
 
// o usuario informa a coluna 
printf("Informe a Coluna (1 a 10): "); 
scanf("%d", &c); 
 printf ("\n"); 

//terceiro teste de verificação da matriz 
if(inimigos[l][c]==0){ 
    tabuleiro [l][c]='A'; 
    printf ("VOCE ATINGIU A AGUA \r\n"); 
    contx=contx+0; 
    printf ("\n"); 
	} 
	else if(inimigos[l][c]==1){ 
    tabuleiro [l][c]= 'S'; 
    printf ("VOCE ACERTOU UM SUBMARINO \r\n"); 
    contx=contx+1; 
    printf ("\n"); 
	} 
	else if(inimigos[l][c]==2){ 
   tabuleiro [l][c]='N'; 
   printf ("VOCE ACERTOU UM NAVIO \r\n"); 
   contx=contx+2; 
   printf ("\n"); 
        } 
	else if(inimigos[l][c]==3){ 
   tabuleiro [l][c]='P'; 
   printf ("VOCE ACERTOU UM PORTA AVIAO\r\n"); 
   contx=contx+3; 
   printf ("\n"); 
        } 
	else if(inimigos[l][c]==4){ 
   tabuleiro [l][c]= 'H'; 
   printf ("VOCE ACERTOU UM HIDRO AVIAO\r\n"); 
   contx=contx+4; 
   printf ("\n"); 
        } 
	else if(inimigos[l][c]==5){ 
   tabuleiro [l][c]= 'B'; 
   printf ("VOCE ACERTOU UMA BOMBA\r\n"); 
   contx=contx-1; 
   printf ("\n"); 
        } 
fim++; 
} 
// PARA INFORMAR A PONTUAÇÃO 
printf ("VOCE TERMINOU O JOGO COM UM TOTAL DE %d PONTOS \r\n", contx); 
}
 '
  
## contatos  
meduardafreire.melf@gmail.com   
@_mdudaf
