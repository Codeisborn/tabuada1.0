# tabuada1.0
from time import sleep
n = int(input('Digite um numero: '))
for n2 in range(0, 11):
    print('{} x {} = {}'.format(n, n2, n*n2))
    sleep(0.9)
