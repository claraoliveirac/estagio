# estagio
s1 = int(0)
s2 = int(1)
s3 = int(0)
print('-'*42)
print('-'*3,'Consulta da Sequência de Fibonacci')
print('-'*42)
Valor = int(input('Digite um número: '))
while Valor > s3:
  s3 = s1 + s2
  s1 = s2
  s2 = s3
if Valor == 0 or Valor == 1:
  print('O número faz parte da sequência de Fibonacci.')
elif Valor == Termo3:
  print('O número faz parte da sequência de Fibonacci.')
else:
  print('O número digitado não faz parte da sequência de Fibonacci.')
