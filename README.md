import random

# Lista de possíveis estados de espírito
estados_de_espirito = ['feliz', 'triste', 'animado', 'entediado', 'preocupado']

# Gera um número aleatório entre 0 e 1 para escolher o estado de espírito
estado_de_espirito_index = random.randint(0, 1)

# Cria a string do perfil com base no estado de espírito escolhido aleatoriamente
if estado_de_espirito_index == 0:
    perfil = f"Estou me sentindo {estados_de_espirito[random.randint(0, 4)]} hoje!"
else:
    perfil = "Não estou me sentindo muito bem hoje..."

print(perfil)
