<h2 align="center">Monte, Ligue e Execute Manualmente em Assembly x64 com GAS</h2>

Crie um arquivo `mensagem6.s` no seu diretório home, em sintaxe AT&T
(GAS), Assembly x86-64 (64 bits), que imprima `Montado com GAS!` seguido
de quebra de linha, usando syscalls (`write` + `exit`).

Diferente do exercício de GAS anterior, dessa vez **você** precisa
montar e ligar o código, na mão, antes de rodar o `check`:

```
as mensagem6.s -o mensagem6.o
ld mensagem6.o -o mensagem6
./mensagem6
```

O `/challenge/check` não compila nada por você — ele só confere se
`mensagem6.o` e `mensagem6` existem no seu diretório home, se `mensagem6`
é um executável ELF 64-bit válido, e se produz a saída correta.
