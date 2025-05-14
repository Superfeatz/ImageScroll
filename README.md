| Nama  | NRP         |
|--------|------------|
| Muhammad Hafidz Harridil Mahali | 5025221030 |

# 📜 ImageScroll (Affirmations App)

Aplikasi Android sederhana berbasis Jetpack Compose yang menampilkan daftar afirmasi harian yang dilengkapi dengan gambar inspiratif

## ✨ Fitur

* Menampilkan daftar afirmasi harian.
* Setiap afirmasi ditampilkan dalam bentuk kartu berisi teks dan gambar.
* Desain UI menggunakan `Material3` dan `Jetpack Compose`.
* Responsif terhadap status bar dan padding aman perangkat.

## 🧱 Struktur Proyek

```
app/
├── src/main/java/com/example/affirmations/
│   ├── MainActivity.kt          # Entry point aplikasi
│   ├── data/Datasource.kt       # Sumber data afirmasi
│   ├── model/Affirmation.kt     # Data class afirmasi
│   └── ui/theme/                # File terkait tema Compose
├── res/
│   ├── drawable/                # Gambar-gambar afirmasi
│   ├── values/strings.xml       # Daftar teks afirmasi
│   └── values/themes.xml        # Tema aplikasi
├── AndroidManifest.xml
└── build.gradle.kts
```

## 📱 Tampilan

Setiap item ditampilkan dalam bentuk kartu seperti berikut:

```
+---------------------------------------------+
| [Image Background]                          |
| "I am strong."                              |
+---------------------------------------------+
```

Contoh afirmasi:

* "I am strong."
* "I believe in myself."
* "New opportunities await me at every turn."


## 📦 Dependensi Utama

* Jetpack Compose
* Material3
* Kotlin Android Extensions
* AndroidX Activity Compose


