# Uyku Analizi Projesi

Bu proje, uyku süresi ve günlük adım sayısı verilerinin incelenmesini sağlayan bir araçtır. Verilerin analiz edilmesiyle uyku düzeni ile günlük aktivite arasındaki ilişkiler keşfedilebilir.

## Kurulum

Proje kodunu klonlamak için aşağıdaki komutu kullanın:
https://github.com/Volkan35Koc/uyku-analizi-projesi

Projenin çalışması için aşağıdaki bağımlılıkların yüklü olması gerekmektedir:

- Python 3.x
- Pandas
- Matplotlib ve Seaborn

Gerekli bağımlılıkların yüklenmesi için aşağıdaki komutu çalıştırın:
pip install -r uyku.txt

## Kullanım

Proje kodunu çalıştırmak için aşağıdaki komutu kullanın:
python uyku_analizi.jpynb --input_file uyku.csv

Parametreler:
- `--input_file`: Uyku ve adım verilerinin bulunduğu CSV dosyasının yolu

## Veri Formatı

Uyku ve adım verileri, aşağıdaki sütunlarda bulunan bir CSV dosyasında olmalıdır:

- `Tarih`: Verilerin kaydedildiği tarih (YYYY-MM-DD formatında)
- `UykuSaati`: Günlük uyku süresi (saat olarak)
- `GunlukAdimsayisi`: Günlük adım sayısı

Örnek veri:

Tarih,UykuSaati,adim_sayisi 2022-01-01,7,8000 2022-01-02,6.5,10000 2022-01-03,8,6000


## Analiz Sonuçları

Proje, verilerin analiz edilmesi ve uyku süresi ile adım sayısı arasındaki ilişkilerin görselleştirilmesiyle çeşitli sonuçlar üretmektedir. Analiz sonuçları, proje çıktı klasöründe oluşturulan grafik dosyaları olarak kaydedilir.

## Katkıda Bulunma

Bu proje, geliştirilmeye açıktır. Katkıda bulunmak isterseniz, lütfen bir 'issue' açın veya bir 'pull request' gönderin.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakın.

## Destek ve İletişim

Proje hakkında sorularınız veya geribildirimleriniz için aşağıdaki e-posta adresine iletişime geçebilirsiniz:

volkankoc3535@outlook.com

