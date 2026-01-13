# ShopApp - ASP.NET Core MVC E-Commerce Project

Bu proje, modern bir e-ticaret uygulamasının temel özelliklerini barındıran, çok katmanlı mimari (N-Tier Architecture) ile geliştirilmiş bir web uygulamasıdır.

## 🚀 Kullanılan Teknolojiler
* **Backend:** ASP.NET Core MVC
* **ORM:** Entity Framework Core
* **Database:** Microsoft SQL Server
* **Identity:** ASP.NET Core Identity (Authentication & Authorization)
* **Frontend:** Bootstrap, JQuery, HTML5, CSS3
* **Design Patterns:** Repository Pattern, Unit of Work

## ✨ Öne Çıkan Özellikler
* **Ürün ve Kategori Yönetimi:** CRUD işlemleri ve kategori tabanlı filtreleme.
* **Identity Sistemi:** Kullanıcı kayıt, giriş, rol yönetimi (Admin/User) ve şifre işlemleri.
* **Alışveriş Sepeti:** Dinamik sepet yönetimi ve sipariş tamamlama.
* **Güvenlik:** Role-based authorization ve form validation.
* **Veritabanı Mimarlığı:** Çoklu DbContext yapısı ve verimli SQL sorguları.

## 🛠️ Kurulum
1. Repoyu klonlayın: `git clone https://github.com/kullanici-adin/repo-adin.git`
2. `appsettings.json` içindeki `ConnectionStrings` kısmını kendi SQL Server'ınıza göre güncelleyin.
3. Package Manager Console üzerinden `update-database` komutlarını çalıştırın.
4. Projeyi çalıştırın: `dotnet run`
