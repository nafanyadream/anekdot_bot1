Telegram Bot for Jokes
Этот проект представляет собой простого Telegram-бота, который отправляет случайные анекдоты пользователям по команде /joke. Бот использует библиотеку aiogram для работы с Telegram API и BeautifulSoup для парсинга анекдотов с сайта anekdot.ru.

Как это работает
Бот инициализируется с использованием токена, указанного в password.py.
При получении команды /joke бот вызывает функцию get_white_joke(), которая делает HTTP-запрос к сайту anekdot.ru и парсит HTML-код для извлечения анекдотов.
Случайный анекдот отправляется пользователю в ответ на команду.

Примечания
Убедитесь, что у вас есть доступ к интернету, чтобы бот мог получать анекдоты с сайта.
Если бот не может найти анекдоты, он отправит сообщение "Не удалось найти анекдоты."

Лицензия
Этот проект лицензирован на условиях MIT License. Вы можете свободно использовать и изменять код, но не забудьте указать авторство.

Контрибьюция
Если вы хотите внести изменения или улучшения в проект, пожалуйста, создайте pull request или откройте issue для обсуждения.
