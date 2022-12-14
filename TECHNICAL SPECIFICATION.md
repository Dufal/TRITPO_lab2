# Требования к проекту
### Содержание
1. [Введение](#1) <br>
  1.1. [Назначение](#1.1) <br>
  1.2. [Бизнес-требования](#1.2) <br>
      1.2.1. [Границы проекта](#1.2.1) <br>
  1.3 [Аналоги](#1.3) <br>
2. [Требования пользователя](#2) <br>
  2.1. [Программные интерфейсы](#2.1) <br>
  2.2. [Интерфейс пользователя](#2.2) <br>
  2.3. [Характеристики пользователей](#2.3) <br>
  2.4. [Предположения и зависимости](#2.4) <br>
3. [Системные требования](#3) <br>
  3.1. [Функциональные требования](#3.1) <br>
  3.2. [Нефункциональные требования](#3.2) <br>
     3.2.1. [Атрибуты качества](#3.2.1) <br>
     3.2.2. [Внешний интерфейс](#3.2.2) <br>

### Глоссарий
* Напоминание – это специальное уведомление, которое поступает на телефон в заранее заданное время.
* Будильник – стандартная функция телефона, созданная для помощи пользователю в вопросах временного планирования
  
### 1. Введение <a name="1"></a>
#### 1.1 Назначение <a name="1.1"></a>
Специалисты по планированию и ученые, изучающие человеческую память, рекомендуют составлять списки важных вещей, о которых необходимо помнить в течение дня. Считается, что гораздо эффективнее записать информацию о повестке дня. Это разгрузит наш мозг от попыток удержать в голове необходимые данные и позволит сосредоточиться на выполнении задач.
Хорошим подспорьем для составления списка текущих задач может стать ваш смартфон. Он всегда под рукой, а значит вы в любой момент сможете обратиться к ежедневному плану и внести в него коррективы.
Однако, большинство подобных приложений не могут удержать пользователя на долго или грамотно напомнить об им же составленных планах. А что, если создать приложение-напоминалку, на подобии игры с возможностью получения достижений и взаимодействием с другими пользователями? Ответ на этот вопрос – RemindMe.

#### 1.2 Бизнес-требования <a name="1.2"></a>
##### 1.2.1. Границы проекта <a name="1.2.1"></a>
Приложение позволит создавать повторяющиеся задачи, отображать календарь при просмотре и создании напоминаний, добавлять дни рождения, создавать напоминания-будильники, делиться с друзьями собственным прогрессом выполнения задач.
#### 1.3 Аналоги <a name="1.3"></a>
Проект является более продвинутым и лояльным к пользователю по сравнению с ["BZ Reminder"](https://bzreminder.com/), ["Tasks"](https://mytasksapp.com/) и ["Evernote"](https://evernote.com/intl/ru).
### 2. Требования пользователя <a name="2"></a>
#### 2.1. Программные интерфейсы <a name="2.1"></a>
Проект создан с помощью Android SDK и языка программирования Java.
#### 2.2. Интерфейс пользователя <a name="2.2"></a>
Графический интерфейс приложения представлен с помощью мокапов нескольких окон.
Отдельного рассмотрения требует главное окно:

Клавиша | Реакция
--- | ---
"Профиль" | Появляется окно отображения информации о пользователе
"Добавить" | Создание нового напоминания с возможностью его регулировки
"Список напоминаний" | Просмотр списка добавленных напоминаний
"Настройки" | Всплывание окна полной настройки приложения
"Удалить" | Удаление выбранной заметки

#### 2.3. Характеристики пользователей <a name="2.3"></a>
Целевая аудиория:
* Люди подростковой и старшей возрастной категории.
* Пользователи, которым необходимо простое и многофункциональное приложение для регулирования собственных задач
#### 2.4. Предположения и зависимости <a name="2.4"></a>
При запуске данного проекта на Android используются внтуренние ресурсы.
### 3. Системные требования <a name="3"></a>
Запуск приложения осуществляется на Android.
#### 3.1. Функциональные требования <a name="3.1"></a>
Пользователю предоставлены возможности, представленные в таблице.

Функция | Требования
--- | ---
Просмотр профиля | Приложение должно предоставить пользователю возможность просмотра, добавления, удаления личной информации, получение информации о достижениях, а также о добавленных друзьях.
Добавить напоминание | Приложение должно предоставить пользователю возможность создание нового напоминания с полной его настройкой и регулировкой.
Просмотр списка напоминаний | Приложение должно предоставить пользователю возможность вывода информации о существующих напоминаниях. Просмотр задач по календарю.
Настройки | Приложение должно предоставить пользователю возможность полной настройки приложения (начиная от цветовой гаммы, заканчивая языком отображения информации)
Удаление напоминания | Приложение должно предоставить пользователю возможность удаления выбранного напоминания.

#### 3.2. Нефункциональные требования <a name="3.2"></a>
  ##### 3.2.1. Атрибуты качества <a name="3.2.1"></a>
Важными атрибутами качества данного приложения являются: быстрый запуск, малое потребление ресурсов, высокая производительность, приятный графический интерфейс, многофункциональность.
Также атрибутами качества являются: интуитивное использование за счет минималистического интерфейса, удобство в использовании для людей с ограниченным возможностями.

  ##### 3.2.2 Внешний интерфейс <a name="3.2.2"></a>
Приложение должно быть разработано в одном стиле с использованием интуитивно понятного интерфейса, а также, поддерживание разработок для людей с ограниченными возможностями.
