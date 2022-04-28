# HesapMakinesii
PerformansÖdevi
print("--Hoşgeldiniz--")
print("Şevval Ela Sarıipek 9/A 626 ")
sayi1 = int(input("Birinci Sayıyı Giriniz: "))
sayi2 = int(input("İkinci Sayıyı Giriniz: "))

hesapmakinesi = input("Bir İşlem Seçiniz(+,-,*,/) : ")

if hesapmakinesi == "+":
  sonuc = sayi1 + sayi2
  print(sayi1, "+", sayi2, "=", sonuc)
  
elif hesapmakinesi == "-":
  sonuc = sayi1 - sayi2
  print(sayi1,"-",sayi2, "=", sonuc)

elif hesapmakinesi == "*":
  sonuc = sayi1 * sayi2
  print(sayi1,"*", sayi2,"=",sonuc)


elif hesapmakinesi == "/":
  sonuc = sayi1 / sayi2
  print(sayi1,"/",sayi2,"=",sonuc)


else:
  print("Hatalısınız yeniden deneyiniz!")
