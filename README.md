Необходимо распаковать ffmpeg в папке с кодом

________________________________________

Задача - создать дискорд бота, который при подключении к голосовому каналу на сервере, будет воспроизводить музыку по команде с вставленной ссылкой с ютуба.
Для этого, я буду пользоваться ffmpeg - библиотеками, которые позволяют записывать, конвертировать и передавать цифровые аудио- и видеозаписи в различных форматах.
Также, необходимы библиотеки:

discord

python-dotenv

asyncio

yt_dlp - для ссылок с ютуба

________________________________________

Бот обладает такими возможностями, как:

!play ссылка с ютуба - проигрывает вставленную музыку.

!pause - останавливает играющую музыку.

!resume - воспроизводит остановленную музыку.

!stop - бот оканчивает работу.

!queue ссылка с ютуба - добавляет вставленную музыку в очередь.

!skip - включает следующую музыку из очереди.

!clear_queue - очищает очередь. 
