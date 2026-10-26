TAYYAB FILLING STATION - CLEAN GITHUB APK BUILD

اہم: یہ سورس/Build ZIP ہے، پہلے سے تیار APK نہیں۔ GitHub Actions میں build چلانا ہوگا۔

اس ZIP کے اندر package.json، capacitor.config.json، www/index.html اور ایک ہی workflow موجود ہے۔

اپ لوڈ کرنے کا درست طریقہ:
1) ZIP کو کمپیوٹر پر Extract کریں۔
2) اپنے GitHub repository Tayyab_Filling_Station_APK-31 کے مرکزی صفحے (root) میں جائیں۔
3) پرانی فائلوں کو پہلے محفوظ کر لیں۔ پھر اس ZIP کے اندر کی فائلیں/فولڈرز root میں upload کریں۔
4) repository کے .github/workflows فولڈر میں موجود پرانی workflow YAML فائلیں حذف کریں۔ صرف .github/workflows/tayyab-apk-build.yml رہنے دیں۔
5) Commit changes کریں۔
6) Actions tab کھولیں۔ 'TAYYAB APK BUILD - CLEAN NO CACHE' منتخب کریں اور Run workflow دبائیں۔
7) کامیاب run کے بعد Artifacts میں Tayyab-Filling-Station-APK ڈاؤن لوڈ کریں۔

اگر Actions میں اب بھی 'Dependencies lock file is not found' آئے تو لازماً پرانی workflow چل رہی ہے یا repository میں کوئی دوسری workflow فائل موجود ہے۔ اس ZIP کی نئی workflow میں cache بند ہے اور npm ci استعمال نہیں ہوتا۔

اہم حدود:
- یہ build پیکج ہے، APK پہلے سے شامل نہیں۔
- GitHub پر run کیے بغیر compile کی کامیابی کی ضمانت نہیں دی جا سکتی۔
- پرانے JSON backup کی Restore اور تصاویر upload کی درستگی الگ functional test مانگتی ہے۔ اپنی اصل backup فائل محفوظ رکھیں۔
