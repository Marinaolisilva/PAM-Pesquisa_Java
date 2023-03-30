# PAM-Pesquisa_Java
Trabalho de pesquisa sobre Java da disciplina de Programação de Aplicativos Mobile 

## Tipos de Dados do Java

#### Os tipos de dados básicos são divididos nas seguintes categorias:

#### Tipo boolean: esse tipo de dado é armazenar apenas dois valores. Sendo eles true or false.
#### Tipos integrais: 
####- byte: 
, short, int, lomg, char;
#### - Tipos de pontos flutuantes: float, double;

## Estruturas Condicionnais 

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

## Referências:

<https://blog.betrybe.com/java/switch-case-java/>









