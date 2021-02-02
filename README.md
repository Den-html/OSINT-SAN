## OSINT SAN 3.0  Красная тревога.


Framework создан для сбора информации с открытых источников.
Но есть инструменты поиска и брутфорса которые использовать нужно, только с разрешения владельца ресурса, хочу вас предупредить что я не несу никакой ответственности за ваши действия при работе с Framework.

На данный момент это бесплатная версия продукта она же финальная. Платная версия находится в разработке. Как только будет готова платная версия продукта мы сообщим в телегарам канале.

![alt tag](https://github.com/Bafomet666/screen/blob/main/bafomet%20soft%20logo.png)

### Инструмент работает на Kali Linux * Parrot OS, адаптации под другие os и termux пока нету.
Перед работой с framework обязательно поддержки нас подпиской на офицальный канал: https://t.me/osint_san_framework и поставь звезду на репозиторий.

Меню OSINT SAN. Во время вашего прочтения, уже введены новые функции.

![alt tag](https://github.com/Bafomet666/screen/blob/main/3.0%2001.png)

В меню вы увидите 45 функций для поиска. От простого до сложного. Сейчас заполнено только одно menu, второе меню начнем пополнять в обнолении 4.0 и выше.
            
## Установка API.
Их нужно зарегистрировать и прописать по указаному пути. Многие я оставлю прописаными в инструменте но так как там лимиты маленькие, лучше создать свои.

Название API и их путь.

     nomber api /OSINT SAN 3.0 RED OSINT/plugins/api [http://apilayer.net/api]

     gmap api /OSINT SAN 3.0 RED OSINT/plugins/api [https://developers.google.com/maps/documentation]

     ipstack api /OSINT SAN 3.0 RED OSINT/plugins/api [https://ipstack.com/]

     shodan api /OSINT SAN 3.0 RED OSINT/core/config and OSINT SAN 3.0 RED OSINT/exploit_database/api [https://www.shodan.io/]

     maildb api /OSINT SAN 3.0 RED OSINT/plugins/maildb [Уже введен]

     whatcms /OSINT SAN 3.0 RED OSINT/plugins/webosint/CMSdetect [https://whatcms.org/API]

     virus total /OSINT SAN 3.0 RED OSINT/plugins/webosint/subdomain.py [Уже введен]

     hunter /OSINT SAN 3.0 RED OSINTplugins/maildb.py hunter.io [https://hunter.io/api]

     ZoomEye api вход проходит через авторизацию.
     
## Установка зависимостей.
 
Как только вы ввели все свои API, вам нужно установить зависимости. Установка легкая.

     sudo pip3 install -r requerements.txt
    
     В сложных модулях, вам будет предоставлен выбор дополнительной установки модулей.


## Баннер авторизации.
Инструменты запускаются в двух вариантах.

Запускаем инструмент командой:

      Если вам нужны функции без root, запускайте:  python3 osintsan.py
      
      Если вам нужны функции root, запускайте:      sudo python3 osintsan.py
      
     
Пароль и логин хранится у нас в паблике в telegram.

![alt tag](https://github.com/Bafomet666/screen/blob/main/3.0%2002.png)

После успешной авторизации тебе будет доступно меню с инструментами.

![alt tag](https://github.com/Bafomet666/screen/blob/main/3.0%2001.png)

Обязательно прочитай лицензионное соглашение, 45 функция.
Вроди все расписал, теперь нам нужно переходить к самим инструментам и их описанию, так что готовься много читать, их там много.

### Функция [ 01 ]
Начнем с простого инструмента, это проверка IP адреса в Shodan and Censys на утечки, здесь все просто, прописываете IP адрес и получаете результат.

![alt tag](https://github.com/Bafomet666/screen/blob/main/0130.png)

### Функция [ 02 ]
Здесь уже все по круче. Использовать только с разрешения владельца ресурса.
Вам будет предложенно ввести адрес сайта, пример google.com и ввести порт, можно просто enter нажать он сам все сделает.
Очень много подпунктов, использовать осторожно.

![alt tag](https://github.com/Bafomet666/screen/blob/main/3.0-002.png)

### Функция [ 03 ]
Вводим номер ( Пример: +74997059999 ) и получаем сведенья.

![alt tag](https://github.com/Bafomet666/screen/blob/main/3.0-003.png)

### Функция [ 04 ]
После успешного использования, карта появляется в папке инструмента, всегда в высоком разрешении и очень детальная.

![alt tag](https://github.com/Bafomet666/screen/blob/main/044.png)

### Функция [ 05 ]
Если в фото есть геолокация, софт её найдет, вам толко нужно будет указать путь. Пример пути: /home/bafomet/Desktop/deanon.png
### Функция [ 06 ]
Поиск по фото.
Вам нужно указать путь до картинки. После вас спросят хотите ли
вы открыть браузер, вы жмете “ y “ и открывается браузер.

![alt tag](https://github.com/Bafomet666/screen/blob/main/0066.png)

### Функция [ 07 ]
Проверка сервера либо IP адреса на HoneyPot ( ловушку для
хакеров )

![alt tag](https://github.com/Bafomet666/screen/blob/main/07.png)

Показывает все в процентах.

### Функция [ 08 ]
 Mac address info, с вероятностью 40% покажет еще и геолкацию.
 
![alt tag](https://github.com/Bafomet666/screen/blob/main/88854.png)

### Функция [ 09 ]
IP геолокация на картах.
Как по мне самые вкусное что я делал. IP геолокация GUI на картах.
При нажатии функции 9 вам выпадет вот такое окно.

![alt tag](https://github.com/Bafomet666/screen/blob/main/00009.png)​

Далее вам нужно либо ввести IP адрес либо домен.
Вариант выберите обязательно.  
### Функция [ 10 ]
Проверяем что качает через torrent в данный момент жертва.
Попутно узнаем её координаты.
 (Скрин сделан на версии продукта 2.0)
 
![alt tag](https://github.com/Bafomet666/screen/blob/main/photo_2020-12-13_02-33-17.jpg)​

Если в данный момент, жертва ничего не загружает будет
выводиться окно:
 (Скрин сделан на версии продукта 2.0)
 
![alt tag](https://github.com/Bafomet666/screen/blob/main/011.png)

### Функция [ 11 ]
OSINT Instagram.
![alt tag](https://github.com/Bafomet666/screen/blob/main/1111111.png)
### Функция [ 12 ]
DNS info, огромнейший pack информации выводит, я не смогу здесь все в один скрин выложить.
### Функция [ 13 ]
Ищем адреса mail с сайтов. Используем API censys.

![alt tag](https://github.com/Bafomet666/screen/blob/main/014.png)

### Функция [ 14 ]
Подключение через ADB, точнее это оболочка для быстрого подключения. Обязательно установить зависимости.

![alt tag](https://github.com/Bafomet666/screen/blob/main/14000.png)

### Функция [ 15 ]
Big bro 8.0 режим геолокации.

![alt tag](https://github.com/Bafomet666/screen/blob/main/big%20bro%20geo.png)

### Функция [ 16 ]
Массовый dump данных с Shodan. Работает через API, тот же поисковик только в консоли и анонимный.
Скрин сделать на версии продукта 2.0

![alt tag](https://github.com/Bafomet666/screen/blob/main/017.jpg)

### Функция [ 17 ]
Графический мониторинг твоей сети.

![alt tag](https://github.com/Bafomet666/screen/blob/main/99.png)

https://etherape.sourceforge.io/
https://ru.wikipedia.org/wiki/EtherApe
### Функция [ 18 ]
Сейчас эта функция нечего не загружает. Пока я не буду выкладывать dls либо другие обновления. Как минимум до конца января. Только глобальные. По причине не хочу заебывать вас мелкими обновами.

![alt tag](https://github.com/Bafomet666/screen/blob/main/016.png)

### Функция [ 19 ]
Просто открывает инструкцию.
### Функция [ 20 ]
Окно списка зависимостей.
### Функция [ 21 ]
Огромная многостраничная википедия по осинту.

![alt tag](https://github.com/Bafomet666/screen/blob/main/00000021.png)

### Функция [ 22 ]
Брутфорс instagram.
указываете логин и вперед. Если вдруг надо пароли сменить, в папке OSINT SAN 3.0 RED OSINT/exploit_database лежит документ password, удаляете все и вставляете свои пароли.
### Функция [ 23 ]
Рекомендуемые средства для анонимизации.
### Функция [ 24 ]
База данных паролей Bafomet +
Сейчас в базе 1.9 миллиарда паролей собрано. Все разбито по частями, что бы удобно было загружать. Пароли под различные задачи.

### Функция [ 25 ]
Поднимаем сайт Beff-XSS в сеть

Сначал вам нужно будет нажать 1. Это вариант с онлайном.
Потом вам выпадет инструкция по установке ngrok в положение ( start --all на 4 ссылки ) После вы запускаете ngrok в полном режиме и даете старт программе.

![alt tag](https://github.com/Bafomet666/screen/blob/main/250.png)

После вас попросят вписать ссылки, вписываем до http, https в таком формате:

     f19d35259оaff5.ngrok.io  всегда сначала по 80 порту
     
     f19d3c96533ff5.ngrok.io  потом по 3000 порту
     
А теперь установка стилей для сайта. Вам нужно перейти в папку "OSINT SAN" и скопировать все там из папки "Стили Beef" в директорию /var/www/html

Если вдруг у вас нет доступа к копированию стилей в beef html, Сделайте:
         
         sudo chmod 777 /var/www/htm

### Функция [ 26 ]
Наше большое сообщество OSINT СНГ. Здесь я собрал адреса всех ресурсов где есть полезная информация. Админов ресурсов знаю лично. Отличные парни.

### Функция [ 27 ]
Работа с доменом 2.0

![alt tag](https://github.com/Bafomet666/screen/blob/main/270.png)

### Функция [ 28 ]
Open Maltego, просто открывает мальтего.

![alt tag](https://github.com/Bafomet666/screen/blob/main/maltego.jpg)

### Функция [ 29 ]
Массовый dump данных с ZoomEye. Аналог shodan.
Вход через логин и пароль от самого сайта. Анонимный поиск с выбором с какой страницы дампить данные. Все данные сохраняются в папке с инструментом.
![alt tag](https://github.com/Bafomet666/screen/blob/main/290.png)

### Функция [ 30 ]
Деанонимизация хакера его же ссылкой, это обычный парсер, представим ситуацию, вам мамкин хакер скинул ссылку ngrok, что бы вы перешли и он узнал вашу геолокацию. Но вы возьмете эту ссылку и впишите в инструмент отслеживания и подождете, обычно он на себе ёё проверяет и деанонит себя.
Функция 30 направленна на то что бы автоматически воровать результат с его машины. Обратный деанон, Так-же можно отключить его ngrok, либо сломать, проверить с какого он железа работает. 

![alt tag](https://github.com/Bafomet666/screen/blob/main/300.png)

### Функция [ 31 ]
IP logger для профи, Firefox.
Вы можете создавать как ссылки логеры так и файлы. Практически любые.

### Функция [ 32 ]
Анонимный чат.(Ожидайте в след месяце)

### Функция [ 33 ]
dns whois сайтов.

![alt tag](https://github.com/Bafomet666/screen/blob/main/33.png)

### Функция [ 34 ]
Данные по утечкам, взято из открытых источников.

![alt tag](https://github.com/Bafomet666/screen/blob/main/340.png)


### Функция [ 36 ]
Большой пак по осинту. Будет пополняться по мере возможности.

![alt tag](https://github.com/Bafomet666/screen/blob/main/3600.png)

### Функция [ 39 ]
Big Bro 8.0 fish mod (alfa)


### Функция [ 45 ] Лицензионное соглашение.
![alt tag](https://github.com/Bafomet666/screen/blob/main/sogl.png)


## Техническая поддержка.

![alt tag](https://github.com/Bafomet666/screen/blob/main/Screenshot%20at%202020-12-13%2002-02-20.png)​

Техническая поддержка осуществлется всем кто поддержал донатом, в течении трех месяцев, с момента последнего доната.


Также фреимворк вы можете запускать как с рутом так и без. Часть функций требует рут а часть нет. Под каждым инструментом подписано.

Первый вариант это без рута полностью, в функциях подписано [N] значит, запускайте консоль без рута вообще  python3 osintsan.py.
Второй это уже с рутом, подпись [R], то есть запуск sudo python3 osintsan.py

Приятного использования.

##FAQ

- Почему не описаны некоторые функции на github ?

- Я не стал их описывать так как это либо свободный слот, либо секретная функция.


- Почему не работает на windows, termux ?

- Порта еще нету, не выпустил адаптацию.

- Если вдруг фреимворк подвис или сам терминал, выйди комбинацией ctrl + z


