import random

karakter_dizisi = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
uzunluk = int(input('şifrenin uzunluğu ne kadar olsun? '))
parola = ''
for i in range(uzunluk):
    parola += random.choice(karakter_dizisi)
print(parola)
