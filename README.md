# ISE 465 - Bulut Bilişim Projesi: Nextcloud (AWS & Docker)

Bu proje, Sakarya Üniversitesi Bilgi Sistemleri Mühendisliği **ISE 465 Bulut Bilişim** dersi kapsamında hazırlanmıştır.

## 👥 Grup Üyeleri
* **Hamza Akbaş** - B211200056
* **Eren Porsuk** - B211200010
* **Osman Can** - B211200053

## 📺 Proje Tanıtım Videosu
Projenin kurulumu, mimarisi ve canlı demosunu içeren sunum videomuzu buradan izleyebilirsiniz:
👉 **[https://youtu.be/b0V2qGZtoJ4]**

## 📺 Proje Uygulama Link
Projenin web sitesine burdan erişebilirsiniz:
Kullanıcı adı : admin
Parola : admin123
👉 **[http://18.195.52.139:8080/login?clear=1]**


---

## ☁️ Proje Özeti
Bu çalışmada, **Amazon Web Services (AWS)** üzerinde **Docker** konteyner teknolojisi kullanılarak güvenli ve ölçeklenebilir bir **Kişisel Bulut Depolama (Nextcloud)** sistemi kurulmuştur.

### 🛠 Kullanılan Teknolojiler
* **Cloud Provider:** AWS (EC2 t2.micro)
* **OS:** Ubuntu Server 24.04 LTS
* **Container Engine:** Docker & Docker Compose
* **Application:** Nextcloud (App) + MariaDB (Database)

## 📂 Proje Dosyaları
* **[Rapor PDF](./bbNexCloudRapor.pdf):** Projenin tüm teknik detaylarını, mimari şemasını ve ekran görüntülerini içeren detaylı rapor.
* **[docker-compose.yml](./docker-compose-common.yml):** Projeyi ayağa kaldırmak için kullanılan otomasyon kodu.

## 🚀 Kurulum Komutları
Proje aşağıdaki komutlarla AWS üzerinde ayağa kaldırılmıştır:

```bash
# 1. Gerekli Paketlerin Kurulumu
sudo apt update && sudo apt install docker.io docker-compose -y

# 2. Servisin Başlatılması
sudo docker-compose up -d
