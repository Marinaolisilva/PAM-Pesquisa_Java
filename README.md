# PAM-Pesquisa_Java
Trabalho de pesquisa sobre Java da disciplina de Programação de Aplicativos Mobile 

## Tipos de Dados do Java

#### Os tipos de dados básicos são tipos primitivos e são divididos da seguinte forma:

### Boolean -  recebe apenas dois valores: true or false

### Numéricos integrais - são compostos por:

- byte: pode conter valores negativos ou inteiros e requer 8 bits para  serem implemntedas.
- short: também pode conter valores negativos, positivos ou inteiros, porém utiliza 16 bits par implementar os valores.
- int: armazena valores negativos ou positivos, contendo 32 bits para  ser implementadi.
- long: pode armazenar valores positivos, negativos ou inteiros, tendo 64 bits para ser implementado.
- char: esse tipo armazena caracteres, 16 bit que pode ser textos.

### Apesar da variável do **tipo char** receber apenas um caracter essa variável também recebe valores literais do tipo  **int e unicode**. 

### Ponto flutuanted:
- float: armazena valores de ponto flutuante, com 32 bit de precisãqo única.
- double: armazena números flutuantes de precisão dupla, podendo conter 64 bits.

## Estruturas Condicionais 

#### Elas servem para controlar quais códigos vão ser executados de acordo com a situação.

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

#### - *While* :
####	A estrutura do while é escrita de forma diferente do *For*. Além disso, vale ressaltar que ele primeiro verifica a condição para depois executar o código. Sua estrutura é da seguinte forma:
- #### na 1º em uma linha é definido quanto vale a variável de controle;
- #### na 2º linha e definido a condição que irá validar;

### Sintaxe:

>       int i = 0;
>            while(i<=9){
>                 //comando
>       }

#### - Do while:
####	A única diferença entre ele e o restante, é que ele executa o bloco de comandos primeiro e depois verifica a condição.
### Sintaxe:

>     do {
>     		//comandos
>     } while(condição);
## Propriedades de views do Android

## Referências:

<https://blog.betrybe.com/java/switch-case-java/>
<https://glysns.gitbook.io/java-basico/controle-de-fluxo/estruturas-de-repeticao>
<https://www.treinaweb.com.br/blog/estruturas-condicionais-e-estruturas-de-repeticao-em-java>
<https://blog.grancursosonline.com.br/os-tipos-primitivos-da-linguagem-java/>
<https://www.dio.me/articles/java-tipos-primitivos>
<http://www.universidadejava.com.br/java/java-do-while/>
<http://excript.com/java/estrutura-while-java.html>
<http://fabrica.ms.senac.br/2015/03/tipos-de-dados-em-java/#:~:text=Os%208%20tipos%20primitivos%20de,%C3%A9%20a%20economia%20de%20mem%C3%B3ria.>
<https://www.javatpoint.com/pt/tipo-de-dado-em-java#:~:text=O%20tipo%20de%20dado%20float,de%20n%C3%BAmero%20de%20ponto%20flutuante.>
<https://www.devmedia.com.br/tipos-de-dados-por-valor-e-por-referencia-em-java/25293#:~:text=As%20vari%C3%A1veis%20do%20tipo%20double,como%20literais%20de%20ponto%20flutuante.>










