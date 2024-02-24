kucuk_harfler = "qwertyuıopğüasdfghjklşizxcvbnmöç"
buyuk_harfler = "QWERTYUIOPĞÜASDFGHJKLŞİZXCVBNMÖÇ"
sayilar = "0123456789"
ifadeler = "+-*/?}])([{&%$#£" 

p_length = int(input("Şifreniz kaç haneli olsun?"))
parola = ""






for i in range(p_length): 
    if i % 4 == 0:
        parola += random.choice(kucuk_harfler)
    elif i % 4 == 1:
        parola += random.choice(buyuk_harfler)
    elif i % 4 == 2:
        parola += random.choice(sayilar)
    elif i % 4 == 3:
        parola += random.choice(ifadeler)

print(f"Parolanız: {parola}")
