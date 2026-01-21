# temperature-converter
学習用サンプル, simple temperature converter, #Python, __init__method
import math

class Temperature:
  def __init__(self, Celcius, Fahrenheit):
    self.Celciud = Celcius
    self.Fehrenheit = Fehrenheit

  #Converting celcius to fehrenheit
  def convert_to_Fahrenheit(self, Fahrenheit):
    rerturn float(self.Celcius * (5/ 9) + 32)       # Formula for converting Fahrenheit to Celcius

  #Converting Fehrenheit to Celcius
    def convert_to_acelcius(self, Fehrenheit):
      return float((self.Fehrenheit - 32) * 5 / 3)  #formula for converting celcius to fehrenheit

C = int(input("Input Temperature in Celcius: "))		# Getting C temp from user
F = int(input("Input Temperature in Fehrenheit: "))	# getting F temp from user

p1 = Temperature(C, F)

print(f"{C}c to Fehrenheit: {p1.convert_to_Fehrenheit("Celcius")}f")
print(f"{C}c to Fehrenheit: {p1.convert_to_Celcius("Fehrenheit")}c")
