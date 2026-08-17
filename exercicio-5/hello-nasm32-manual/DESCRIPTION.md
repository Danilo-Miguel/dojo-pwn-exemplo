<h2 align="center">Monte, Ligue e Execute Manualmente em Assembly x86 (32 bits) com NASM</h2>

Crie um arquivo `mensagem5.asm` no seu diretório home, em Assembly x86
(32 bits), que imprima `Montado em 32 bits!` seguido de quebra de linha,
usando syscalls (`write` + `exit`) via `int 0x80`.

Diferente do exercício de 32 bits anterior, dessa vez **você** precisa
montar e ligar o código, na mão, antes de rodar o `check`:

```
nasm -f elf32 mensagem5.asm -o mensagem5.o
ld -m elf_i386 mensagem5.o -o mensagem5
./mensagem5
```

O `/challenge/check` não compila nada por você — ele só confere se
`mensagem5.o` e `mensagem5` existem no seu diretório home, se `mensagem5`
é um executável ELF 32-bit válido, e se produz a saída correta.
