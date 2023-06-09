<h1 align="center">Sistem Pemerintahan Berbasis Elektronik</h1>


## Fitur 

- Autentikasi Admin, Penulis dan Pembaca
- CRUD Kategori
- CRUD Tag
- CRUD Post
- CRUD Banner
- CRUD Logo
- CRUD Footer
- CRUD Tentang/About
- Rekomendasi post
- Like post
- Dan lain-lain

## User

**Admin**

- email: admin@gmail.com
- Password: 123123123

**Penulis**

- email: penulis@gmail.com
- Password: 123123123

**Pembaca**

- email: pembaca@gmail.com
- Password: 123123123

## Install

**Clone Repository**

```bash
git clone https://github.com/musyahya/laravel_8_blog.git
```

**Download zip**

```bash
extract file zip
```

## Buka di kode editor


## Install composer

```bash
composer update
```

## Copy .Env

```bash
copy .env.example menjadi .env
```

## Buat database di localhost 

```bash
buat nama database bebas
```

## Setting database di .env

```bash
DB_PORT=3306
DB_DATABASE=your database
DB_USERNAME=root
DB_PASSWORD=
```

## Generate key

```bash
php artisan key:generate
```

## Jalankan migrate dan seeder

```bash
php artisan migrate --seed
```

## Buat storage link

```bash
php artisan storage:link
```

## Jalankan Serve

```bash
php artisan serve
```
