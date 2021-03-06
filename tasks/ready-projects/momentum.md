# momentum

| Deadline         | Folder name | Branch name |
| ---------------- | ----------- | ----------- |
| 04.10.2020 23:59 | momentum    | momentum    |

В первую очередь ознакомьтесь с [инструкцией к заданию](introduction.md) 

## Task 2. Momentum

![screenshot](images/momentum.png)

Momentum - аналог [одноимённого приложения](https://chrome.google.com/webstore/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca?hl=ru) интернет-магазина Chrome. Приложение показывает время и имя пользователя, его цель на текущий день. Фоновое изображение меняется в зависимости от времени суток. Для хранения данных приложение использует локальное хранилище - local storage. Автор - Brad Traversy - известен качеством своих туториалов. Именно этот — довольно короткий, и достаточно простой. Выполняя проект вы научитесь работать с датой и временем, создавать часы, сохранять данные в local storage и, самое главное, на конкретных примерах познакомитесь с асинхронными запросами. 

- Видео: https://youtu.be/fSTQzlprGLI (35:10)
- Код: https://github.com/irinainina/ready-projects/tree/momentum/momentum (113 lines js-code)
- Demo: https://irinainina.github.io/ready-projects/momentum/

Чтобы склонировать проект выполните команду:

`git clone https://github.com/irinainina/ready-projects/ -b momentum`

## Критерии оценки

**Максимальный балл за задание +40**

- Базовая функциональность +10
  - воспроизводится функциональность исходного проекта: отображается время; можно ввести имя пользователя и его цель, эти данные сохраняются после обновления страницы, фоновое изображение и приветствие изменяются в зависимости от времени суток. Отличия от исходного проекта: 1) выводится не только время, но и день недели, дата, месяц, например: "Пятница, 25 сентября" 2) время выводится в 24-часовом формате;
- Смена фонового изображения +10
  - фоновое изображение рандомно выбирается из коллекции изображений ([предложенной в самом задании](https://github.com/irinainina/ready-projects/tree/momentum/momentum/assets/images), или вашей собственной) в зависимости от времени суток (утро, день, вечер, ночь), меняется каждый час. Есть кнопка, позволяющая пролистать все фоновые изображения за текущие сутки. Основное требование - плавная смена фоновых изображений (пример есть в материалах к заданию). Если пролистать все изображения за сутки, вернёмся к исходному, с которого начинали просмотр
- Мотивирующая цитата +10
  - при загрузке приложения выводится цитата или другой короткий текст (высказывание, шутка, анекдот и т.д.). При перезагрузке страницы или клике на предназначенную для этого кнопку цитата заменяется на другую. Источником цитаты может быть соответствующее API или собственный файл с данными. Язык цитаты русский или английский, на ваше усмотрение. Пример получения цитаты есть в материалах к заданию.
- Прогноз погоды +10
  - В приложении выводится прогноз погоды для указанного пользователем города. Пример получения прогноза погоды и статья с объяснением кода есть в материалах к заданию.

## Материалы

- Дата и время https://learn.javascript.ru/date
- Window.localStorage https://developer.mozilla.org/ru/docs/Web/API/Window/localStorage
- LocalStorage на пальцах https://tproger.ru/articles/localstorage/
- Поймут даже дети: простое объяснение async/await и промисов в JavaScript https://habr.com/ru/post/474726/
- JavaScript. Как работает Async, Await https://youtu.be/SHiUyM_fFME
- Вебинар: Асинхронность в JavaScript https://youtu.be/Ih6Q7ka2eSQ

## Примеры кода

- Плавная смена фоновых изображений https://codepen.io/irinainina/pen/abzwapy
- Пример получения цитаты https://codepen.io/irinainina/pen/LYNqmQd
- Simple Weather App https://codepen.io/tutsplus/pen/gObLaEP
- Build a Simple Weather App With Vanilla JavaScript https://webdesign.tutsplus.com/tutorials/build-a-simple-weather-app-with-vanilla-javascript--cms-33893

Документ для вопросов: https://docs.google.com/spreadsheets/d/1dMDLBC4-1XPaVMehZB6DqetToXZhq4x0PiZtj-jvLRc/

Ссылки на лучшие работы, добавьте, пожалуйста, в эту форму https://forms.gle/4uUvCsJ1WWXPJHCg7
