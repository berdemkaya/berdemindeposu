Dosya Adı
customer_experience_data (1).csv

Açıklama
Bu veri seti, müşteri deneyimi ile ilgili çeşitli bilgileri içermektedir. Veriler; müşteri memnuniyeti, alışveriş deneyimi, hizmet kalitesi, geri bildirimler ve demografik bilgileri kapsayabilir.
Bu veri seti, müşteri davranışlarını analiz etmek ve müşteri memnuniyetini artırmaya yönelik stratejiler geliştirmek için kullanılabilir.

Kullanım Amaçları
Müşteri memnuniyeti analizi
Segmentasyon çalışmaları
Hizmet kalitesi değerlendirmesi
Makine öğrenmesi modelleri için öngörü oluşturma
Veri analizi ve görselleştirme projeleri

Dosya Formatı:
CSV 

Kolon Bilgileri 
Customer_ID : Müşteri kimlik numarası
Age : Yaş
Gender : Cinsiyet
Location = Konum
Num_Interactions = Toplam etkileşim sayısı
Products_Purchased = Satın alınan ürün adedi
Products_Viewed = Görüntülenen ürün sayısı
Satisfaction_Score : Memnuniyet puanı (ör. 1-10 arası)
Feedback_Score : Müşteri geri bildirimi
Time_Spent_on_Site = Sitede geçirilen toplam süre (dakika
Retention_Status = Müşteri durumu
Gender_Encoded = Cinsiyetin sayısal kodlaması
Location_Encoded = Konumun sayısal kodlaması
Retention_Status_Encoded = Durumun sayısal kodlaması


Nasıl Kullanılır?
CSV dosyasını uygun bir veri analiz aracı ile açabilirsiniz:
Python (Pandas kütüphanesi)
Colab

Örnek Python kodu:
import pandas as pd
df = pd.read_csv('customer_experience_data (1).csv')
print(df.head())

Adımlar
Verinin yüklenmesi ve genel ön incelemesi
Eksik değerlerin analizi ve temizlenmesi
Keşifsel veri analizi (EDA)
Görselleştirme
(Opsiyonel) Model geliştirme ve değerlendirme

Gereksinimler
Python 3.x (opsiyonel)
Pandas
NumPy
Matplotlib
Seaborn

Berdem Nur Kaya
