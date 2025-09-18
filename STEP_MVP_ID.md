# Step Membuat Aplikasi MVP

## 1. Tentukan Flow User
- Definisikan alur pengguna saat menggunakan aplikasi.
- Contoh: user login → tambah todo → lihat daftar todo.

## 2. Sketsa Desain Aplikasi
- Buat wireframe sederhana untuk memvisualisasikan user flow.
- Fokus pada kebutuhan utama (MVP).

## 3. Buat Backend
### 3.1 Tentukan Domain
- Contoh: Auth, Todo.

### 3.2 Tentukan Entity Bisnis
- Contoh: `LoginResponse`, `TodoList`.

### 3.3 Tentukan Interface Usecase & Repository
- Contoh: `AuthUsecase`, `TodoUsecase`, `UserRepository`, `TodoRepository`.

### 3.4 Implementasi Code
- Tulis implementasi usecase & repository sesuai kontrak interface.

### 3.5 Integrasi Delivery/Controller
- Hubungkan usecase dengan delivery/controller layer.

### 3.6 Pasang Controller di Router
- Mapping controller ke setiap route.

## 4. Buat Frontend
### 4.1 Tentukan API yang Akan Dihit
- Contoh: `/login`, `/todos`.

### 4.2 Buat Masing-Masing Page
- Contoh: LoginPage, TodoPage.

### 4.3 Assign ke Route
- Contoh: `/login`, `/todo`.

### 4.4 Integrasi Page & Komponen dengan API
- Hubungkan UI dengan backend melalui API.

## 5. Testing
### 5.1 Test Semua Fitur
- Pastikan flow berjalan dari frontend → backend → database.

### 5.2 Fix Semua Bug
- Perbaiki semua error/bug yang ditemukan saat pengujian.

## 6. Deploy
- Deploy backend & frontend ke server/hosting.
- Pastikan semua service bisa diakses oleh user.
