---
description: İyi oyun nasıl olur?
---

# Bilgisayar Oyunları

## OYUN TÜRLERİ

Neredeyse bütün oyunlar belli başlı ANA KATEGORİLERE dahildirler.

### Masa oyunları

Satranç yada yapboz gibi oyunlar. Yüzyıllardır insanların beğendiği bir gurup oyundur.

![scratch ile satran&#xE7; bile yazabilirsiniz](.gitbook/assets/satranc.png)

### Yarış Spor

![Spor yada araba yar&#x131;&#x15F;lar&#x131;](.gitbook/assets/spor.png)

### Rol oynama

![ejderhalar kaleler kanl&#x131; karanl&#x131;k safa&#x15F;lar](.gitbook/assets/rol.png)

### Savaş

![parmaklar&#x131;n sava&#x15F;&#x131;](.gitbook/assets/savas.png)

### Strateji

![kararlar &#xFC;zerine kurulu oyunlar](.gitbook/assets/strateji.png)

### Çok oyunculu

![](.gitbook/assets/cok-oyunculuk.png)

### Müzik Dance

Sanal bir enstruman çalınıyor

![](.gitbook/assets/guitar-hero-3_4.jpg)

## İyi Oyun Nasıl Olur?

**Bazı oyunları** oyuncular tekrar ve tekrar oynamak ister. İşte böyle oyunlar geliştirmek için öncelikle oyunlar hangi elemanlardan oluşuyor onu düşünüp, bunların nasıl bir araya geleceğini öğrenmeliyiz.

### Atmosfer

![oyundaki t&#xFC;m renkler oyuna uygun olmal&#x131;](.gitbook/assets/project-octopath-9.jpg)

#### Hikaye

Oyun sahnesinin hazırlanabilmesi ve oyuncuların yapacaklarına bir anlam verebilmeleri için oyunların hikayeleri olmalıdır.

![Arkaplanda bir hikayesi olmal&#x131;](.gitbook/assets/karp.png)

#### Hız

Oyun hızı oyuncunun heyecanını etkiler

![gelecek bulan&#x131;kken durup d&#xFC;&#x15F;&#xFC;necek zaman olmaz](.gitbook/assets/afa.png)

#### Renk Paleti

![](.gitbook/assets/parlak.png)

![](.gitbook/assets/renk.png)

#### Mekan

Atmosfer oluşturmanın en kolay yollarından birisi elbette hikayenin geçtiği yeri seçmektir.

![](.gitbook/assets/kale.png)

![Dekor se&#xE7;me ekran&#x131;](.gitbook/assets/dekor.png)

### Tasarım

Bu bölümde kısaca windows içinde bulunan _Paint 3D_ kullanarak karakter tasarımı anlatılacak.

![](.gitbook/assets/octopath-traveler-niente-dlc-180618.jpg)

![oyuncular bir karakteri y&#xF6;netirler](.gitbook/assets/compiled_1200.0.jpg)

{% tabs %}
{% tab title="Karakterler" %}
Karakterler ; 

* Bir hayvan 
* Prenses 
* Yarış arabası 
* hatta bir baloncuk bile olabilir.

![dairelerden bile karakter olur](.gitbook/assets/1200x630bb.jpg)
{% endtab %}

{% tab title="Mekanik" %}
Mekanik oyundaki **eylem**lerdir. Yani 

* Zıplama
* Uçma
* Bir nesneyi tutma
* Büyü yapma
* Silah kullanma

![Mekanik oyunu g&#xFC;zel yapan ana unsurdur.](.gitbook/assets/1304872797.webp)
{% endtab %}

{% tab title="Kurallar" %}
Ne yapıp yapamayacağını söyleyen kurallar. Örneğin karakterin nasıl ve neleri yapabiliyor, duvarlardan geçebiliyor musun yada uçabiliyor musun?

![](.gitbook/assets/kural.png)
{% endtab %}

{% tab title="Hedefler" %}
Her oyunda mutlaka bir meydan okuma olmalı, başarılması gereken hedefler oyunları oynama isteği oluşturur. 

![](.gitbook/assets/hedef.png)
{% endtab %}

{% tab title="Kontroller" %}
Klavye, mouse, joystick ve haraket sensörleri.
{% endtab %}

{% tab title="Dünya" %}
Oyunun geçtiği sahne detaylarını da tasarım anında düşünmek gerekir.

Dünya oyuncuyu sınırlayacak duvarlara sahip mi? Mevsimler var mı?
{% endtab %}
{% endtabs %}

### Ses

**Kim sessiz oyun oynamak isterki?**

Oyunları çekici yapan en önemli unsurlardan biri de oyundaki seslerdir.

#### Müzik

![](.gitbook/assets/chrome_2019-01-24_17-03-51.png)

#### Ses efektleri

### Kod

Güzel bir oyun sorunsuz çalışan bir kod gerektirir.

![scratch ile m&#xFC;zik program kodu](.gitbook/assets/kod.png)

### Oyun Tasarımı

İyi pazarlama müzik yada tasarım bile kötü bir oyun tasarımını düzeltemez.

## Kodlar ne işe yarıyor

Bilgisayarlar henüz kendi başlarına düşünemiyor. Sadece programcıların kendilerine verdiği komutları yaparlar. Bilgisayarların anlayacağı dilde komutlar yazmayı öğreneceğiz.

![](.gitbook/assets/tavuk%20%281%29.png)

Diyelimki bir tavuğun tilkiye yakalanmadan dereden akan mısırları yemeye çalıştığı bir oyun yazmak istiyorsunuz.  Bu durumda 3 nesne için ayrı kod yazmanız gerekiyor.

1. Tavuk için
2. Tilki için kod
3. Mısırlar için kod

**Tavuk için Kod**

1. [ ] Ekranın sol altında görün
2. [ ] Aşağıdaki görevleri tekrarla
   1. [ ] Eğer oyuncu sol tuşa basarsa..
      1. [ ] Eğer gidebiliyorsan biraz sola git
   2. [ ] Eğer oyuncu sağ tuşa basarsa...
      1. [ ] Eğer gidebiliyorsan biraz sağa git
   3. [ ] Eğer oyuncu boşluk tuşuna basarsa
      1. [ ] Mısırlara doğru git

**Tilki için Kod**

* [ ] Ekranın ortasında görün
* [ ] Aşağıdaki görevleri tekrarla
  * [ ] Eğer tavuk sağımdaysa
    * [ ] biraz sağa git
  * [ ] Eğer Tavuk Solumdaysa
    * [ ] biraz sola git
  * [ ] Eğer tavuk bana dokunursa 
    * [ ] oyunu durdur

**Mısırlar için Kod**

* [ ] Ekranın üstünde görün
* [ ] Aşağıdaki görevleri tekrarla
  * [ ] biraz aşağı ilerle
  * [ ] biraz sağa ilerle
  * [ ] Eğer ekranın sonuna gelirsen
    * [ ] ekrandan kaybol
    * [ ] başladığın yerde tekrar görün
  * [ ] Eğer Tavuk dokunursa
    * [ ] oyun puan tablosuna bir puan ekle
    * [ ] ekrandan kaybol
    * [ ] başladığın yerde tekrar görün

### **Programlama Dilleri**

**Bu sayfadaki kodlar basit türkçe diliyle yazıldı böyle konuşma diliyle yazılan kodlara PSEUDO CODE denir.** 

PSEUDO CODE bilgisayarların anlayabileceği değil insanların anlayabileceği bir dildir.

Bigisayarların anlayabileceği bir dile çevrilmesi gerekir. Bu kitapta Scratch kodlama dilini kullanacağız.

Scratch kodlamayı öğrenmek için geliştirilmiştir.

