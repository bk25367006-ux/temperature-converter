# temperature-converter
学習用サンプル, simple temperature converter, #Python, __init__method
class Temperature:
    def __init__(self, celsius, fahrenheit):
        self.celsius = celsius
        self.fahrenheit = fahrenheit

    def to_fahrenheit(self):
        """Convert Celsius to Fahrenheit"""
        return self.celsius * 9/5 + 32

    def to_celsius(self):
        """Convert Fahrenheit to Celsius"""
        return (self.fahrenheit - 32) * 5/9


# Input from user
C = float(input("Enter temperature in Celsius: "))
F = float(input("Enter temperature in Fahrenheit: "))

p1 = Temperature(C, F)

print(f"{C}°C to Fahrenheit: {p1.to_fahrenheit():.2f}°F")
print(f"{F}°F to Celsius: {p1.to_celsius():.2f}°C")
