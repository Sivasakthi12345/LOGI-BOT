<p align="center"><a href="https://t.me/VeezVideoBot"><img src="https://github.com/LOGI-TECH/LOGI-BOT/blob/master/logi/resources/logi.png"></a></p>
<p align="center">
    <br><b>The Telegram group management and music & video Stream bot repo in Open-Source. Telegram Bot project that's allow you to Manage your group with extra features and  play Video & Music trough the Telegram Group Video Chat</b><br>
</p>
<p align="center">
    <a href="https://app.codacy.com/gh/LOGI-TECH/LOGI-BOT/dashboard"> <img src="https://img.shields.io/codacy/grade/a723cb464d5a4d25be3152b5d71de82d?color=red&logo=codacy&style=flat-square" alt="Codacy" /></a>
    <a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/Made%20with-Python-black.svg?style=flat-square&logo=python&logoColor=blue&color=red" /></a>
    <a href="https://github.com/LOGI-TECH/LOGI-BOT/graphs/commit-activity" alt="Maintenance"> <img src="https://img.shields.io/badge/Maintained%3F-yes-red.svg?style=flat-square" /></a><br>
    <a href="https://github.com/LOGI-TECH/LOGI-BOT"> <img src="https://img.shields.io/github/repo-size/LOGI-TECH/LOGI-BOT?color=red&logo=github&logoColor=blue&style=flat-square" /></a>
    <a href="https://github.com/LOGI-TECH/LOGI-BOT/commits/main"> <img src="https://img.shields.io/github/last-commit/LOGI-TECH/LOGI-BOT?color=red&logo=github&logoColor=blue&style=flat-square" /></a>
    <a href="https://github.com/LOGI-TECH/LOGI-BOT/issues"> <img src="https://img.shields.io/github/issues/LOGI-TECH/LOGI-BOT?color=red&logo=github&logoColor=blue&style=flat-square" /></a>
    <a href="https://github.com/LOGI-TECH/LOGI-BOT/network/members"> <img src="https://img.shields.io/github/forks/LOGI-TECH/LOGI-BOT?color=red&logo=github&logoColor=blue&style=flat-square" /></a>
    <a href="https://github.com/LOGI-TECH/LOGI-BOT/network/members"> <img src="https://img.shields.io/github/stars/LOGI-TECH/LOGI-BOT?color=red&logo=github&logoColor=blue&style=flat-square" /></a>
</p>

</details>

# Depolying Method --> Step by Step

Step 1 :
                  Star and Fork this Two Repo
                 ✔ [*Management bot](https://github.com/LOGI-TECH/LOGI-BOT)
                  ✔ [*music bot](https://github.com/LOGI-TECH/MUSIC)
                  
Step 2 :
            First We Depoly Management bot repo : 
            
            Notes* --> you must fork and use this depoly button in yours forked repo

      
<p><a href="https://heroku.com/deploy"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a>
  </p>
 Step 3:
  
   - In this manager bot you want the Telethon string session
   
  - so you can generate Telethon session using this [bot](https://t.me/SessionStringGeneratorZBot)
  
  Step 4:
   Fill all required blanks 
  
  
1. `API_ID` : Bot Account Telegram API_ID, get it from my.telegram.org
2. `API_HASH` : Bot Account Telegram API_HASH, get it from my.telegram.org
3. `BOT_TOKEN` : Your Telegram Bot Token, get it from @Botfather (Make sure Inline is turned On)
4. `SESSION_STRING` : Telethon Session String of Assistant Account.
5. `ARQ_API_KEY ` : Get this from @ARQRobot.
6. `MONGO_DB_URI` : MongoDB Database URL.
7. `EVENT_LOGS` : Chat ID where bot will log everything. Use Group Chats Only.
8. `HEROKU_API_KEY ` : Your Heroku API key, get it from 'https://dashboard.heroku.com/account'
9. `DRAGONS` : Sudo Users for Bot. (For multiple users seperate IDs with space)
10. `OWNER_ID`: Owner ID of Bot
11. `SUPPORT_CHAT` : Support Group Link (Leave blank if you don't have one)
12. `SUPPORT_CHANNEL` : Support Channel Link ( Leave blank if you don't have one)
13. `START_IMG` : Enter Your Bot Image Telegraph Link
  
 After filled all required variables press the depoly botton and trun on the resource .
  
                             *BOOM 🎉 YOUR MANAGEMENT BOT IS READY*
  
 Next we depoly the music bot !
  
  Notes--> Depoly your music bot in same bot where you depoly the above management bot
  
 Step 5 :
        
 Press this Button to Depoly Music Bot in Heroku
  
 
   [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/LOGI-LAB/MUSIC)
  
  Step 6:
  
  - Now You need to generate the Pyrogram String Session 
  <h2 align="center">
   Generating Pyrogram Session
</h2>

<p align="center">
<a href="https://t.me/SessionStringGeneratorZBot"><img src="https://img.shields.io/badge/Generate%20On%20Repl-blueviolet?style=for-the-badge&logo=appveyor" width="245""/></a>
 </p>  
 
 Step 7:
 
 Fill the Required variables in the blanks:
 1. `API_ID` : Assistant Account Telegram API_ID, get it from my.telegram.org
2. `API_HASH` : Assistant Account Telegram API_HASH, get it from my.telegram.org
3. `BOT_TOKEN` : Your Telegram Bot Token, get it from @Botfather (Make sure Inline is turned On)
4. `SESSION_STRING` : Pyrogram Session String of Assistant Account.
5. `MUSIC_BOT_NAME` : A name for your Music bot.
6. `MONGO_DB_URI` : MongoDB Database URL.
7. `ALIVE_NAME` : fill with your telegram account nickname/name.
8. `OWNER_USERNAME` : fill with your telegram account username without @
9. `SUDO_USERS` : Sudo Users for Bot. (For multiple users seperate IDs with space)
10. `OWNER_ID`: Owner ID of Bot
11. `SUPPORT_GROUP` : Support Group Link (Leave blank if you don't have one)
12. `SUPPORT_CHANNEL` : Support Channel Link ( Leave blank if you don't have one)

After filled all required variables press the depoly botton and trun on the resource .

                             *BOOM 🎉 NOW YOUR MUSIC BOT IS ALSO READY*
  
  
  AFTER COMPLETE ALL PROCESS START YOUR BOT !

## Contact & Support

<a href="https://t.me/telegram"><img src="https://img.shields.io/badge/Join-Group%20Support-blue.svg?style=for-the-badge&logo=Telegram"></a><br>
<a href="https://t.me/logi_channel"><img src="https://img.shields.io/badge/Join-Updates%20Channel-blue.svg?style=for-the-badge&logo=Telegram"></a><br>
<a href="https://t.me/cl_me_logesh"><img src="https://img.shields.io/badge/Contact-Repo%20Owner-blue.svg?style=for-the-badge&logo=Telegram"></a>

## License

Distributed under the [GNU General Public License v3.0 License](https://github.com/LOGI-TECH/LOGI-BOT/blob/master/LICENSE) See `LICENSE.md` for more information.

## Credits
- [Logesh](https://github.com/LOGI-LAB) ``Dev``
- [Kennedy](https://github.com/kennedy-ex) ``Dev``
- [Levina](https://github.com/levina-lab) ``For Music bot Base``


