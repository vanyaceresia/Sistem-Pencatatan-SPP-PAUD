# 💰SISTEM INFORMASI SPP PAUD💰
Sistem ini berisi fitur untuk melakukan pencatatan pembayaran SPP pada tingkat PAUD dengan menggunakan php 7.1.3
# ⚙️Requirement⚙️
1. XAMPP 7.1.3

2. Composer
# ⚙️Flowchart⚙️
![Flowchart SIA](https://github.com/vanyaceresia/Sistem-Pencatatan-SPP-PAUD/assets/152596005/b5c498fc-33f4-4e1a-ba7e-d57643d473dc)

# ⚙️Database⚙️ 
![Screenshot (501)](https://github.com/vanyaceresia/Sistem-Pencatatan-SPP-PAUD/assets/152596005/9b369d38-f9d9-4829-a44b-794522b75a42)

# ⚙️Structure⚙️
![Screenshot (500)](https://github.com/vanyaceresia/Sistem-Pencatatan-SPP-PAUD/assets/152596005/d7b91bed-bd33-4914-b879-7ab2923878a1)

# ⚙️Langkah-Langkah⚙️
Clone the repository
```
git clone https://github.com/ajikamaludin/spp-paud.git
```
Switch to the repo folder
```
cd spp-paud
```
Install all the dependencies using composer
```
composer install
```
Create database for this app, copy the example env file and make the required database configuration changes in the .env file
```
cp .env.example .env
```
Run the database migrations (Set the database connection in .env before migrating)
```
php artisan migrate --seed
```
Start the local development server
```
php artisan serve
```

# ⚙️Tampilan⚙️
![Screenshot (502)](https://github.com/vanyaceresia/Sistem-Pencatatan-SPP-PAUD/assets/152596005/1615d299-5bb7-4c54-bf39-df6b1292ee54)
