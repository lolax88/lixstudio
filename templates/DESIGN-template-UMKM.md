---
# DESIGN.md — Template UMKM
# Template ini diisi oleh LixStudio saat client order logo/brand
# Format: Google design.md spec (v0.2.0)
# 
# CARA ISI:
# 1. Ganti semua nilai [BRACKETED] dengan data client
# 2. Hapus komentar (#) yang gak perlu
# 3. Simpan sebagai DESIGN.md di folder client

# ============================================
# INFO BISNIS (WAJIB ISI)
# ============================================
business:
  name: "[NAMA BISNIS]"
  type: "[JENIS BISNIS]"  # contoh: warung kopi, laundry, salon, toko kelontong
  owner: "[NAMA PEMILIK]"
  location: "[KOTA/DAERAH]"
  tagline: "[TAGLINE SINGKAT]"  # contoh: "Kopi Nikmat, Harga Merakyat"
  whatsapp: "[NOMOR WhatsApp]"
  instagram: "[@username]"

# ============================================
# WARNA BRAND (ISI SESUAI LOGO YANG DIBUAT)
# ============================================
colors:
  # Warna utama brand
  primary: "[HEX CODE]"      # contoh: #2D5016 (hijau tua)
  secondary: "[HEX CODE]"    # contoh: #F5E6D3 (krem)
  
  # Warna pendukung
  accent: "[HEX CODE]"       # contoh: #D4A574 (coklat kopi)
  
  # Warna dasar (biasanya gak perlu diubah)
  ink: "#1a1a1a"             # warna teks utama
  white: "#ffffff"           # background bersih
  light: "#f8f8f8"           # background halaman
  gray: "#666666"            # teks sekunder
  border: "#e5e5e5"          # garis tepi

# ============================================
# TYPOGRAFI (PILIH SALAH SATU KOMBINASI)
# ============================================
typography:
  # Opsi A: Modern & Clean (cocok: cafe, salon, fashion)
  option_a:
    heading: "'Poppins', sans-serif"
    body: "'Inter', sans-serif"
  
  # Opsi B: Elegan & Premium (cocok: restoran, hotel, wedding)
  option_b:
    heading: "'Playfair Display', serif"
    body: "'DM Sans', sans-serif"
  
  # Opsi C: Fun & Ramah (cocok: anak muda, street food, laundry)
  option_c:
    heading: "'Nunito', sans-serif"
    body: "'Open Sans', sans-serif"
  
  # Opsi D: Klasik & Terpercaya (cocok: toko tradisional, bengkel)
  option_d:
    heading: "'Merriweather', serif"
    body: "'Source Sans Pro', sans-serif"
  
  # PILIHAN CLIENT: [A/B/C/D]
  heading: "[FONT HEADING]"
  body: "[FONT BODY]"

# ============================================
# KOMPONEN DASAR
# ============================================
components:
  # Tombol utama (WhatsApp, Order, dll)
  button_primary:
    background: "{colors.primary}"
    color: "#ffffff"
    borderRadius: "8px"
    fontWeight: 600
    padding: "12px 24px"
  
  # Tombol sekunder
  button_secondary:
    background: "transparent"
    color: "{colors.primary}"
    border: "2px solid {colors.primary}"
    borderRadius: "8px"
    fontWeight: 600
    padding: "12px 24px"
  
  # Card produk/layanan
  card:
    background: "{colors.white}"
    border: "1px solid {colors.border}"
    borderRadius: "12px"
    shadow: "0 2px 8px rgba(0,0,0,0.06)"
  
  # Badge/promo tag
  badge:
    background: "{colors.accent}"
    color: "#ffffff"
    fontSize: "0.75rem"
    fontWeight: 700
    borderRadius: "4px"
    padding: "4px 8px"

# ============================================
# SPACING & BENTUK
# ============================================
rounded:
  sm: "4px"
  md: "8px"
  lg: "12px"
  xl: "16px"
  pill: "100px"

spacing:
  section: "4rem"    # jarak antar section
  card: "1.5rem"     # padding dalam card
  gap: "1rem"        # jarak antar elemen

# ============================================
# MEDIA SOSIAL & ASSET
# ============================================
assets:
  logo_svg: "logo.svg"
  logo_png: "logo.png"         # 1024x1024 transparent
  favicon: "favicon.png"       # 32x32
  og_image: "og-image.jpg"     # 1200x630 untuk share
  
  # Variasi logo yang disediakan:
  # - logo-full.svg (logo + teks)
  # - logo-icon.svg (icon aja)
  # - logo-dark.svg (untuk background terang)
  # - logo-light.svg (untuk background gelap)
