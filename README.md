# 11.hafta-1.-dev
#ödev: fonksiyona parametre olarak verilen 3 basmaklı bir sayının tam bölünenlerini yazdırın?
#asal çarpanları bulacaksınız?
for i in range(0,50):
    if i%3==0:
        print(i)
i = 2
sayı = 50
liste=[]
çarpan=[]

while i < sayı:

    if sayı % i == 0:
        print(i)
        liste.append(i)
    i += 1
del i
#print(liste)
for i in liste:
    bitir=True
    for a in liste:
        if (bitir):
            if(i==a):
                çarpan.append(i)
            elif(i%a==0):
                bitir=False



