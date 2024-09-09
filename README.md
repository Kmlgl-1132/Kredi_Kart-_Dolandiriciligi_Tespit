# Kredi_Kart-_Dolandiriciligi_Tespit
Paylaşılmış olan komut isteminin amacı; kredi kartı dolandırıcılığı ile ilgili veri setiyle model oluşturup, seçilmiş olan değişkenler üstünden tespit etmektir.
Veri seti validation kısmındaki veri sayısı arttırılması gerekir. "Class = 0" durumu için aşırı öğrenme mevcuttur. 
XGBoost için hiperparametre ayarı yapılmamıştır.

# Veri Seti Hakkında,
Avrupa'dan kredi kartı kullanıcılarının Eylül 2013'te gerçekleştirdiği işlemleri içeren bir veri setini analiz ettim. Veri seti, iki gün boyunca gerçekleşen işlemleri kapsamaktadır ve toplamda 284,807 işlem içermektedir. Bu işlemlerden 492'si dolandırıcılık olup, dolandırıcılık oranı sadece %0.172'dir. Veri seti oldukça dengesizdir ve pozitif sınıf (dolandırıcılıklar) toplam işlemlerin yalnızca küçük bir kısmını temsil etmektedir.

📊 Veri Setinin Özellikleri:
V1, V2, ... V28: PCA (Principal Component Analysis) dönüşümü ile elde edilen ana bileşenlerdir. Bu özellikler sayısaldır ve orijinal özelliklerden daha fazla bilgi içermez.

Time: Her bir işlemin ilk işlemden itibaren geçen süresi (saniye cinsinden).

Amount: İşlem tutarı, bu özellik örnek bağımlı maliyet duyarlılığı öğrenmesi için kullanılabilir.

Class: Yanıt değişkenidir ve dolandırıcılık durumunda 1, aksi takdirde 0 değerini alır.

💡 Gizlilik Notu: Orijinal özellikler ve veri hakkında daha fazla bilgi gizlilik nedenleriyle sağlanmamıştır. Veri setinin yalnızca sayısal dönüşümlü bileşenleri ve işlem bilgileri paylaşılmıştır.
