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

``` cada instrução carrega  bits ```

|      Operações      |      Num bits       |
| ------------------- | ------------------- |
|         LD          |        0001         |
|         ST          |        0010         |
|        MVNZ         |        0011         |
|        MVI          |        0100         |
|        ADD          |        0101         |
|        SUB          |        0110         |
|         OR          |        0111         |
|        SLT          |        1000         |
|        SLL          |        1001         |
|        SRL          |        1010         |

Registradores
============
R1, R2, R3, R4, R5, R6, R7, R8 e R9. O último é para incremento de PC. <br />
``` cada reg tem 16 bits ```


Estágios habilitados
============
