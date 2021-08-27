# Exercicio_24

#counting letters and identifying positions


stre = str (input ('digite uma frase: ')).upper()


print ('A letra A aparece {} vezes na frase' .format (stre.count('A')))
print ('A primeira letra A aparece na posicao {}' .format (stre.find('A')))
print ('A ultima letra A aparece na posicao {}' .format (stre.rfind('A')))
