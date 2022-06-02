# نشر التطبيقات باستخدام Spring boot

# أولا: تجهيز المشروع على Heroku
- إنشاء حساب على  https://www.heroku.com/
- تثبيت git عن طريق الرابط: https://git-scm.com/downloads 
- تثبيت nodejs عن طريق الرابط: https://nodejs.org/en/
- تسجيل الدخول عن طريق الأمر:
    npx heroku login



# **ثانيا:تجهيز المشروع باستخدام Git**

استخدم الاوامر التاليه بداخل ملفات مشروعك 

    git init
    git add . 
    git commit -m "first commit"


# **ثالثا:نشر التطبيق باستخدام heroku**

انشئ تطبيق heroku  

    npx heroku create <your_unique_app_name>

الامر السابق ينشئ تطبيق heroku و يجعلك تختار اسم المشروع 

انشر التطبيق باستخدام 

    git push heroku master


**مصادر اضافية:**

- https://devcenter.heroku.com/articles/deploying-spring-boot-apps-to-heroku
- https://www.youtube.com/watch?v=KDK5xXPJVIg


