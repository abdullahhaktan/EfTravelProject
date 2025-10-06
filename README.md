# EfTravelProject

[TR]

**Entity Framework Kullanılarak Geliştirilmiş Seyahat ve Gezi Yönetim Uygulaması**

[![Entity Framework](https://img.shields.io/badge/ORM-Entity_Framework-774996.svg)](https://docs.microsoft.com/en-us/ef/)
[![C#](https://img.shields.io/badge/Language-C%23-blue.svg)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![Database](https://img.shields.io/badge/Database-SQL_Server-CC2927.svg)](https://www.microsoft.com/en-us/sql-server)
[![GitHub repo size](https://img.shields.io/github/repo-size/abdullahhaktan/EfTravelProject)](https://github.com/abdullahhaktan/EfTravelProject)

---

## 💻 Proje Hakkında

Bu proje, **Entity Framework (EF)** teknolojisinin veri erişim katmanında nasıl kullanılacağını gösteren, basit bir **seyahat ve gezi yönetim uygulamasıdır**. Temel amaç, **Code First** veya **Database First** yaklaşımıyla veritabanı işlemlerini, özellikle **CRUD** operasyonlarını, pratik olarak uygulamaktır.

---

## ✨ Temel Özellikler

### Entity Framework Uygulaması
* **ORM (Object-Relational Mapping):** Veritabanı tablolarının C# sınıfları (Entity'ler) olarak temsil edilmesi ve yönetilmesi.
* **CRUD Operasyonları:** Gezi, rotalar ve kullanıcılar gibi temel varlıklar üzerinde **ekleme, listeleme, güncelleme ve silme** işlemlerinin EF aracılığıyla gerçekleştirilmesi.
* **LINQ Kullanımı:** Veri sorgulamalarının C# kodu içinde (Language Integrated Query) ile yazılması.
* **İlişkisel Veri Yönetimi:** Tablolar arası **bire-çok (one-to-many)** ve **çok-çok (many-to-many)** ilişkilerinin EF ile modellenmesi.

### Fonksiyonel Modüller (Varsayımsal)
* **Rota/Gezi Yönetimi:** Yeni gezi rotaları oluşturma, lokasyon ve tarih bilgilerini yönetme.
* **Kullanıcı Kayıtları:** Gezilere katılan veya rezervasyon yapan kullanıcıların takibi.
* **Listeleme ve Filtreleme:** Gezilerin destinasyon, fiyat veya tarihe göre listelenmesi ve filtrelenmesi.

### Kullanılan Teknolojiler
* **C#:** Programlama dili.
* **Entity Framework (EF):** Veri erişim teknolojisi.
* **SQL Server:** Veritabanı yönetim sistemi.
* **.NET (Web/Console):** Uygulama altyapısı (projenin türüne göre).

---

## 🚀 Nasıl Çalıştırılır?

Bu proje, bir **SQL Server** veritabanı ve **Visual Studio** ortamını gerektirir.

1.  **Projeyi Klonlama:**
    ```bash
    git clone [https://github.com/abdullahhaktan/EfTravelProject](https://github.com/abdullahhaktan/EfTravelProject)
    cd EfTravelProject
    ```

2.  **Veritabanı Kurulumu:**
    * **Entity Framework Migrations** kullanılıyorsa: **Package Manager Console** üzerinden `Update-Database` komutunu çalıştırarak veritabanını oluşturun veya güncelleyin.
    * Manuel kurulum gerekiyorsa: **SQL Server Management Studio'yu** açın ve projenin gerektirdiği şemayı (tabloları) oluşturun.

3.  **Bağlantı Dizesini Ayarlama:**
    * Projenin yapılandırma dosyasındaki (`Web.config` veya `appsettings.json`) **SQL Server bağlantı dizesini** kendi yerel sunucu adınıza göre güncelleyin.

4.  **Projeyi Başlatma:**
    * **Visual Studio** ile `.sln` (Solution) dosyasını açın.
    * Gerekliyse **NuGet** paketlerini geri yükleyin.
    * Uygulamayı çalıştırın (F5).

---
---

[EN]

# EfTravelProject

**Travel and Tour Management Application Developed Using Entity Framework**

---

## 💻 About the Project

This project is a simple **travel and tour management application** demonstrating the use of **Entity Framework (EF)** in the data access layer. The primary goal is to practically apply database operations, particularly **CRUD** operations, using the **Code First** or **Database First** approach.

---

## ✨ Core Features

### Entity Framework Implementation
* **ORM (Object-Relational Mapping):** Representation and management of database tables as C# classes (Entities).
* **CRUD Operations:** Implementation of **Create, Read, Update, and Delete** operations on core entities like tours, routes, and users via EF.
* **LINQ Usage:** Writing data queries directly within C# code using Language Integrated Query.
* **Relational Data Management:** Modeling **one-to-many** and **many-to-many** relationships between tables using EF.

### Functional Modules (Assumed)
* **Route/Tour Management:** Creating new travel routes and managing location and date details.
* **User Records:** Tracking users who join or make reservations for tours.
* **Listing and Filtering:** Listing and filtering tours based on destination, price, or date.

### Technologies Used
* **C#:** Programming language.
* **Entity Framework (EF):** Data access technology.
* **SQL Server:** Database management system.
* **.NET (Web/Console):** Application platform (depending on project type).

---

## 🚀 How to Run

This project requires a **SQL Server** database and a **Visual Studio** environment.

1.  **Cloning the Project:**
    ```bash
    git clone [https://github.com/abdullahhaktan/EfTravelProject](https://github.com/abdullahhaktan/EfTravelProject)
    cd EfTravelProject
    ```

2.  **Database Setup:**
    * If **Entity Framework Migrations** are used: Run the `Update-Database` command via the **Package Manager Console** to create or update the database.
    * If manual setup is needed: Open **SQL Server Management Studio** and create the required schema (tables) for the project.

3.  **Configuring the Connection String:**
    * Update the **SQL Server connection string** in the project's configuration file (`Web.config` or `appsettings.json`) to match your local server name.

4.  **Starting the Project:**
    * Open the **`.sln`** (Solution) file with **Visual Studio**.
    * Restore **NuGet** packages if necessary.
    * Run the application (F5).

---
---

<img width="865" height="423" alt="Ekran görüntüsü 2025-10-06 114033" src="https://github.com/user-attachments/assets/e2858745-2e7e-4605-946a-f4b77d152932" />
