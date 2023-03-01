# Convers-o-de-medidas
Essas linhas de código pedem que o usuário insira um valor em metros e, em seguida, converte esse valor para centímetros e milímetros, e imprime as conversões na tela. Aqui está uma explicação linha a linha:

v1 = float(input('Escreva quantos metros:'))
Esta linha solicita ao usuário que insira um valor em metros e armazena o valor digitado na variável v1. A função input é usada para solicitar que o usuário insira um valor e float é usado para garantir que o valor digitado seja interpretado como um número decimal.

centimetros = v1 * 100
Esta linha converte o valor armazenado em v1 (que representa a medida em metros) em centímetros, multiplicando-o por 100 e armazenando o resultado na variável centimetros.

milimetros = v1 * 1000
Esta linha converte o valor armazenado em v1 (que representa a medida em metros) em milímetros, multiplicando-o por 1000 e armazenando o resultado na variável milimetros.

print(v1,'mm em centímetros é igual a:', centimetros, 'cm')
Esta linha imprime na tela a mensagem que mostra a conversão de metros para centímetros, usando as variáveis v1 (que armazena o valor em metros) e centimetros (que armazena o valor em centímetros).

print(v1,'cm em milímetros é igual a:', milimetros, 'mm')
Esta linha imprime na tela a mensagem que mostra a conversão de centímetros para milímetros, usando as variáveis v1 (que armazena o valor em metros) e milimetros (que armazena o valor em milímetros).
