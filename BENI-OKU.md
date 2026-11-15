# MuscleRank → APK (GitHub ile, ücretsiz)

## 1. Depo oluştur
1. github.com'a gir (hesabın yoksa ücretsiz aç).
2. Sağ üstte **+** → **New repository**.
3. İsim: `musclerank` → **Private** (ya da Public) → **Create repository**.

## 2. Dosyaları yükle
1. Açılan sayfada **"uploading an existing file"** linkine tıkla.
2. Bu klasörün (musclerank-android) **içindeki her şeyi** seç ve sayfaya sürükle
   (`.github`, `app`, `build.gradle`, `settings.gradle`, `gradle.properties` ...).
3. Aşağıda **Commit changes**'e bas.

## 3. APK'yı indir
1. Deponun üstündeki **Actions** sekmesine gir.
2. **APK olustur** çalışıyor olacak (sarı nokta). 3–6 dakika bekle.
3. Yeşil ✓ olunca üstüne tıkla → sayfanın altında **Artifacts** → **MuscleRank-APK**'ya tıkla.
4. İnen zip'in içinde **MuscleRank-debug.apk** var. Telefona at ve kur.

## Actions'ta hiçbir şey yoksa
`.github` klasörü yüklenmemiştir (gizli klasörler bazen atlanır). O zaman:
1. **Actions** → **set up a workflow yourself**.
2. Açılan editördeki her şeyi sil, `workflow-yedek-build.yml` dosyasının içeriğini yapıştır.
3. **Commit changes** → 3. adıma dön.

## Uygulamayı güncellemek
Yeni `index.html`'i `app/src/main/assets/` klasörüne yükle (eskisinin üstüne).
GitHub yeni APK'yı kendisi derler; Actions'tan indirip telefona tekrar kur. Verilerin silinmez.
