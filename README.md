# DoriScan AI — Android prototip

Android ilovasi (Java, AndroidX Activity, Google ML Kit OCR). Interfeys o‘zbek va rus tillarida.

## Imkoniyatlar
- Telefon kamerasi orqali dori qutisini suratga olish.
- Galereyadan quti yoki yo‘riqnoma suratini tanlash.
- ML Kit orqali suratdagi lotin va kirill yozuvlarini aniqlash.
- Aniqlangan matnni ko‘rish va dori nomini qo‘lda kiritish/tahrirlash.
- Dori nomi bo‘yicha yo‘riqnoma, tarkib, qo‘llanish, qarshi ko‘rsatmalar va nojo‘ya ta’sirlarni internetda qidirish.

## APK’ni telefondan GitHub orqali yig‘ish
1. GitHub’da `DoriScanAI` nomli repository yarating.
2. Ushbu ZIP ichidagi **DoriScanAI papkasining ichidagi barcha fayl va papkalarni** repository’ga yuklang (ZIP faylning o‘zini emas).
3. `Actions` bo‘limini oching. `Build DoriScan AI APK` workflow avtomatik ishga tushadi; zarur bo‘lsa `Run workflow` ni bosing.
4. Yashil yakunlangan build’ni oching va `DoriScanAI-debug-APK` artifact’ini yuklab oling.
5. Yuklangan ZIP’ni oching, `app-debug.apk` faylini bosing va Android so‘raganda brauzer/fayl menejeridan ilova o‘rnatishga ruxsat bering.

## Tibbiy xavfsizlik
Bu prototip dori vositasini suratdan ishonchli tasdiqlamaydi. U qadoqdagi matnni OCR orqali o‘qiydi; OCR xato qilishi mumkin. Qidiruv Google natijalarini ochadi, tekshirilgan tibbiy ma’lumotlar bazasi emas. Doza yoki davolash tavsiyasi bermaydi. Dorini qabul qilishdan oldin rasmiy yo‘riqnomani tekshiring va shifokor yoki farmatsevt bilan maslahatlashing.

## Texnik talablar
JDK 17, Gradle 8.9, Android SDK Platform 35. GitHub Actions workflow bu muhitni avtomatik sozlaydi.
