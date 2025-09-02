# varredura de host e porta
O código abaixo faz uma varredura de host e porta automatizado.

📝 Guia: Criando e executando seu primeiro script Python
1. Criar o arquivo do script

Abra o terminal e crie um arquivo chamado script-1.2.py:

nano script-1.2.py

2. Adicionar o código Python

Cole o seguinte código (corrigi alguns detalhes de sintaxe do seu exemplo):

#!/usr/bin/python3
# Meu primeiro script em Python
# Uso educativo - Aprendendo tipos de dados e entrada de usuário

print("M!ss s3c")  # Apenas um print inicial

# Solicitando informações ao usuário
ip = input("Digite o IP: ")
porta = int(input("Digite a porta: "))  # convertendo para inteiro
ver = 1.1  # versão fictícia do script

# Exibindo os tipos de dados
print("IP -", type(ip))
print("Porta -", type(porta))
print("Ver -", type(ver))

# Exibindo uma mensagem formatada
print("Varrendo Host: %s na porta %d" % (ip, porta))


⚠️ Observação: Esse código não faz varredura real de rede (nem deve). É apenas um exemplo educativo para treinar entrada de dados, variáveis e tipos em Python.

3. Dar permissão de execução

No terminal, dê permissão ao arquivo para ser executado como programa:

chmod +x script-1.2.py

4. Executar o script

Agora rode no terminal:

./script-1.2.py


Você verá algo assim:

M!ss s3c
Digite o IP: 127.0.0.1
Digite a porta: 80
IP - <class 'str'>
Porta - <class 'int'>
Ver - <class 'float'>
Varrendo Host: 127.0.0.1 na porta 80

🔍 O que você aprendeu com esse script?

Shebang (#!/usr/bin/python3) → permite rodar o script direto no terminal.

print() → exibe mensagens na tela.

input() → captura dados do usuário (sempre como texto).

int() → converte string em número inteiro.

type() → mostra o tipo da variável (str, int, float...).

Formatação %s e %d → insere valores de variáveis em uma string.

👉 Esse é o primeiro passo para criar scripts úteis e seguros em Python.
Aos poucos, você pode evoluir esse código para:

testar conexões (com socket),

validar se o IP é válido,

criar pequenos utilitários automatizados.
