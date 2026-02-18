# 03 — Dosya ve Klasör İşlemleri

Bu bölümden sonra Linux'ta gerçek işler yapmaya başlayacaksın.

Artık sadece bakmayacağız.
Dosya oluşturacak, taşıyacak ve sileceğiz.

---

## touch

Boş dosya oluşturur.

touch not.txt

Kontrol:

ls

---

## mkdir

Klasör oluşturur.

mkdir belgeler

---

## cp

Dosya kopyalar.

cp not.txt kopya.txt

---

## mv

Dosyayı taşır veya adını değiştirir.

Dosyayı yeniden adlandırma:

mv not.txt yeni.txt

Başka klasöre taşıma:

mv yeni.txt belgeler/

---

## rm

Dosya siler.

rm kopya.txt

Dikkat:
Geri dönüşüm kutusu yoktur.
Silinen dosya geri gelmez.

---

## Klasör silme

Boş klasör:

rmdir belgeler

İçi dolu klasör:

rm -r belgeler

---

## En çok kullanılanlar

touch → dosya oluştur
mkdir → klasör oluştur
cp → kopyala
mv → taşı / yeniden adlandır
rm → sil
