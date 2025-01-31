# Phishing para captura de senhas do Facebook

### Configurando o Phishing no Kali Linux

- Kali Linux foi iniciado através do VirtualBox.
- Em seguida, o terminal foi aberto e a seguinte sequência de comandos foi executada:
  - Entrar como root: sudo su
  - Iniciar setoolkit: setoolkit
  - No menu, selecionei a opção correspondente a Social-Engineering Attacks digitando: 1
  - Escolhi Website Attack Vectors digitando: 2
  - Para o método Credential Harvester Attack, digitei: 3
  - Para a opção Site Cloner, utilizei: 2
- O sistema sugeriu o IP do computador.
- Informei o site a ser clonado: http://www.facebook.com/
- Acessei o IP indicado no terminal através do navegador, no modo anônimo
- A tela falsa de login do Facebook apareceu, e então inseri as credenciais.

### Resutados

![Alt text](./passwd.png "Optional title")
