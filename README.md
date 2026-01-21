# temperature-converter
学習用サンプル, simple temperature converter, #Python, __init__method
import math
import math

class Temperature:
    def __init__(self, Celcius, Fahrenheit):
        self.Celcius = Celcius
        self.Fehrenheit = Fahrenheit
        return

    #Converting celcius tempereture to fehrenheit
    def convertere_to_Fohrenheit(self, Celcius):
        return float(self.Celcius * (5 / 9) + 32)       # Formula for converting C temp to F

    #Convertig Fehrenheit to celsius
    def convertere_to_Celcius(self, Fehrennheit):
        return float((self.Fehrenheit - 32) * 5 / 3)   # Formula for converting F to C
        
C = int(input("Enter Temperaturein Celcius:"))          # Getting C temp from user
f = int(input("Input Temperature in Fahrenheit:"))      # Getting F temp from user

p1 = Temperature(C, f)

print(f"{C}c to Fehrenheit: {p1.convertere_to_Fohrenheit("Celcius")}f")                    # 
print(f"{f}f to Celcius :{p1.convertere_to_Celcius("Fehrenheit")}c")
