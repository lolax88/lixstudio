---
# DESIGN.md — Kedai Nusantara
# Dibuat oleh LixStudio — Logo Design untuk UMKM
# Format: Google design.md spec (v0.2.0)

business:
  name: "Kedai Nusantara"
  type: "Kedai Kopi & Makanan Nusantara"
  owner: "[NAMA PEMILIK]"
  location: "[KOTA/DAERAH]"
  tagline: "Cita Rasa Nusantara, Segelas Penuh Cerita"
  whatsapp: "[NOMOR WHATSAPP]"
  instagram: "@kedainusantara"

colors:
  # Warna utama (dari logo)
  primary: "#2d5a3d"        # Hijau Nusantara — melambangkan alam, kesegaran, tradisi
  secondary: "#c9a96e"      # Emas Nusantara — melambangkan kemewahan, cita rasa premium
  
  # Variasi hijau
  primary-light: "#3d7a52"  # Hijau lebih terang untuk hover/akcent
  primary-dark: "#1e3d29"   # Hijau lebih gelap untuk teks di atas terang
  
  # Variasi emas
  secondary-light: "#d4b87a" # Emas lebih terang
  secondary-dark: "#a88a52"  # Emas lebih gelap untuk teks
  
  # Warna dasar
  ink: "#1a1a1a"             # Teks utama
  white: "#ffffff"           # Background bersih
  cream: "#faf6f0"           # Background hangat (kertas kopi)
  light: "#f5f2ec"           # Background section
  gray: "#666666"            # Teks sekunder
  border: "#e5e0d8"          # Garis tepi (warm gray)

typography:
  heading: "'Playfair Display', Georgia, serif"
  body: "'DM Sans', sans-serif"
  # Pilihan: Opsi B (Elegan & Premium)
  # Cocok karena: kesan tradisional premium, sesuai "Nusantara"

  heading_sizes:
    h1: "clamp(2.5rem, 5vw, 4rem)"     # Hero headline
    h2: "clamp(1.8rem, 3vw, 2.5rem)"   # Section title
    h3: "clamp(1.3rem, 2vw, 1.8rem)"   # Card title
  
  body_sizes:
    lg: "1.125rem"    # Deskripsi penting
    md: "1rem"        # Teks normal
    sm: "0.875rem"    # Caption, metadata

components:
  button_primary:
    background: "{colors.primary}"
    color: "#ffffff"
    borderRadius: "8px"
    fontWeight: 600
    padding: "14px 28px"
    fontSize: "0.95rem"
    hoverBackground: "{colors.primary-dark}"
  
  button_secondary:
    background: "transparent"
    color: "{colors.primary}"
    border: "2px solid {colors.primary}"
    borderRadius: "8px"
    fontWeight: 600
    padding: "14px 28px"
    hoverBackground: "{colors.primary}"
    hoverColor: "#ffffff"
  
  button_gold:
    background: "{colors.secondary}"
    color: "#ffffff"
    borderRadius: "8px"
    fontWeight: 700
    padding: "14px 28px"
    fontSize: "0.95rem"
    hoverBackground: "{colors.secondary-dark}"
  
  card:
    background: "{colors.white}"
    border: "1px solid {colors.border}"
    borderRadius: "12px"
    shadow: "0 2px 12px rgba(45,90,61,0.08)"
    hoverShadow: "0 8px 30px rgba(45,90,61,0.12)"
    hoverTranslateY: "-3px"
  
  badge_promo:
    background: "{colors.secondary}"
    color: "#ffffff"
    fontSize: "0.7rem"
    fontWeight: 700
    letterSpacing: "0.08em"
    textTransform: "uppercase"
    borderRadius: "4px"
    padding: "4px 10px"
  
  badge_category:
    background: "{colors.cream}"
    color: "{colors.primary}"
    fontSize: "0.75rem"
    fontWeight: 600
    borderRadius: "100px"
    padding: "4px 12px"
    border: "1px solid {colors.border}"

  price_tag:
    fontFamily: "'Playfair Display', serif"
    fontSize: "1.5rem"
    fontWeight: 700
    color: "{colors.secondary-dark}"
    # Harga pakai font serif emas — kesan premium

rounded:
  sm: "4px"
  md: "8px"
  lg: "12px"
  xl: "16px"
  pill: "100px"

spacing:
  section: "5rem"
  card: "1.5rem"
  gap: "1rem"

