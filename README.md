<img width="939" height="274" alt="Ekran görüntüsü 2025-11-27 154809" src="https://github.com/user-attachments/assets/d4cfa48d-1488-4c11-a802-db96c7b8a491" /># AgricultureManagementSystem

[TR]

**ASP.NET Core MVC + Entity Framework Core + Identity Kullanılarak Geliştirilmiş Tarım Yönetimi Uygulaması**

[![Entity Framework](https://img.shields.io/badge/ORM-Entity_Framework_Core-6C2DBE.svg)](https://docs.microsoft.com/en-us/ef/core/)
[![C#](https://img.shields.io/badge/Language-C%23-blue.svg)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![ASP.NET Core](https://img.shields.io/badge/Framework-ASP.NET_Core-5C2D91.svg)](https://docs.microsoft.com/en-us/aspnet/core/)
[![Database](https://img.shields.io/badge/Database-SQL_Server-CC2927.svg)](https://www.microsoft.com/en-us/sql-server)
[![GitHub repo size](https://img.shields.io/github/repo-size/username/AgricultureManagementSystem)](https://github.com/username/AgricultureManagementSystem)

---

## 💻 Proje Hakkında

Bu proje, **ASP.NET Core MVC**, **Entity Framework Core** ve **Identity** teknolojilerini kullanarak geliştirilmiş bir **tarım yönetimi uygulamasıdır**.  
Amaç, kullanıcıların **tarım hizmetlerini, duyuruları, ekip üyelerini ve iletişim bilgilerini** yönetebildiği bir sistem oluşturmaktır.

---

## ✨ Temel Özellikler

### Kullanıcı ve Kimlik Yönetimi
* **Login/Logout:** ASP.NET Core Identity ile güvenli giriş ve çıkış işlemleri.
* **Rol Yönetimi:** Kullanıcı yetkilendirme (Admin, User vb.).

### CRUD Operasyonları
* **Duyurular:** Ekleme, güncelleme, silme ve listeleme.
* **Hizmetler:** Tarım hizmetlerini yönetme.
* **Takım Yönetimi:** Ekip üyeleri ekleme, düzenleme ve silme.
* **Adres ve İletişim Yönetimi:** Firma veya çiftçi bilgilerini kaydetme ve görüntüleme.

### Validasyon
* **FluentValidation:** Model doğrulama ve kullanıcı dostu hata mesajları.
* **Tarih ve Alan Kontrolü:** Boş alan kontrolü, tarih geçerliliği, minimum karakter kontrolü.

### Kullanılan Teknolojiler
* **C#**  
* **ASP.NET Core MVC**  
* **Entity Framework Core**  
* **SQL Server**  
* **ASP.NET Core Identity**  
* **FluentValidation**  
* **Razor View Engine**

---

## 🚀 Nasıl Çalıştırılır?

1.  **Projeyi Klonlama:**
    ```bash
    git clone https://github.com/username/AgricultureManagementSystem
    cd AgricultureManagementSystem
    ```

2.  **Veritabanı Kurulumu:**
    * Eğer **EF Migrations** kullanıyorsa: **Package Manager Console** üzerinden `Update-Database` komutunu çalıştırın.  
    * Manuel kurulum gerekiyorsa: **SQL Server Management Studio** açın ve gerekli tabloları oluşturun.

3.  **Bağlantı Dizesi Ayarı:**
    * `appsettings.json` içindeki SQL Server bağlantı dizesini kendi ortamınıza göre güncelleyin:
    ```json
    "ConnectionStrings": {
        "DefaultConnection": "Server=YOUR_SERVER;Database=DbAgriculture;Trusted_Connection=True;Encrypt=True;TrustServerCertificate=True;"
    }
    ```

4.  **Projeyi Başlatma:**
    * Visual Studio ile `.sln` dosyasını açın.
    * Gerekirse NuGet paketlerini geri yükleyin.
    * **F5** ile çalıştırın.

---

[EN]

# AgricultureManagementSystem

**ASP.NET Core MVC + EF Core + Identity Based Agriculture Management System**

---

## 💻 About the Project

This project is an **agriculture management system** built with **ASP.NET Core MVC**, **EF Core**, and **Identity**.  
The goal is to manage **agriculture services, announcements, team members, and contact information** efficiently.

---

## ✨ Core Features

### User & Identity Management
* **Login/Logout:** Secure login and logout with ASP.NET Core Identity.
* **Role Management:** Admin and user role authorization.

### CRUD Operations
* **Announcements:** Add, update, delete, list.
* **Services:** Manage agriculture services.
* **Team Management:** Add, edit, delete team members.
* **Address & Contact Management:** Store and view addresses and contact information.

### Validation
* **FluentValidation:** Model validation with user-friendly messages.
* **Date & Field Control:** Non-empty fields, minimum character length, future date validation.

### Technologies
* **C#**  
* **ASP.NET Core MVC**  
* **Entity Framework Core**  
* **SQL Server**  
* **ASP.NET Core Identity**  
* **FluentValidation**  
* **Razor View Engine**

---

## 🚀 How to Run

1.  **Clone the Project:**
    ```bash
    git clone https://github.com/username/AgricultureManagementSystem
    cd AgricultureManagementSystem
    ```

2.  **Database Setup:**
    * If **EF Migrations** are used: run `Update-Database` in **Package Manager Console**.  
    * If manual setup: create required tables in **SQL Server Management Studio**.

3.  **Configure Connection String:**
    * Update the connection string in `appsettings.json` to match your local SQL Server.

4.  **Start the Project:**
    * Open the `.sln` file in Visual Studio.
    * Restore NuGet packages if needed.
    * Press **F5** to run.

---

<img width="938" height="434" alt="Ekran görüntüsü 2025-11-27 154457" src="https://github.com/user-attachments/assets/15499a4a-9d56-46cb-9510-38187d562771" />

---

<img width="938" height="440" alt="Ekran görüntüsü 2025-11-27 154614" src="https://github.com/user-attachments/assets/818ba918-dbbd-469b-9494-3169e1873686" />

---

<img width="916" height="365" alt="Ekran görüntüsü 2025-11-27 154747" src="https://github.com/user-attachments/assets/e344e509-2c8a-438e-943f-4172db653f12" />

---

<img width="939" height="274" alt="Ekran görüntüsü 2025-11-27 154809" src="https://github.com/user-attachments/assets/7fb67fda-cfc4-4143-b4a9-ba48e6a57573" />

---

<img width="939" height="274" alt="Ekran görüntüsü 2025-11-27 154809" src="https://github.com/user-attachments/assets/3f4c0668-9868-4042-8b4a-92298846d86e" />


---

<img width="937" height="269" alt="Ekran görüntüsü 2025-11-27 154825" src="https://github.com/user-attachments/assets/56bab2e2-241b-4123-b9ee-36e348ad865a" />

---

<img width="938" height="241" alt="Ekran görüntüsü 2025-11-27 154842" src="https://github.com/user-attachments/assets/3326380e-e26c-4572-9f29-67bd6d5cfece" />

