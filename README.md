# ListasPython
#Exercício 1
print ("Meu primeiro programa em python")
print("Meu segundo", "Programa", "em python")
nome='Python'
print("Meu segundo programa em", nome)

#Exercício 2
print((2/2)-3)
print(4*(7-4))
print((5-5)*(2+1)/2)
print(4%2)
# %resto da divisão
# ** esponenciação
print(5+(4%2)-1)

'''
== comparação de valores
i=j( com apenas 1= estaria atribunindo )
i!=j ( se i for diferente de j)
'''

#Exercício 3
x=3
y=5
z=4

print( y+4)
print((z+x)-y)
print((z*x)/y)
print((((x*y)/y)-z)*(z-5))

print(type(3))
print(type(3.0))

#print(type())
#objetos escalar são os primitivos int float bool(true, false) e none(faltante) 
#não escalares são os 'abs'
'''
atribuição (=)
tal coisa = outra coisa
O identificador "tal coisa" faz referencia a uima instancia de classe string que tem valor "outra coisa"
'''
#Operadores lógicos
#not,and e or
nome="Sergio"
idade=22
nome=="Sergio" and idade == 8
nome=="Sergio" and idade == 38

nome=="Sergio" or idade == 38
nome=="Cleiton" or idade == 38

#Exercício 5
a=10
b=4
c=8
print((not a==b) and c<10)
print((a>b)or (4==b))
print((a<b)and (not (a==10)))
print(((b<a)and (c>b))or (c==7))

#len= tamanho da observação
len(nome)<10 and not nome=="Sergio"

#exercício 6
velocidade=60
tempo=3
distancia=tempo*velocidade

#exercicio 7
nota1=(input('10'))
nota2=(input('10'))
nota3=(input('10'))
media=sum(nota1,nota2,nota3)/3
print("A média foi de", media)

#Se você percorer 10Km em 53 min, qual será a média de tempo (em segs) por Km?
distPercorrida=10
tempogasto=(50*60)
TempoxKm=tempogasto/distPercorrida
print(TempoxKm)
