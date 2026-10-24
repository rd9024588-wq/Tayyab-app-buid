TAYYAB FILLING STATION — APK BUILD PACKAGE

اہم: یہ APK بنانے کا پیکج ہے؛ APK پہلے سے compile نہیں ہے۔ GitHub اسے آن لائن build کرے گا۔ Android Studio انسٹال کرنے کی ضرورت نہیں۔

آسان طریقہ:
1) اس ZIP کو Extract کریں۔
2) https://github.com پر اپنے اکاؤنٹ میں Sign in کریں۔
3) اوپر + پر کلک کریں، پھر New repository منتخب کریں۔
4) Repository name لکھیں: Tayyab-Filling-Station-APK
5) Public یا Private منتخب کریں، پھر Create repository دبائیں۔
6) نئی repository میں Add file > Upload files کھولیں۔
7) ZIP کے اندر موجود تمام فائلیں/فولڈر اپ لوڈ کریں، ZIP خود اپ لوڈ نہ کریں۔ خاص طور پر .github فولڈر بھی شامل ہونا چاہیے۔
8) Commit changes دبائیں۔
9) Actions ٹیب کھولیں۔ اگر اجازت مانگے تو I understand my workflows, go ahead and enable them دبائیں۔
10) بائیں طرف Build Tayyab Filling Station APK منتخب کریں۔ Run workflow > سبز Run workflow دبائیں۔
11) Build مکمل ہونے تک انتظار کریں۔ سبز نشان آنے کے بعد اسی workflow run کو کھولیں۔
12) نیچے Artifacts میں Tayyab-Filling-Station-APK پر کلک کریں۔ ZIP ڈاؤن لوڈ ہوگی؛ اسے Extract کریں۔ اس کے اندر app-debug.apk ہوگی۔
13) APK موبائل میں بھیجیں، کھولیں اور Android کے پوچھنے پر صرف اسی فائل/ایپ کے لیے Install unknown apps کی اجازت دیں۔ پھر Install کریں۔

اگر Actions میں workflow نظر نہ آئے:
- یقینی بنائیں .github/workflows/build-apk.yml اپ لوڈ ہوئی ہے۔
- repository میں Actions ٹیب کھولیں اور workflows enable کریں۔
- پہلے commit کے بعد ایک مرتبہ صفحہ refresh کریں۔

اہم حدود:
- یہ پیکج آپ کے موجودہ Tayyab_Filling_Station_Supabase_Sync.html کو Android app میں پیک کرتا ہے۔ یہ cloud build ہے، پہلے سے تیار APK نہیں۔
- Supabase Sync چلانے کے لیے آپ کے موجودہ Supabase Project URL، Publishable Key، Auth اور database policy درست ہونا ضروری ہے۔
- اس APK میں وہی ویب ایپ کوڈ شامل ہے؛ اس پیکج سے Supabase لاگ اِن/سنک یا موبائل پر ہر PDF فیچر کی کامیابی کی ضمانت نہیں دی جا سکتی۔ انسٹال کے بعد پہلے test data سے آزمائیں اور اصل ڈیٹا کی JSON backup محفوظ رکھیں۔
- GitHub repository میں اپنے Supabase secret/service_role key کبھی اپ لوڈ نہ کریں۔ صرف Publishable key استعمال کریں۔
