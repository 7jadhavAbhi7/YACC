

```yacc
lex filename.l
yacc -d filename.y
cc lex.yy.c y.tab.c -ll
./a.out
```
