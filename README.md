# Canzade-ToastyStat

# Kurulum

**1-** process.env klasorünün ismini .env çevir 

**2-** Bot tokenini gir
**3-** MongoDB url'ni gir, eğer urlyi almayı bilmiyorsan Youtube'dan araştırıp alabilirsin.
**4-** LeaderBoard kanal id'ni LEADERBOARDS_CHANNEL kısmına gir yani bu kanala 2 tane embed atıp o mesajları her 30 dakikada bir düzenleyecek
**5-** Şimdi biraz sıkıntılı kısma geliyoruz yukarıda bellirtiğin leaderboard kanalına ilk önce aynı token ile başka bir bota girip, o kanala 2 tane mesaj attırman gerekiyor.
**6-** Attırdığın mesajın id'ini LEADERBOARDS_MESSAGE_TEXT kısmına girmelisin bu mesaj verilerini güncelleyecektir.
**7-** Attırdığın mesajın id'ini LEADERBOARDS_MESSAGE_VOICE kısmına girmelisin bu ses verilerini güncelleyecektir.
**8-** GUILD_ID kısmına sunucu id'ni gir

# Kurulum 2

**1-** config.ts dosyasına girip bazı idleri girmen gerekiyor
**2-** VOICE_REWARDS yeri ses ödülleridir yani belirtilen kullanıcı belirttiğin bir süre seste durursa ona belirttiğin hediye rolünü ekler. Alttaki ss'de gözüktüğü gibi kullanıcı toplam 4 gün, 12 gün, 33 gün ve 83 gün seste durursa rollerini verecek
![image](https://user-images.githubusercontent.com/77938499/139867292-589247c8-7f77-495a-bd6f-43d555e2a11a.png)
#**3-** TEXT_REWARDS yeri chat ödülleridir yani belirtilen kullanıcı belirttiğin bir mesaj sayısına oluşursa ona belirttiğin hediye rolünü ekler. Alttaki ss'de gözüktüğü gibi kullanıcı toplam 1000, 5000, 50000 ve 100000 mesaj atarsa rollerini verecek

# BOTU ÇALIŞTIRMA
**1-** Evet artık hazırsın sıra botu çalıştırma kısmına geldi. Öncelikle terminali açıp npm install yazmalısın, **UNUTMA** modülleri indirmediğin için her modül hata verecektir. Eğer modülleri indirdikten sonra modüller hata vermeye devam ediyorsa Visual Studio Code'u kapatıp yeniden açmanı tavsiye ederiz.
**2-** Modülleri kurduktan sonra geriye sadece botu başlatmak kaldı. Bunu da terminale npm run start veya ts-node index.ts yazarak halledebilirsin iyi kullanımlar!


# BOTA DAİR GÖRÜNTÜLER

![image](https://user-images.githubusercontent.com/77938499/121361655-2c1a2b80-c93e-11eb-8536-dac1b8979317.png)

![image](https://user-images.githubusercontent.com/77938499/121361700-376d5700-c93e-11eb-97b4-8e2020c81e41.png)

![image](https://user-images.githubusercontent.com/77938499/121361741-3dfbce80-c93e-11eb-912d-3849c83851c4.png)
