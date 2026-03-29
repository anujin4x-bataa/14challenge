# 14 Хоногийн Сорилт 💪
### GitHub Pages дээр байрлуулах заавар

---

## 🗄 1-р алхам — Supabase тохируулах

1. [supabase.com](https://supabase.com) → **New Project** үүсгэх
2. **SQL Editor** нээж `supabase-setup.sql` файлыг paste хийн **Run** дарах
3. **Settings → API** хэсгээс:
   - `Project URL` → хуулах
   - `anon public` key → хуулах
4. `index.html` файлд эдгээрийг оруулах:
   ```
   const SB_URL = 'https://xxxx.supabase.co';   ← таны URL
   const SB_KEY = 'eyJhbGci...';                ← таны anon key
   ```

---

## 📁 2-р алхам — GitHub Repository үүсгэх

```bash
# Шинэ folder үүсгэх
mkdir 14-honog-sorilт
cd 14-honog-sorilт

# Файлуудыг хуулах
# index.html   ← 14-honog-sorilт.html-ийг index.html болгон нэрлэх!

# Git эхлүүлэх
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/ТAНЫ_USERNAME/ТAНЫ_REPO.git
git push -u origin main
```

---

## 🌐 3-р алхам — GitHub Pages идэвхжүүлэх

1. GitHub дээр repository нээх
2. **Settings** → **Pages**
3. **Source**: `Deploy from a branch`
4. **Branch**: `main` → `/ (root)`
5. **Save** дарах
6. Хэдхэн минутын дараа:
   `https://ТAНЫ_USERNAME.github.io/ТAНЫ_REPO/`

---

## 📱 4-р алхам — Гар утсандаа суулгах (PWA)

### iPhone (Safari):
1. Safari-аар апп-ийн хаягийг нээх
2. Share товч (□↑) → **Add to Home Screen**
3. **Add** дарах → Дэлгэцийн доод хэсгээс апп шиг нээгдэнэ

### Android (Chrome):
1. Chrome-аар нээх
2. Дээд баруун буланд ⋮ → **Add to Home screen**
3. **Add** дарах

---

## 🔑 Нэвтрэх мэдээлэл

| Хэрэглэгч | Нэр | Нууц үг шаардлагагүй |
|---|---|---|
| 👨 Батаа | `bataa` | Нэрийг дарахад шууд нэвтэрнэ |
| 👩 Бямбажав | `byambaa` | Нэрийг дарахад шууд нэвтэрнэ |

---

## ☁️ Дата синхронизаци

- Аль нэг хэрэглэгч нэвтэрсний дараа **☁️ Sync** товч дарна
- Бүх дата Supabase-рүү хадгалагдана
- Нөгөө хүн нэвтрэхэд **Харьцуул** таб → шууд харна

---

## 📋 Файлын жагсаалт

```
14-honog-sorilт/
├── index.html          ← Апп (14-honog-sorilт.html-ийг нэрлэнэ)
└── README.md           ← Энэ файл
```

---

*Батаа, Бямбажав хоёрт зориулан хийсэн — 14 хоног тасрахгүй яв! 💪*