assets:
  logo_icon: "kedai-nusantara-icon.svg"
  logo_wordmark: "kedai-nusantara-wordmark.svg"
  logo_icon_png: "kedai-nusantara-icon.png"
  logo_wordmark_png: "kedai-nusantara-wordmark.png"
  favicon: "kedai-nusantara-icon.png"
  og_image: "kedai-nusantara-og.jpg"

  # Variasi logo:
  # - Icon saja (cangkir kopi + asap) → untuk favicon, profil sosmed
  # - Wordmark (teks "KEDAI NUSANTARA" + dekorasi) → untuk header, menu
  # - Full (icon + wordmark) → untuk banner, signage
---

# Kedai Nusantara — Brand Guidelines

## Tentang Brand

**Kedai Nusantara** adalah kedai kopi dan makanan yang mengusung cita rasa nusantara. Menghadirkan kopi lokal pilihan dari berbagai daerah di Indonesia dengan sentuhan tradisional yang autentik.

**Tagline:** "Cita Rasa Nusantara, Segelas Penuh Cerita"

**Kontak:**
- WhatsApp: [NOMOR]
- Instagram: @kedainusantara
- Lokasi: [ALAMAT]

## Visual Identity

### Logo

Logo Kedai Nusantara terdiri dari:
- **Icon:** Cangkir kopi dengan asap yang membentuk siluet khas Nusantara
- **Wordmark:** "KEDAI NUSANTARA" dengan font serif elegan + elemen dekoratif
- **Warna:** Hijau tua (#2d5a3d) dan emas (#c9a96e)

**Makna logo:**
- 🟢 **Hijau tua** → Alam Indonesia, kesegaran bahan, keaslian
- 🟡 **Emas** → Kemewahan rasa, cita rasa premium, warisan nusantara
- ☕ **Cangkir kopi** → Inti bisnis: kopi berkualitas
- 💨 **Asap** → Kopi disajikan hangat, pengalaman menikmati

**Penggunaan logo:**
- ✅ Icon saja untuk: favicon, foto profil, stempel, watermark
- ✅ Wordmark untuk: menu, header, kop surat
- ✅ Full logo untuk: banner, signage, kemasan
- ❌ Jangan di-rotate, di-stretch, atau ganti warna sembarangan
- ❌ Jangan taruh logo di background ramai tanpa kontras

### Warna

| Warna | Kode | Fungsi | Makna |
|-------|------|--------|-------|
| Hijau Nusantara | `#2d5a3d` | Judul, tombol utama, elemen penting | Alam, kesegaran, tradisi |
| Emas Nusantara | `#c9a96e` | Harga, promo, aksen premium | Kemewahan, cita rasa |
| Krem | `#faf6f0` | Background hangat | Kertas kopi, kenyamanan |
| Tinta | `#1a1a1a` | Teks utama | Kejelasan, profesional |
| Warm Gray | `#666666` | Teks sekunder | Ketenangan, elegan |

**Kombinasi warna yang ideal:**
- Menu: hijau (#2d5a3d) di atas krem (#faf6f0)
- Promo: emas (#c9a96e) di atas hijau (#2d5a3d)
- Harga: emas gelap (#a88a52) di atas putih (#ffffff)
- CTA: hijau (#2d5a3d) tombol dengan teks putih

### Tipografi

**Font Heading:** Playfair Display (serif)
- Digunakan untuk: nama menu, judul section, harga
- Vibe: elegan, tradisional premium, seperti buku resep warisan
- Bobot: 400 (normal), 700 (bold untuk harga)

**Font Body:** DM Sans (sans-serif)
- Digunakan untuk: deskripsi, alamat, informasi umum
- Vibe: modern, bersih, mudah dibaca
- Bobot: 400 (normal), 500 (medium), 600 (semi-bold)

**Contoh penggunaan:**
```
[Playfair Display 700] Rp 25.000        ← Harga
[Playfair Display 400] Kopi Aceh Gayo   ← Nama menu
[DM Sans 400] Robusta pilihan dari      ← Deskripsi
               dataran tinggi Gayo,
               disangrai medium roast
```

### Tone of Voice

Brand Kedai Nusantara berbicara dengan gaya:
- **Hangat** → Seperti ngobrol sama teman di kedai
- **Puitis** → Sedikit puitis, tapi gak lebay
- **Lokal** → Bangga dengan cita rasa Indonesia
- **Edukasi** → Kasih tau asal-usul kopi, cerita di balik rasa

**Contoh copywriting:**

✅ Yang cocok:
- "Segelas kopi Aceh, segenggam cerita Gayo"
- "Kopinya Nusantara, harganya tetangga"
- "Dari petani lokal, untuk kamu yang appreciate"
- "Setiap tegukan punya cerita. Mau dengar?"

❌ Yang tidak cocok:
- "PREMIUM COFFEE EXPERIENCE!!!" (teriak, gak hangat)
- "Kopi berkualitas tinggi dengan harga terjangkau" (generic)
- "Best coffee in town" (klaim gak personal)
- "Discount 50%!!!" (hard sell, gak elegan)

## Menu Design Guidelines

### Layout Menu
- Background: krem (#faf6f0)
- Nama menu: Playfair Display, hijau tua (#2d5a3d)
- Deskripsi: DM Sans, abu-abu (#666666)
- Harga: Playfair Display Bold, emas gelap (#a88a52)
- Garis pemisah: border halus (#e5e0d8)

### Kategori Menu
- **Kopi Nusantara** → Kopi dari berbagai daerah
- **Minuman Segar** → Non-kopi, jus, teh
- **Makanan Ringan** → Snack, roti, pastry
- **Paket Spesial** → Bundling promo

### Contoh Item Menu
```
┌─────────────────────────────────────────┐
│                                         │
│  KOPI ACEH GAYO                         │  ← Playfair 700, #2d5a3d
│  Robusta pilihan dari dataran tinggi    │  ← DM Sans 400, #666666
│  Gayo, disangrai medium roast           │
│                                         │
│  Rp 25.000                              │  ← Playfair 700, #a88a52
│                                         │
└─────────────────────────────────────────┘
```

## Aplikasi Brand

### Kemasan (Paper Cup / Takeaway)
- **Paper cup:** Hijau (#2d5a3d) sebagai warna dominan
- **Logo:** Icon di satu sisi, wordmark di sisi lain
- **Tutup:** Hitam atau putih
- **Sleeve:** Kertas kraft coklat dengan stamp logo emas

### Sosial Media
- **Foto profil:** Icon logo (cangkir kopi) di atas hijau
- **Bio:** "☕ Cita Rasa Nusantara, Segelas Penuh Cerita | 📍 [Lokasi]"
- **Feed:** Konsisten pakai filter warm/earthy
- **Story:** Template hijau-emas untuk promo, hitam-emas untuk quote

### Interior Kedai
- **Dinding:** Putih/krem dengan aksen hijau
- **Furniture:** Kayu natural, rotan
- **Signage:** Logo full di atas pintu masuk
- **Menu board:** Hitam dengan tulisan kapur atau hijau dengan emas

### Seragam
- **Aprron:** Hijau tua (#2d5a3d) dengan logo bordir emas
- **Kaos:** Putih atau hitam dengan logo kecil di dada kiri
- **Topi:** Hijau tua dengan logo embroidery

## Do's and Don'ts

### ✅ Yang Boleh
- Pakai logo sesuai panduan di atas
- Konsisten dengan palet hijau-emas-krem
- Gunakan tone hangat dan sedikit puitis
- Ceritakan asal-usul kopi di menu dan sosmed
- Minta approval LixStudio untuk penggunaan brand baru

### ❌ Yang Tidak Boleh
- Mengubah warna logo (hijau dan emas sudah final)
- Menggunakan font Comic Sans atau font dekoratif lain
- Hard sell atau bahasa promosi yang agresif
- Meng-copy desain atau copywriting kompetitor
- Menggunakan warna neon atau terlalu mencolok

## Agent Prompt Guide

**Untuk AI yang bikin konten/materi Kedai Nusantara:**

```
Brand: Kedai Nusantara
Jenis: Kedai Kopi & Makanan Nusantara

Warna:
- Primary: #2d5a3d (hijau tua — alam, segar, tradisional)
- Secondary: #c9a96e (emas — premium, cita rasa)
- Background: #faf6f0 (krem — hangat, kertas kopi)

Font: Playfair Display untuk judul/harga, DM Sans untuk body

Tone: Hangat, sedikit puitis, bangga lokal, edukatif
Target: Pecinta kopi 20-40 tahun, appreciate cita rasa nusantara

Buatkan [MATERIAL] dengan gaya yang sesuai brand guidelines.
Gunakan bahasa Indonesia yang hangat dan bercerita.
```

---

*Brand guidelines ini dibuat oleh LixStudio — Logo Design untuk UMKM*
*Hubungi: WhatsApp | Instagram: @lolaxx__*
