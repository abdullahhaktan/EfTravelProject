# EfTravelProject

[TR]

**Entity Framework Kullanılarak Geliştirilmiş Seyahat ve Gezi Yönetim Uygulaması**

[![Entity Framework](https://img.shields.io/badge/ORM-Entity_Framework-774996.svg)](https://docs.microsoft.com/en-us/ef/)
[![C#](https://img.shields.io/badge/Language-C%23-blue.svg)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![Database](https://img.shields.io/badge/Database-SQL_Server-CC2927.svg)](https://www.microsoft.com/en-us/sql-server)
[![GitHub repo size](https://img.shields.io/github/repo-size/abdullahhaktan/EfTravelProject)](https://github.com/abdullahhaktan/EfTravelProject)

---

## 💻 Proje Hakkında

Bu proje, **Entity Framework (EF)** teknolojisinin veri erişim katmanında kullanımını gösteren, basit bir **seyahat ve gezi yönetim uygulamasıdır**.  
Amaç, **Code First** veya **Database First** yaklaşımıyla veritabanı işlemlerini ve **CRUD operasyonlarını** pratik olarak göstermek.

---

## ✨ Temel Özellikler

### Entity Framework Uygulaması
* **ORM (Object-Relational Mapping):** Veritabanı tablolarının C# sınıfları (Entity) olarak temsil edilmesi.
* **CRUD Operasyonları:** Gezi ve rehberler üzerinde **ekleme, listeleme, güncelleme, silme** işlemleri.
* **LINQ Kullanımı:** Verilere C# üzerinden sorgulama yapılması.
* **İlişkisel Veri Yönetimi:** Tablolar arası **one-to-many** ilişkilerinin modellenmesi (ör: Guide → Location).

### Fonksiyonel Modüller
* **Rehber Yönetimi:** Rehber ekleme, listeleme, güncelleme ve silme.
* **Lokasyon Yönetimi:** Turistik lokasyon ekleme, düzenleme, silme ve listeleme.
* **İstatistikler:** Kapasite, fiyat, rehber sayısı gibi özet bilgilerin görüntülenmesi.

### Kullanılan Teknolojiler
* **C#**  
* **Entity Framework (EF)**  
* **SQL Server**  
* **Windows Forms**  

---

## 🚀 Nasıl Çalıştırılır?

1.  **Projeyi Klonlama:**
    ```bash
    git clone https://github.com/abdullahhaktan/EfTravelProject
    cd EfTravelProject
    ```

2.  **Veritabanı Kurulumu:**
    * Eğer **EF Migrations** kullanıyorsa: **Package Manager Console** üzerinden `Update-Database` komutunu çalıştırın.  
    * Manuel kurulum gerekiyorsa: **SQL Server Management Studio** açın ve gerekli tabloları oluşturun.

3.  **Bağlantı Dizesi Ayarı:**
    * `Web.config` veya `appsettings.json` içindeki SQL Server bağlantı dizesini kendi ortamınıza göre güncelleyin.

4.  **Projeyi Başlatma:**
    * Visual Studio ile `.sln` dosyasını açın.
    * Gerekirse NuGet paketlerini geri yükleyin.
    * **F5** ile çalıştırın.

---

[EN]

# EfTravelProject

**Travel and Tour Management Application Developed Using Entity Framework**

---

## 💻 About the Project

This project is a simple **travel and tour management application** demonstrating **Entity Framework (EF)** usage in data access.  
The goal is to practically apply database operations, particularly **CRUD**, using **Code First** or **Database First** approaches.

---

## ✨ Core Features

### Entity Framework Implementation
* **ORM (Object-Relational Mapping):** Database tables represented as C# classes (Entities).  
* **CRUD Operations:** Create, Read, Update, Delete for tours and guides.  
* **LINQ Usage:** Query data directly from C# code.  
* **Relational Data:** One-to-many relationships (Guide → Location) modeled in EF.

### Functional Modules
* **Guide Management:** Add, list, update, delete guides.  
* **Location Management:** Add, update, delete, list tourist locations.  
* **Statistics:** View totals like capacity, price, guide count.

### Technologies
* **C#**  
* **Entity Framework (EF)**  
* **SQL Server**  
* **Windows Forms**  

---

## 🚀 How to Run

1.  **Clone the Project:**
    ```bash
    git clone https://github.com/abdullahhaktan/EfTravelProject
    cd EfTravelProject
    ```

2.  **Database Setup:**
    * If **EF Migrations** are used: run `Update-Database` in **Package Manager Console**.  
    * If manual setup: create required tables in **SQL Server Management Studio**.

3.  **Configure Connection String:**
    * Update the connection string in `Web.config` or `appsettings.json` to match your local SQL Server.

4.  **Start the Project:**
    * Open the `.sln` file in Visual Studio.  
    * Restore NuGet packages if needed.  
    * Press **F5** to run.

---

<img width="865" height="423" alt="Ekran görüntüsü" src="https://github.com/user-attachments/assets/e2858745-2e7e-4605-946a-f4b77d152932" />
