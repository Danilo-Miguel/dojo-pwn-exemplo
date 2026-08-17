Crie um arquivo `mensagem.asm` no seu diretório home que imprima 
"Ola, Mundo!" seguido de quebra de linha, usando syscalls (write + exit) 
com NASM, em **Assembly x86-64 (64 bits)**.

O `check` monta seu código com `nasm -f elf64`, então use as convenções de
64 bits: registradores `rax`/`rdi`/`rsi`/`rdx` e a instrução `syscall`
(não `int 0x80` nem código de 32 bits).

Depois de escrever, rode `/challenge/check` para validar e receber a flag.
