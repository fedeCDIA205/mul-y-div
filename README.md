# mul-y-div
programa de federico def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "Error: No se puede dividir por cero."
    return a / b

def main():
    print("Calculadora de Multiplicación y División")
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))

    print(f"{num1} x {num2} = {multiplicar(num1, num2)}")
    division_result = dividir(num1, num2)
    print(f"{num1} ÷ {num2} = {division_result}")

if __name__ == "__main__":
    main()
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
