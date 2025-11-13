Para começar a programar, em primeiro lugar, é preciso baixar o `Python`, isso irá depender do sistema operacional que será usado, vamos falar de dois o Windows e Linux. Para o MacOS basta seguir esse [guia](https://python.org.br/instalacao-mac/).

## Windows

Existe mais de uma forma de baixar o `Python` no windows, aqui vamos tratar de uma, o que se deve ser feito é abrir o terminal, apertando o botão `Win` e pesquisando terminal, ou digitando `win+R` e digitando `cmd`, quando abrir o terminal (tela preta) digite `Python`, isso deve abrir a loja do windows, caso não abra procure a loja e o `Python` nela, então é só clicar em baixar.

## Linux

O primeiro passo é abrir o terminal, e em seguida digitar os seguintes comandos

```bash
sudo apt update
```

Que irá atualizar os pacotes existentes

```bash
sudo apt install python3 python3-pip
```

Em primeiro lugar baixa-se a última versão do `Python` e baixa o `pip`, que é usado para baixar [[Bibliotecas Importantes|novas bibliotecas]]

# Validando que está baixado

Para checar se o `Python` está baixado ou não, digite `Python` ou `Python3`, normalmente ele é salvo como `Python3`, porém pode ser que seja somente `Python`, caso o `Python` não esteja baixado, tente seguir os passos anteriores novamente. Supondo que está instalado, o que deve aparecer é o `Interactive Python Shell (REPL)`, que é uma forma de escrever scripts de `Python` e roda-lo linha por linha

```python
>>> 
>>> 
>>> 
```

# Primeiro Script

É uma tradição na comunidade de desenvolvimento que o primeiro código escrito deve ser uma saudação para o mundo, para fazer isso usa-se a [[Funções|função]] [[Funções Nativas#print|print]], que será discutida mais para frente

```python
>>> print('Hello World!')
```

O output esperado disso é

```text
Hello World!
```

Aqui já da para começar a brincar com o `Python`.

## Download da IDE e das bibliotecas

O próximo passo é garantir que o ambiente de desenvolvimento esteja pronto, instalando o VScode e as bibliotecas Python essenciais: 

Acesse o seguinte site para instalar o VScode: [https://code.visualstudio.com](https://code.visualstudio.com) ;  

Acesse o prompt de comando (vá para o menu ‘Iniciar’ e digite ‘cmd’); 

Com o prompt de comando iniciado digite o seguinte comando: 

```bash
pip install requests beautifulsoup4 pandas numpy selenium 
``` 
dê enter, espere e em seguida digite o seguinte comando 

```bash
pip install scrapy  
``` 
