﻿# Web Sitesi

Bu bir ürün satış web sitesidir. Bu web sitesi, C# programlama dilini kullanarak ASP.NET MVC tabanlı olarak geliştirilmiştir.

---

## Ekip Üyeleri:
- Annida Maharani Rakhmadi
- ePosta: 131830099@ogr.uludag.edu.tr
- Nagirash Toktabay
- eposta: 132130120@ogr.uludag.edu.tr

---

## Demo

[Demoyu izlemek için buraya tıklayın](https://youtu.be/BtA_7BZRASo?si=IqC80PJsPI4hlN8X)

---

## Özellikler

### 1. Kayıt ve Giriş

- Kullanıcılar Kayit Ol özelliği ile yeni bir hesap oluşturabilir.
- Kayıt olduktan sonra, Giriş Yap özelliği ile sisteme giriş yapabilirler.

### 2. Ürün Yönetimi

- Ürün Ekleme: Kullanıcılar sisteme yeni ürünler ekleyebilir.
- Ürün Detayları: Her ürün, ayrıntılı bilgilerin görüntülendiği bir sayfaya sahiptir.
- Ürün Düzenleme: Kullanıcılar ürün bilgilerini düzenleyebilir.
- Ürün Silme: Gereksiz ürünler silinebilir.

### 3. Veritabanı

- Kullanıcı Tablosu: user_id birincil anahtar olarak kullanılarak kullanıcı verilerini saklar.
- Ürün Tablosu: product_id birincil anahtar olarak kullanılarak ürün verilerini saklar.
- İşlem Tablosu: Kullanıcı ve ürün tablolarını bağlayarak satın alma işlemlerini kaydeder.

### 4. Controller

- Home Controller: Ana sayfanın veya uygulama giriş ekranının kontrolünü sağlar.
- Hesap Controller: Giriş, çıkış ve kullanıcı kayıt işlemlerini yönetir.
- Ürün Controller: Ürünler için CRUD (Ekle, Oku, Güncelle, Sil) işlemlerini yönetir.

---

## Uygulama Görünümleri

- Ana Sayfa: -Genel ürün listesini gösterir.
  -Giriş yapma, kayıt olma veya ürün ekleme gibi diğer sayfalara yönlendirme sağlar.
- Kayıt ve Giriş Sayfaları: -Kayıt Ol: Yeni kullanıcılar için bir form.
  -Giriş Yap: Kullanıcıların sisteme kimlik doğrulaması yapması için bir form.
- Ürün Detay Sayfası: -Ürünün adı, açıklaması, fiyatı ve görselleri gibi ayrıntılı bilgileri gösterir.
  -Kullanıcının ürün düzenleme veya silme seçeneklerine erişimi olabilir.

- CRUD Ürün Sayfaları: -Ürün Ekleme: Yeni ürünler eklemek için bir form.
  -Ürün Düzenleme: Mevcut ürünlerin bilgilerinin güncellenmesini sağlar.
  -Ürün Silme: Belirli bir ürünü kaldırmak için bir onay penceresi.

- Veritabanı Kök Dizini (Root Directory)
  Ürün görselleri ve diğer destekleyici dosyalar için ayrılmış bir klasör.

---

## Nasıl Kullanılır

- Hesap Kaydı
  -Kayıt sayfasını açın ve gerekli bilgileri doldurun.
  -Kayıt işleminden sonra, giriş yaparak sisteme erişin.
- Ürün Ekleme
  -Ürün Ekleme sayfasına gidin.
  -Ürün adı, açıklaması, fiyatı gibi bilgileri doldurun ve bir görsel yükleyin.
  -Kaydet butonuna tıklayarak ürünü sisteme ekleyin.
- Ürün Detaylarını Görüntüleme
  -Ana sayfadaki bir ürüne tıklayarak ayrıntılı bilgilerini görüntüleyin.
- Ürün Düzenleme veya Silme
  -Ürün detayları sayfasından Düzenle seçeneğini kullanarak bilgileri güncelleyin.
  -Sil seçeneği ile ürünü sistemden kaldırın.
- İşlemler
  -(Opsiyonel) Kullanıcılar ve ürünler arasındaki satın alma işlemleri için işlem tablosunu kullanın.

---

## Kullanılan Teknolojiler

- ASP.NET MVC
  -Model-View-Controller tabanlı bir yapıya ASP.NET framework’ü.
- Programlama Dili
  -C#: Backend ve veritabanı yönetimi için kullanılır.
- Veritabanı
  -SQLite: Kullanıcı, ürün ve işlemleri saklamak için kullanılan hafif bir veritabanı.
- HTML ve CSS
  -Giriş, ürün sayfaları ve diğer kullanıcı arayüzlerini oluşturmak için kullanılır.
- JavaScript (Opsiyonel)
  -Dinamik sayfa etkileşimleri ve form doğrulamaları için kullanılır.
- Program.cs
  -ASP.NET MVC uygulamasının başlatılması için kullanılan ana dosya.

---

## Lisans

Bu uygulama, ASP.NET MVC ve SQLite gibi modern teknolojiler kullanılarak oluşturulmuş basit bir pazar yeri uygulamasıdır. Ürün yönetimi, kullanıcı kimlik doğrulaması ve kolay kullanımlı arayüzü ile bu sistem, küçük ve orta ölçekli çevrimiçi satış ihtiyaçlarını karşılamak için uygundur.
