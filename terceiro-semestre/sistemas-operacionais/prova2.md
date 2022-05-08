# Sistemas Operacionais

## Aula 05/04

Kernel do S.O.: 


* Rotinas do SO que oferecem serviços aos usuários

* Rotinas do SO que oferecem serviços as aplicações

* Rotinas do SO que oferecem serviços ao Sist Operacional

* É o núcleo do Sistema Operacional

Estrutura do SO:

* Executado com base em eventos assincronos

* Eventos executados de forma concorrente

Funções do Kernel:

* Faz o tratamento de interrupçoes e exceções

* Cria, elimina, sincroniza e comunica processos e threads

* Gerencia memória, processador, sist de arquivos e I/O

System Call:

* Porta de acesso ao núcleo do Sistema Operacional

* Pode ser solicitada pelo usuário ou por uma aplicação

* No Windows é conhecido como API

* É um mecanismo de proteção do Kernel do SO

Pq uma aplicação desenvolvida em Windows não pode ser portada para Unix?

* Por que as system calls dos SOs não são padronizadas

* Por que a Microsoft não seguiu o padrão

Trap:

*  Instrução que desvia o controle do usuário para o SO

* Instrução que desvia o controle da aplicação para o SO

Modo que um processo pode estar sendo executado (dois modos de acesso):

* Modo usuário ou não-privilegiado

* Modo kernel ou privilegiado

* Modo usuário não oferece riscos ao sistema operacional

* Modo kernel podem comprometer a integridade do SO

Numa Máquina Virtual Real, não há a camada do SO depois do Hardware. Como se chama essa c...

* Hypervisor

Tipos de SO

*  Microkernel

* Em camadas

* Monolítico