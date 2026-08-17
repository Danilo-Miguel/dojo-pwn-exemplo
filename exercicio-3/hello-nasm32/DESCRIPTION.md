<h2 align="center">Olá, Mundo em Assembly com NASM e Arquitetura x86 (32 bits)</h2>

Crie um arquivo `mensagem3.asm` no seu diretório home que imprima
"Ola, 32 bits!" seguido de quebra de linha, usando syscalls (write + exit)
com NASM, em **Assembly x86 (32 bits)**.

O `check` monta seu código com `nasm -f elf32` e liga com `ld -m elf_i386`,
então use as convenções de 32 bits: registradores `eax`/`ebx`/`ecx`/`edx`
e a interrupção `int 0x80` (não `syscall`, que é específico de 64 bits).

Depois de escrever, rode `/challenge/check` para validar e receber a flag.
