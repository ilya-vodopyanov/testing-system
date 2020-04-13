# WEB-приложение для тестирования

Создавайте **тесты**, объединяйте учеников в **группы** и контролируйте **каждый ответ**, используя приложение как **на компьютере**, так и на любом **мобильном устройстве** с одинаковым удобством!

## Тесты
Тесты импортируются в формате *.gift*, так что вы можете создавать любое количество вопросов множественнного выбора с любым количеством ответов, но правильный должен быть только один. Подробнее - в пунктах "Формат" и "Пример" ниже.

Вы можете управлять доступом учеников к тесту, открывая его только для одной группы или сразу для нескольких.

В списке в своём профиле вы видите все свои созданные тесты.

## Прохождение
Чтобы начать тест, нужно выбрать его из списка во вкладке "Тесты" и нажать кнопку "Начать".

Выбрав ответ, вы можете перейти к следующему вопросу. 

После заверешения теста вы можете ознакомиться с результатом теста и узнать, какие ответы были неправильными, а также увидеть процент и количество правильных ответов. Вы будете автоматически перенаправлены на нужную страницу. Помимо этого, вы можете увидеть статистику по кнопке "История" на карточке теста.

Вы в любой момент можете прервать выполнение, статистика сохранится, если вы ответили хотя бы на один вопрос.

## Пользователи
В системе есть три типа пользователей: **администратор**, **учитель** и **ученик**.

### Учитель

Пользователи данного типа создаются администратором или другим учителем. Учитель может:
  * создавать **тесты**
  * проходить **их**
  * управлять доступом к **ним**
  * удалять **их**
  * смотреть статистику прохождения **тестов**
  * создавать **пользователей** типа *учитель* и *ученик*
  * удалять **их**
  * создавать и удалять **группы**
  * добавлять других пользователей в **группы** и исключать их оттуда
  * просматривать список *всех* пользователей
  * просматривать список *всех* групп
  
 *Обратите внимание, что учитель может взаимодействовать только с теми объектами, которые он сам создал*


### Ученик

Пользователи данного типа создаются администратором или учителем. Ученик может:
  * проходить доступные тесты
  * просматривать статистику по пройденным тестам
  * просматривать группы, в которых он состоит
  
### Администратор

Никем не создаётся и никем не удаляется. Может:
  * **Всё**
  
## Импорт тестов
Перейдя на вкладку "Тесты", нажмите кнопку "Новый тест", выберите название и файл для импорта. Если при импорте не выявится никаких ошибок, тест будет сохранён. Вы можете редактировать доступ или архивировать тест, нажав на кнопку редактирования на карточке теста. Архивированные тесты можно найти в профиле.
  
## Формат тестов
* Каждый вопрос начинается с двойного двоеточия "::". 
* Варианты ответов записываются между фигурными скобками "{}". 
* Каждый вопрос и вариант ответа следует записывать с новой строки
* Правильный ответ начинается со знака равно "=", неправильный - с тильды "~". 
* Вариантов ответа может быть любое количество, но обязательно должен быть **ровно один правильный** и **хотя бы один неправильный**
* Строки комментариев начинаются с двойного слэша "//" 

## Пример теста

//Комментарий  
::Как называли Ивана IV? {  
    =Грозный  
    ~Жестокий  
    ~Мягкий  
    ~Жадный  
}  
  
// Ещё один комментарий  
::Название ноты:{  
    ~сахар  
    =фа  
    ~фасоль  
    ~лям  
}  

## Группы
Группы нужны, чтобы упростить взаимодействие с пользователями в системе.

Если вы учитель или администратор, вы можете создать новую группу, отредактировать или удалить существующую, перейдя на вкладку "Профиль -> Группы"

## Создание новых пользователей
Вы можете просматривать пользователей, удалять их и создавать новых во вкладке "Профиль -> Пользователи".
