# 🛡️ Ferramentas de Segurança Cibernética

## 1. Nmap 🌐
- **Descrição**: Nmap é uma ferramenta de varredura de rede que permite descobrir dispositivos e serviços em uma rede.
- **Como usar**:
  - Instale o Nmap (disponível para Windows, Linux e macOS).
  - Abra o terminal ou prompt de comando.
  - Para escanear um IP específico: 
    ```bash
    nmap [IP]
    ```
  - Para escanear uma rede inteira: 
    ```bash
    nmap [IP]/[máscara]  # Ex: nmap 192.168.1.0/24
    ```
  - Para um ping scan: 
    ```bash
    nmap -sP [IP]/[máscara]
    ```
- ![Nmap]([(https://cdn.discordapp.com/attachments/1314063319920803901/1314065324131221514/image.png?ex=67526a33&is=675118b3&hm=6ec04383ca1502eda50d5f48d53fc73143b7dbe912de4e5bb179263ccdca0a92&)])  <!-- Substitua pelo link da imagem do Nmap -->

## 2. Wireshark 🐋
- **Descrição**: Wireshark é um analisador de pacotes que permite capturar e examinar o tráfego de rede.
- **Como usar**:
  - Instale o Wireshark.
  - Abra o programa e selecione a interface de rede que deseja monitorar.
  - Clique em "Iniciar Captura".
  - Após capturar os pacotes, você pode filtrá-los por protocolo, IP, etc.
  - Analise os pacotes para entender o tráfego.
- ![Wireshark](https://example.com/wireshark_image.png)  <!-- Substitua pelo link da imagem do Wireshark -->

## 3. Metasploit 💻
- **Descrição**: Metasploit é uma plataforma para testes de penetração que permite explorar vulnerabilidades.
- **Como usar**:
  - Instale o Metasploit (geralmente incluído no Kali Linux).
  - Abra o terminal e inicie o Metasploit com o comando:
    ```bash
    msfconsole
    ```
  - Use `search [nome do exploit]` para encontrar exploits.
  - Carregue um exploit com:
    ```bash
    use [exploit]
    ```
  - Configure as opções necessárias com:
    ```bash
    set [opção] [valor]
    ```
  - Execute o exploit com:
    ```bash
    exploit
    ```
- ![Metasploit](https://example.com/metasploit_image.png)  <!-- Substitua pelo link da imagem do Metasploit -->

## 4. Burp Suite 🕵️‍♂️
- **Descrição**: Burp Suite é uma ferramenta para testes de segurança em aplicações web.
- **Como usar**:
  - Instale o Burp Suite.
  - Configure seu navegador para usar o proxy do Burp (geralmente `localhost:8080`).
  - Navegue pelo site que deseja testar.
  - Use as ferramentas do Burp para interceptar e modificar requisições.
- ![Burp Suite](https://example.com/burp_suite_image.png)  <!-- Substitua pelo link da imagem do Burp Suite -->

## 5. Kali Linux 🐧
- **Descrição**: Kali Linux é uma distribuição Linux voltada para testes de penetração.
- **Como usar**:
  - Baixe e instale o Kali Linux em uma máquina virtual ou como sistema operacional principal.
  - Explore as ferramentas pré-instaladas, como Nmap, Wireshark, Metasploit, etc.
  - Use a documentação oficial para aprender sobre cada ferramenta.
- ![Kali Linux](https://example.com/kali_linux_image.png)  <!-- Substitua pelo link da imagem do Kali Linux -->

## Considerações Finais ⚖️
- **Ética**: Sempre obtenha permissão antes de testar qualquer sistema que não seja seu. O uso não autorizado de ferramentas de segurança pode ser ilegal e antiético.
- **Aprendizado**: Considere fazer cursos de cibersegurança e certificações, como CompTIA Security+, Certified Ethical Hacker (CEH) ou Offensive Security Certified Professional (OSCP).
