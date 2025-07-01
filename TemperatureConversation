def celsius_to_fahrenheit(celsius):
    return (celsius * 9/5) + 32

def celsius_to_kelvin(celsius):
    return celsius + 273.15

def fahrenheit_to_celsius(fahrenheit):
    return (fahrenheit - 32) * 5/9

def fahrenheit_to_kelvin(fahrenheit):
    return (fahrenheit - 32) * 5/9 + 273.15

def kelvin_to_celsius(kelvin):
    return kelvin - 273.15

def kelvin_to_fahrenheit(kelvin):
    return (kelvin - 273.15) * 9/5 + 32

def main():
    print("Temperature Conversion Program")
    print("------------------------------")
    temperature = float(input("Enter the temperature value: "))
    original_unit = input("Enter the original unit of measurement (Celsius, Fahrenheit, Kelvin): ").lower()

    if original_unit == 'celsius':
        fahrenheit = celsius_to_fahrenheit(temperature)
        kelvin = celsius_to_kelvin(temperature)
        print(f"{temperature} Celsius is equal to {fahrenheit:.2f} Fahrenheit and {kelvin:.2f} Kelvin.")
    elif original_unit == 'fahrenheit':
        celsius = fahrenheit_to_celsius(temperature)
        kelvin = fahrenheit_to_kelvin(temperature)
        print(f"{temperature} Fahrenheit is equal to {celsius:.2f} Celsius and {kelvin:.2f} Kelvin.")
    elif original_unit == 'kelvin':
        celsius = kelvin_to_celsius(temperature)
        fahrenheit = kelvin_to_fahrenheit(temperature)
        print(f"{temperature} Kelvin is equal to {celsius:.2f} Celsius and {fahrenheit:.2f} Fahrenheit.")
    else:
        print("Invalid unit of measurement. Please enter Celsius, Fahrenheit, or Kelvin.")

if __name__ == "__main__":
    main()
