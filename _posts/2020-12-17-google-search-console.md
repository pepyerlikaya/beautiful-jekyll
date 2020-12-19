---
layout: post
title: Google Search Console Rehberi
date: '2020-12-17'
author: Hakan Yerlikaya
permalink: /google-search-console/
published: true
subtitle: Web sitenizin performansını iyileştirmesine yardımcı olacak Google Search Console rehberi.
---

Web sitenizin performansını iyileştirmesine yardımcı olacak Google Search Console rehberi.

İlk önce web sitenizi Google Search Console aracına kayıt etmek ile başlayalım. Daha sonra ise sitenizdeki önemli olan eksiklikleri gidereceğiz.

Bunlar ise XML site haritası oluşturmayı, ardından site doğrulama adımlarını ve gereksiz sayfaları arama sonuçlarından kaldırma işlemini ve en önemlisi sitenizin performansını iyileştirecek taktikler vereceğim.

<h2> Google Search Console </h2>

Web sayfanızı birbirinden farklı iki yöntemden herhangi birisini kullanarak yapabilirsiniz.

1. Alan Adı
2. URL Ön Eki

<h3> Alan Adı </h3>

Bu yöntem web sitenizi barındırdığınız DNS kayıtlarına TXT kaydı ekleyeceğiniz Google site verification kodunu ekleyerek gerçekleştire bilirsiniz.

Alan adı özelliğinin tek farkı ise tüm URL varyasyonların hepsini doğruluyor olması.

* http://example.com/
* http://www.example.com/
* https://example.com/
* https://www.example.com/

Kutucuğa sitenizin http, https ve www ön ekleri olmadan yazarak ilerleyin.

<img alt="Google Search Console Alan Adı" title="Google Search Console Alan Adı" src="/img/Google-Search-Console-Alan-Adi.png">

Alan sahipliğinizi DNS kaydıyla doğrulayın uyarısı ile karşılaşacaksınız.

<img alt="Google Search Console Alan Sahipliğinizi DNS Kaydıyla Doğrulayın" title="Google Search Console Alan Sahipliğinizi DNS Kaydıyla Doğrulayın" src="/img/Google-Search-Console-DNS-Kaydi-Dogrula.png">

TXT kaydını kopyalayın ve web sitenizi hangi hosting sağlayıcısında barındırıyor iseniz site adresini ziyaret edin.

* GoDaddy
* Veridyen
* Güzel Hosting
* Turhost

Web sayfamı GoDaddy hosting'de barındırdığımdan dolayı örneğim bu şekilde olacaktır.

1. GoDaddy hesabınıza giriş yapın.
2. Ürünlerim
3. Alan Adları
4. DNS'i Yönelt
5. Kayıtlar

<img alt="GoDaddy Kayıtlar" title="GoDaddy Kayıtlar" src="/img/GoDaddy-Kayitlar.png">

Ekle düğmesine tıklayarak aşağıdaki adımları takip ediniz.

* Tür: TXT
* Ana Bilgisayar: @
* TXT Değeri: Google TXT kaydını yapıştırın
* TTL: 1 Saat

<img alt="GoDaddy DNS TXT Kayıtlar" title="GoDaddy DNS TXT Kayıtlar" src="/img/GoDaddy-DNS-TXT.png">

<img alt="GoDaddy DNS Google TXT Kayıtlar" title="GoDaddy DNS Google TXT Kayıtlar" src="/img/GoDaddy-DNS-Google-TXT.png">

Değişiklikten sonra kaydet düğmesine tıklayarak yapmış olduğunuz değişiklikleri gözden geçirin.

<img alt="GoDaddy TXT Kayıtlar" title="GoDaddy TXT Kayıtlar" src="/img/GoDaddy-TXT-Kayitlar.png">

Google Search Console aracına geri dönerek doğrula düğmesine tıklayın. DNS kayıt değişiklikleri biraz zaman alacağından dolayı Sahiplik Doğrulamadı uyarısı alabilirsiniz.

<img alt="Google Search Console Sahiplik Doğrulanamadı" title="Google Search Console Sahiplik Doğrulanamadı" src="/img/Google-Search-Console-Sahiplik-Dogrulanamadi.png">

Birkaç saat sonra tekrardan doğrula yapacağınız zaman 

<h3> URL Ön Eki </h3>

Web sayfanızı bir başka özellik olan URL ön eki özelliğini kullanarakta yapabilirsiniz.

Burada dikkat etmeniz gereken nokta ise web sitenizin tüm URL varyasyonlarını tek tek ekleyerek doğrulama yapmalısınız. 

Aşağıdaki örneğe göz atarak sitenizin URL varyasyonlarını ekleyin.

* http://example.com/
* http://www.example.com/
* https://example.com/
* https://www.example.com/

<img alt="Google Search Console URL Ön Eki" title="Google Search Console URL Ön Eki" src="/img/Google-Search-Console-URL-On-Eki.png">

1. HTML Dosyası
2. HTML Etiketi
3. Google Analytics
4. Google Etiket Yöneticisi
5. Alan Adı Sağlayıcı

<img alt="Google Search Console Sahipliği Doğrulayın" title="Google Search Console Sahipliği Doğrulayın" src="/img/Google-Search-Console-Sahipligi-Dogrulayin.png">

<h4> HTML Dosyası </h4>

HTML dosyasını indirin.

cPanel dosya yöneticisi bölümüne erişerek sitenizin dosyaları bulunduğu bölüme indirmiş olduğunuz dosyayı yükleyin.

<img alt="Google Search Console HTML Dosyası" title="Google Search Console HTML Dosyası" src="/img/Google-Search-Console-HTML-Dosyasi.png">

<h4> HTML Etiketi </h4>

Benzersiz olarak verilen HTML etiketi veya meta etiketi kopyalayın.

<img alt="Google Search Console HTML Etiketi" title="Google Search Console HTML Etiketi" src="/img/Google-Search-Console-HTML-Etiketi.png">

<h4> Google Analytics </h4>

Google Analytics, kullanıcıların web sayfanızı nasıl bulduklarını ne kadar süre geçirdikleri gibi sitenizde ne kadar zaman geçirdikleri gibi detaylı bilgilere sahip olma imkanınız bulunuyor.

Google Search Console aracına Google Analytics 

<img alt="Google Search Console Google Analytics" title="Google Search Console Google Analytics" src="/img/Google-Search-Console-Google-Analytics.png">

<h4> Google Etiket Yöneticisi </h4>

<img alt="Google Search Console Google Etiket Yöneticisi" title="Google Search Console Google Etiket Yöneticisi" src="/img/Google-Search-Console-Google-Etiket-Yoneticisi.png">

<h4> Alan Adı Sağlayıcı </h4>

<img alt="Google Search Console Alan Adı Sağlayıcı" title="Google Search Console Alan Adı Sağlayıcı" src="/img/Google-Search-Console-Alan-Adi-Saglayici.png">


