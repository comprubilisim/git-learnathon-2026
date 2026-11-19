# 🚀 COMPRU Git & GitHub Learnathon 2026 — Canlı Uygulama

Bu repo, **19 Kasım 2026** tarihinde Piri Reis Üniversitesi'nde düzenlenen **Git & GitHub Learnathon** etkinliğinin canlı pratik uygulamasıdır.

## Görevin Nedir? (6 Adımda İlk Pull Request)

### 1. Repoyu Kendi Hesabına Kopyala (Fork)
Sağ üst köşedeki **Fork** butonuna tıklayarak bu repoyu kendi GitHub hesabına kopyala.

### 2. Projeyi Çalışma Ortamına Al (Clone veya Codespaces)
* **Kendi Bilgisayarında Çalışıyorsan:** Kendi fork repondaki yeşil **`<> Code`** butonundan HTTPS linkini kopyala ve terminalde çalıştır:
  ```bash
  git clone https://github.com/KENDI_KULLANICI_ADIN/git-learnathon-2026.git
  cd git-learnathon-2026
  ```
* **GitHub Codespaces ile Tarayıcıda Çalışıyorsan:** Kendi fork repondayken **`<> Code` -> `Codespaces` -> `Create codespace on main`** yolunu izle (otomatik olarak klonlanmış halde terminalin açılacaktır).

### 3. Kendi Dalını Oluştur (Branch)
Ana dal olan `main` üzerinde doğrudan değişiklik yapmıyoruz. Kendi isminle yeni bir dal aç:
```bash
git checkout -b katilimci/ad-soyad
```

### 4. Kendi Katılımcı Kartını Oluştur
`katilimcilar/` klasörünün içine **`ad-soyad.md`** adında yeni bir dosya oluştur (örnek format için `katilimcilar/ornek-katilimci.md` dosyasına bakabilirsin).

### 5. Değişikliklerini Kaydet ve GitHub'a Gönder (Add, Commit, Push)
```bash
git add .
git commit -m "Feat: Ad Soyad katilimci karti eklendi"
git push -u origin katilimci/ad-soyad
```

### 6. Pull Request (PR) Aç!
1. GitHub'da kendi fork repo sayfana dön ve sayfayı yenile.
2. Üstte beliren yeşil **"Compare & pull request"** butonuna tıkla.
3. Kontrol kutucuklarını işaretle ve **"Create pull request"** butonuna basarak kodunu ana projeye gönder!

---

### 💡 Takılırsan Hızlı Kurtarma Komutları
* **Fork açmayı unutup doğrudan ana repoyu `clone`ladıysan:** Tarayıcıdan repoyu forkla, ardından terminalde adresini güncelle:
  ```bash
  git remote set-url origin https://github.com/KENDI_KULLANICI_ADIN/git-learnathon-2026.git
  git push -u origin katilimci/ad-soyad
  ```
* **Commit mesajında yazım hatası yaptıysan:**
  ```bash
  git commit --amend -m "Feat: Duzeltilmis commit mesaji"
  ```
