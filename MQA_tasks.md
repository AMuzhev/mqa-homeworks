# Домашнее задание к занятию «Тестирование мобильных приложений»

### Цель заданий

1. Научиться проводить предварительные исследования и строить на их основе проверки.
2. Углубиться в практику по нахождению багов в рабочем продукте.

### Инструкция к заданию

1. Скопируйте шаблон таблицы по [ссылке](https://docs.google.com/spreadsheets/d/1lgKBmV-ix5xJ8AqT6lAuXRKBuYK_nRCsXhCHaQhSmwU/edit?usp=sharing).
2. В названии файла введите корректное название лекции, ваши фамилию и имя.
3. Зайдите в «Настройки доступа» и выберите доступ «Просматривать могут все в интернете, у кого есть ссылка». [Ссылка на инструкцию](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop), как предоставить доступ к файлам и папкам на Google Drive.
4. В таблице прикрепите ссылки на выполненную работу по каждому заданию. Пожалуйста, прикладывайте прямые ссылки на скриншоты.
5. В личном кабинете прикрепите ссылку на свою таблицу с решениями и ждите, когда преподаватель её проверит.
6. Дополнительные задачи, отмеченные звёздочкой (\*), выполняются по желанию. При помощи них можно получить дополнительную практику.
7. Выполненные задания присылать в полном объеме, по завершению всех обязательных пунктов, для получения положительной оценки.

---

## Задание 1

Нужно протестировать приложение Everybook, которое позволяет читать книги бесплатно или за деньги.
Если оно недоступно для использования, можете провести тестирование для приложения Shein. Оно есть и в Google Play, и в App Store. Так как оно довольно простое, вы будете применять исследовательскую технику тестирования.
Обратите внимание, что приложение боевое, поэтому совершать покупки за реальные деньги и отправлять отзывы в саппорт через приложение не нужно.

Ваша задача — найти минимум три функциональных или GUI-бага, а лучше — больше, и оформить их по стандартам.

Результат задания — заполненный раздел в шаблоне.

## Задание 2 Для студентов с девайсами Android

Вы получили новый тестовый Android-девайс.

Перед началом тестирования обязательно нужно включить на устройстве меню разработчика и функции в нём:

- показывать границы элементов;
- показывать нажатия и касания;
- установить настройку ANR — уведомление о том, что приложение не отвечает;
- установить лимит фоновых процессов — максимум 1 процесс;
- установить приложение Fake GPS Location. В меню разработчика выбрать данное приложение для фиктивных местоположений.

Результат задания — Google Docs с прямыми ссылками на скриншоты с включёнными функциями.
Напишите, для достижения каких целей тестирования эти функции меню разработчика могут вам помочь.

Обязательно изучите меню более детально и попробуйте другие функции в работе :)

## Задание 3\* Для студентов с девайсами Android

Включите на вашем устройстве режим **«Do not keep activities»** в меню разработчика.

**Что нужно сделать:**

- протестируйте любое ваше любимое приложение с включённым режимом DNKA и постарайтесь найти проблемные места.

Результат задания — ссылка на скринкаст найденной ошибки. Определите, почему особенно важно тестировать DNKA.

## Задание 4 Для студентов с девайсами IOS

Команда вашего друга несколько лет трудилась над фитнес-приложением. Процесс сильно затянулся, но в итоге приложение создали и наполнили контентом для тренировок.
После долгой разработки и тестирования приложение наконец-то отправлено на ревью для релиза в App Store. Но Apple отказал в его размещении с формулировкой:
«Не соответствует [установленным гайдлайнам](https://developer.apple.com/app-store/review/guidelines/) публикации в App Store». Версия на русском есть [по ссылке](https://habr.com/ru/post/574850/).
Другой дополнительной информации предоставлено не было.
Ваш друг запросил детали, и, чтобы не терять времени, попросил вас помочь проанализировать по предоставленным данным, что не так с приложением.

**Данные приложения:**

1. Название: Ad Workout X.
2. Возрастная категория: 4+.
3. Категория: здоровье и фитнес.
4. Язык: английский.
5. [Cкриншоты для App Store.](https://drive.google.com/drive/u/1/folders/1Hr5ICtukg-c_8ZJoyAO261OiWpef8UXO)
6. [Видео разделов приложения.](https://drive.google.com/file/d/1at3CHH0sjpyqer041inRN1SDAEyf45Xx/view?usp=drive_link)

**Что нужно сделать:**

1. Проведите анализ соответствия приложения гайдлайнам iOS.
2. Обратите внимание на важные моменты: иконка, скриншоты, авторизация, вид элементов экрана, селекторов, отображение кнопок, навигации, работа приложения с использованием нативных жестов.
3. Определите минимум три пункта несоответствия требованиям.

Результат выполнения — ссылка на Google Docs с ответом в свободной форме.

## Задание 5\* Для студентов с девайсами IOS

Установка сборки с TestFlight. Выполняется при наличии тестового устройства iOS.

1. Зайдите на [сервис](https://departures.to/).
2. Попробуйте присоединиться к бета-тестированию любого понравившегося вам приложения.
3. Установите последнюю сборку.

Результат выполнения — ссылка на скриншот установленного приложения с TestFlight.

## Задание 6\*

Вы тестировщик мобильного приложения «Онлайн-кинотеатр». К выпуску готовится новая версия приложения. Функциональность самого приложения уже проверена, но нужно провести тестирование специфики мобильной платформы.

Помимо стандартных проверок для мобильных приложений, нужно учесть дополнительные требования к приложению:

1. Поддержка темной\светлой темы.
2. Есть загрузка контента (фильмов). Приложение должно стабильно работать при 3G.
3. Есть уведомления при выходе новых серий сериала.
4. Если просмотр фильма был прерван, то после возвращения пользователя просмотр должен продолжаться с того же места.
5. Фильмы можно скачать на устройство и смотреть в офлайне.

Вам нужно:

- Составить на их основе чек-лист для тестирования онлайн-кинотеатра из задания. Чек-лист должен быть разделен на блоки.

Результат задания — заполненный раздел в шаблоне.

### Критерии оценки

1. Положительная оценка (принимается) — выполнены все задания, ответы даны в развёрнутой форме, в решениях нет противоречий и нарушения логики. Задачи повышенной сложности, отмеченные звёздочкой, выполняются по желанию.
2. На доработку (удаление задания преподавателем) — задания выполнены частично или не выполнены совсем, в логике решения заданий есть противоречия и существенные недостатки.

Любые вопросы по решению задач задавайте в чате учебной группы.
