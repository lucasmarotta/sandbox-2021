# Compiladores - Exercício E1

Solução do [exercício de compiladores E1](https://classroom.google.com/u/2/c/MTk1MzE5Mzc1MzY5/a/MzAzMDcxMDg1NTQ1/details).

## Como executar

Para executar e testar o programa LEX, abra um terminal *Bash* com *GCC* e *FLEX*. Em seguida execute os seguintes comandos:

```bash
flex wc.flex
gcc lex.yy.c -lfl
./a.out
```

Em seguida digite alguma entrada, podendo ter múltiplas linhas, e para finalizar tecle `CTRL + D`
