# python-primeiros-passos-00

Teste de Python

nome = input("Qual é seu nome? ")
nota1 = float(input("Digite a primeira nota: "))
nota2 = float(input("Digite a segunda nota: "))

media = (nota1 + nota2) / 2

print(f"{nome}, sua média é {media:.1f}")

if media >= 7:
    print("Você passou! 🎉")
else:
    print("Continue estudando! 📚")
    
