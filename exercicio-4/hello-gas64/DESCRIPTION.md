<h2 align="center">Olá, Mundo em Assembly com GAS e Arquitetura x64</h2>

Crie um arquivo `mensagem4.s` no seu diretório home que imprima
"Ola, GAS!" seguido de quebra de linha, usando syscalls (write + exit),
em **sintaxe AT&T do GNU Assembler (GAS)**, Assembly x86-64 (64 bits).

O `check` monta seu código com `as` e liga com `ld`. Use a instrução
`syscall` e os registradores `rax`/`rdi`/`rsi`/`rdx`, só que em sintaxe
AT&T (operandos invertidos e registradores com `%`, ex: `mov $1, %rax`).

Depois de escrever, rode `/challenge/check` para validar e receber a flag.
