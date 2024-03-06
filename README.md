### Olá, Sou José Muller =)
import sys
import time

def digitar_frase(frase):
    for char in frase:
        sys.stdout.write(char)  # Escreve o caractere
        sys.stdout.flush()      # Limpa o buffer
        time.sleep(0.1)         # Aguarda um curto período de tempo
    print()  # Pula para a próxima linha

frase = "Sou cientista de dados"
digitar_frase(frase)




