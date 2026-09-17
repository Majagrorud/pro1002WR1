# Exercise 1: Greeting and Age Check.py
navn = input("Hva heter du? ")
alder = int(input("Hvor gammel er du? "))

if alder >= 18:
    print(f"Velkommen, {navn}! Du er gammel nok til å komme inn.")
else:
    print(f"Beklager, {navn}, du er dessverre for ung til å komme inn.")

    # Exercise 2: Number List Processor
n = int(input("Skriv inn et tall n: "))

tall_liste = []
for i in range(1, n + 1):
    tall_liste.append(i)

print(tall_liste)

if n > 5:
    print("Listen er lang.")
else:
    print("Listen er kort.")

    # Exercise 4: Fruit Basket
frukt_kurv = {"apple": 10, "banana": 5, "orange": 8, "grape": 20}

frukt = input("Hvilken frukt leter du etter? ").lower()

if frukt in frukt_kurv:
    print(f"Vi har {frukt_kurv[frukt]} av {frukt}.")
    for bokstav in frukt:
        print(bokstav)
else:
    print("Vi har ikke den frukten.")

    # Exercise 5: Temperature Converter
celsius = float(input("Skriv inn temperatur i Celsius: "))
fahrenheit = celsius * 9 / 5 + 32

print(f"{celsius} Celsius er {fahrenheit} Fahrenheit.")

if fahrenheit > 80:
    print("Det er varmt!")
else:
    print("Det er ikke så varmt.")

temp_liste = [celsius, fahrenheit]
print(temp_liste)

# Exercise 8: Letter Counter
ord_input = input("Skriv inn et ord: ").lower()

bokstav_antall = {}
for bokstav in ord_input:
    if bokstav in bokstav_antall:
        bokstav_antall[bokstav] += 1
    else:
        bokstav_antall[bokstav] = 1

print(bokstav_antall)

if len(ord_input) > 5:
    print("Det er et langt ord!")
