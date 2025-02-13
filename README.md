# Criptografando-Arquivos
Projeto: Criando um Ransomware com Python

Ferramentas:
Kali Linux
Instalar o Python no ambiente Kali Linux

A) Instalar o Python:
1. sudo apt update
2. sudo apt install python3
3. python3 --version

Obs.: Se você utilizar o Kali em uma máquina virtual, talvez seja necessário criar um ambiente virtual dentro da máquina virtual para executar o 'Pyae'. Caso ocorra, execute os seguintescomandos:

1. Instale o Pacote python3-venv: sudo apt install python3-venv
2. Crie um ambiente virtual: python3 -m venv ~/meu_venv
3. Ative o ambiente virtual: source ~/meu_venv/bin/activate
4. Instalar o pyaes dentro do ambiente virtual: pip install pyaes

B) Utilizando os arquivos no Kali:

1. Abrir o terminal do Kali - caso a sua interface for a gráfica. Caso seja comand line, apenas executar os comandos abaixo;
2. Os arquivos encrypter.py e decrypter.py podem ser criados dentro do próprio Kali Linux, ou enviados para a Máquina Virtual;
3. criar uma pasta chamada projeto-ransomware dentro do Kali. Se for na pasta Documents, executar os comandos: cd ~/Documents;
4. Dentro da pasta Documents, criar a pasta 'projeto-ransomware': mkdir projeto-ransomware;
5. Colocar os arquivos encrypter.py e decrypter.py dentro da pasta projeto-ransomware;
6. Criar um arquivo de texto chamado teste.txt: nano texto.txt;
7. Escrever um texto como "Este é um arquivo legível."
8. Salvar: CTRL+O e sair do editor de texto: CTRL+X;
9. Encriptar o arquivo 'teste.txt': python encrypter.py
10. Abrir o arquivo 'teste.txt';
11. Verificar se o arquivo foi criptografado;
12. Descriptar o arquivo 'teste.txt': python descrypter.txt
13. Abrir novamente o arquivo 'teste.txt' e verificar se o arquivo foi descriptado corretamente.
