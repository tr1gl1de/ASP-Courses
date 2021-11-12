# ASP-Courses

Пошаговый курс по изучению ASP на примере Rest API


## Содержание

1. [Для кого этот курс](#Для-кого-этот-курс)
2. [Структура репозитория](#Структура-репозитория)
3. [Рассмотренные темы](#Рассмотренные-темы)


## Для кого этот курс

1. [Что это за курс](#Что-это-за-курс)
2. [Необходимые знания](#Необходимые-знания)
3. [Подход к подаче материала](#Подход-к-подаче-материала)
4. [Язык](#Язык)

### Что это за курс

Этот репозиторий представляет из себя пошаговый гайд к изучению ASP.

### Необходимые знания

Было бы неплохо, если бы уже знали c#, или какой-либо другой язык хотя бы на том
уровне, когда для вас не составляет особого труда написать цилк, функцию, класс.
Если же вы этого не можете, то лучше вернуться к курсу через какое-то время,
когда вышеуказанные требования будут удовлетворены.

### Подход к подаче материала

Большинство аспектов будут рассматриваться с учётом того, что читающий уже
знаком с ними (также будет предоставлена ссылка на документацию или статью), но
не объяснены (читающий должен разобраться в этих аспектах самостоятельно).

Также сами курсы будут структурированы так, что большинство аспектов
рассматриваются не сразу, а только когда читающему потребуется с ними
взаимодействовать: например, DI и конфигурация пайплайна приложения будут
рассмотрены не раньше 10го урока.

### Язык

Все статьи, документации, видео и прочие прикреплённые материалы будут на
английском языке. Данный курс на русском только потому, что мой уровень
английского не позволяет мне не напрягаясь писать на английском, а сидеть с
переводчиком и писать этот курс мне кажется перебором.

В моём представлении, *минимальным* уровнем английского для разработчика является
тот уровень, когда разработчик может спокойно читать технические тексты в его
сфере деятельности и воспринимать видео-материал той же направленности.


## Структура репозитория

Каждый урок представляет из себя отдельный solution (за исключением уроков без
кода), где код – финальный результат, полученный после прохождения урока, а
Readme.md – сам текст урока.


## Рассмотренные темы

- [x] Общие понятия о разработке, .Net и ASP
- [x] Настройка окружения
- [ ] Создание Minimal API
- [ ] Добавление нового эндпоинта со статическими данными
- [ ] CRUD API и понятие Rest API
- [ ] Вынесение раутов Minimal API в отдельные файлы
- [ ] Переход от Minimal API к отдельным контроллерам
- [ ] Data Transfer Objects
- [ ] Валидация
- [ ] Entity Framework Core
- [ ] Фильтрование, сортировка и пагинация
