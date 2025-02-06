# **WINDOWS - PESQUISA 💻**

### O windows é um dos sistemas operacionais mais usados do mundo!<br>Nessa pesquisa, iremos abordar com detalhes o seu sistema, anali-<br>sando sua história e evoluções, até os dias de hoje.
<br>


# **SISTEMAS OPERACIONAIS** 👨‍💻

### Os sistemas operacionais são basicamente softwares como Windows, macOS, Android, Linux, entre outros, sendo uma 'maneira' mais fácil de interagir com a sua máquina, assegurando que o usuário tenha uma interface interativa e tranquila de usar.
<br>


##  **1° - SEU COMEÇO**📈

Os sistemas operacionais funcionavam de uma forma bem diferente comparado aos dias de hoje. O seu inicio, na decada de 70, os códigos que o usuario digitava até a maquina eram mais ou menos assim:
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

- ### esse "simples" código esta apenas mandando uma mensagem escrito olá mundo para o computador, com isso já podemos ver a dificuldade que os programadores passavam.

-  ### Com os anos se passando, as maquinas foram evoluindo, e para acompanha-las, os softwares e sistemas operacionais precisavam inovar. Foi ai que as **linguagens de alto nivel** foram criadas, otimizando tempo e espaço para programa-las.
<br>
<br>

   - ## **2° - WINDOWS - COMEÇO**
      ![1° Logo do Windows](https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/Windows_logo_-_1985-1989.svg/169px-Windows_logo_-_1985-1989.svg.png)  **Em 1985, a Microsoft Lança seu Primeiro Windows, chamado de **Windows 1**. Esse Sistema foi feito para armazenar todos aplicativos desenvolvidos por ela até então.**
  <br>

 **NOVIDADES**
  - **Sua interface era uma novidade na época! introduzindo um display colorido e bastante unico por causa do seu sistema de aplicativos organizados por blocos.**<br>

    ![1° Logo do Windows](https://tm.ibxk.com.br/2021/06/24/windows-1-0-24164607926359.png)

    ###### Este é um exemplo da interface do Windows 1.

    - ## WINDOWS - NOVA GERAÇÃO
- ### O Windows 95 (1995) Inaugurou um dos sistemas operacionais mais importantes da história, produzido em 32 bits (Novidade na época), o software conseguiu trazer processadores modernos e começou a se tornar popular nas casas das familias do mundo todo.
   
   - ![1° Logo do Windows](https://tm.ibxk.com.br/2021/06/24/windows-95-24164803318361.png)
  
      - ## Evolução e Otimização
    
      - ### O Windows XP(2001) Foi muito inovador, principalmente no quesito visual, apostando em cores mais vivas e um visual mais realista, que agradou bastante o publico da época.
           - ![1° Logo do Windows](https://tm.ibxk.com.br/2021/06/24/windows-xp-24165158133364.png)
             ###### Este é um exemplo da interface do Windows XP.

      - ## Realismo Exagerado
    
      - ### O Windows 7 (2009) foi um sistema que maximizou em todos os sentidos a estetica, trazendo um novo visual, chamado Frutiger Aero, alem de implementar suporte a Touch Screen, Blue-Ray, entre outro.
    
           - ![1° Logo do Windows](https://upload.wikimedia.org/wikipedia/pt/8/89/Ambiente_Windows_7.png)
    
     - ## Modernização e Minimalismo
    

       ### Nesse ultimo tópico, irei abordar 2 sistemas operacionais que são bem parecidos nesse aspecto: o Minimalismo.
       
       ### os sistemas que estou falando são o Windows 10 (2015) e Windows 11 (2021). Esses sistemas otimizaram a velocidade e segurança do software, mais a sua mudança extrema no visual foi o que chamou mais atenção, o abandono do Frutiger aero e a escolha do minimalismo foram decisões que desapontaram muitos usuarios, mas por outro lado, trouxe um visual mais limpo e profissional
       
         - ![1° Logo do Windows](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTGRRFX2HwiumftxSvIQl_ti4ojBkirMxlBn48ajCMbZRgCTlr4SbIZ5dy9f5UwU6uk_Cc&usqp=CAU)
      

<br>

  # ARQUITETURA DO WINDOWS
    
   - ### A arquitetura do um windows são uma serie de sistemas que são integrados para garantir a funcionabilidade do sistema, começando no hardware, sendo controlado pelo processador, memórias e dispositivos de entrada e saida ( Sistema ). Integrado junto ao Kernel, um núcleo que corresponde o sistema e os gerencia.




  - ![1° Logo do Windows](https://learn.microsoft.com/pt-br/windows-hardware/customize/desktop/wsim/images/dep-win8-l-wsim-arch.jpg)

    <br>

    # COMANDOS

      - ## Aqui Está uma lista de comandos uteis para usar no Windows (CMD):

  ```
        - ipconfig /all
  ```
  ```
        - chkdsk
  ```
  ```
        - sfc /scannow
  ```
  ```
        - tasklist
  ```
  ```
        - shutdown /r /f /t 0
  ```
  ```
        - netstat -an
  ```
  ```
        - ping [endereço IP ou domínio]
  ```
  ```
        - dir
  ```
  

  # CURIOSIDADES

   - ### o Windows Não foi o primeiro sistema da Microsoft, o primeiro sistema se chama MS-DOS(1981)
   
   - ### A Microsoft quase comprou a Apple
      
   - ### Bill Gates não utilizava o Windows, ele sempre adotou sistemas antigos e alternativos
  
   
   - ### O nome Windows foi escolhido por causa das "janelas", usadas no primeiro Software
  
      
    

    
         
             
        

   
    

  



