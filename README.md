## WINDOWS - PESQUISA 💻

O Windows é um dos sistemas operacionais mais usados do **mundo!** Nessa pesquisa, iremos abordar com detalhes o seu sistema, analisando sua história e evoluções, até os dias de hoje.

***

## SISTEMAS OPERACIONAIS 👨‍💻

Os sistemas operacionais são basicamente softwares como Windows, macOS, Android, Linux, entre outros, sendo uma 'maneira' mais fácil de interagir com a sua máquina, assegurando que o usuário tenha uma interface interativa e tranquila de usar.

***

##  **1° - SEU COMEÇO**📈

Os sistemas operacionais funcionavam de uma forma bem diferente comparado aos dias de hoje. O seu início, na década de 70, os códigos que o usuário digitava até a máquina eram mais ou menos assim:
<br>
<br>

```
section .data
    msg db 'Hello, World!', 0    ; Define a string terminada em null

section .text
    global _start

_start:
    ; Escrever na tela
    mov eax, 4          ; Número da chamada de sistema (sys_write)
    mov ebx, 1          ; File descriptor (1 = stdout)
    mov ecx, msg        ; Ponteiro para a mensagem
    mov edx, 13         ; Tamanho da mensagem
    int 0x80            ; Interrupção para chamar o sistema operacional

    ; Sair do programa
    mov eax, 1          ; Número da chamada de sistema (sys_exit)
    xor ebx, ebx        ; Código de saída (0)
    int 0x80            ; Interrupção para sair do programa
```
<br>

- Esse "simples" código está apenas mandando uma mensagem escrita **olá mundo** para o computador, com isso já podemos ver a dificuldade que os programadores passavam.

- Com os anos se passando, as máquinas foram evoluindo, e para acompanhá-las, os softwares e sistemas operacionais precisavam inovar. Foi aí que as **linguagens de alto nível** foram criadas, otimizando tempo e espaço para programá-las.

***

# WINDOWS - SISTEMAS

**`Windows 1`**  
O **Windows 1** (1985) foi um sistema feito para armazenar todos aplicativos desenvolvidos por ela até então. Sua interface era uma novidade na época! Introduzindo um display colorido e bastante único por causa do seu sistema de aplicativos organizados por blocos.

**`Windows 95`**  
O **Windows 95** (1995) inaugurou um dos sistemas operacionais mais importantes da história, produzido em **32 bits** (novidade na época), o software conseguiu trazer processadores modernos e começou a se tornar popular nas casas das famílias do mundo todo.

**`Windows XP`**  
O **Windows XP** (2001) foi muito inovador, principalmente no quesito visual, apostando em cores mais vivas e um visual mais realista, que agradou bastante o público da época.

**`Windows 7`**  
O **Windows 7** (2009) foi um sistema que maximizou em todos os sentidos a estética, trazendo um novo visual, chamado Frutiger Aero, além de implementar suporte a Touch Screen, Blu-Ray, entre outros.

**`Windows 10`**  
O **Windows 10** (2015) foi um modelo que otimizou a segurança e velocidade do software, mas a sua mudança no design que chamou a atenção, abandonando o famoso **Frutiger Aero** e escolhendo o minimalismo.

***

# ARQUITETURA DO WINDOWS

A arquitetura do Windows é basicamente a engenharia por trás desse sistema operacional, organizando tudo e definindo exatamente como cada setor funciona, começando no **Hardware** (processador, memória, disco rígido, etc.), e passando pelo **Kernel**, que é basicamente um "cérebro" que comanda os sistemas, além dos **Drivers**, que são tradutores que ajudam o Windows a conversar com a máquina.

***

# COMANDOS

#### Aqui está uma lista de comandos úteis para usar no Windows **(CMD)**:

  - **`ipconfig /all`** : Mostra detalhes da conexão de rede, como IP e DNS.

  - **`chkdsk`** : Verifica e corrige erros no disco rígido.

  - **`sfc /scannow`** : Repara arquivos do sistema corrompidos.
       
  - **`tasklist`** : Lista todos os processos em execução no sistema.
     
  - **`shutdown /r /f /t 0`** : Reinicia o computador imediatamente.

  - **`netstat -an`** : Mostra conexões de rede ativas e portas em uso.
        
  - **`ping [endereço IP ou domínio]`** : Testa a conexão com um site ou servidor.
    
  - **`dir`** : Lista arquivos e pastas no diretório atual.

***

# CURIOSIDADES

>**`O Windows não foi o primeiro sistema da Microsoft`** : o primeiro sistema se chama MS-DOS (1981), o Windows foi criado para adicionar uma interface gráfica ao sistema MS-DOS.
>
>**`A Microsoft quase comprou a Apple`** : Na década de 90, a **Apple** passava por dificuldades, quase sendo comprada pela **Microsoft**, porém, a empresa decidiu investir na Apple, ajudando-a a se recuperar.
>
>**`Bill Gates não utilizava o Windows`** : Inesperadamente, **Bill Gates** sempre adotou sistemas mais antigos e alternativos, como o **MacOS** e versões mais antigas do **Windows**.
>
>**`O nome Windows veio de "janelas"`** : O nome **Windows** foi escolhido por causa das "**janelas**" que o usuário podia acessar ao mesmo tempo.
>
>**`Windows XP durou 13 anos!`** : O **Windows XP** foi tão popular e amado pelo público que a Microsoft continuou dando suporte por **13 anos!** De 2001 até 2014.
