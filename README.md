# Compiler-Principle
lexical使用方法
flex lexical.l
gcc -c lex.yy.c
gcc -o scanner lex.yy.o -ll
