طريقة عمل التطبيق (APK) بدون Android Studio
=============================================
1) ادخل github.com واعمل حساب مجاني، وبعدين New repository (اسمه أي حاجة، Public أو Private).
2) من الكمبيوتر: افتح الريبو > Add file > Upload files، وانزّل محتويات الفولدر ده كله
   (لازم يظهر معاهم فولدر .github وفولدر app). بعدين Commit changes.
3) افتح الملف app/src/main/res/values/strings.xml واستبدل
   https://YOUR-SITE.infinityfreeapp.com/  برابط موقعك (لازم https وينتهي بـ /) وعمل Commit.
4) روح تبويب Actions > Build APK > استنى لحد ما يبقى أخضر (3 - 6 دقايق).
5) افتح التشغيلة الأخيرة، ونزّل app-apk من تحت Artifacts، وفك الضغط هتلاقي app-debug.apk.
6) ابعت app-debug.apk على الموبايل وثبّته (فعّل "التثبيت من مصادر غير معروفة" لو طلب).

التطبيق بيفتح موقعك بس. أي رابط تاني بيتمنع، وبس الاتصال والواتساب بيتفتحوا بتطبيقاتهم.
