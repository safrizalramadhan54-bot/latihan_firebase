# Latihan Firebase

Aplikasi Flutter sederhana untuk latihan Firebase Authentication dengan metode Email dan Password.

## Fitur

- Login dengan email dan password
- Halaman register terpisah (nama lengkap, email, password, konfirmasi password)
- Validasi input sebelum dikirim ke Firebase
- Halaman Home yang menampilkan nama dan email pengguna
- Logout

## Teknologi

- Flutter (Dart)
- Firebase Core
- Firebase Authentication

## Struktur Singkat

```
lib/
  main.dart              -> AuthGate, LoginPage, RegisterPage, HomePage
  firebase_options.dart  -> konfigurasi Firebase (hasil FlutterFire CLI)
```

## Cara Menjalankan

1. Clone repository ini:

   ```bash
   git clone https://github.com/safrizalramadhan54-bot/latihan_firebase.git
   cd latihan_firebase
   ```

2. Pasang dependency:

   ```bash
   flutter pub get
   ```

3. Aktifkan **Email/Password** di Firebase Console, menu **Authentication > Sign-in method**.

4. Jalankan aplikasi:

   ```bash
   flutter run -d chrome
   ```

## Konfigurasi Firebase (jika memakai project sendiri)

```bash
firebase login
dart pub global activate flutterfire_cli
flutterfire configure
```

## Pembuat

Safrizal Ramadhan