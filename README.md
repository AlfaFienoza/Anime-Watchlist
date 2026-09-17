# 🌌 Anime Universe – Watchlist & Tracker

![Next.js](https://img.shields.io/badge/Next.js-15.4.7-black?style=for-the-badge&logo=next.js)  
![Firebase](https://img.shields.io/badge/Firebase-Backend-orange?style=for-the-badge&logo=firebase)  
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-Design-blue?style=for-the-badge&logo=tailwindcss)  
![TypeScript](https://img.shields.io/badge/TypeScript-Strict-blue?style=for-the-badge&logo=typescript)  
![Anime](https://img.shields.io/badge/Powered%20by-AniList%20API-blue?style=for-the-badge&logo=graphql)

✨ Sebuah aplikasi web modern untuk menjelajahi anime, membuat
watchlist, melacak progress episode, dan mengatur profil pribadi.

---

## ⚠️ Status Project

🚧 **Project ini masih dalam tahap pengembangan.**  
Masih terdapat beberapa bug dan error yang perlu diperbaiki, serta fitur-fitur yang mungkin belum sepenuhnya berfungsi dengan baik.  
Kontribusi, saran, dan masukan sangat diterima untuk membantu pengembangan lebih lanjut. 🙌

---

## 📸 Preview

[Coming Soon]

---

## 🚀 Fitur Utama

- 🔍 **Cari & Temukan Anime** – Trending, populer, movie top, dan yang akan datang.
- 🎬 **Detail Anime Lengkap** – Score, genre, sinopsis, studio, rating, dan informasi lainnya.
- 📑 **Watchlist Pribadi** – Simpan anime favoritmu dan kelola koleksi pribadi.
- ✅ **Progress Tracker** – Tandai episode yang sudah ditonton, tampilkan persentase progress.
- 👤 **Profil Pengguna** – Ubah username, bio, lokasi, dan genre favorit.
- 🔐 **Autentikasi & Keamanan** – Login dengan Firebase, ganti password, dan kelola akun.

---

## 🛠️ Teknologi yang Digunakan

- **Frontend**: [Next.js 15+](https://nextjs.org/), [React](https://react.dev/), [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [TailwindCSS](https://tailwindcss.com/), [Framer Motion](https://www.framer.com/motion/)
- **Backend & Auth**: [Firebase Firestore](https://firebase.google.com/), Firebase Auth
- **API Data**: [AniList API](https://anilist.co/) (MyAnimeList Unofficial API)

---

## 📂 Struktur Halaman Utama

```
anime-watchlist/
├── app/
│ ├── anime/
│ │ └── [id]/
│ │ └── page.tsx
│ ├── dashboard/
│ │ ├── anime/
│ │ │ └── [id]/
│ │ │ └── page.tsx
│ │ └── page.tsx
│ ├── components/
│ │ ├── AddToWatchlist.tsx
│ │ ├── AnimeCard.tsx
│ │ ├── AnimeCardSip.tsx
│ │ ├── AnimeCarousel.tsx
│ │ ├── AnimeGrid.tsx
│ │ ├── AnimeImage.tsx
│ │ ├── AuthProvider.tsx
│ │ ├── EpisodeDialog.tsx
│ │ ├── EpisodeTracker.tsx
│ │ ├── GenreFilter.tsx
│ │ ├── LoadingSpinner.tsx
│ │ ├── Navbar.tsx
│ │ ├── SearchBar.tsx
│ │ └── WatchlistItems.tsx
│ ├── lib/
│ │ ├── anilist-queries.ts
│ │ ├── anilist-service.ts
│ │ └── firebase.ts
│ └── page.tsx
├── public/
└── package.json
```

---

## ⚡ Cara Menjalankan Project

1. **Clone repo ini**

   ```bash
   git clone https://github.com/username/anime-watchlist.git
   cd anime-watchlist
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Konfigurasi Firebase**

   - Buat project Firebase baru
   - Tambahkan file `.env.local` di root project dengan konfigurasi:
     ```env
     NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
     NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
     NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
     NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_bucket
     NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
     NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
     ```

4. **Jalankan server development**

   ```bash
   npm run dev
   ```

5. Buka di browser:
   ```
   http://localhost:3000
   ```

---

## 👩🏻‍💼 Kenapa Saya Membuat Project Ini

Saya membuat project Anime Universe – Watchlist & Tracker sebagai media pembelajaran pribadi. Ada beberapa alasan utama mengapa project ini saya kerjakan:

- 📡 Belajar API – Saya ingin memahami bagaimana cara mengambil data dari API publik (AniList API), mengolah response JSON, dan menampilkannya dalam aplikasi web.

- ⚛️ Mendalami Next.js & React – Project ini menjadi sarana saya untuk mengeksplorasi Next.js (App Router), routing dinamis, serta konsep server & client components.

- 📘 Mengenal TypeScript (TSX) – Dengan menggunakan TypeScript, saya belajar menulis kode yang lebih terstruktur, aman, dan mudah dikelola.

- 🔐 Eksperimen dengan Firebase – Saya ingin mengetahui bagaimana autentikasi dan database real-time bekerja dalam aplikasi modern.

- 🎨 Meningkatkan kemampuan UI/UX – Saya memanfaatkan TailwindCSS dan animasi untuk membuat antarmuka yang menarik dan interaktif.

- 🌍 Lebih mengenal dunia teknologi – Melalui project ini, saya bisa memahami alur kerja pengembangan aplikasi web modern, mulai dari frontend, backend, hingga integrasi layanan pihak ketiga.

- 🤖 Pemanfaatan AI – Dalam proses pengembangan project ini, saya juga memanfaatkan bantuan AI untuk memberikan ide, membantu penulisan kode, dan menyusun dokumentasi agar lebih terstruktur.

---

## 📬 Kontak & Diskusi

Jika kamu punya saran, masukan, atau ingin berdiskusi seputar project ini,  
silakan hubungi saya melalui DM Discord 🙌

[![Discord](https://img.shields.io/badge/Discord-Join%20Chat-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discordapp.com/users/717195113503260714)

---

> Dibuat dengan ❤️ dan ☕ oleh XzawDev untuk penggemar anime.
