# 🚀 Fish It Companion - GitHub Pages Setup Guide

## 📱 CARA UPLOAD & AKSES DARI HP

---

## ✅ STEP 1: Buat Akun GitHub (kalau belum punya)

1. Buka browser di HP
2. Ke: https://github.com/signup
3. Isi email, password, username
4. Verify email
5. Login

---

## ✅ STEP 2: Buat Repository Baru

### **Via HP Browser:**

1. Login ke GitHub
2. Klik **"+"** (pojok kanan atas) → **"New repository"**
3. Isi data:
   - **Repository name:** `fish-it-companion`
   - **Description:** `Fish It Companion Web App`
   - **Public** ✅ (pilih ini)
   - **Add README** ❌ (jangan centang)
4. Klik **"Create repository"**

---

## ✅ STEP 3: Upload Files

### **Method 1: Upload Via Browser (Paling Mudah)**

1. Di repository baru, klik **"Add file"** → **"Create new file"**

2. **Upload index.html:**
   - File name: `index.html`
   - Copy paste code dari artifact **"index.html - Fish It Companion Web App"**
   - Scroll bawah, klik **"Commit new file"**

3. **Upload manifest.json:**
   - Klik **"Add file"** → **"Create new file"** lagi
   - File name: `manifest.json`
   - Copy paste code dari artifact **"manifest.json - PWA Config"**
   - Klik **"Commit new file"**

---

## ✅ STEP 4: Aktifkan GitHub Pages

1. Di repository, klik **"Settings"** (tab paling kanan)
2. Scroll cari **"Pages"** di sidebar kiri
3. Di **"Source"**, pilih:
   - Branch: **`main`** (atau `master`)
   - Folder: **`/ (root)`**
4. Klik **"Save"**
5. Tunggu ~1 menit
6. Refresh page
7. Akan muncul link: `https://YOUR_USERNAME.github.io/fish-it-companion/`

---

## ✅ STEP 5: Buka App di HP

1. Copy link GitHub Pages kamu
2. Buka di browser HP
3. **DONE!** App langsung bisa dipakai! 🎉

---

## 📱 INSTALL SEBAGAI APP (PWA)

### **Android (Chrome):**
1. Buka app di Chrome
2. Menu (⋮) → **"Add to Home screen"**
3. Klik **"Install"**
4. Icon app muncul di home screen!

### **iPhone (Safari):**
1. Buka app di Safari
2. Tap tombol **Share** (kotak dengan panah)
3. Scroll cari **"Add to Home Screen"**
4. Tap **"Add"**
5. Icon app muncul di home screen!

---

## 🔑 TEST KEY SYSTEM

### **Admin Key (Kamu):**
```
RullXFlyy
```

### **Test User Keys:**
```
FISHIT-TEST-1234
FISHIT-DEMO-5678
FISHIT-ABCD-EFGH
```

**Note:** Semua key dengan format `FISHIT-XXXX-XXXX` diterima untuk demo.

---

## 🎨 CUSTOMIZE APP

### **Ganti Warna:**

Edit `index.html`, cari:
```css
background: linear-gradient(135deg, #3b82f6 0%, #2563eb 100%);
```

Ganti hex code warna sesuai selera!

### **Ganti Nama:**

Edit `manifest.json`:
```json
"name": "Nama App Kamu",
"short_name": "Singkatan"
```

### **Ganti Icon:**

Ganti emoji 🎣 dengan emoji lain di `index.html`:
```html
<div class="app-logo">🎣</div>  <!-- Ganti ini -->
```

---

## 🔧 UPDATE APP

Kalau mau update:

1. Buka repository di GitHub
2. Klik file yang mau diedit (contoh: `index.html`)
3. Klik icon **pencil** (✏️ Edit)
4. Edit code
5. Scroll bawah, klik **"Commit changes"**
6. Tunggu ~1 menit
7. Refresh app di HP → Update otomatis!

---

## 📊 FITUR YANG AKTIF

### ✅ Sudah Berfungsi:
- [x] Key activation system
- [x] Admin key (1 year): `RullXFlyy`
- [x] User keys (24 hours)
- [x] Discord webhook notifications
- [x] Persistent storage (LocalStorage)
- [x] PWA installable
- [x] Responsive mobile UI
- [x] Auto logout saat expired
- [x] Real-time countdown

### 🚧 Coming Soon:
- [ ] RNG Calculator (full)
- [ ] Stats Tracker
- [ ] Fish Encyclopedia
- [ ] Webhook notifications

---

## 🐛 TROUBLESHOOTING

### **Problem: Link tidak bisa dibuka**
**Solution:**
- Pastikan GitHub Pages sudah aktif di Settings
- Tunggu 1-2 menit setelah aktivasi
- Coba buka di **incognito/private mode**

### **Problem: Key tidak tersimpan**
**Solution:**
- Jangan gunakan **private/incognito mode**
- Pastikan LocalStorage diaktifkan di browser
- Coba clear cache browser

### **Problem: Discord webhook tidak jalan**
**Solution:**
- Pastikan HP punya internet
- Check webhook URL masih valid
- Coba test webhook di Postman/browser

### **Problem: Install app tidak muncul**
**Solution:**
- Pastikan buka di **Chrome** (Android) atau **Safari** (iOS)
- Jangan buka di **in-app browser** (Instagram, Facebook, dll)
- Coba buka langsung di browser HP

---

## 💡 TIPS

1. **Share Link:**
   - Copy link GitHub Pages
   - Share ke temen untuk test
   - Generate user keys untuk mereka

2. **Custom Domain:**
   - Bisa pake custom domain (contoh: `fishit.com`)
   - Settings → Pages → Custom domain
   - (Butuh beli domain dulu)

3. **Backup:**
   - Code tersimpan di GitHub = auto backup
   - Bisa di-clone ke repo lain
   - Download as ZIP kapan aja

4. **Analytics:**
   - Bisa tambah Google Analytics
   - Track berapa user yang akses
   - Lihat statistik penggunaan

---

## 🎯 EXAMPLE LINKS

**Repository:** 
```
https://github.com/YOUR_USERNAME/fish-it-companion
```

**Live App:**
```
https://YOUR_USERNAME.github.io/fish-it-companion/
```

**Contoh (ganti YOUR_USERNAME):**
```
https://rullxflyy.github.io/fish-it-companion/
```

---

## 📞 SUPPORT

- **Discord:** https://discord.gg/Y3QJ5WjEU
- **GitHub Issues:** Report bugs di repository
- **Email:** Contact admin

---

## 🎉 SELESAI!

**App kamu sekarang:**
- ✅ Online & accessible dari mana aja
- ✅ Bisa install sebagai app
- ✅ Auto sync dengan GitHub
- ✅ Gratis selamanya!

**Tinggal:**
1. Share link ke temen
2. Generate keys untuk user
3. Track aktivasi di Discord webhook

**GOOD LUCK!** 🚀🎣
