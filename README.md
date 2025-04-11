1. Paket yöneticisi (apt) hakkında bilgiyi görüntülemek için kullanılan konutu yazınız?

Komut:

apt

-help

2. "grep" komutuna ilişkin detaylı bilgileri görüntülemek için kullanılan komutu yazınız?

Komut: man

grep

3. Linux İşletim sisteminin dağıtım bilgisini görüntülemek için kullanılan komutu yazınız?

Komut:

cat /etc/issua

Komut: Isb-release

4. İşletim sisteminin kullandığı kernel versiyonunu ve ağ içinde kullanılan host adını görüntülemek için kullanılan komutları yazınız?

Komut: uname

Komut:

uname

13

5. İşletim sisteminin hangi kimlikle çalıştığını ve en son ne zaman açıldığını bilgisini veren komutları yazınız?

Komut:

whoami

Komut: who-b

6. Disk kullanımına dosya bilgisini de dahil ederek görüntülemek için kullanılan komutu yazınız?

Komut: df -T

7. Bellek ve Swap alanını görüntülemek için kullanılan komutu yazınız?

Komut: free

8. $cd/usr/local/bin

$cd../../local

spwd hangi dizinde olduğunu

Yukarıdaki komut bloğu çalıştırıldığında oluşan çıktı ekranını yazınız?

Çıktı: /usr/local

9. Sistemde sadece 'b' ile başlayan gizli dosyaları görüntülemek için kullanılan komutu yazınız?

Komut: Is-d.b

10. Sistemdeki dosyaları büyüklüğüne ve dosya üzerinde yapılan değişiklik tarihine göre sıralayan

komutları yazınız?

Komut: Is 5

Komut: Is-1+


------------------------


Adım 1: cd Masaüstü
Masaüstü dizinine geçilir.

Adım 2: touch guvenlik.txt
Boş bir guvenlik.txt dosyası oluşturulur.

Adım 3: cat > guvenlik.txt
guvenlik.txt dosyasına kullanıcıdan veri girişi alınır. (Kullanıcıdan “CİSEN” ile başlayan veriler girilmiş)

Adım 4: Ctrl+D
cat komutundan çıkılır ve dosya kaydedilir.

Adım 5: cat >> guvenlik.txt
guvenlik.txt dosyasına veri eklemek için tekrar giriş yapılır.

Adım 6: Kullanıcı yeni veri girer

Adım 7: Ctrl+D ile veri girişi tamamlanır ve dosya kapanır.
Son olarak cat guvenlik.txt ile dosya içeriği görüntülenir.

2. cat -n /etc/passwd komutunun işlevi:

Açıklama:
/etc/passwd dosyasını satır numaralarıyla birlikte ekrana yazdırır.
-n parametresi, satır numaralarını görüntülemeye yarar.

3.

$ echo Açık Kaynak > ders1.txt
$ echo İşletim Sistemi > ders2.txt
$ cat ders1.txt ders2.txt

Ekran Çıktısı:

Açık Kaynak
İşletim Sistemi

4. Sadece 2. satırı görüntülemek için:

Komut:

sed -n '2p' Deneme.txt

5. passwd dosyasının ilk ve son 5 satırını görüntülemek için:

Komut:

head -n 5 /etc/passwd
tail -n 5 /etc/passwd

6. 
touch okul.txt
echo "Adınız Soyadınız" > okul.txt
echo "Okuduğunuz bölüm" >> okul.txt
cat okul.txt
wc -w okul.txt
wc -m okul.txt

7.
touch ben.txt program.txt
echo "Ad Soyad Memleket" > ben.txt
echo -e "Python\tC++\tJava" > program.txt
paste ben.txt program.txt > birlestirme.txt
mkdir komut
mv birlestirme.txt komut/

8. 
mkdir yetki
cd yetki
touch yetkilendirme.txt
ls -l
chmod 722 yetkilendirme.txt
ls -l


