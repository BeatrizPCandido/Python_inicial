# # Lista de Estrutura Sequencial

#### 1. Faça um Programa que mostre a mensagem (print) "Alo mundo" na tela.


```python
print("Alo Mundo")
```

    Alo Mundo
    

#### 2. Faça um Programa que peça um número (input) e então mostre a mensagem: "O número informado foi [número]."


```python
numero = input("Insira um número: ")
print(f'O número informado foi {numero}')
```

    Insira um número: 12
    O número informado foi 12
    

#### 3. Faça um Programa que peça dois números e imprima a soma.


```python
numero1 = int(input("Insira um numero: "))
numero2  = int(input("Insira o segundo numro:"))

soma = numero1 + numero2

print(soma)
```

    Insira um numero: 15
    Insira o segundo numro:10
    25
    

#### 4. Faça um Programa que peça as 4 notas bimestrais de um aluno e mostre a média de todas as notas.


```python
nota1 = float(input("Insira a 1º nota: "))
nota2 = float(input("Insira a 2º nota: "))
nota3 = float(input("Insira a 3º nota: "))
nota4 = float(input("Insira a 4º nota: "))

media = (nota1 + nota2 + nota3 + nota4) / 4

print('A media é: ', media)

```

    Insira a 1º nota: 9
    Insira a 2º nota: 7
    Insira a 3º nota: 6
    Insira a 4º nota: 10
    A media é:  8.0
    

 #### 5. Faça um Programa que converta metros para centímetros. Você pode pedir o comprimento em metros para o usuário (input).


```python
comprimento_m = float(input('Informe um comprimento em metros: '))

comprimento_cm = comprimento_m * 100

print('Este comprimento em centímetros é:', comprimento_cm, 'cm')
```

    Informe um comprimento em metros: 25.8
    Este comprimento em centímetros é: 2580.0 cm
    

#### 6. Faça um Programa que calcule a área de uma sala de um apartamento. Para isso, o seu programa precisa pedir a largura da sala, o comprimento da sala e imprimir a área em m² da sala.


```python
largura = float(input('informe a largura da sala em metros: '))
comprimento = float(input('Informe o compromento da sala: '))

medida = largura * comprimento

print('A área em m²', medida , 'da sala')
```

    informe a largura da sala em metros: 9.5
    Informe o compromento da sala: 10.5
    A área em m² 99.75 da sala
    

 #### 7. Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês.


```python
valor_hora = float(input('Qanto é sua remuneração por hora R$: '))
horas_trabalhada = float(input('Informe a hora tabalhada no mês: '))

total = valor_hora * horas_trabalhada

print('O salario a recebe é de R$:  ', total)
```

    Qanto é sua remuneração por hora R$: 100
    Informe a hora tabalhada no mês: 120
    O salario a recebe é de R$:   12000.0
    

#### 8. Vamos criar um conversor de temperatura. Faça um Programa que peça a temperatura em graus Fahrenheit, transforme e mostre a temperatura em graus Celsius.
$C = \frac{5}{9}(F-32)$


```python
temperatura_f = float(input('Informe a temperatura em Fahrenheit: '))
temperatura_c = (5/9) * (temperatura_f - 32)

print('A temperatura é:', temperatura_c, '°C')
```

    Informe a temperatura em Fahrenheit: 45
    A temperatura é: 7.222222222222222 °C
    

#### 9. Faça um Programa que peça a temperatura em graus Celsius, transforme e mostre em graus Fahrenheit.
$F = \frac{9}{5}C + 32$


```python
temperatura_c = float(input('Informe a temperatura: '))
temperatura_f = (9/5) * (temperatura_c + 32)

print('A temperatura Fahrenheit é:', temperatura_f, '°F')
```

    Informe a temperatura: 25
    A temperatura Fahrenheit é: 102.60000000000001 °F
    

#### 10. Tendo como dados de entrada a altura (h) de uma pessoa, construa um algoritmo que calcule seu peso ideal, usando a seguinte fórmula:
$P = 72,7h - 58$

Lembrando que "algoritmo" nada mais é do que um programa, como todos os outros que você vem fazendo


```python
altura = float(input('Insira sua altura: '))
peso_ideal = 72.7 * altura - 58

print('Seu peso ideal é:', peso_ideal, 'Kg')


```

    Insira sua altura: 1.70
    Seu peso ideal é: 65.59 Kg
    

#### 11. Tendo como dado de entrada a altura (h) de uma pessoa, construa um algoritmo que calcule seu peso ideal, utilizando as seguintes fórmulas:
##### a. Para homens: $P = 72,7h - 58$
##### b. Para mulheres: $P = 62,1h - 44,7$


