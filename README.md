## Marcos Andrade
**Systems & Low-Level Engineer | Linux Kernel Contributor**

Engenheiro de software com foco no desenvolvimento de sistemas de baixo nível, infraestrutura e exploração do espaço do Kernel (Ring 0). Minha base acadêmica em Física (UFCG) me proporciona o rigor matemático e analítico necessário para lidar com gerenciamento de memória, concorrência e arquitetura de hardware.

Minha transição do ecossistema de microsserviços (Java/Spring) para o baixo nível me permite entender a pilha completa de execução: de como uma API recebe um request no Anel 3, até como o Sistema Operacional agenda a thread e aloca os blocos de memória no Anel 0.

### Core Competencies
* **Linguagens:** C, x86 Assembly, Java.
* **Linux Kernel Development:** Desenvolvimento de módulos (`.ko`), character/misc devices, gerenciamento de concorrência (`mutex`, `spinlocks`), ioctl, e VFS (Virtual File System).
* **Systems Architecture:** Memory Allocators, estruturas de dados intrusivas, IPC (Inter-Process Communication).
* **Ambiente & Ferramental:** Arch Linux, Hyprland, GCC, GNU Make, Git (patch flow via e-mail e signed-off commits).

### Projetos em Destaque

* **[vCrypto (Em Desenvolvimento)](#)**: Um driver de Sistema Operacional que simula um coprocessador criptográfico de hardware. Escrito inteiramente em C para o Kernel Linux, implementa controle de concorrência restrito e isolamento de hardware global com chamadas via `ioctl`.
* **[Safer / Virtual Vault](#)**: Módulo de Kernel projetado para fornecer cofres virtuais isolados por sessão. Gerencia alocação dinâmica de heap no espaço do Kernel evitando *Race Conditions* e garantindo sanitização de *Buffer Overflows*.
* **[Custom Memory Allocator](#)**: Biblioteca de alocação de memória dinâmica desenvolvida do zero em C, focada em estratégias de *First-Fit*/*Best-Fit* para contornar a fragmentação do heap de forma determinística.

### 📬 Contato
Sempre aberto para discutir arquitetura de sistemas, *patch reviews* ou literatura técnica.
* **Email:** marcosandrade95963@gmail.com
