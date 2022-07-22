# kasiyer-programi

meyveler =["çilek","mandalina","muz","ananas"]
fiyatlar =["9","5","10","15"]

for veri in meyveler , fiyatlar:
    print(veri)

secenek = 1

while secenek == 1:
    soru = input("Hangi meyveyi istiyorsunuz ?")

    if soru=="çilek":
        kg = input("Kaç kilo çilek istiyorsunuz ?" )
        tutar1 = int(kg) * 9
        print("Çilek için ödeyeceğiniz tutar: " , tutar1)

    elif soru=="mandalina":
        kg = input("Kaç kilo mandalina istiyorsunuz ?" )
        tutar2 = int(kg) * 5
        print("Mandalina için ödeyeceğiniz tutar: " , tutar2)

    elif soru=="muz":
        kg = input("Kaç kilo muz istiyorsunuz ?" )
        tutar3 = int(kg) * 10
        print("Muz için ödeyeceğiniz tutar: " , tutar3)

    elif soru=="ananas":
        kg = input("Kaç kilo ananas istiyorsunuz ?" )
        tutar4 = int(kg) * 15
        print("Ananas için ödeyeceğiniz tutar: " , tutar4)

    cevap = input("Alışverişe devam etmek istiyor musunuz? (e/h) ")
    if cevap == "h":
        print("İyi günler.")
        break
    else :
        continue
