# Android AI Builder V3
واجهة هاتف ترفع ZIP لمشروع Android حقيقي إلى GitHub، ثم GitHub Actions يبني APK Native.
المشروع يجب أن يحتوي Gradle Wrapper وملفات Android Gradle صالحة. هذه النسخة لا تغلف HTML ولا تحول HTML إلى APK.

## الاستخدام
1. أنشئ مستودع GitHub فارغاً.
2. أضف `index.html` إلى GitHub Pages/استضافة ويب.
3. أنشئ Fine-grained Token بصلاحية Contents: Read and write للمستودع.
4. أدخل `username/repository` والـ ZIP.
5. بعد الرفع افتح Actions > آخر تشغيل > Artifacts > android-native-apk.

لا تضع Token داخل ZIP.