---

# [NAMA BISNIS] — Brand Guidelines

## Tentang Brand Ini

[NAMA BISNIS] adalah [JENIS BISNIS] yang berlokasi di [KOTA/DAERAH].
[TAGLINE].

**Kontak:**
- WhatsApp: [NOMOR]
- Instagram: [@username]
- Lokasi: [ALAMAT LENGKAP]

## Visual Identity

### Logo

Logo [NAMA BISNIS] terdiri dari:
- **Icon:** [DESKRIPSI ICON — contoh: "cangkir kopi dengan asap"]
- **Wordmark:** [DESKRIPSI TEKS — contoh: "nama brand dengan font Poppins Bold"]
- **Warna utama:** [WARNA PRIMARY] — melambangkan [MAKNA]

**Penggunaan logo:**
- ✅ Logo penuh (icon + teks) untuk: banner, menu, kartu nama
- ✅ Icon saja untuk: favicon, profil sosmed, watermark
- ❌ Jangan di-rotate, di-stretch, atau ganti warna sembarangan

### Warna

| Warna | Kode | Fungsi |
|-------|------|--------|
| [NAMA WARNA 1] | [HEX] | Judul, tombol utama, elemen penting |
| [NAMA WARNA 2] | [HEX] | Background, area konten |
| [NAMA WARNA 3] | [HEX] | Aksen, highlight, promo |

### Tipografi

**Font Heading:** [NAMA FONT]
- Digunakan untuk: judul menu, nama produk, headline
- Vibe: [DESKRIPSI — contoh: "modern, bersih, mudah dibaca"]

**Font Body:** [NAMA FONT]
- Digunakan untuk: deskripsi, harga, teks biasa
- Vibe: [DESKRIPSI — contoh: "ramah, profesional"]

### Tone of Voice

Brand [NAMA BISNIS] berbicara dengan gaya:
- [KARAKTER 1 — contoh: "Ramah, seperti ngobrol sama teman"]
- [KARAKTER 2 — contoh: "Jujur, gak lebay"]
- [KARAKTER 3 — contoh: "Lokal, pakai bahasa sehari-hari"]

**Contoh copywriting:**
- ✅ "Kopi susu kita manisnya pas, gak bikin enek!"
- ❌ "Premium artisanal single-origin coffee experience"

## Aplikasi Brand

### Menu / Daftar Produk
- Gunakan font heading untuk nama produk
- Font body untuk deskripsi dan harga
- Warna primary untuk harga penting/promo

### Sosial Media
- **Foto profil:** Logo icon (bulat)
- **Banner:** Logo full + tagline
- **Posting:** Konsisten pakai warna brand
- **Story:** Pakai font yang sama dengan menu

### Kemasan / Paper Cup / Tas
- Logo full di satu sisi
- Warna brand dominan
- Font body untuk info legal (izin, alamat)

### Seragam / Merchandise
- Logo icon di dada kiri
- Warna seragam: [WARNA BRAND] atau netral

## Do's and Don'ts

### ✅ Yang Boleh
- Pakai logo sesuai panduan di atas
- Konsisten dengan warna brand
- Gunakan tone of voice yang ramah
- Minta approval LixStudio untuk penggunaan baru

### ❌ Yang Tidak Boleh
- Mengubah warna logo sembarangan
- Meng-stretch atau memutar logo
- Menggunakan font lain yang gak ada di panduan
- Meng-copy desain kompetitor

---

## Agent Prompt Guide

**Untuk AI yang bikin konten/materi brand ini:**

```
Brand: [NAMA BISNIS]
Jenis: [JENIS BISNIS]
Lokasi: [KOTA]

Warna:
- Primary: [HEX] ([DESKRIPSI])
- Secondary: [HEX] ([DESKRIPSI])
- Accent: [HEX] ([DESKRIPSI])

Font: [HEADING] untuk judul, [BODY] untuk teks

Tone: Ramah, [KARAKTER], lokal

Target: [TARGET MARKET — contoh: "anak muda 18-30, suka kopi"]

Buatkan [MATERIAL — contoh: "caption Instagram untuk promo kopi susu"]
dengan gaya yang sesuai brand guidelines di atas.
```

---

*Brand guidelines ini dibuat oleh LixStudio — Logo Design untuk UMKM*
*Hubungi: [NOMOR WHATSAPP] | Instagram: @lolaxx__*
