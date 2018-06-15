# new
new

Maior

def maior(vetor):
    maior = 0
     for v in vetor:
        if v > maior:
            maior = v
    return maior
vetor = [7,8,9,3]
print(maior(vetor))

media matriz

matriz = [[6,10,10], [7,4,2],[10,5,3]]

alunoMaiorMedia = -1
maiorMedia = 0

for linha in range(len(matriz)):
    soma = 0
    for coluna in range(len(matriz[linha])):
        soma+=matriz[linha][coluna]
    media = soma/3
    if media>maiorMedia:
        maiorMedia = media
        alunoMaiorMedia = linha
        
print("Aluno com maior média:",alunoMaiorMedia, " - Maior média:", maiorMedia)

media 

notas  =  [3,5,9]

def  calcularMedia (vetor):
    soma = 0
    for nota in vetor:
        soma+=nota
    media = soma/3
    return media

def resultado(nota):
    if nota>=6:
        print("Aprovado")
    else:
        print("Reprovado")    
        
mediaCalculada = calcularMedia(notas)
resultado(mediaCalculada)

add invertido

lista =["a", "b", "c"]
def inverter(lista):
    lista.reverse()
    lista.append(5)
    return lista
print(inverter(lista))

add normal

lista =["a", "b", "c"]
def listar(lista):
    lista.append(5)
    return lista
print(listar(lista))
