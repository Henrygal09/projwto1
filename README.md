Como executar o arquivo Calculadora

1- Para executar esse arquivo é necessario um terminal linux, ou o WSL para o windows.

2- Adicionar o arquivo no diretorio Linux/Ubuntu-24.04/home. usando o explorador de arquivos.

3- Abrir o terminal ou WSL, e executar o comando: "cd /home", para selecionar o diretorio.

4- Agora para executar o arquivo use o comando:"./ Calculadora_Max.sh"

E pronto voce vai executar o script da calculadora.
 
###################################################################################################

Explicação da calculadora em python:

Primeiramente para executar o codigo e necessario ter um programa de linguagem em python e 
executar o arquivo Calculadora_

Sobre o codigo:

Comecei o programa pedindo para o usuario colocar seu nome,com o comando "input" assim criando uma
variavel "nome".

Depois uso o comando "while True:", para ser o ponto de reiniciação do meu codigo caso o usuario queira
realizar outra conta, e tambem serve para que seja possivel o uso do comando "break" caso o usuario não
queira realizar outra conta assim finalizando o programa.

logo abaixo uso o "print" e direcionando o usuario para que ele selecione o sinal da conta listando de
1 a 4 cada sinal[1=+, 2=-, 3=*, 4=/.] , assim criando mais uma variavel do tipo (int) chamada "sinal".

Em baixo coloco um "if", então se o sinal for maior que '4' o programa passará uma mensagem de erro
pedindo para que o usuario use numeros de 1 a 4,usei o "else" para que se o numero que usuario colocar
for entre 1 e 4 ele continua.

Em seguida ja pede ao usuario o primeiro numero da conta,e em seguida o segundo numero da equação com
o "input",assim criando mais duas variaveis do tipo (int) "num1" e "num2".

Abaixo ja coloquei outro "if" e usei a variavel "sinal" para que se "sinal" for igual a '1' realiza-se
a soma do "num1" e "num2" e escreve na tela do usuario usando o seu nome,e o resultado da conta.

Apos gerar o resultado perguntei ao usuario se ele vai querer usar de novo a calculadora ou encerrar o
programa utilizando o "input" para criar uma variavel chamada "repetir" assim se repetir for igual a '1'
ele reinicia a calculadora do apos o comando "while True",e se for igual a  '2' ele encerra o programa
com o comando "break".

Para implementar os outros sinais e necessario repetir os codigos listados a cima somente trocando o "if"
por "elif" e usando variavel "sinal" igual a 2,3 e 4, aplicando "num1" e "num2" -,* e /.

Assim finalizando o código...
