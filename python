#calculator
continuar = "y"
while continuar == "y":
    try:
        numero1 = float(input("Enter a number: "))
        numero2 = float(input("Enter another number: "))
        operaçao = input("Enter the operation (+; -; x or /): ")
    
        if operaçao == "+":
            soma = numero1 + numero2
            print(f"The sum is: {soma}")
        elif operaçao == "-":
            subtraçao = numero1 - numero2
            print(f"The subtraction is: {subtraçao}")
        elif operaçao == "x":
            multiplicaçao = numero1 * numero2
            print(f"The multiplication is: {multiplicaçao}")
        elif operaçao == "/":
            divisao = numero1 / numero2
            print(f"The division is: {divisao}")
        else:
            print("Enter a valid operation")
    except ValueError:
        print("Enter a valid number")
    continuar = input("\nDo you want to perform another calculation? (y/n): ").lower()

print("Calculator closed. See you!")
