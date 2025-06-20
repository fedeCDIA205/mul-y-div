# mul-y-div
programa de federico 
def suma(a, b):
    return a + b

def resta(a, b):
    return a - b

def main():
    print("Calculadora simple: suma y resta")
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))
    operacion = input("Escribe '+' para sumar o '-' para restar: ")

    if operacion == '+':
        resultado = suma(num1, num2)
        print(f"El resultado de la suma es: {resultado}")
    elif operacion == '-':
        resultado = resta(num1, num2)
        print(f"El resultado de la resta es: {resultado}")
    else:
        print("Operación no válida.")

if __name__ == "__main__":
    main()
