Crie um arquivo `mensagem2.asm` no seu diretório home, em Assembly x86-64
(64 bits), que imprima `Montado e Ligado!` seguido de quebra de linha,
usando syscalls (`write` + `exit`).

Diferente do desafio anterior, dessa vez **você** precisa montar e ligar
o código, na mão, antes de rodar o `check`:

```
nasm -f elf64 mensagem2.asm -o mensagem2.o
ld mensagem2.o -o mensagem2
./mensagem2
```

O `/challenge/check` não compila nada por você — ele só confere se
`mensagem2.o` e `mensagem2` existem no seu diretório home e se o executável
produz a saída correta.
