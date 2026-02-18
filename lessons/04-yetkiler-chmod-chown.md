# 04 — Yetkiler (chmod & chown)

Linux'un Windows'tan en büyük farkı:
Güvenlik mantığıdır.

Linux'ta her dosyanın sahibi vardır.
Ve herkes her dosyayı açamaz.

---

## Dosya bilgilerini görme

ls -l

Çıktının başında şöyle bir ifade görürsün:

-rw-r--r--

Buna "dosya izinleri" denir.

---

## Harflerin anlamı

r → read (okuma)
w → write (yazma)
x → execute (çalıştırma)

---

## Kimler?

3 grup vardır:

user  → dosya sahibi
group → aynı gruptakiler
other → diğer herkes

---

## chmod

Dosya izinlerini değiştirir.

Örnek:

chmod +x script.sh

Bu komut dosyayı çalıştırılabilir yapar.

---

## Neden önemli?

Bir script indirirsin ama çalışmaz.
Sebebi genelde şudur:

izin yoktur.

Çözüm:

chmod +x script.sh

---

## chown

Dosyanın sahibini değiştirir.

sudo chown kullanici dosya.txt

Bu komut dosyanın sahibini değiştirir.

---

## Özet

chmod → izin değiştirir
chown → sahip değiştirir

Linux'ta birçok hata aslında izin hatasıdır.
