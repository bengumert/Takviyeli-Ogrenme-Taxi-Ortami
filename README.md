# Taksi Ortamında Q-Learning Uygulaması

Bu proje, OpenAI Gym kütüphanesindeki "Taxi-v3" ortamında bir takviyeli öğrenme ajanı (agent) eğitmek için Q-Learning algoritmasını kullanmaktadır. Amaç, ajanın en az ceza alarak ve en verimli şekilde yolcuları alıp bırakmasını öğrenmesini sağlamaktır.

## İçerik

Bu depo aşağıdaki Jupyter Notebook dosyasını içermektedir:

* **`taksi.ipynb`**: Bu not defteri, "Taxi-v3" ortamının temel kurulumunu, Q-Tablosu (Q-Table) ile Q-Learning algoritmasının uygulanmasını, ajanın eğitim sürecini ve eğitilmiş ajanın performansının değerlendirilmesini detaylı olarak göstermektedir. Eğitim boyunca alınan ödüller ve cezalar izlenir.

## Özellikler

* OpenAI Gym'in "Taxi-v3" ortamında deneyler yapma.
* Temel bir takviyeli öğrenme algoritması olan Q-Learning'in adım adım uygulanması.
* Q-Tablosu kullanarak öğrenme sürecini yönetme.
* Epsilon-greedy stratejisi ile keşif (exploration) ve sömürü (exploitation) dengesi.
* Eğitim sonrası ajanın performansını gözlemleme ve metriklerini analiz etme.
* 

## Kullanılan Teknolojiler

* **Python**
* **OpenAI Gym**: Takviyeli öğrenme ortamı sağlamak için.
* **NumPy**: Q-tablosu ve sayısal hesaplamalar için.
* **tqdm**: Eğitim döngülerinde ilerlemeyi göstermek için.
