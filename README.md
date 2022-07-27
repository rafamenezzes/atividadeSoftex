# atividadeSoftex
Atividade 03 modulo 2 - laços de repetição

Faça um código que execute a contagem regressiva de uma bomba, informando 
o número de segundos para explodir. Ele deverá mostrar a mensagem “iniciando contagem regressiva”,
os segundos passados e, no final, a mensagem “BUM!”.

Não é necessário, mas, caso deseje tornar o sistema mais realista para que o tempo realmente passe
em segundos, você pode usar a função time.sleep() que existe na Python (acesse o link em anexo).
No entanto, é preciso adicionar uma biblioteca antes de executá-la. 


py

from time import sleep 
print("iniciando contagem regressiva...")
sleep(0.5)
for cont in range(10, -1, -1):
    print(cont)
    sleep(0.7)
print("Buuuum!")
