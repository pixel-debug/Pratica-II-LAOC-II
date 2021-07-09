# Pratica II LAOC-II
Prática II implementada na disciplina de Laboratório de Arquitetura e Organização de Computadores II do curso de Engenharia de Computação - CEFET/MG

Check List
=================

<!--ts-->
   * [Operações](#operacoes)
   * [Registradores](#registradores)
   * [Estágios habilitados](#estagios-habilitados)
<!--te-->


Operações
============

LD = carregar valor; <br />
ST = armazenar valor; <br />
MVNZ = move se não for zero; <br />
MV = conteúdo de registrador passa para o outro <br />
MVI = move um imediato para um registrador <br />
ADD = adiciona dois registradores <br />
SUB = subtrai dois registradores <br />
OR = operação lógica <br />
SLT = compara se um registrador é menor que outro <br />
SLL = move bits para esquerda <br />
SRL = move bits para direita <br />

``` cada instrução carrega 4 bits ```

|      Operações      |      Num bits       |
| ------------------- | ------------------- |
|         LD          |        0001         |
|         ST          |        0010         |
|        MVNZ         |        0011         |
|        MV           |        0100         |
|        MVI          |        0101         |
|        ADD          |        0110         |
|        SUB          |        0111         |
|         OR          |        1000         |
|        SLT          |        1001         |
|        SLL          |        1010         |
|        SRL          |        1011         |

Registradores
============
R0, R1, R2, R3, R4, R5, R6, R7, A. O último é para incremento de PC. <br />
``` cada reg tem 16 bits ```


Estágios habilitados
============
