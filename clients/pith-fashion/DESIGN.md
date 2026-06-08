---
# DESIGN.md — PITH
# Dibuat oleh LixStudio — Logo Design untuk UMKM
# Format: Google design.md spec (v0.2.0)

business:
  name: "PITH"
  type: "Fashion Old Money — Quiet Luxury"
  owner: "[NAMA PEMILIK]"
  location: "[KOTA]"
  tagline: "The essence of style"
  instagram: "@pith"

colors:
  # Core palette (dari logo)
  primary: "#0C0A09"        # Hitam pekat — warna logo, teks utama
  secondary: "#1C1917"      # Hitam hangat — secondary text
  accent: "#A16207"         # Emas tua — aksen premium, harga, CTA
  
  # Neutrals (Old Money palette)
  cream: "#F5F0E1"          # Krem hangat — background premium
  off-white: "#FAFAF9"      # Putih bersih — background utama
  sand: "#D4C4A8"           # Pasir — divider, border halus
  warm-gray: "#8C8377"      # Abu hangat — teks sekunder
  charcoal: "#44403C"       # Arang — sub-judul
  
  # Functional
  card: "#FFFFFF"           # Card background
  border: "#E8E4DD"         # Border halus
  muted: "#9CA3AF"          # Teks muted

typography:
  heading: "'Didot', 'Bodoni Moda', 'Playfair Display', Georgia, serif"
  body: "'Montserrat', 'Jost', system-ui, sans-serif"
  # High-contrast serif untuk heading (sama seperti logo PITH)
  # Clean sans-serif untuk body (readability)

  heading_sizes:
    h1: "clamp(3rem, 8vw, 6rem)"     # Hero — besar, dramatic
    h2: "clamp(2rem, 4vw, 3.5rem)"   # Section title
    h3: "clamp(1.3rem, 2vw, 1.8rem)" # Card title
  
  body_sizes:
    lg: "1.125rem"
    md: "1rem"
    sm: "0.875rem"
    xs: "0.75rem"

  font_weights:
    light: 300      # Body text — elegant, airy
    regular: 400    # Normal text
    medium: 500     # Emphasis
    bold: 700       # Headings, harga

components:
  button_primary:
    background: "{colors.primary}"
    color: "{colors.off-white}"
    borderRadius: "0"  # Sharp corners — Old Money, no fluff
    fontWeight: 600
    fontSize: "0.8rem"
    letterSpacing: "0.15em"
    textTransform: "uppercase"
    padding: "16px 40px"
  
  button_secondary:
    background: "transparent"
    color: "{colors.primary}"
    border: "1.5px solid {colors.primary}"
    borderRadius: "0"
    fontWeight: 600
    fontSize: "0.8rem"
    letterSpacing: "0.15em"
    textTransform: "uppercase"
    padding: "16px 40px"
  
  button_accent:
    background: "{colors.accent}"
    color: "{colors.off-white}"
    borderRadius: "0"
    fontWeight: 600
    fontSize: "0.8rem"
    letterSpacing: "0.15em"
    textTransform: "uppercase"
    padding: "16px 40px"
  
  card:
    background: "{colors.card}"
    border: "1px solid {colors.border}"
    borderRadius: "0"  # Sharp — no rounded corners
    shadow: "none"     # Flat, clean
    hoverShadow: "0 4px 20px rgba(0,0,0,0.06)"
  
  price:
    fontFamily: "heading"
    fontSize: "1.2rem"
    fontWeight: 700
    color: "{colors.accent}"
    letterSpacing: "0.02em"

rounded:
  none: "0"    # PRIMARY — Old Money = sharp, clean
  sm: "2px"    # Subtle
  md: "4px"    # Rare use

spacing:
  section: "8rem"    # Generous — luxury feel
  card: "2rem"
  gap: "1.5rem"

assets:
  logo: "pith-logo.png"
  logo_dark: "pith-logo-dark.png"  # Untuk background gelap
  favicon: "pith-favicon.png"
---

# PITH — Brand Guidelines

## Tentang Brand

