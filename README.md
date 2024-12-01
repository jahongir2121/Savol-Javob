O'rnatish
(sizda mavjud bo'lmagan dastur va paketlarni o'rnating, platformani ishlatish vaqtida xatolik kelib chiqmasligi uchun)

Agar sizda php(XAMPP) o'rnatilmagan bo'lsa, quyidagi havola orqali yuklab olib, o'rnatishingiz mumkin:

    https://www.apachefriends.org/

Composer o'rnatish kerak bo'lsa:

    https://getcomposer.org/download/

NodeJS kerak bo'lsa:

    https://nodejs.org/en

Kerakli paketlar o'rnatib bo'lingandan keyin, quyidagi qadamlarni bajarib, loyihani o'z tizimingizda ishga tushirishingiz mumkin: Repositoryni klonlash:

    git clone https://github.com/jahongir2121/savol-javob

Loyihaning papkasiga o'tish:

    cd savol-javob

Composer o'rnatish:
    
    composer install

env faylni yarating: 

    cp env.example .env

.env faylni o'zgartiring va ma'lumotlar bazasi ma'lumotlarini kiriting:

    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=savol_javob
    DB_USERNAME=root
    DB_PASSWORD=

Key Generatsiya qiling:

    php artisan key:generate

Ma'lumotlar bazasini migratsiya qilish:
    
    php artisan migrate

Serverni ishga tushirish:

    php artisan serve


<!-- kornish-->
## korinish
![Screenshot (1177)](https://github.com/izzanka/luora/assets/59280562/76bcdc32-ca53-4943-b5a0-43dd37237381)
![Screenshot (1178)](https://github.com/izzanka/luora/assets/59280562/e035ac71-776d-4978-b932-300ae00a9175)
![Screenshot (1179)](https://github.com/izzanka/luora/assets/59280562/f4cb8fa7-836d-401a-9027-566a945d86ea)
![Screenshot (1182)](https://github.com/izzanka/luora/assets/59280562/39ab8671-028e-4ef0-974c-a569d15d0bd0)
![Screenshot (1184)](https://github.com/izzanka/luora/assets/59280562/c75ba0d1-d7b8-46bc-bbed-00bfa0cab7f6)
![Screenshot (1194)](https://github.com/izzanka/luora/assets/59280562/1f99e2ac-98d5-4227-ba21-c8540920a305)
![Screenshot (1195)](https://github.com/izzanka/luora/assets/59280562/67875d7e-b022-46b5-9478-4f4140a54c97)
![Screenshot (1197)](https://github.com/izzanka/luora/assets/59280562/8e5fc442-8080-4355-9519-691858130360)



