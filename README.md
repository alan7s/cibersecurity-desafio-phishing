# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

![Alt text](./passwd.png "Optional title")

### Prática

- Error

![Alt text](./facebook_setolkit_script_error.png "SETOLKIT ERROR")

Após clonar o website não é possível obter as credenciais.

- Bypass

![Alt text](./facebook_setolkit_script_solved.png "Facebook Protection")
![Alt text](./facebook_setolkit_script_comment.png "Facebook Protection Bypass")

Para bypassar essa proteção é necessário comentar o script que é chamado quando o botão "Entrar" é pressionado.

- Working

![Alt text](./facebook_setolkit_worked.png "SETOLKIT Working")

Credenciais obtidas com sucesso.