**PITH** adalah fashion brand Old Money yang mengutamakan kualitas, craftsmanship, dan desain tak lekang waktu. Nama "PITH" berarti inti/sari dari sesuatu — merepresentasikan filosofi brand: **kualitas ada di inti, bukan di permukaan**.

**Tagline:** "The essence of style"

**Filosofi:**
- Bukan trend, tapi klasik abadi
- Bukan logo besar, tapi kualitas terasa
- Bukan teriak, tapi diam-diam mahal
- Bukan banyak, tapi yang terbaik

## Visual Identity

### Logo

Logo PITH terdiri dari:
- **Wordmark:** "PITH" dalam high-contrast serif font (Didot/Bodoni style)
- **Warna:** Hitam pekat (#0C0A09) di atas putih/off-white
- **Layout:** Centered, generous whitespace

**Ciri khas logo:**
- Serif high-contrast → thick verticals, thin horizontals
- Semua huruf uppercase → confident, authoritative
- Spacing antar huruf konsisten → balanced, refined
- Gak ada icon/symbol → murni tipografi

**Penggunaan logo:**
- ✅ Hitam di atas putih/cream (primary)
- ✅ Putih di atas hitam (inverted — untuk dark sections)
- ✅ Emboss/deboss di material (kulit, kertas premium)
- ❌ Jangan ganti warna (hitam atau putih saja)
- ❌ Jangan tambah efek (shadow, gradient, outline)
- ❌ Jangan stretch atau rotate

### Warna

| Warna | Kode | Fungsi | Makna |
|-------|------|--------|-------|
| Hitam Pekat | `#0C0A09` | Logo, teks utama, CTA | Kekuatan, keanggunan |
| Emas Tua | `#A16207` | Harga, aksen premium | Kemewahan, kualitas |
| Krem | `#F5F0E1` | Background premium | Kelembutan, warmth |
| Off-White | `#FAFAF9` | Background utama | Bersih, lapang |
| Sand | `#D4C4A8` | Divider, border | Netral, refined |
| Charcoal | `#44403C` | Sub-judul | Depth, sophistication |

**Kombinasi ideal:**
- Homepage: off-white background + hitam teks + emas accent
- Product page: white card + sand border + emas harga
- Dark section: hitam background + putih teks + emas accent
- Promo: cream background + hitam teks + emas CTA

### Tipografi

**Font Heading:** Didot / Bodoni Moda / Playfair Display (serif high-contrast)
- Digunakan untuk: headline, nama produk, harga
- Vibe: dramatic, elegant, high-fashion editorial
- Bobot: 400 (normal), 700 (bold untuk harga)
- Letter-spacing: -0.02em (tight) untuk headline, normal untuk lainnya

**Font Body:** Montserrat / Jost (sans-serif geometric)
- Digunakan untuk: deskripsi, navigasi, body text
- Vibe: clean, modern, readable
- Bobot: 300 (light — airy feel), 400 (normal), 500 (medium)
- Letter-spacing: 0.02em (sedikit loose untuk readability)

**Contoh penggunaan:**
```
[Didot 700] Rp 12.500.000         ← Harga (emas)
[Didot 400] Cashmere Overcoat      ← Nama produk (hitam)
[Montserrat 300] Outerwear         ← Kategori (abu)
[Montserrat 400] Crafted from...   ← Deskripsi (charcoal)
```

### Tone of Voice

Brand PITH berbicara dengan gaya:
- **Understated** → Gak perlu teriak, kualitas bicara sendiri
- **Confident** → Percaya diri tanpa sombong
- **Timeless** → Bukan trend, tapi klasik abadi
- **Refined** → Halus, sophisticated, berkelas
- **Direct** → Singkat, powerful, to the point

**Contoh copywriting:**

✅ Yang cocok:
- "Crafted for those who know the difference"
- "Quality speaks quietly"
- "Not for everyone. And that's the point."
- "Investment pieces, not impulse buys"
- "The essence of style"
- "Less, but better"

❌ Yang tidak cocok:
- "BEST DEAL!! DISKON 50%!!!" (norak)
- "Premium quality at affordable price" (kontradiksi)
- "Trend terbaru 2026!" (PITH gak ikut trend)
- "Follow us for daily updates!" (too casual)
- "Hey guys!" (gak sesuai brand)

## Layout Principles

**Prinsip utama:**
- **Whitespace = luxury** — jangan takut space kosong
- **Typography as decoration** — huruf indah = dekorasi alami
- **Symmetry = order** — balanced, centered, harmonious
- **No clutter** — setiap elemen harus punya alasan ada

**Grid:** 12-column grid, centered content, max-width 1200px
**Section spacing:** 8rem (sangat generous)
**Card padding:** 2rem
**Mobile:** Stack vertically, tetap generous whitespace

## Elevation & Depth

**Shadow:** Minimal atau none
- Card: no shadow at rest, subtle shadow on hover (`0 4px 20px rgba(0,0,0,0.06)`)
- Button: no shadow, flat
- No decorative shadows

**Surface hierarchy:**
1. Page background (#FAFAF9) — ground level
2. Section background (#F5F0E1) — elevated section
3. Card (#FFFFFF) — first elevation
4. Modal/overlay — top level

## Aplikasi Brand

### Website
- **Hero:** Full-width, hitam/cream, headline besar "PITH" + tagline
- **Product grid:** Clean cards, foto besar, harga emas
- **About:** Split layout, foto + teks, generous whitespace
- **Contact:** Simple form, WhatsApp CTA

### Katalog / Lookbook
- **Layout:** Magazine-style, full-bleed foto
- **Typography:** Large headlines, airy body text
- **Paper:** Matte, premium feel

### Kemasan
- **Box:** Hitam matte dengan logo emboss
- **Tissue paper:** Cream/putih dengan logo watermark
- **Bag:** Kertas hitam dengan handle kulit
- **Tag:** Kartu teks dengan logo foil emas

### Sosial Media
- **Foto profil:** Logo "PITH" hitam di putih (atau putih di hitam)
- **Bio:** "The essence of style | [link]"
- **Feed:** Consistent mood — warm, earthy, minimal
- **Story:** Clean template, hitam-putih-emas

### Kartu Nama
- **Material:** Kartu teks 400gsm, matte finish
- **Depan:** Logo PITH centered, hitam di putih
- **Belakang:** Nama, kontak, minimalis
- **Detail:** Foil emas di logo (opsional)

## Do's and Don'ts

### ✅ Yang Boleh
- Pakai logo sesuai panduan (hitam/putih saja)
- Konsisten dengan palet hitam-krem-emas
- Gunakan whitespace secara generous
- Tone understated dan confident
- Foto produk berkualitas tinggi, pencahayaan natural
- Gunakan tipografi sebagai elemen desain utama

### ❌ Yang Tidak Boleh
- Mengubah warna logo (hitam atau putih SAJA)
- Menambah efek pada logo (shadow, gradient, outline)
- Menggunakan warna neon atau mencolok
- Banner diskon besar atau hard sell
- Font dekoratif atau script
- Animasi berlebihan
- Logo terlalu besar atau norak
- Menggunakan border-radius (PITH = sharp corners)

## Agent Prompt Guide

**Untuk AI yang bikin konten/materi PITH:**

```
Brand: PITH
Type: Fashion Old Money — Quiet Luxury
Tagline: "The essence of style"

Warna:
- Primary: #0C0A09 (hitam pekat)
- Accent: #A16207 (emas tua)
- Background: #FAFAF9 (off-white)
- Cream: #F5F0E1 (section premium)

Font: Didot/Bodoni Moda untuk heading, Montserrat untuk body
Border-radius: 0 (sharp corners, no rounded)
Shadow: minimal atau none
Whitespace: sangat generous

Tone: Understated, confident, timeless, refined, direct
Target: Pria/wanita 25-45, kelas atas, appreciate craftsmanship

HINDARI: warna neon, border-radius, shadow berat, font dekoratif, hard sell, animasi berlebihan

Buatkan [MATERIAL] dengan gaya yang sesuai brand guidelines.
Gunakan bahasa Indonesia yang sophisticated tapi gak lebay.
```

---

*Brand guidelines ini dibuat oleh LixStudio — Logo Design untuk UMKM*
*Instagram: @lolaxx__*
