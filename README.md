# Kalkulátor
Kalkulátor na výpočet plateb, který vypočítá spropitné v % a dokáže rozdělit platbu dle počtu osob

print("Vítej v kalkulátoru plateb")

platba = int(input("Kolik máte celkem zaplatit v Kč ?\n"))

spropitné = int(input("Kolik chcete dát spropitné v (%)\n"))

Lidi = int(input("Mezi kolik lidí se má rozdělit částka?\n"))



spropitné = platba / 100 * spropitné / Lidi

platba = platba / Lidi 

print(f"Každý člověk by mněl zaplatit\n {platba} platba,\n {spropitné} spropitné,\n {Lidi} Lidi,\n")
