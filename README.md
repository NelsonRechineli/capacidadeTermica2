# Novidade de criar uma variável que recebe a subtração de dois inputs

quantidade de calor
quantidadeCalor = float(input("Quantidade de calor em Calorias: ")) 

tempInicial = float(input("Temperatura inicial: ")) 	
tempFinal = float(input("Temperatura final: ")) 	

variacaoTemperatura = tempFinal - tempInicial

#capacidade térmica = quantidade de calor/variação da temperatura
capacidadeTermica = quantidadeCalor / variacaoTemperatura

print(f"A capacidade térmica do corpo foi de : {capacidadeTermica:,.2f} calorias por grau Celsius (cal/Cº)")
