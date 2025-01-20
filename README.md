# Ferramenta Phishing para capturar usuário e senha do Facebook "Projeto Escolar"

### Ferramentas

- VirtualBox
- Kali Linux "VM to configure the phishing"
- setoolkit
- Windows 10 "I create another VM to test the chalenge"

### Configurando o Phishing com o Kali Linux

- Open your VM with Kali Linux
- Access the Linux Terminal
- Access root: ``` sudo su ```

![Alt text](./01-rootaccess.png "Optional title")

- Starting setoolkit: ``` setoolkit ```

![Alt text](./02-Social-EngineeringAttacks.png "Optional title")

- Tipo de ataque: ``` Social-Engineering Attacks ```

![Alt text](./03-WebsiteAttackVectors.png "Optional title")

- Vetor de ataque: ``` Web Site Attack Vectors ```

![Alt text](./03-WebsiteAttackVectors.png "Optional title")

- Método de ataque: ```Credential Harvester Attack Method ```

![Alt text](./04-CredentialHavesterAttackMethod.png "Optional title")

- Método de ataque: ``` Site Cloner ```

![Alt text](./05-SiteCloner.png "Optional title")

- Obtendo o endereço da máquina: ``` 192.168.1.26 ```

![Alt text](./06-IPtoClone.png "Optional title")

- URL para clone: http://www.facebook.com

![Alt text](./07-SitetoClone.png "Optional title")

- URL para site clone: 192.168.1.26

![Alt text](./08-Cloneofsite.png "Optional title")

### Resutado

![Alt text](./09-Credentialshacked.png "Optional title")


### Resolução de Problema para o caso de digitar o usuário e senha o setoolkit não salvar

- Configure normalmente o ``` setoolkit ``` seguindo os passos acima

- Quando der essa mensagem final

![Alt text](./00-setoolkitConfigurado.JPG "Optional title")

- Abra o navegador de arquivos

- Vá em File System

- Clique com o botão direito e clique abrir como ``` root ```

![Alt text](./01-AbrirPastaroot.png "Optional title")

- Navegue até a pasta ``` /root/.set/web_clone/ ```

![Alt text](./02-NavegarAtéaPasta.png "Optional title")

- Clique com o botão direito e ``` Abra com o "Mousepad" ```

![Alt text](./03-AbrircomMousepad.png "Optional title")

- Procure no arquivo aberto ``` Ctrl+F ```
- Digite ``` script src= ```

![Alt text](./04-ProcurareExcluirLinha.png "Optional title")

- Exclua a linha e salve o arquivo ``` Ctrl+S ```

![Alt text](./04-Salvar.png "Optional title")

### Qualquer dúvida estou a disposição

### Creditos

- URL para clone: https://github.com/Weslley22Marques/cibersecurity-desafio-phishing

- URL para clone: http://ai.zendev.com.br/proof.mp4
