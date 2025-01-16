from datetime import date

def yas_hesapla():
    dogum_yili = int(input("Doğum yılınızı girin: "))
    bugun = date.today()
    yas = bugun.year - dogum_yili
    
    print(f"Yaşınız: {yas}")

yas_hesapla()