```python
altura = float(input('Informe a altura em metros: '))
peso_ideal_homens = 72.7 * altura - 58
peso_ideal_mulheres = 62.1 * altura - 44.7

print('O peso ideal com essa altura para homens é:', peso_ideal_homens, 'kg')
print('O peso ideal com essa altura para mulheres é:', peso_ideal_mulheres, 'kg')

```

    Informe a altura em metros: 1.63
    O peso ideal com essa altura para homens é: 60.50099999999999 kg
    O peso ideal com essa altura para mulheres é: 56.522999999999996 kg
    

#### 12. Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês.


```python
remuneracao = float(input('Informe a remuneração em R$ por hora: '))
horas_trabalhadas = int(input('Informe a quantidade de horas trabalhadas: '))
```

    Informe a remuneração em R$ por hora: 50.00
    Informe a quantidade de horas trabalhadas: 125
    

#####  Calcule o salário bruto (horas * salario por hora)


```python
remuneracao = float(input('Informe a remuneração em R$ por hora: '))
horas_trabalhadas = int(input('Informe a quantidade de horas trabalhadas: '))

salario_bruto = remuneracao * horas_trabalhadas

print('O seu ladario é de:', salario_bruto)
```

    Informe a remuneração em R$ por hora: 50.00
    Informe a quantidade de horas trabalhadas: 125
    O seu ladario é de: 6250.0
    


```python
salario_bruto = remuneracao * horas_trabalhadas
print(f'O salário bruto é R$ {salario_bruto}')
```

    O salário bruto é R$ 6250.0
    

##### Calcule o desconto do IR (11% do salário bruto)


```python
ir = 0.11 * salario_bruto
print(f'O desconto do IR é R$ {ir}')
```

    O desconto do IR é R$ 687.5
    

##### Calcule o desconto do INSS (8% do salário bruto)


```python
INSS = 0.08 * salario_bruto
print(f'O desconto do INSS é R$ {INSS}')
```

    O desconto do INSS é R$ 500.0
    

##### Calcule o desconto do sindicato (5% do salário bruto)


```python
sindicato = 0.05 * salario_bruto
print(f'O valor do desconto do sincato é R$ {sindicato}')
```

    O valor do desconto do sincato é R$ 312.5
    

##### Calcule o salário líquido (salário bruto - descontos) 


```python
salario_liquido = salario_bruto - ir - INSS - sindicato
print(f'O salario liquido é {salario_liquido}')
```

    O salario liquido é 4750.0
    

#### 13. Faça um programa para uma loja de tintas. O programa deverá pedir o tamanho em metros quadrados da área a ser pintada. Considere que a cobertura da tinta é de 1 litro para cada 3 metros quadrados e que a tinta é vendida em latas de 18 litros, que custam R\$ 80,00. Informe ao usuário a quantidades de latas de tinta a serem compradas e o preço total. (para simplificação nesse momento, não se preocupe em arredondar a quantidade de latas a serem compradas - vamos trabalhar isso em breve)


```python
area = float(input('Informe o tamanho da área a ser pintada em m²: '))

litros_tinta = area / 3 

latas = litros_tinta / 18
preco = latas * 80
print(f'Serão necessárias {latas} latas, custando R$ {preco} no total')
```

    Informe o tamanho da área a ser pintada em m²: 10
    Serão necessárias 0.1851851851851852 latas, custando R$ 14.814814814814817 no total
    

#### 14. Faça um programa que peça o tamanho de um arquivo para download (em MB) e a velocidade de um link de Internet (em Mbps), calcule e informe o tempo aproximado de download do arquivo usando este link (em minutos).

Detalhe: MB significa megabyte, Mb (com b minúsculo) significa megabit. Um megabit é 1/8 de um megabyte. 


```python
tamanho = float(input('Informe o tamanho do arquivo em MB: '))
velocidade = float(input('Informe a velocidade da conexão em Mbps: '))

# aqui trasnformamos megabytes em megabits para que tamanho e velocidade estejam na mesma unidade
tamanho_megabits = tamanho * 8

tempo = tamanho_megabits / velocidade
# transformando em minutos
tempo_minutos = tempo / 60
print(f'O tempo de download é de {tempo_minutos} minutos')
```

    Informe o tamanho do arquivo em MB: 59.8
    Informe a velocidade da conexão em Mbps: 9
    O tempo de download é de 0.8859259259259259 minutos
    


```python

```
