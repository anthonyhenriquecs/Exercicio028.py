# Exercicio028.py

#Escreva um programa que faça o computador “pensar” em um número inteiro entre 0 e 5 e peça para o usuário tentar descobrir qual foi o número escolhido pelo computador. O programa deverá escrever na tela se o usuário venceu ou perdeu.

from random import randint
comp = randint(0,5)#faz o computador "pensar"

t = int(input('Em que numero eu pensei:'))
if t == comp:
    print('voce ganhou!')
else:
    print('voce perdeu pensei no numero',comp)
    
