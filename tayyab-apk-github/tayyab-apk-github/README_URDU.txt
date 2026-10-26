Tayyab Filling Station v3.3.2 — GitHub APK Build Project

اس ZIP میں Android APK بنانے کے لیے GitHub Actions workflow شامل ہے۔

طریقہ:
1) ZIP extract کریں۔
2) اس کے اندر موجود تمام فائلیں اپنے GitHub repository کے root میں upload کریں۔
   خاص طور پر www/index.html، package.json، capacitor.config.json اور .github/workflows/build-apk.yml
3) GitHub میں repository کھولیں، Actions tab پر جائیں۔
4) “Build Tayyab Filling Station APK” workflow منتخب کریں۔
5) Run workflow دبائیں اور build مکمل ہونے کا انتظار کریں۔
6) کامیاب run کھولیں، نیچے Artifacts میں Tayyab-Filling-Station-v3.3.2-APK ڈاؤن لوڈ کریں۔
7) ZIP extract کریں؛ app-debug.apk موبائل میں install کریں۔

اگر repository میں پہلے سے کوئی پرانی .github/workflows فائل ہو تو اسے فوراً delete نہ کریں؛ پہلے اس نئی workflow کا نام اور folder path چیک کریں۔

اہم:
- یہ GitHub-ready source/build package ہے، پہلے سے تیار APK نہیں۔ APK GitHub Actions پر build ہوگی۔
- موجودہ پرانے APK کے اندر محفوظ ڈیٹا خودکار طور پر نئی APK میں منتقل نہیں ہوتا۔ پہلے app سے JSON backup بنائیں اور محفوظ رکھیں۔
- APK build کامیاب ہونے کا مطلب یہ نہیں کہ تمام features عملی طور پر test ہو گئے ہیں۔ Backup/Restore کو اپنے backup کی copy سے test کریں، اصل واحد backup پر نہیں۔
