
#Uygulama : Sözlük Oluşturma ve Manipülasyon

#veri_bilimci_profili adında bir sözlük oluştur. Bu sözlüğe aşağıdaki anahtar-değer çiftlerini ekle:
#ad: "Ayşe"
#soyad: "Demir"
#uzmanlik_alani: "Doğal Dil İşleme"
#deneyim_yili: 5

data_scientist = {
    "İsim": "Ayşe",
    "Soy isim" : "Demir",
    "Uzmanlık alanı" : "Doğal Dil İşleme",
    "Deneyim Yılı" : "5"
}


#deneyim_yili değerini 6 olarak güncelle.
data_scientist["Deneyim Yılı"] = 6

print(data_scientist["Deneyim Yılı"])

#Sözlüğe yeni bir anahtar-değer çifti olarak programlama_dilleri: ["Python", "R", "SQL"] ekle. (Not: Değer bir liste olabilir!)

data_scientist["Programlama dilleri"] = ["Python", "R", "SQL"]
print(data_scientist)

#uzmanlik_alani anahtarını sözlükten sil.

del data_scientist["Uzmanlık alanı"]

#Sözlüğün son halini ekrana yazdır.
print(data_scientist)


