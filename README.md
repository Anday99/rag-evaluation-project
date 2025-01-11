# rag-evaluation-project
RAG tabanlı modeller kullanılarak 5 paragraftan oluşan 50 adet soru üzerinde yanıt tahmini üretildi. Üretilen yanıtlar RAGAS metriklerine göre değerlendirildi. RAG tabanlı modellerin ürettiği yanıtlar BERT tabanlı modellere bağlam olarak verildi ve yanıtların optimize edilmesi sağlandı.

# Örnek Soru Veri Seti
Örnek test sorularının yer aldığı veri seti questions.json dosyasında yer almaktadır.

# RAG Tabanlı Modeller Kullanılarak Cevapların Üretilmesi
RAG Modellerinden Tahmin Üretme.ipynb dosyası içerisindeki kodlar çalıştırılarak 3 farklı RAG tabanlı model için sonuçlar üretilir ve belirlenen dosya yoluna kayıt edilir.

# RAG Tabanlı Modellerden Üretilen Cevapların Değerlendirilmesi
RAG Model Sonuçları.ipynb dosyası içerisindeki kodlar çalıştırılarak 3 farklı RAG modelinin ürettiği sonuçlar belirli RAGAS metriklerine göre değerlendirilir ve grafikler çıktıları oluşturulur. Elde edilen sonuçlar BERT tabanlı modellerin kullanımına verilmek üzere saklanır.

# BERT Tabanlı Modelleri Kullanarak RAG Tabanlı Modellerin Cevaplarından Yeni Cevapların Oluşturulması
bert-base-turkish-squad.ipynb, bert-turkish-question-answering.ipynb ve mdeberta-v3-base-squad2.ipynb dosyaları içerisindeki kodlar çalıştırılarak her bir BERT tabanlı modelin RAG tabanlı modeller tarafından üretilen cevapları bağlam olarak alması ve yeni cevaplar üretmesi sağlanır. Sonuçlar RAGAS metrikleri ile değerlendirilerek grafik haline getirilir.
