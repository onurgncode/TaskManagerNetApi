## Programı Çalıştırmak için
Her iki appsettings.json dosyasınıda ayarlanmalı
"ConnectionStrings": {
    "DefaultConnection": "Server=servername;Database=DbName;Trusted_Connection=True;MultipleActiveResultSets=true;TrustServerCertificate=True"
}

## Database çağırması Migrations işlemi
dotnet ef migrations add DbDeneme --project C:\TaskManager\TaskUI.csproj // Oluşturma
dotnet ef database update --project C:\TaskManager\TaskUI.csproj // Güncelleme

Aldığımız Token Rolüne göre Get isteği gösteriliyor
![TokenAlma](https://github.com/user-attachments/assets/411b2f1b-1ff9-428b-ad9e-4dca33179c89)
![AdminVeri](https://github.com/user-attachments/assets/ef507a11-14b6-443e-84fb-e63ab8468ba9)
##Eğer Admin Olmasaydık 
![UserToken](https://github.com/user-attachments/assets/120dbe4f-8970-4172-ac7d-768d6b0717a9)

