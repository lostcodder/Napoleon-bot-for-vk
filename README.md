# Napoleon-bot-for-vk

In order for the bot to work, you need to install Node.js and ConEmu on your computer
  
   * Node.js https://nodejs.org/en/   ConEmu https://conemu.github.io/
  
Place the Napoleon.js file in the folder with Node.js

For the convenience of modifying the file, you need to download the Notepad ++ editor

   * Notepad ++ https://notepad-plus-plus.org/
    

To get Access Token with all the rights, you need to follow the link and create your Standalone application
https://vk.com/apps?act=manage

After creation, copy the ID of your application and paste into this link, for the place of the APPLICATION ID and press Enter.
https://oauth.vk.com/authorize?client_id=ID_APPLICATIONS&scope=notify,photos,friends,audio,video,notes,pages,docs,status,questions,offers,wall,groups,messages,notifications,stats,ads, offline & redirect_uri = http: //api.vk.com/blank.html&display=page&response_type=token
After clicking on the link, in the address bar, copy your Access Token

Open the Napoleon.js file with the downloaded editor and in 43 line enter your Access Token

Open ConEmu and enter the command
   - cd c: / Program Files / Nodejs
   - node napoleon.js
   
In the console, you will see a small welcome message and information that the bot has been successfully launched and running. That's all.

Pleasant use.


//Русская версия пояснения

Для того, что бы бот работал, вам необходимо установить на свой компьютер Node.js и ConEmu
   - Node.js https://nodejs.org/en/
   - ConEmu  https://conemu.github.io/
Поместить файл Napoleon.js в папку с Node.js

Для удобства изменения файла, необходимо скачать редактор Notepad++ 
   - Notepad++  https://notepad-plus-plus.org/
    
Для получения Access Token со всеми правами, вам необходимо пройти по ссылке и создать свое Standalone приложение
https://vk.com/apps?act=manage

После создания, скопируйте ID вашего приложения и вставьте в эту ссылку, за место ID ПРИЛОЖЕНИЯ и нажмите Enter. 
https://oauth.vk.com/authorize?client_id=ID_ПРИЛОЖЕНИЯ&scope=notify,photos,friends,audio,video,notes,pages,docs,status,questions,offers,wall,groups,messages,notifications,stats,ads,offline&redirect_uri=http://api.vk.com/blank.html&display=page&response_type=token
После перехода по ссылке, в адресной строке скопируйте ваш Access Token 

Откройте файл Napoleon.js скачаным редактором и в 43 строке введите ваш Access Token

Откройте ConEmu и введите команду
   - cd c:/Program Files/Nodejs
   - node napoleon.js
   
В консоли вы увидите небольшой приветствие и информацию о том что бот успешно запущен и работает. На этом все.

Приятного пользования.

