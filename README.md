# Тестовое задание АгроТорги

1.	Сверстать страницу из трёх  блоков:
- Хедер: логотип, строка меню (5 пунктов, двухуровневое), контакты (телефон, whatsapp), кнопка вход. Блок закреплён вверху экрана. При маленьких разрешениях (< 1000px) меняется на «гамбургер», вызывающий меню с такими же пунктами в развёрнутом виде в полноэкранном попапе, логотип, контакты, кнопка «вход»
- Блок преимущества: 7 пунктов вида картинка, заголовок, текст
- Блок обратная связь: форма с полями имя, телефон, email, вопрос. После ajax отправки должен показывать результат – успех или ошибка. Вывести  текст ошибки для каждого поля.

2.	Свёрстанную страницу отобразить средствами symphony:
- Использовать twig
- Данные из формы обратной связи записать в БД
- Проверить на корректность и заполненность на стороне сервера (пустым может быть или телефон или email, остальные поля должны содержать информацию)
- Ответ вернуть в формате json

За образец дизайна можно использовать https://agro.club/
В репозитории только установлена symfony. Для разработки склонируйте и создайте свою ветку.
При необходимости можем предоставить тестовую площадку для работы.
