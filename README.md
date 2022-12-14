# Exam_OOP
 
Реалізувати повнофункціональну систему тестування.
У системі має бути реалізовано 2 режими:
■ Адміністратор;
■ Тестований.
Опис режиму робота для Тестованого (надалі гість)
Для входу в систему гість мусить зареєструватися. Ця процедура виконується один раз, при подальших входах в систему доступ надається за логіном і паролем. При реєстрації потрібно вказувати ПІБ, домашню адресу, телефон. Важливо, щоб логіни для користувачів були унікальними. Після входу гість має змогу переглянути свої попередні результати тестування, пройти нове тестування. Тестування може бути за різними категоріями знань. Наприклад:
Математика (розділ) –> Дискретна математика (конкретний тест);
–> Математичний аналіз (конкретний тест).
Фізика (розділ) –> Квантова фізика (конкретний тест);
–> Механіка (конкретний тест).
Після здачі тесту гість бачить результат тестування, кількість питань, на які він відповів правильно, відсоток правильних відповідей і отриману оцінку. Студент має змогу зупинити тестування і продовжити його тоді, коли йому це буде зручно. Оцінювання має будуватися на 12-бальній системі, що прив’язана до кількості питань тесту. Паролі та логіни гостей зберігаються в зашифрованому вигляді.

Опис режиму робота для Адміністратора (надалі адмін)
У системі може бути тільки один адмін, логін і пароль адміна задається при першому вході в програму. Надалі пароль і логін можна змінити (але цю змогу має тільки адмін). Пароль і логін необхідно зберігати тільки в зашифрованому вигляді. При роботі з системою адмін має такі можливості:
■ Управління користувачами – створення, видалення, модифікація користувачів.
■ Перегляд статистики – перегляд результатів тестування загалом за категоріями, за конкретними тестами, за конкретними користувачами. Результати перегляду статистики можна вивести у файл.
■ Управління тестуванням – адмін має змогу додавати категорії, тести, питання до тестів, задавати правильні й неправильні відповіді, імпортувати й експортувати категорії і тести з питаннями з файлу (та у файл).
