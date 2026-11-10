# خطوات التشغيل (مرة واحدة)

1. https://console.firebase.google.com ← Add project (مجاني).
2. Build ← Authentication ← Get started ← فعّل Google.
3. Build ← Firestore Database ← Create (production mode).
4. Firestore ← Rules ← الصق محتوى firestore.rules بعد ما تغيّر الايميل جواه لايميلك ← Publish.
5. Project settings ← Your apps ← Web (</>) ← انسخ firebaseConfig والصقه في config.js، وغيّر ADMIN_EMAILS لايميلك.
6. ارفع كل الملفات على GitHub repo ← Settings ← Pages ← Deploy from branch (main / root).
7. Authentication ← Settings ← Authorized domains ← أضف: username.github.io
8. افتح الرابط وادخل بايميلك (أدمن)، وأضف إيميلات الأعضاء (Gmail) من اللوحة. كل عضو بيدخل بحسابه.
