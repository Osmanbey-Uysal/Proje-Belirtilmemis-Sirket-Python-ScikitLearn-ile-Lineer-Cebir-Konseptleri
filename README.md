<p align="center">
  <b>Proje</b><br> 
  Belirtilmemiş Şirket | Python - Scikit Learn ile Lineer Cebir Konseptleri</b>
</p>

---

<p align="center">
  <b>İş Problemi</b><br>
  Veri bilimi ve makine öğrenmesinde Lineer Cebir’in konseptlerini anlamak ve uygulamak için temel oluşturulması hedeflenmektedir<br>
  Bu bağlamda Python programlama dili ve ilgili kütüphaneler kullanılarak Lineer Cebir, Temel İstatistikler, Boyut Azaltma ve Lineer Regresyon gibi konseptleri içeren bir çalışma yapılacaktır
</p>
<img width="1200" height="600" alt="0 Python Scikit Learn" src="https://github.com/user-attachments/assets/e1dd253f-63b3-437a-af00-eac4269caa1a" />

---

<p align="center">
  <b>VERİ SETİ HİKAYESİ</b><br>
  9 DEĞİŞKENDEN VE 769 GÖZLEMDEN OLUŞMAKTADIR
</p>
<img width="1920" height="1080" alt="-1 VERİ SETİ" src="https://github.com/user-attachments/assets/019e82cf-540a-4163-b514-c9be2bf86dc9" />

---

<p align="center">
  <b>1.ADIM</b><br>
  NUMPY, PANDAS, SCIKIT LEARN KÜTÜPHANELERİ VE SCIKIT LEARN KÜTÜPHANESİ İÇERİSİNDE GÖMÜLÜ OLARAK YER ALAN “LOAD_DIABETES” İSİMLİ VERİ SETİ YÜKLENDİ
</p>
<img width="1869" height="933" alt="Adım 1" src="https://github.com/user-attachments/assets/90f47b73-6035-4fad-a3d1-fbd46f3eb978" />

---

<p align="center">
  <b>2.ADIM</b><br>
  MEVCUT VERİ SETİ 2 BOYUTLU VERİ YAPISI VE BAĞIMSIZ DEĞİŞKEN OLARAK “X” ÜZERİNE TANIMLANDI. SÜTUN İSİMLERİ OLARAK KÜTÜPHANEDE VERİ SETİ İÇİN GÖMÜLÜ OLARAK YER ALAN İSİMLENDİRMELER KULLANILDI<br>
  MEVCUT VERİ SETİ 1 BOYUTLU VERİ YAPISI VE BAĞIMLI DEĞİŞKEN OLARAK “Y” ÜZERİNE TANIMLANDI. HEDEF İÇİN KÜTÜPHANEDE VERİ SETİ İÇİN GÖMÜLÜ OLARAK YER ALAN “KAN ŞEKERİ SEVİYESİ” KULLANILDI
</p>
<img width="1867" height="932" alt="Adım 2" src="https://github.com/user-attachments/assets/f5fe2731-c065-4c63-a045-2508aa173707" />

---

<p align="center">
  <b>3.ADIM</b><br>
  X BAĞIMSIZ DEĞİŞKENİ “HEAD” FONKSİYONU ARACILIĞIYLA İLK 5 GÖZLEM GELECEK ŞEKİLDE İNCELENDİ
</p>
<img width="1868" height="932" alt="Adım 3" src="https://github.com/user-attachments/assets/33b7b9f2-227e-4664-88de-2630700a6b97" />

---

<p align="center">
  <b>4.ADIM</b><br>
  Y BAĞIMLI DEĞİŞKENİ “HEAD” FONKSİYONU ARACILIĞIYLA İLK 5 GÖZLEM GELECEK ŞEKİLDE İNCELENDİ
</p>
<img width="1868" height="932" alt="Adım 4" src="https://github.com/user-attachments/assets/ad7fce59-6948-4447-a06a-e7de6a3538d5" />

---

<p align="center">
  <b>5.ADIM</b><br>
  X BAĞIMSIZ DEĞİŞKENİ VE Y BAĞIMLI DEĞİŞKENİ İÇERİSİNDE BOŞ DEĞERİN VARLIĞI “ISNULL” VE “VALUES.ANY” FONKSİYONLARI ARACILIĞIYLA KONTROL EDİLDİ
</p>
<img width="1867" height="932" alt="Adım 5" src="https://github.com/user-attachments/assets/94a13fc3-7e87-4cea-a7eb-4c20e49a87e8" />

---

<p align="center">
  <b>6.ADIM</b><br>
  “PRINCIPAL COMPONENT ANALYSIS (PCA)” TEKNİĞİ KULLANILARAK MEVCUT DEĞİŞKEN SAYISI 5’E İNDİRİLDİ<br>
  “FIT” FONKSİYONU ARACILIĞIYLA X BAĞIMSIZ DEĞİŞKENİNİN KOVARYANS YAPISI İNCELETİLDİ<br>
  “TRANSFORM” FONKSİYONU ARACILIĞIYLA ORJİNAL VERİ SETİNDE YER ALAN 10 DEĞİŞKEN YENİ OLUŞTURULAN 2 DEĞİŞKENE ENTEGRE EDİLDİ<br>
  YAPILAN ENTEGRASYON “X_PCA” İSİMLİ BİR DEĞİŞKENE TANIMLANDI
</p>
<img width="1867" height="932" alt="Adım 6" src="https://github.com/user-attachments/assets/1d725027-6a1a-4026-be31-6bc2203abc1a" />

---

<p align="center">
  <b>7.ADIM</b><br>
  “EN KÜÇÜK KARELER” TEKNİĞİ KULLANILARAK LİNEER REGRESYON MODELİ OLUŞTURULDU<br>
  “TRAIN_TEST_SPLIT” FONKSİYONU KULLANILARAK VERİNİN EĞİTİLMESİ VE TEST EDİLMESİ SAĞLANDI 
</p>
<img width="1867" height="932" alt="Adım 7" src="https://github.com/user-attachments/assets/9b4017a9-c13e-4bb8-a35c-77f883666026" />

---

<p align="center">
  <b>8.ADIM</b><br>
  OLUŞTURULAN LİNEER REGRESYON MODELİNİN PERFORMANSININ DEĞERLENDİRİLMESİ MAKSADIYLA “TEST” VERİ SETİ ÜZERİNDEKİ TAHMİNLERİ VE GERÇEK DEĞERLERİ ARASINDAKİ FARKI ÖLÇMEK İÇİN “ORTALAMA HATA KARE”, “ORTALAMA MUTLAK HATA” VE “R2 SKORU” METRİKLERİ KULLANILMIŞTIR
</p>
<img width="1867" height="932" alt="Adım 8" src="https://github.com/user-attachments/assets/7d9190b4-02b6-4e39-923e-1fa88a41ae96" />

---

<p align="center">
  <b>9.ADIM</b><br>
  MODELİN KATSAYILARI “COEF” FONKSİYONU ARACILIĞIYLA YAZDIRILDI<br>
  “INTERCEPT” FONKSİYONU ARACILIĞIYLA MODELİN 0 STANDARDINDA SUNDUĞU TAHMİN YAZDIRILDI 
</p>
<img width="1867" height="932" alt="Adım 9" src="https://github.com/user-attachments/assets/2f03e620-635c-4918-9d29-55f9f5b2e602" />

---

<p align="center">
  <b>PROJE SAHİBİ</b><br>
  OSMANBEY UYSAL
</p>

---
