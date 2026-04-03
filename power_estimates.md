---
layout: page
title: HESAPLAMA
permalink: /intro/estimates/
---

[GİRİŞ](/intro/) | [EKSİKLER](/intro/downsides/) | [**HESAPLAMA**]


# Piyasadaki Aşırı Besleme Değerleri

Güç ve performans değerleri ölçülürken sadece tepe noktaya bakmak aldatıcı olabilir. Ancak burdaki amacımız motor karakteristiklerini veya güç bandını karşılaştırmak değildir. Tamamen potansiyellerin karşılaştırılmasıdır. Ayrıca işlemleri kolaylaştırmak için tork verileri göz ardı edilip sadece beygire bakılmıştır.
<br>
Tablodaki değerler, kendilerini kanıtlamış farklı garajların projelerinden alınmıştır. Projeleri görüntülemek için isimlerine tıklayabilirsiniz.

| Garaj                  | ND1 - 1.5L    | ND1 - 2.0L    | ND2 - 2.0L    | 
|:-----------------------|:-------------:|:-------------:|:-------------:|
| BBR GTi - Turbocharger |      210      |      247      |      295      |
| BBR GTi - S/C Stage 1  |       -       |      225      |      250      |
| BBR GTi - S/C Stage 2  |       -       |      245      |      290      |
| Fab9Tuning (HKS)       |       -       |     ~258      |     ~273      | 
| SPS Motorsport (HKS)   |       -       |      230      |      256      |

# 1.5L ND2 için Tahmini Değerler

Farklı aşırı besleme yöntemleri ve motor jenerasyonları birbirleriyle oranlanarak tahmini bir güç artış değeri bulunacaktır. <br>
Artış değerleri yüzdelik olarak değerlendirilecek ve fabrika verileri bu yüzdelik ile oranlanacaktır.

## Güç Artışlarının Oranlanması

Tablonun ilk iki sütununda 2.0L için supercharger ve turbocharger projeleri fabrika gücüyle oranlanmıştır. Bütün oranlar artış şeklinde ve anlaşılır olması adına yüzdelik olarak verilmiştir. Yani %12 olarak verilen değer 1.12 orana tekabül etmektedir.

| Garaj                  | 2.0 SC/ND1 Stok | 2.0 TC/ND1 Stok | 2.0 SC/ND2 Stok | 2.0 TC/ND2 Stok | 1.5 TC/Fabrika |
|:-----------------------|:---------------:|:---------------:|:---------------:|:---------------:|:--------------:|
| BBR GTi - Stage 1      |      %53        |      %54        |      %39        |      %39        |      %62       |
| BBR GTi - Stage 2      |       -         |       -         |      %61        |      %64        |       -        |
| Fab9Tuning (HKS)       |      %61        |       -         |      %52        |       -         |       -        |
| SPS Motorsport (HKS)   |      %44        |       -         |      %42        |       -         |       -        |

## Artış Oranlarının Yorumlanması
Tablo bir saf veri karmaşası olsa da bu sonuçları dikkatli analizlerle yorumlara bağlayacağız. <br>

## ND1 2.0 1.5 Artışı
Elimizde 1.5L için referans değerindeki en önemli veri. Ancak elde sadece tek bir veri olduğu için en en şüpheli yaklaşılması gerekendir aynı zamanda. Ancak 1.5L aşırı besleme projesi dünya genelinde markette pek yer edinmiyor. O yüzden kısıtlı veriden en çok bilgiyi çıkarmaya çalışacağız. Yalnız bunu yaparken bilginin önemini çok da abartmayacağız. <br>
BBR ND1 turboşarj projelerindeki artış çarpanlarını oranladığımızda 1.62/1.54= **1.05** sonucunu elde ediyoruz. Yani 1.5L Skyactive-G'nin 2.0L versiyonuna göre %5 daha çok tepki verdiğini görüyoruz. <br>
Bu bilgi ne kadar kulağa güzel gelse de unutmamak lazım ki ND1'de 2.0 modelin devir kapasitesi 1.5'tan daha kısıtlıydı. Aynı yüzde beşlik oranın ND2'de görünceğini ummak çok da sağlıklı olmayabilir. Ancak ND2 güncellemesinde [hafifletilmiş krank ve pistonların](https://paultan.org/2018/06/20/mazda-mx-5-update-detailed-2-0l-jumps-from-160-to-184-ps-lower-emissions-improved-active-safety) 1.5L versiyonunun da yararlandığını unutmamak lazım. Sadece bu güncellemeler 2.0 için daha fazla e-devir yani doğrudan daha fazla beygir demekken redline değeri değişmeyen 1.5L için görünür bir fark oluşturmadı. <br>
Sonuç olarak, %5 olarak belirlenen verim oranı **hesaplamalara dahil edilecektir** ancak ağırlığı diğer faktörlere göre düşük tutulacaktır. 


<details>
  <summary>BBR'dan notlar</summary>
    <p>
      <ul>
          <li>
            ND1 1.5L için limit 7 psi basınç olarak belirlenmiş. 
            <a href="https://bbrgti.com/blogs/news/bbr-210-bhp-turbocharger-upgrade-now-available-for-1-5-litre-engine-mx-5-nd-variants"
              target="_blank" rel="noopener noreferrer">
              bilgi için tıklayınız
            </a>
          </li>
          <li>
            ND2 stage 1 turbo ve stage 1 supercharger uygulamalarında motor güvenliği için devir limitini 7000'e düşürmüşler. Kararın fabrika yakıt sistemi kaynaklı olduğu söyleniyor. 
            <a href="https://bbrgti.com/products/bbr-mx-5-nd2-stage-1-turbo-2-0-2019-2024-184-ps) [bilgi için tıklayınız](https://bbrgti.com/products/bbr-mx-5-nd2-stage-1-turbo-2-0-2019-2024-184-ps"
              target="_blank" rel="noopener noreferrer">
              bilgi için tıklayınız
            </a>
          </li>
          <li>
            ND2 stage 1 254 bg. Stage 2 ise grafikteki gibi 295 bg. Bu farkı ise yakıt sisteminde yapılan değişikliklerle yapıyorlar. İddiaları o ki basit bir yakıt pompası ve enjektör değişiminden fazlasını yapmışlar, adına da BBR yakıt sistemi demişler. Bununla birlikte NGK Iridium bujiler var. 
            <a href="https://bbrgti.com/products/bbr-mx-5-nd2-stage-2-turbo-2-0-2019-2024-184-ps"
              target="_blank" rel="noopener noreferrer">
              bilgi için tıklayınız
            </a>
          </li>
          <li>
            ND2 stage 2 supercharger motor iç aksamının sağlığı için 290-300 beygire kısıtlanmış. Eğer döküm parçalara kullanılırsa paketin 360 bg göreceği belirtilmiş. 
          <a href="https://bbrgti.com/products/bbr-stage-two-mazda-mx-5-nd2-2019-2024-184-ps-supercharger-upgrade"
              target="_blank" rel="noopener noreferrer">
              bilgi için tıklayınız
          </a>
        </li>
      </ul>
    </p>
</details>


