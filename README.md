# PAM-Pesquisa_Java
Trabalho de pesquisa sobre Java da disciplina de Programação de Aplicativos Mobile 

## Tipos de Dados do Java

#### Os tipos de dados básicos são tipos primitivos e são divididos da seguinte forma:

 
> boolean - esse tipo só recebe  dois valores true or false;
> numéricos integrais -  são compostos por
- byte
- short
- int
- long
- char
### Apesar da variável do **tipo char** receber apenas um caracter essa variável também recebe valores literais do tipo  **int e unicode**. 
>ponto flutuante - composto  por
-float
-double

## Estruturas Condicionais 

#### Elas servem para controlar quais códigos vão ser executados de acordo com a situaç.

- ### If/Else

#### Usar a sintaxe _if_ serve para definir uma condição, e caso a situação se enquadre nela, será verdadeira e automaticamente as instruções dela irão ser executadas. O _else_ é utilizado para executar instruções quando o _if_ é falso (pois as instruções do _if_ deles são interrompidas).

#### Exemplo:

>     if(x>9){
>             instrução;       
>     } else {
>             instrução;
>     }

- #### Também é possível usar o _if_ e o _else_ de forma encadeada. Por exemplo:

>       if (x>9){
>             instrução;
>       }else if (x<=9) {
>             instrução;
>       } else {
>             instrução;
>       }

- ### Swith/case

#### É uma condição de múltipla escolha, usada para testar as várias condições e determinar qual instruçãos será executada. 
#### A sintaxe dele é:

>     switch (expressão) { 
>        case 1:
>            códigos;
>            break;
>        case 2:
>            códigos;
>            break;
>        default:
>            instrução
>      }

- *Não há valor definido em relação a quantos cases pode adicionar, dessa forma é permitido N valores.*
- *Não pode conter valores de cases iguais.*
- *Cada case deve ter o mesmo tipo de valor que variável;*

### Definições:
- #### switch (expressão): onde é colocado a variável que será a referência das condições que o programa executar;
- #### case: é condição que será comparada com variável, sendo executado se for compatível;
- #### break: quebra opcional;
- #### default: quebra opcional para executar alguma instrução caso nenhuma das condições forem verdadeiras;

## Estruturas de Repetição

#### É uma estrutura que permite executar os mesmos comandos mais de uma vez. Abas é possível definir até quando executar o comando, atráves da variável. Há três tipos de repetição:
- #### *for*:
#### Esse comando define em uma linha de código, a variável de controle, para assim conseguir definir a quantidade de vezes que os comandos serão executados; a expressão que irá validar a variável, e assim partir que os comandos sejam executados ou não; e incremento da variável de controle, que vai definir o quanto a variável será mudada.

### Sintaxe *for*

>     > for (variável de controle, expressão de validação, incremento da variável de controle) {
>    	      //Comandos
>      }

### Exemplo: 

>     for ( int i  =  1; i <= 10; i++){
>       	System.out.orintln( i * ”num”);
>     }

## Referências:

<https://blog.betrybe.com/java/switch-case-java/>
<https://glysns.gitbook.io/java-basico/controle-de-fluxo/estruturas-de-repeticao>
<https://www.treinaweb.com.br/blog/estruturas-condicionais-e-estruturas-de-repeticao-em-java>
<https://blog.grancursosonline.com.br/os-tipos-primitivos-da-linguagem-java/>
<https://www.dio.me/articles/java-tipos-primitivos>









