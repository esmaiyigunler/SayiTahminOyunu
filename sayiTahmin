import random

#bilgisayarın rastgele seçeceği sayı

gizliSayi=random.randint(1,100)
print("1 ile 100 arasında bir sayı tuttum. Bakalım doğru tahmin edebilecek misin?")

while True:
    #kullanıcıdan tahmin alıyoruz
    tahmin=int(input("Tahmin ettiğin sayı: "))

    #tahmini kontrol ediyoruz
    if tahmin<gizliSayi:
        print("Daha büyük bir sayı tahmin et!")
    elif tahmin>gizliSayi:
        print("Daha küçük bir sayı tahmin et!")
    else:
        print("Tebrikler doğru tahmin ettin.")
        break 
