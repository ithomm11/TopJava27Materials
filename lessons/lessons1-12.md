Java Enterprise Online Project 
===============================
Разработка полнофункционального Spring/JPA Enterprise приложения c авторизацией и правами доступа на основе ролей с использованием наиболее популярных инструментов и технологий Java: Maven, Spring MVC, Security, JPA(Hibernate), REST(Jackson), Bootstrap (css,js), datatables, jQuery + plugins, Java 8 Stream and Time API и хранением в базах данных Postgresql и HSQLDB.

![topjava_structure](https://user-images.githubusercontent.com/13649199/27433714-8294e6fe-575e-11e7-9c41-7f6e16c5ebe5.jpg)

    Когда вы слышите что-то, вы забываете это.
    Когда вы видите что-то, вы запоминаете это.
    Но только когда вы начинаете делать это,
    вы начинаете понимать это

    Старинная китайская поговорка

## <a href="http://topjava.herokuapp.com/" target=_blank>Демо разрабатываемого приложения</a>

Возможно, будет удобнее проходить урок с использованием плагина форматирования страниц, например [Postlight Reader](https://chrome.google.com/webstore/detail/postlight-reader/oknpjjbmpnndlpmnhmekjpocelpnlfdi)


Вводное занятие (обязательно смотреть все видео)
===============
## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. <a href="https://drive.google.com/file/d/0B9Ye2auQ_NsFY1ZDNXRCd1NCTG8/view?resourcekey=0-NKNOHbTWXnsZtbe5_8B6Bg">Осваиваем Java Enterprise. Трудоустройство. Ответы на вопросы.</a>
- <a href="https://goo.gl/XNVOj4">Слайды презентации</a>
- [Как стать профессиональным Java разработчиком](https://www.youtube.com/watch?v=ft0Nj8Cm9kk)
- [Популярность Java-технологий в 2019 году](https://topjava.ru/blog/sostoyanie-java-v-2019-godu)
- [Java Technology Report 2021](https://www.jrebel.com/blog/2021-java-technology-report)
- [The State of Developer Ecosystem 2020](https://www.jetbrains.com/lp/devecosystem-2020/java/)
- [JVM Ecosystem Report 2021](https://snyk.io/jvm-ecosystem-report-2021/)
- [Быть программистом: от детства к зрелости](https://www.youtube.com/watch?v=D5Hej0TyLaU)
- [Литература](https://javaops.ru/view/books)

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. <a href="https://drive.google.com/file/d/0B9Ye2auQ_NsFSUNrdVc0bDZuX2s/view?resourcekey=0-6scb0PBj2A3Oqf6rsU2egQ">Системы управления версиями. Git.</a>
-  **<a href="https://github.com/JavaOPs/topjava/wiki/Git">Wiki по ведению проекта в Git</a>**
-  <a href="http://ru.wikipedia.org/wiki/Система_управления_версиями">Система управления версиями</a>. <a href="http://ru.wikipedia.org/wiki/%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0_%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F%D0%BC%D0%B8#.D0.A0.D0.B0.D1.81.D0.BF.D1.80.D0.B5.D0.B4.D0.B5.D0.BB.D1.91.D0.BD.D0.BD.D1.8B.D0.B5_.D1.81.D0.B8.D1.81.D1.82.D0.B5.D0.BC.D1.8B_.D1.83.D0.BF.D1.80.D0.B0.D0.B2.D0.BB.D0.B5.D0.BD.D0.B8.D1.8F_.D0.B2.D0.B5.D1.80.D1.81.D0.B8.D1.8F.D0.BC.D0.B8">VCS/DVSC</a>.
-  Ресурсы:            
    -  <a href="https://try.github.io/levels/1/challenges/1">Интерактивная Git обучалка</a>
    -  <a href="http://learngitbranching.js.org/">Еще одна интерактивная обучалка, по-русски</a>    
    -  <a href="https://git-scm.com/book/ru/v2">Книга Git</a>
    -  <a href="https://illustrated-git.readthedocs.org/en/latest/#working-with-remote-repositories">Working with remote repositories</a>
    -  <a href="https://www.youtube.com/playlist?list=PLIU76b8Cjem5B3sufBJ_KFTpKkMEvaTQR">Видео по обучению Git</a>
    -  <a href="https://blog.interlinked.org/tutorials/git.html">Git Overview</a>
    -  [Основы Git за 20 минут](https://www.youtube.com/watch?v=TMeZGvtQnT8)
    -  [Git - для новичков](https://www.youtube.com/watch?list=PLY4rE9dstrJyTdVJpv7FibSaXB4BHPInb&v=PEKN8NtBDQ0)
    - [Руководство по написанию комментариев в коммитах](https://techrocks.ru/2019/12/02/writing-good-commit-messages)

##  ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. <a href="https://drive.google.com/file/d/0B9Ye2auQ_NsFZDdaaU5fZEo4X3c/view?resourcekey=0-DvpzWIlMHZ7KX_v1SMuiAw">Работа с проектом (выполнять инструкции)</a>
- **ВНИМАНИЕ: выбирайте для проекта простой пусть без пробелов и русских букв, например (Windows) `c:\projects\topjava\`. Иначе впоследствии будут проблемы**
- **Плагин уже Git Intergation не требуется и вкладку `Version control` в IDEA переименовали в `Git`**

Для переключения режима отображения изменений из вкладки Commit в Git: Local Changes нужно переключить `Settings/Preferences | Version Control | Commit | Use non-modal commit interface` или в контекстном меню вкладки `Commit`:

![image](https://user-images.githubusercontent.com/13649199/105491518-72d8f300-5cc7-11eb-8b79-c46382562deb.png)  ![image](https://user-images.githubusercontent.com/13649199/105488663-05c35e80-5cc3-11eb-962e-30f403d623e8.png)

### Патч [prepare_to_HW0.patch](https://drive.google.com/file/d/1LNPpu9OkuCpfpD8ZJHO-o0vwu49p2i5M) (скачать и положить в каталог вашего проекта)

> Проект постоянно улучшается, поэтому видео иногда отличается от кода проекта. Изменения указываю после видео: 
> - переименовал класс `UserMealWithExceed` и его поле `exceed` в `UserMealWithExcess.excess`
> - в `UserMeals/UserMealWithExcess` поля изменились на `private`
> - обновил данные `UserMealsUtil.meals` и переименовал некоторые пременные, поля и методы
> - добавил `UserMealWithExcess.toString()` и метод для выполнения _Optional домашнего задания_
> - метод фильтрации в `TimeUtil` переименовали в `isBetweenHalfOpen` (также изменилась логика сравнения - `startTime` включается в интервал) 

### GitHub поменял политику - теперь пушить нужно через токен. IDEA предложит его сгенерить при пуше или можно [создать токен в настройках](https://githubhelp.com/EvgenKuz/Intellij-IDEA-GitHub-SetUp)

##  Инструкция по шагам (из видео):</h3>
-  <a href="http://javaops.ru/view/soft">Установить ПО (git, JDK8, IntelliJ IDEA, Maven)</a>
-  Создать аккаунт на <a href="https://github.com">GitHub</a>
-  Сделать Fork **ЭТОГО** проекта (https://github.com/JavaOPs/topjava) </a>
-  Сделать локальный репозиторий проекта:
            <pre>git clone https://github.com/[Ваш аккаунт]/topjava.git</pre>

> Вместо Fork, можно сделать [клонирование проекта](https://github.com/JavaOPs/topjava/wiki/Git#user-content-Клонирование-проекта): он не будет привязан к исходному https://github.com/JavaOPs/topjava и у него не будет истории.

-  Открыть и настроить проект в IDEA
   - <a href="http://stackoverflow.com/questions/29695918/intellij-idea-console-issue#33035499">Выставить кодировку UTF-8 в консоли</a>
   - <a href="https://github.com/JavaOPs/topjava/wiki/IDEA#%D0%9F%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C-%D0%BA%D0%BE%D0%B4%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D1%83-utf-8">Поставить кодировку UTF-8</a>
   - Опционально: <a href="https://github.com/JavaOPs/topjava/wiki/IDEA#%D0%9F%D0%BE%D0%BC%D0%B5%D0%BD%D1%8F%D1%82%D1%8C-%D1%84%D0%BE%D0%BD%D1%82-%D0%BF%D0%BE-%D1%83%D0%BC%D0%BE%D0%BB%D1%87%D0%B0%D0%BD%D0%B8%D1%8E-dejavu">Поменять фонт по умолчанию (DejaVu)</a> или на **новый [JetBrains Mono](https://habr.com/ru/company/jugru/news/t/484134/)**
-  По ходу видео сделать Apply Patch... скаченного патча [Prepare_ to_ HW0.patch](https://drive.google.com/file/d/1LNPpu9OkuCpfpD8ZJHO-o0vwu49p2i5M)
-  Закоммитить и запушить изменения (commit + push)
-  Сделать ветку домашнего задания
-  Выполнить задание и залить на GitHub (commit + push)
-  Переключиться в основную ветку проекта master.

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4. [Maven](https://drive.google.com/file/d/1qEJTwv9FNUQjx-y9MSydH01xaAne0-hu)
- Wiki: [Apache Maven](https://ru.wikipedia.org/wiki/Apache_Maven)
- [The Central Repository](http://search.maven.org)
- Дополнительно:
    - [Мое Wiki Maven](https://github.com/JavaOPs/topjava/wiki/Maven)
    - [Основы Maven](https://www.youtube.com/watch?v=0uwMKktzixU)
    - JavaRush: [Основы Maven](https://javarush.ru/groups/posts/2523-chastjh-4osnovih-maven)
    - Инструмент сборки проектов [Maven](https://www.examclouds.com/ru/java/java-core-russian/lesson20)
    - [Maven Getting Started Guide](https://maven.apache.org/guides/getting-started/index.html)
    - [Видео: Maven vs Gradle vs SBT (Архипов, Борисов, Садогурский)](https://www.youtube.com/watch?v=21qdRgFsTy0)
    - [Build Lifecycle](http://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html)
    - [Dependency Mechanism](http://maven.apache.org/guides/introduction/introduction-to-dependency-mechanism.html)

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5. [Тех.задание: библия или допускаются изменения. Полуоткрытый интервал.](https://drive.google.com/file/d/1BpTzjNFjS0TSekCyt_xvt6YoLvuw5KTZ/view?usp=sharing)
- [Типы промежутков](https://ru.wikipedia.org/wiki/Промежуток_(математика))

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW0

### ВНИМАНИЕ: НЕ НАДО в репозиторий делать Pull Request со своими решениями! См. видео выше - работа с проектом
Реализовать метод `UserMealsUtil.filteredByCycles` через циклы (`forEach`):
-  должны возвращаться только записи между `startTime` и `endTime`
-  поле `UserMealWithExcess.excess` должно показывать, превышает ли сумма калорий за весь день значение `caloriesPerDay`
        
Т.е `UserMealWithExcess` - это запись одной еды, но поле `excess` будет одинаково для всех записей за этот день.
    
> - Проверьте результат выполнения ДЗ (можно проверить логику в http://topjava.herokuapp.com , список еды)
> - Оцените Time complexity алгоритма. Если она больше O(N), например O(N*N) или N*log(N), сделайте O(N).  
> **Внимание: внимательно прочитайте про O(N). O - это любой коэффициент, 2*N это тоже O(N).**

-  <a href="http://www.mscharhag.com/2014/02/java-8-datetime-api.html">Java 8 Date and Time API</a>
-  <a href="http://web.archive.org/web/20201128101944/https://tproger.ru/translations/algorithms-and-data-structures/">Алгоритмы и структуры данных для начинающих: сложность алгоритмов</a>
-  [Головач: сложность алгоритмов в теме коллекций](https://www.youtube.com/watch?v=Ek9ijOiplNE&feature=youtu.be&t=778)
-  <a href="https://drive.google.com/file/d/0B9Ye2auQ_NsFNEJWRFJkVDA3TkU/view?usp=sharing&resourcekey=0-MPCuoLVdSLiSc7hlE2jefQ">Time complexity</a>
-  <a href="https://ru.wikipedia.org/wiki/Временная_сложность_алгоритма">Временная сложность алгоритма</a>
-  <a href="https://ru.wikipedia.org/wiki/Вычислительная_сложность">Вычислительная сложность</a>

#### ВНИМАНИЕ: варианты Optional делайте в `UserMealsUtil` в одной ветке в разных методах. Проще делать, проще проверять

### Optional (Java 8 Stream API)
```
Реализовать метод `UserMealsUtil.filteredByStreams` через Java 8 Stream API.
```
-  <a href="http://www.youtube.com/watch?v=_PDIVhEs6TM">Видео: Доступно о Java 8 Lambda</a>
-  <a href="https://devcolibri.com/java-8-killer-features-%D1%87%D0%B0%D1%81%D1%82%D1%8C-1/">Java 8: Lambda выражения</a>
-  <a href="https://devcolibri.com/java-8-killer-features-%D1%87%D0%B0%D1%81%D1%82%D1%8C-2/">Java 8: Потоки</a>
-  <a href="https://javadevblog.com/polnoe-rukovodstvo-po-java-8-stream.html">Pуководство по Java 8 Stream</a>
-  [Полное руководство по Java 8 Stream API в картинках и примерах](https://annimon.com/article/2778)    
-  [7 способов использовать groupingBy в Stream API](https://habrahabr.ru/post/348536)
-  <a href="http://habrahabr.ru/post/224593/">Лямбда-выражения в Java 8</a>
-  <a href="https://github.com/winterbe/java8-tutorial">A Guide to Java 8</a>
-  <a href="http://habrahabr.ru/company/luxoft/blog/270383/">Шпаргалка Java Stream API</a>
-  <a href="https://www.youtube.com/watch?v=hEyCK4ueBlc">Алексея Владыкин: Элементы функционального программирования в Java</a>
-  <a href="https://www.youtube.com/watch?v=iD8H7cmxw_w">Yakov Fain о новом в Java 8</a>
-  <a href="http://stackoverflow.com/questions/28319064/java-8-best-way-to-transform-a-list-map-or-foreach">stream.map vs forEach</a>
-  [Руководство по Java Stream в Java 8](https://javarush.com.ua/groups/posts/3974-kofe-breyk-177-podrobnoe-rukovodstvo-po-java-stream-v-java-8)
-  Дополнительно
   - [Сергей Куксенко — Stream API, часть 1](https://www.youtube.com/watch?v=O8oN4KSZEXE)
   - [Сергей Куксенко — Stream API, часть 2](https://www.youtube.com/watch?v=i0Jr2l3jrDA)

### Optional 2 (+5 бонусов, только после выполнения базового и Optional задания!)
Сделать реализацию со сложностью O(N) (обратите внимание на п.13 замечаний)  
Решение должно быть рабочим в общем случае (работать в приложении с многими пользователями, не только при запуске main)  
Нельзя 2 раза проходить по исходному списку (в том числе его отфильтрованной или преобразованной копии)
- циклом за 1 проход по `List<UserMeal>`
  - без циклов по другим коллекциям/массивам (к ним также относим методы коллекций `addAll()/removeAll()`)
- через Stream API за 1 проход по исходному списку `meals.stream()`
  - нельзя использовать внешние коллекции, не являющиеся частью коллектора
  - возможно дополнительные проходы по частям списка, при этом превышение должно считаться один раз для всего подсписка. Те например нельзя разбить список на на 2 подсписка с четными и нечетными датами и затем их объединить, с подсчетом превышения для каждого элемента.
 

Ресурсы:
- [Java 8 Stream API, часть шестая: собственный коллектор](https://web.archive.org/web/20220519062533/https://easyjava.ru/java/language/java-8-stream-api-chast-shestaya-sobstvennyj-kollektor/)
- [Руководство по Java 8 Stream API: Collector](https://annimon.com/article/2778#collector)
- [Хватит писать циклы! Топ-10 лучших методов для работы с коллекциями из Java 8](https://javarush.ru/groups/posts/524-khvatit-pisatjh-ciklih-top-10-luchshikh-metodov-dlja-rabotih-s-kollekcijami-iz-java8)
- [Понять Java Stream API](https://vc.ru/u/604567-yerlan-akzhanov/194409-ponyat-java-stream-api)    

### Замечания по использованию Stream API:
- Когда встречаешь что-то непривычное, приходится перестраивать мозги. Например, переход с процедурного на ООП программирование дается непросто. Те, кто не знает шаблонов (и не хотят учить) также их встречают плохо. Хорошая новость в том, что если это принять и начать использовать, то начинаешь получать от этого удовольствие. И тут главное не впасть в другую крайность:
  - [Используйте Stream API проще (или не используйте вообще)](https://habrahabr.ru/post/337350/)
- Если вас беспокоить производительность стримов, обязательно прочитайте про оптимизацию 
    - ["Что? Где? Когда?"](http://optimization.guide/intro.html)
    - [Перформанс: что в имени тебе моём?](https://habrahabr.ru/company/jugru/blog/338732/)
    - [Performance это праздник](https://habrahabr.ru/post/326242/)
    
При использовании Stream API производительность улучшиться только на больших задачах, где возможно распараллеливание.
Еще - просто так запустить и померять скорость JVM нельзя (как минимум дать прогреться и запустить очень большое число раз). Лучше использовать какие-нибудь бенчмарки, например [JMH](http://tutorials.jenkov.com/java-performance/jmh.html), который мы юзаем на другом проекте (Mastejava).
  
## ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Замечания к HW0
- 1: Код проекта менять можно! Одна из распространенных ошибок как в тестовых заданиях на собеседовании, так и при работе на проекте, что ничего нельзя менять. Конечно при правках в рабочем проекте обязательно нужно проконсультироваться/проревьюироваться у авторов кода (находится по истории VCS)
- 2: Наследовать `UserMealWithExcess` от `UserMeal` нельзя, т.к. это разные сущности: Transfer Object и Entity. Мы будет их проходить на 2м уроке. Это относится и к зависимости.
- 3: Правильная реализация должна быть простой и красивой, можно сделать 2-мя способами: через стримы и через циклы. Сложность должна быть O(N), т.е. без вложенных стримов и циклов.
- 4: При реализации через циклы посмотрите в `Map` на методы `getOrDefault` или `merge`
- 5: **При реализации через `Stream` заменяйте `forEach` оператором `stream.map(..)`**
- 6: Объявляйте переменные непосредственно перед использованием (если возможно - сразу с инициализацией). При объявлении коллекций используйте тип переменной - интерфейс (Map, List, ..)
- 7: Если IDEA предлагает оптимизацию (желтым подчеркивает), например заменить лямбду на метод-референс, соглашайтесь (Alt+Enter)
- 8: Пользуйтесь форматированием кода в IDEA: `Alt+Ctrl+L`
- 9: Перед check-in проверяйте чендж-лист (курсор на файл и Ctrl+D): не оставляйте в коде ничего лишнего (закомментированный код, TODO и пр.). Если файл не меняется (например только пробелы или переводы строк), не надо его чекинить, делайте ему `revert` (Git -> Revert / `Ctrl+Alt+Z`).
- 10: `System.out.println` нельзя делать нигде, кроме как в `main`. Позже введем логирование.
- 11: Результаты, возвращаемые `UserMealsUtil.filteredByStreams` мы будем использовать [в нашем приложении](http://topjava.herokuapp.com/) для фильтрации по времени и отображения еды правильным цветом.
- 12: Обращайте внимание на комментарии к вашим коммитам в git. Они должны быть короткие и информативные (лучше на english)
- 13: Не полагайтесь в решении на то, что список еды будет подаваться отсортированным. Такого условия нет.
-----

>  - ДЗ первого урока будет связано с созданием небольшого [CRUD](https://ru.wikipedia.org/wiki/CRUD) приложения (в памяти, без базы данных) на JSP и сервлетах
>  - основы JavaSсript необходимы для понимания проекта, начиная с 8-го занятия

### Полезные ресурсы
#### HTML, JavaScript, CSS 
- [Basic HTML and HTML5](https://learn.freecodecamp.org/responsive-web-design/basic-html-and-html5/say-hello-to-html-elements/)
- [Справочник по WEB](https://developer.mozilla.org/ru/)
- [Видео по WEB технологиям](https://www.youtube.com/user/WebMagistersRu/playlists)
- [Изучение JavaScript в одном видео уроке за час](https://www.youtube.com/watch?v=QBWWplFkdzw)
- <a href="http://www.w3schools.com/default.asp">HTML, CSS, JAVASCRIPT, SQL, JQUERY, BOOTSTRAP</a>
- <a href="https://www.youtube.com/watch?v=j0ycGQKqMT4">Введение в программирование на JavaScript</a>
- <a href="http://anton.shevchuk.name/javascript/html-css-javascript-standarts/">Стандарты кодирования для HTML, CSS и JavaScript’a</a>
- <a href="http://www.intuit.ru/studies/courses/1102/134/info">Основы работы с HTML/CSS/JavaScript</a>
- <a href="http://itchief.ru/lessons/javascript/94-javascript-introduction">JavaScript - Основы</a>
- <a href="http://learn.javascript.ru/first-steps">Основы JavaScript</a>
- <a href="http://itchief.ru/lessons/bootstrap-3/19-introduction-to-twitter-bootstrap-3">Bootstrap 3 - Основы</a>
- <a href="http://anton.shevchuk.name/jquery/">jQuery для начинающих</a>

#### Java (базовые вещи)
- [Сборник видео "Изучаем Java"](https://www.youtube.com/playlist?list=PLyxk-1FCKqockmP-fXZmHQ7UlYP3qvZRa)
- <a href="http://www.intuit.ru/studies/courses/16/16/info">Интуит. Программирование на Java</a>
- <a href="https://github.com/JavaOPs/masterjava#Первое-занятие-многопоточность">1й урок MasterJava: Многопоточность</a>
- [Основы Java garbage collection](http://web.archive.org/web/20180831013112/https://ggenikus.github.io/blog/2014/05/04/gc)
- <a href="https://habrahabr.ru/post/134102/">Размер Java объектов</a>
- <a href="http://www.quizful.net/post/java-reflection-api">Введение в Java Reflection API</a>
- <a href="https://habrahabr.ru/users/tarzan82/topics/">Структуры данных в картинках</a>
- <a href="https://habrahabr.ru/company/luxoft/blog/157273/">Обзор java.util.concurrent.*</a>
- <a href="http://web.archive.org/web/20200808064416/http://www.skipy.ru/technics/synchronization.html">Синхронизация потоков</a>
- <a href="http://java67.blogspot.ru/2014/08/difference-between-string-literal-and-new-String-object-Java.html">String literal pool</a>
- <a href="https://habrahabr.ru/post/132241/">Маленькие хитрости Java</a>
-  <a href="https://github.com/winterbe/java8-tutorial">A Guide to Java 8</a>

### Туториалы, разное
- [Открытый курс: Spring Boot + HATEOAS](https://javaops.ru/view/bootjava)
- [Что нужно знать о бэкенде новичку в веб-разработке](https://tproger.ru/translations/backend-web-development)
- [Туториалы: Spring Framework, Hibernate, Java Core, JDBC](http://proselyte.net/tutorials/)

#### Сервлеты
-  <a href="https://devcolibri.com/как-создать-servlet-полное-руководство/">Как создать Servlet? Полное руководство.</a>
-  [Сервлеты](https://metanit.com/java/javaee/4.1.php)

#### JDBC, SQL
-  <a href="https://habrahabr.ru/post/123636/">Основы SQL на примере задачи</a>
-  <a href="https://www.youtube.com/playlist?list=PLIU76b8Cjem5qdMQLXiIwGLTLyUHkTqi2">Уроки по JDBC</a>
-  <a href="https://www.codecademy.com/learn/learn-sql">Learn SQL</a>
-  <a href="http://www.intuit.ru/studies/courses/5/5/info">Интуит. Основы SQL</a>
-  <a href="http://campus.codeschool.com/courses/try-sql/contents">Try SQL</a>
-  <a href="https://stepic.org/course/Введение-в-базы-данных-551">Курс "Введение в базы данных"</a>

#### Разное
-  <a href="http://javaops.ru/view/test">Вопросы по собеседованию, ресурсы для подготовки</a>
-  <a href="http://jeeconf.com/materials/intellij-idea/">Эффективная работа с кодом в IntelliJ IDEA</a>
-  <a href="http://www.quizful.net/test">Quizful- тесты онлайн</a>
-  <a href="https://stepic.org/course/Введение-в-Linux-73">Введение в Linux</a>

#### Книги
-  <a href="http://www.ozon.ru/context/detail/id/24828676/">Джошуа Блох: Java. Эффективное программирование. Второе издание</a>
-  <a href="http://www.labirint.ru/books/87603/">Гамма, Хелм, Джонсон: Приемы объектно-ориентированного проектирования. Паттерны проектирования</a>
-  <a href="http://www.bookvoed.ru/book?id=639284">Редмонд Э.: Семь баз данных за семь недель. Введение в современные базы данных и идеологию NoSQL</a>
-  <a href="http://www.ozon.ru/context/detail/id/3174887/">Brian Goetz: Java Concurrency in Practice</a>
-  <a href="http://bookvoed.ru/book?id=2593572">G.L. McDowell: Cracking the Coding Interview</a>

# Стажировка <a href="https://github.com/JavaWebinar/topjava">Topjava</a>
- Не стоит стремиться прочитать все ссылки урока, их можно использовать как справочник. Гораздо важнее пройти основной материал урока и сделать Домашнее Задание
- Обязательно посмотри <a href="https://github.com/JavaOPs/topjava/wiki/Git#Правила-работы-с-патчами-на-проекте">правила работы с патчами на проекте</a>
- Делать Apply Patch лучше по одному, непосредственно перед видео на эту тему, а при просмотре видео сразу отслеживать все изменения кода проекта по изменению в патче (`Git-> Local Changes-> Ctrl+D`)
- **При первом Apply удобнее выбрать имя локального ченджлиста Name: Change**. Далее все остальные патчи также будут в него попадать.
- **Код проекта обновляется и не всегда совпадает с видео (можно увидеть как развивался проект). Изменения в проекте указываю после соответствующего патча.** 

## <a href="https://drive.google.com/drive/u/0/folders/0B9Ye2auQ_NsFfm5hSHEtbmxmN2kxb0NocVRwWl9KanowWXVCVXRZTlhaM09wQUswZkRidTA">Материалы занятия</a> (скачать все патчи можно через `Download/Скачать` папки patch)
![image](https://cloud.githubusercontent.com/assets/13649199/18330295/5f2ca214-7560-11e6-8e1e-c0494f798c37.png)

### ![correction](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Рефакторинг проекта

#### Apply 1_0_rename.patch
- переименовал классы `UserMeal*` в более красивые `Meal*`
- преименовал `MealWithExceed` transfer object класс ([что это такое](https://ru.wikipedia.org/wiki/DTO) пройдем позже)  в `MealTo` ([data transfer object naming convention](https://stackoverflow.com/questions/1724774/java-data-transfer-object-naming-convention))

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW0:
### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. <a href="https://drive.google.com/file/d/1hXU8VUKVxrayyQ6Xu7f3OGZWCSdK9Pyi">Optional: реализация getFilteredMealsWithExcess через Stream API</a>
- В патче `prepare_to_HW0.patch` вступительного задания метод фильтрации в `TimeUtil` переименовали в `isBetweenHalfOpen` (также изменилась логика сравнения - `startTime` включается в интервал) 

#### Apply 1_1_HW0_streams.patch

- [Презентация Java 8](https://docs.google.com/presentation/d/1oltLkHK60FqIdsXjUdm4pPLSeC6KpNYjDsM0ips-qBw)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. <a href="https://drive.google.com/open?id=1K0kan7TEUeOAe_qcdCtRF9rsqD-NwFZ7">Работа с git в IDEA. Реализация через цикл.</a>
### ВНИМАНИЕ! Патчей `1_opt_2_HW0_cycles` и `1_opt_3_HW0_opt2` не будет в проекте! Делаем в отдельной ветке (у меня `MealsUtil_opt`). Это варианты решений, которые не идут в `master`

![image](https://user-images.githubusercontent.com/13649199/83656711-8b758b00-a5c8-11ea-9de4-c2ade77d4598.png)

#### Apply 1_opt_2_HW0_cycles.patch

### ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Вопросы по HW0

> почему не использовать в `TimeUtil` методы `isBefore/isAfter` ?

это строгие (excluded) сравнения, а нам также нужно краевые значения

> В `MealsUtil` у нас где-то есть ключевое слово `final`, где-то нет. В чем разница?

Я участвовал в одном  проекте, где `final` был обязательным (в сеттингах IDEA галочка стояла). Но это скорее исключение, чем правило в проектах java (в Java 8 вообще ввели эффективный final, те по факту). Во всех новомодных языках переменные final по умолчанию, а в java нужно помнить и везде добавлять, утомительно. Но если приучитесь - хуже не будет. Я обычно ставлю там, где важно по смыслу (если не забываю).

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. [HW0 Optional 2: реализация в один проход циклами и Stream API](https://drive.google.com/file/d/1dSt3axySxu4V9dMnuR1wczerlI_WzCep)

#### Apply 1_opt_3_HW0_opt2.patch
- [DevEcosystem from JetBrains](https://www.jetbrains.com/lp/devecosystem-2020/java/)
- Дополнительно:
  - [Первое занятие MasterJava: многопоточность](https://github.com/JavaOPs/masterjava)
  - [Обзор java.util.concurrent.*](https://web.archive.org/web/20220427140138/https://habr.com/ru/company/luxoft/blog/157273/)
 
## Занятие 1:

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFRmo0YkVVaDJPTVE">Обзор используемых в проекте технологий. Интеграция ПО.</a>
- [Java Technology Report 2021](https://www.jrebel.com/blog/2021-java-technology-report)
- [Экосистема Java от JetBrains](https://www.jetbrains.com/ru-ru/lp/devecosystem-2021/java/)
- [Популярность Java-технологий в 2019 году](https://topjava.ru/blog/sostoyanie-java-v-2019-godu)
-  <a href="http://www.youtube.com/watch?v=rJZHerwi8R0">Видео "Приложение Spring Pet Clinic"</a> 
-  Приложение <a href="https://github.com/spring-projects/spring-petclinic">Spring Pet Clinic</a>. 

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5. [Обзор языка Java и его инфраструктуры](https://www.youtube.com/watch?v=jWfqopZwcNs)
- [Tiobe index](https://www.tiobe.com/tiobe-index/)
- [JetBrains devecosystem 2021](https://www.jetbrains.com/lp/devecosystem-2021/java/)
- [The State of Java in 2019](https://www.baeldung.com/java-in-2019)
- [JVM Ecosystem Report 2021](https://snyk.io/jvm-ecosystem-report-2021/)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 6. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFT3pWNkMzWVVybnc">WAR. Веб-контейнер Tomcat. Сервлеты.</a>
> - Обновил зависимость до Servlet 4.0. Установите себе [Tomcat 9.x](https://tomcat.apache.org/download-90.cgi)

**Внимание: Tomcat 10 требует пакета `jakarta.*`, устанавливайте 9-ю версию**

> - Устанавливать Tomcat лучше простым скачиванием архива `xxx.zip` (например для Windows `apache-tomcat-9.0.35-windows-x64.zip`) и копированием из него в **каталог без пробелов и русских букв** (пример `С:\java\apache-tomcat-9.0.35`)

### ВНИМАНИЕ! далее патчи идут в ветку `master` после `1_1_HW0_streams` 

#### Apply 1_2_switch_to_war.patch
> - Обновил сервлеты до версии 4.0 (Tomcat 9 использует это API, хотя для нас не принципиально, т.к. мы никакие <a href="https://ru.wikipedia.org/wiki/Сервлет_(Java)">фичи 3.x и 4.x Servlet API</a> не используем)
> - Переименовал `userList.jsp` в `users.jsp`
### Сервлет добавляется в следующем патче, те в `web.xml` он будет подчеркиваться красным.

#### Apply 1_3_add_servlet_api.patch

> - Если зависимость `servlet-api` не подтянулась, сделай `Reimport All Maven Projects` (см. [Обновить зависимости в maven проекте](https://github.com/JavaOPs/topjava/wiki/IDEA#maven_update)).
**Все зависимости в Maven прект подтягиваются ТОЛЬКО через Maven**. 
> - [Проверка, кто занял порт](https://stackoverflow.com/a/38953356/548473) (в случае проблем с запуском и дебагом на портах 8080, 8000)</a>
> - [**Деплой war в Tomcat с Application context**](https://github.com/JavaOPs/topjava/wiki/IDEA#Деплой-war-в-tomcat-application-context-должен-быть-тот-же-что-и-url-приложения-деплоить-надо-war-exploded)
> - [**Динамическое обновление без передеплоя**](https://github.com/JavaOPs/topjava/wiki/IDEA#Для-динамической-перегрузки-ресурсов-кнопка-нажмите-кнопку-update-resource-on-frame-deactivation)

> Если `maven` выдает ошибку
```
[INFO] --- maven-war-plugin:2.2:war (default-war) @ topjava ---
[WARNING] Error injecting: org.apache.maven.plugin.war.WarMojo
com.google.inject.ProvisionException: Unable to provision, see the following errors:
1) Error injecting constructor, java.lang.ExceptionInInitializerError: Cannot access defaults field of Properties
  at org.apache.maven.plugin.war.WarMojo.<init>(Unknown Source)
```
[гуглим по сообщению ошибки](https://stackoverflow.com/questions/66920567/error-injecting-org-apache-maven-plugin-war-warmojo)! Решения:
- или понизить версию JDK <=14 (на JDK 17 мы мигрируем на 5-м занятии).  
После смены JDK в `Project Structure...` обязательно `clean` и `Reload` кнопка в maven окошке.   
- или добавьте после `maven-compiler-plugin`:
```
<plugin>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-war-plugin</artifactId>
    <version>3.3.2</version>
</plugin>
```
Новые версии JDK уже неправильно работают с war package по умолчанию. Им нужна новая версия упаковки, конфигурим ее плагином. 

#### Apply 1_4_forward_to_redirect.patch

- <a href="http://tomcat.apache.org/">Tomcat Home Page</a>
- [Жизненный цикл сервлета. Для каждого сервлета создается только одна копия](https://metanit.com/java/javaee/4.8.php)
- [Сервлеты, Java servlet API. Пишем простое веб-приложение](https://javarush.ru/groups/posts/2529-chastjh-5-servletih-pishem-prostoe-veb-prilozhenie)
- <a href="https://devcolibri.com/как-создать-servlet-полное-руководство/">Руководство: как создать servlet</a>
- Томкат менеджер: [http://localhost:8080/manager](http://localhost:8080/manager)
  - в `TOMCAT_HOME\conf\tomcat-users.xml` нужно добавить 
```
<user username="tomcat" password="tomcat" roles="tomcat,manager-gui,admin-gui"/>
```
- Если проблема с Tomcat debug и работает Dr.Web- нужно его отключить, либо добавить в исключения путь к  `.IntelliJIdeaXXX/`
- Наше приложение: [http://localhost:8080/topjava](http://localhost:8080/topjava)
- Наш сервлет:     [http://localhost:8080/topjava/users](http://localhost:8080/topjava/users)

- Дополнительно:
  - Remote debug встречается много реже - приконнекчивание к уже запущенной JVM, которую, например, нельзя запустить из IDEA. Можно попробовать запустить catalina через `jpda start`, задеплоить туда war и уже после этого после приконнектиться через запуск `Tomcat Server -> Remote`
![image](https://user-images.githubusercontent.com/13649199/120930503-2a5e2700-c6f6-11eb-81c4-f21de8efbb8f.png)
  - [Настройки Remote Debug в новой IDEA](https://github.com/JavaOPs/topjava/wiki/IDEA#remote-debug-в-новой-idea)
  - <a href="http://blog.trifork.com/2014/07/14/how-to-remotely-debug-application-running-on-tomcat-from-within-intellij-idea">Remotely debug on tomcat from IDEA</a>
  - [HTTP](https://developer.mozilla.org/ru/docs/Web/HTTP)
  - <a href="http://info.javarush.ru/idea_help/2014/01/22/Руководство-пользователя-IntelliJ-IDEA-Отладчик-.html">Отладчик IntelliJ IDEA</a>
  - <a href="https://www.youtube.com/watch?v=tN8K1y-HSws&list=PLkKunJj_bZefB1_hhS68092rbF4HFtKjW&index=14">Yakov Fain: Intro to Java EE. Glassfish. Servlets (по-русски)</a>
  - <a href="https://www.youtube.com/watch?v=Vumy_fbo-Qs&list=PLkKunJj_bZefB1_hhS68092rbF4HFtKjW&index=15">Yakov Fain: HTTP Sessions, Cookies, WAR deployments, JSP (по-русски)</a>
  - <a href="https://www.youtube.com/playlist?list=PLoij6udfBncjHaO5s7Ln4w4BLj5FVc49P">Golovach Courses: Junior.February2014.Servlets</a>
  - <a href="http://java-online.ru/jsp.xhtml">Java Server Page</a>
  - <a href="http://stackoverflow.com/questions/1890438/how-to-get-parameters-from-the-url-with-jsp#1890462">Java объекты, доступные в JSP</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 7. [Логирование](https://www.youtube.com/watch?v=mo8z3zRVV1E)
#### Apply 1_5_simple_logging.patch
 
- [Зачем нужно логирование](https://javarush.ru/groups/posts/2293-zachem-nuzhno-logirovanie)
- [Logback Project](https://logback.qos.ch/)

> А зачем мы использовали logback? Почему SLF4J нас не устроило? Почему реализация логирования не log4j?

`SLF4J-API` это API. В нее включена только пустая реализация `org.slf4j.helpers.NOPLogger` (можно посмотреть в исходниках). Logback для новых проектов стал стандарт, *Spring Boot* используют его по умолчанию.
[Reasons to prefer logback over log4j](http://logback.qos.ch/reasonsToSwitch.html)

> Почему `private static final Logger log` а не `LOG/LOGGER` ?

Это [правило именования констант, которые не "deeply immutable"](https://google.github.io/styleguide/javaguide.html#s5.2.4-constant-names), те если их содержимое можно изменить.

#### Apply 1_6_logging_config.patch

- [Java Logging: история кошмара](http://habrahabr.ru/post/113145/)
- [Project dependencies for logging](https://www.slf4j.org/manual.html#projectDep)
- [Добавление зависимостей логирования](http://www.slf4j.org/legacy.html) в проект
- Не делать конкатенацию строк: [форматирование в логах через {}](https://www.slf4j.org/faq.html#logging_performance)
- Дополнительно:
  - [Logback configuration](https://logback.qos.ch/manual/configuration.html)
  - [Ведение лога приложения](http://www.skipy.ru/useful/logging.html)
  - [Владимир Красильщик – Что надо знать о логировании прагматичному Java‑программисту](https://www.youtube.com/watch?v=qzqAUUgB3v8)

**Установите переменную окружения на TOPJAVA_ROOT на корень проекта и перезапустите IDEA. Слеши в пути должны быть в стиле unix (/)**

Проверить, видит ли Java вашу переменную можно через `System.getenv("TOPJAVA_ROOT")`

- [Set environment for Win/Mac/Unix](https://chlee.co/how-to-setup-environment-variables-for-windows-mac-and-linux/)
- [Set environment for UNIX (advanced)](https://askubuntu.com/a/849954)
  - [Определить, какой Login или Non-Login Shell](https://tecadmin.net/difference-between-login-and-non-login-shell)
  - [Порядок запуска скриптов при старте](https://www.baeldung.com/linux/bashrc-vs-bash-profile-vs-profile)
- Или простой вариант (не забудте добавить и в Run, и в Debug)

![image](https://user-images.githubusercontent.com/13649199/76862707-8af21180-686f-11ea-9f8c-2bb30ef4c3b2.png)

**Иногда антивирусы блокируют логирование (например Comodo). Если не работает и стоит антивирус- добавьте исключение.**

#### ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы

> Изменения в проекте, которым могут встретиться в других видео: 
> - убрал `LoggerWrapper` и логирую напрямую в логгер SLF4J.
> - удалил зависимости `jul-to-slf4j` и `jcl-over-slf4j`. Spring 5 напрямую использует `slf4j` без `common-logging`

### ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы

> Используются ли сервлеты на реальных проектах сегодня?

1. Сервлеты лежат в основе любого Java web фреймворка, если взаимодействие не асинхронное и не nio (например Spring MVC). Работать с таким фреймворком и не знать, что такое сервлеты, все равно что работать с JPA/Hibarnate/любым ORM без знания JDBC.
2. Бывают легаси проекты, бывают современные, где не подтягивается сторонний web фреймворк. При этом, даже работая с фреймворком, приходится иметь дело с Servlet API (часто с `HttpServletRequest/HttpServletResponse`) - обработка ошибок, валидаторы, фильтры, пре/пост обработка зарпосов, получение ip, работа с сессией и пр.

>  Используются ли еще где-то в реальной разработке JSP, или это уже устаревшая технология? Заменит ли ее JSF (https://javatalks.ru/topics/38037)?

JSF и JSP- разные ниши и задачи.
JSP- шаблонизатор, JSF - МVС фреймворк. Из моего опыта- с JSP сталкивался в 60% проектов. Его прямая замена: http://www.thymeleaf.org (в Spring-Boot по умолчанию), но в уже запущенных проектах встречается достаточно редко. JSP не умирает, потому что просто и дешево. Кроме того включается в большинство веб-контейнеров (в Tomcat его реализация Jasper)

JSF- sun-овский еще фреймворк, с которым я ни разу не сталкивался и особого желания нет. Вот он как раз, по моему мнению, активно замещается хотя бы javascript фреймворками (angular, react, vue.js).

> Какой метод сервлета вызвается из HTML/JSP: doGet/doDelete/doPut..?

Методы можно посмотреть в вкладке браузера `Network`. По [сcылке](http://htmlbook.ru/html/a/href) вызывается `GET/doGet()`. Из [формы можно делать GET и POST](http://htmlbook.ru/html/form/method), обычно данные формы передаются через POST. **Для других методов нужен JavaScript, пока их не используем**

---------

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW01 (делаем ветку HW01 от последнего патча в master) 

#### **ОСНОВНОЕ, чему мы учимся на проекте: мыслить и работать как Java разработчики уже сейчас**, потом это будет гораздо сложнее и стоить дороже.
Вот на мой взгляд [хорошие советы новичкам](http://blog.csssr.ru/2016/09/19/how-to-be-a-beginner-developer). От себя я добавлю:
> - Учись грамотно формулировать проблему. Проблема "у меня не работает" может иметь тысячи причин. В процессе формулирования очень часто приходит ее решение. 
>    - что я делаю (подробно, чтобы понял человек, который не копался в этом совсем)
>    - что получаю (обычно верх самого последнего эксепшена)
>    - мои попытки решения проблемы

> - Учись исследовать проблему. Внимательное чтение логов и [умение дебажить](http://info.javarush.ru/idea_help/2014/01/22/Руководство-пользователя-IntelliJ-IDEA-Отладчик-.html) - основные навыки разработчика. Обычно самый верх самого нижнего эксепшена- причина ошибки, туда нужно ставить брекпойнт.
> - Грамотно уделяй время каждой проблеме. Две крайности - сразу бросаться за помощью и биться над ней часами. Пробуй решить ее сам и в зависимости от проблемы выделяй на это разумное время.

----------------------------------------------------
- **Обязательно и как можно чаще пользуйтесь `Ctrl+Alt+L` - отформатировать код класса**
- **При изменениях на UI не забываетй сбрасывать кэш браузера - `Ctrl+F5`**
- **При удалении классов не забывате чистить target - в окошке Maven или `mvn clean`**
- **При проблемах с IDEA пользуйтесь `Refresh` в окошке Maven**
- **При проблемах с выполнением проверьте (и удалите) лишние java процессы (например в Task Manager)**

--------------------------------------------
#### 1. Реализовать сервлет с отображением в таблице списка еды (в памяти и БЕЗ учета пользователя)

> Деплоиться в Tomcat лучше как `war exploded`: нет упаковки в war и при нажатой кнопке `Update Resources on Frame Deactivation` можно обновляться css, html, jsp без передеплоя. При изменении `web.xml`, добавлении методов, классов необходим redeploy.

- 1.1 По аналогии с `UserServlet` добавить `MealServlet` и `meals.jsp`
  - Задеплоить приложение (war) в Tomcat c `applicationContext=topjava` (приложение должно быть доступно по <a href="http://localhost:8080/topjava">http://localhost:8080/topjava</a>)
  - Попробовать разные деплои в Tomcat, remote и local debug
- 1.2 Сделать отображения списка еды в JSP [в таблице](http://htmlbook.ru/html/table), цвет записи в таблице зависит от параметра `excess` (красный/зеленый).
  - 1.2.1 Список еды захардкодить (те проинициализировать в коде, желательно чтобы в проекте инициализация была только в одном месте). Норму калорий (caloriesPerDay) сделать в коде константой
  - 1.2.2 Время выводить без 'T'
  - 1.2.3 Список выводим БЕЗ фильтрации по `startTime/endTime`
  - 1.2.4 С обработкой исключений пока можно не заморачиваться, мы будем красиво обрабатывать в конце стажировки
  - 1.2.5 Вариант реализации:
    - из сервлета преобразуете еду в `List<MealTo>`;
    - кладете список в запрос (`request.setAttribute`);
    - делаете `forward` на jsp для отрисовки таблицы (при `redirect` атрибуты теряются).
    - **JSP работает через геттеры: `meal.dateTime` в JSP вызывает `meal.getDateTime()`**
    - в `JSP` для цикла можно использовать `JSTL tag forEach`. Для подключения `JSTL` в `pom.xml` и шапку JSP нужно добавить:
```
    <dependency>
       <groupId>javax.servlet</groupId>
       <artifactId>jstl</artifactId>
       <version>1.2</version>
    </dependency>

    <%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
    ...
```

  - <a href="https://java-course.ru/old/students/part7.html">Интернет-приложения на JAVA</a>
  - <a href="https://java-course.ru/old/students/part8.html">JSP</a>
  - [Как создать Servlet? Полное руководство](https://devcolibri.com/как-создать-servlet-полное-руководство)
  - [JSTL для написания JSP страниц](https://devcolibri.com/jstl-для-написания-jsp-страниц/)
  - <a href="http://javatutor.net/articles/jstl-patterns-for-developing-web-application-1">JSTL: Шаблоны для разработки веб-приложений в java</a>
  - <a href="http://stackoverflow.com/questions/35606551/jstl-localdatetime-format">JSTL LocalDateTime format</a>

### Optional
#### 2. Реализуем в ПАМЯТИ (любая коллекция) CRUD (create/read/update/delete) для еды
**Пример: [Simple CRUD using Servlet/JSP](https://danielniko.wordpress.com/2012/04/17/simple-crud-using-jsp-servlet-and-mysql)**
> - Пример нужно САМОСТОЯТЕЛЬНО переделать: вместо хранения в MySql нужно хранить в коллекции ПАМЯТИ (задание упрощается).
> - Классы: сервлет, **инрерфейс хранения**, его реализация для хранения в памяти
- 2.1 Хранение в памяти будет одна из наших CRUD реализаций (позже будет JDBC, JPA и DATA-JPA).
- 2.2 Работать с реализацией CRUD через интерфейс, который не должен ничего знать о деталях реализации (Map, DB или что-то еще).
- 2.3 Добавить поле `id` в `Meal/ MealTo`. Реализовать генерацию счетчика, УЧЕСТЬ МНОГОПОТОЧНОСТЬ СЕРВЛЕТОВ. В качестве первичного ключа используют UUID, Long, Integer. На нашем проекте будем использовать **Integer**.
    - [обзор java.util.concurrent](https://web.archive.org/web/20220427140138/https://habr.com/ru/company/luxoft/blog/157273/)
- 2.4 Сделать форму редактирования в JSP: AJAX/JavaScript использовать НЕ надо, делаем через `<form method="post">` и `doPost()` в сервлете.
- 2.5 Для ввода дат и времени можно использовать <a href="https://webref.ru/html/input/type">html5 типы</a>, хотя они поддерживаются не всеми браузерами (<a href="https://robertnyman.com/html5/forms/input-types.html">протестировать свой браузер</a>). В конце курса мы добавим <a href="http://xdsoft.net/jqplugins/datetimepicker/">DateTimePicker jQuery plugin</a>, который будет работать на всех браузерах.
- 2.6 Форму на create-update предлагаю не дублировать, сделать одну (хотя это не ошибка сделать разные).

## После выполнения ДЗ обязательно <a href="lesson01.md#-Типичные-ошибки">проверьте решение на ошибки</a>

### ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Вопросы по HW1

> Не попадаю на страничку/брекпойнт в сервлете.

- внимательно проверь url и applicationContext (Application Context должен быть тот же, что и url приложения: <a href="https://github.com/JavaOPs/topjava/wiki/IDEA#%D0%94%D0%B5%D0%BF%D0%BB%D0%BE%D0%B9-war-%D0%B2-tomcat-application-context-%D0%B4%D0%BE%D0%BB%D0%B6%D0%B5%D0%BD-%D0%B1%D1%8B%D1%82%D1%8C-%D1%82%D0%BE%D1%82-%D0%B6%D0%B5-%D1%87%D1%82%D0%BE-%D0%B8-url-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B4%D0%B5%D0%BF%D0%BB%D0%BE%D0%B8%D1%82%D1%8C-%D0%BD%D0%B0%D0%B4%D0%BE-war-exploded">wiki IDEA</a>)
- посмотрите в task manager: возможно запущено несколько JVM и они мешают друг другу. Лишние java приложения убить.

> Приложение не видит TOPJAVA_ROOT.

**После выставления переменной окружения IDEA нужно рестартовать. Слеши в пути должны быть в стиле unix (/)**. Проверить, видит ли java переменную окружения можно так: `System.getenv("TOPJAVA_ROOT")`. Еще вариант: добавить `-DTOPJAVA_ROOT=...` в опции запуска приложения, тогда она доступна из java как `System.getProperty("TOPJAVA_ROOT")`.

> Проблемы с кодировкой в POST (кракозябры). 

Возможное решение - выставьте кодировку ДО первого чтения из request:
```
protected void doPost(HttpServletRequest request, ...) {
    request.setCharacterEncoding("UTF-8");
```

> Если сервлет тыкают несколько пользователей / несколько браузеров, какого должно быть поведение? Нужно ли что-то делать с сессиями?

В Optional нужно делать реализацию хранения потокобезопасной. Cессии пока не используем  (начнутся, когда будет прикручивать авторизацию).

> Для чего нам нужна потокобезопасная реализация коллекции, если каждый пользователь видит только себя?

Реализация хранения в памяти у нас одна на всех. Те коллекция шарится между пользователями, они в разных потоках ее дергают. Если несколько потоков одновременно будут изменять коллекцию без учета потокобезопасная (например один будет удалять, второй вставлять),  без учета потокобезопасности мы получим `ConcurrentModificationException`

> Предпочтительнее ли создавать новый объект `Meal` при каждом update?

Если при обновлении не создавать копию, то сохраненный в памяти объект может кто-то попортить. Вопрос скорее доверия к коду- если проект большой и людей над ним трудится много, то вероятнее нужно копировать.

> Почему теряются атрибуты при передаче на сервлет: `http://localhost:8080/topjava/meals?action=add&...` и `req.getAttribute("action")` = null ?

См. <a href="http://stackoverflow.com/questions/5243754/difference-between-getattribute-and-getparameter">Difference between getAttribute() and getParameter()</a>. Отсюда также следует, что при редиректе атрибуты теряются.

> Зачем нужен в jsp `<jsp:useBean id=".." scope="request" type=".."/>` ?

[jsp:useBean](http://java-online.ru/jsp-actions.xhtml#useBean) нужен IDEA для автодополнений - она понимает тип переменной, которая уже доступна в JSP (например через setAttribute). И еще эта переменная становится доступной в java вставках. Для вывода в JSP это тэг не обязателен. Если тип переменной JSP не совпадает с тем, что в `jsp:useBean`, будет ошибка.

----------------------------
### Итоги занятия после выполнения ДЗ: 
Мы создали CRUD веб-приложение для управления едой (создание-чтение-обновление-удаление) с использованием сервлетов и логированием. Пока в памяти, и пока еда никому не принадлежит.
Пример выполнения ДЗ (не надо сложного интерфейса, Bootstrap css будем проходить на 8-м занятии):

![image](https://user-images.githubusercontent.com/13649199/94701494-6100c800-0345-11eb-9907-2a0099305710.png)
![image](https://user-images.githubusercontent.com/13649199/94701688-9a393800-0345-11eb-9c2d-dd53ba55724c.png)

### ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Типичные ошибки
- 1 **Если в названии класса есть `Meal`, не нужно использовать слово meal в методах класса.**
- 2 Привыкайте писать комментарии к чекину: одной фразой что вы сделали в нем. Например: *Meals CRUD implementation*. См.
[Как писать сообщения коммитов](https://habr.com/ru/post/416887/)
- 3 Хранение в памяти и операции с ней должны выполняться просто и эффективно
- 4 Хранить нужно `Meal` и конвертировать ее в `MealTo` когда отдаем список на отображение в JSP.
  - excess нужно пересчитывать каждый раз перед отображением
  - форматирование должно находится в JSP! Именно он заведует отображением. Повторяем паттерн [MVC](https://ru.wikipedia.org/wiki/Model-View-Controller)
- 5 Стили `color` можно применять ко всей строке таблицы `tr`, а не каждой ячейке.
- 6 `DateTimeFormatter` можно сделать один заранее (он потокобезопасный в отличие от `SimpleDateFormatter`), а не создавать новый при каждом запросе.
- 7 Работать с CRUD надо через интерфейс. 
- 8 Реализаций хранения будет несколько, нужно учитывать это в названии класса имплементации работы в памяти.
- 9 В `web.xml` принято группировать сервлет со своим маппингом
- 10 Не размещайте никакую логику (форматирование, счетчики) в бинах, где хранятся только данные (`Meal, MealTo`)
- 11 Еще раз: детали реализации в памяти не должны быть никому видны. Те НЕ НАДО счетчик размещать в `Meal` или `MealServlet` или `MealsUtil`, в базе же он будет по другому генерится. 
- 12 `volatile` при ++ не помогает от многопоточности. Почему? 
- 13 Обратите также внимание на то, чтобы реализация вашей коллекции для хранения еды была также многопоточной.
- 14 Не делайте дублирование кода `MealsUtil`. Простой вариант - использовать то, что отсутствие фильтрации - это частный случай фильтрации (когда ничего не отсеивается). В моем решении используется [паттерн стратегия](https://refactoring.guru/ru/design-patterns/strategy)
- 15 Не дублируйте строки в `jsp`. Посмотрите на <a href="https://steveswinsburg.wordpress.com/2008/09/04/the-ternary-operator-and-jsp/">тернарный оператор</a>.
- 16 После операции `delete` в браузере должен быть url `http:\\localhost:8080\topjava\meals`
- 17 Перед чекином проверяйте свой ченджлист (`Ctrl+D` на файле из `Local Changes` - посмотреть что поменялось). Если там только пробелы/переводы строк, не надо его комитить - делайте файлу `Git->revert`.
- 18 Учтите в названии реализации CRUD, что
  - 18.1 у нас будет несколько реализаций (не только в памяти)
  - 18.2 у нас будет 2 CRUD (для еды и пользователей). А в реальном проекте их намного больше.
- 19 Сессии НЕ использовать! При редиректе все атрибуты (`req.getAttribute()`) теряются (см. вопрос выше). Сценарий редиректа:
  - 1 из сервлета делаем редирект (снова на сервлет, не на JSP!)
  - 2 снова заходим в сервлет
  - 3 кладем нужные атрибуты и делаем forward на jsp
  - 4 если очень хочется передать параметры из 1. в 2. можно сделать их через параметры запроса (например `meals?id=5`) и доставать через `reg.getParameter(id)`. В моей реализации такого не потребовалось.
- 20 Для cancel в JSP можно использовать код: `<button onclick="window.history.back()" type="button">Cancel</button>`

# Стажировка <a href="https://github.com/JavaWebinar/topjava">Topjava</a>

## <a href="https://drive.google.com/drive/folders/0B9Ye2auQ_NsFfkpsWE1uX19zV19IVHd0bTlDclc5QmhMMm4xa0Npek9DT18tdkwyLTBZdXM">Материалы занятия</a> (скачать все патчи можно через Download папки patch)

### ![correction](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Обновление зависимостей
#### Apply 2_0_update.patch
- Обновил версии slf4j и logback на последние. Обычно ищу их в [Maven Central Repository](https://search.maven.org/)
- Не забудьте сделать `mvn clean` чтобы почистить из `target` старые версии

### Внимание! поправил патч - новая версия logback 1.4.x [работает только с JDK 11+](https://logback.qos.ch/news.html)
Итого - поменял версию logback на 1.3.4.  
Если уже накатили патчи - просто у себя в pom исправьте:
`<logback.version>1.4.4</logback.version>` на `<logback.version>1.3.4</logback.version>`

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW1:

- **Перед сборкой проекта (или запуском Tomcat) откройте вкладку Maven Projects и сделайте `clean`**
- **Если страничка в браузере работает неверно, очистите кэш (`Ctrl+F5` в хроме)**

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFXzByNVF3VV9zM1k">Отображения списка еды в JSP</a>
#### Apply 2_1_HW1.patch

> - Переименовал `TimeUtil` в `DateTimeUtil`
> - Переименовал `mealList.jsp` в `meals.jsp`
> - Изменения в `MealsUtil`:
>    - Сделал константу `List<Meal> meals`. [Правило именования констант, которые не "deeply immutable"](https://google.github.io/styleguide/javaguide.html#s5.2.4-constant-names)
>    - Для фильтрации по времени и без нее в метод `filterByPredicate` передаю реализацию `Predicate`, см. паттерн [Стратегия](https://refactoring.guru/ru/design-patterns/strategy) и, если непонятно, [картинку](https://user-images.githubusercontent.com/13649199/95467365-093a1080-0986-11eb-8177-0985456d857a.png)
> - Форматирование даты сделал на основе <a href="http://stackoverflow.com/questions/35606551/jstl-localdatetime-format#35607225"> Custom EL function</a>
>    - [Create a custom Function for JSTL через tag library descriptor (TLD)](http://findnerd.com/list/view/How-to-create-a-custom-Function-for-JSTL/2869/)
> - Добавил еще один способ вывести `dateTime` через стандартную JSTL функцию `replace`  (префикс `fn` в шапке также надо поменять)

- [jsp:useBean](http://java-online.ru/jsp-actions.xhtml#useBean)
- [MVC - Model View Controller](http://design-pattern.ru/patterns/mvc.html)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFQndBeWFOa3phRTg">Optional: реализация CRUD</a>
#### Apply 2_2_HW1_optional.patch
Про использование паттерна Repository будет подробно рассказано в видео "Слои приложения"
> - Согласно ответам на [Java Interfaces/Implementation naming convention](https://stackoverflow.com/questions/2814805/java-interfaces-implementation-naming-convention) 
убрал `Impl` в `InMemory` (и всех последующих) реализациях репозиториев. Они не нужны.
> - Поправил `InMemoryMealRepository.save()`. Если обновляется еда, которой нет в хранилище (c несуществующим id), вставка не происходит.
> - В `MealServlet.doGet()` сделал выбор через `switch`
> - В местах, где требуется `int`, заменил `Integer.valueOf()` на `Integer.parseInt()`
> - В `mealForm.jsp` использую <a href="http://stackoverflow.com/questions/1890438/how-to-get-parameters-from-the-url-with-jsp#1890462">параметр запроса `param.action`</a>, который не кладется в атрибуты.
> - Переименовал `mealEdit.jsp` в `mealForm.jsp`. Поля ввода формы добавил `required`
> - Пофиксил багу c `history.back()` в `mealForm.jsp` для **FireFox** (коммит формы при Cancel, сделал `type="button"`).

Дополнительно:
  - <a href="http://stackoverflow.com/questions/246859/http-1-0-vs-1-1">HTTP 1.0 vs 1.1</a>

### ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Вопросы по HW1

> Зачем в `InMemoryMealRepository` наполнять map с помощью нестатического блока инициализации, а не в конструкторе?

В общем случае так делать не надо. Сделал, чтобы напомнить вам про эту конструкцию, см. [Малоизвестные особенности Java](https://habrahabr.ru/post/133237/)

> Почему `InMemoryMealRepository` не singleton?

Начиная с Servlet API 2.3 пул сервлетов не создается, [создается только один инстанс сервлетов](https://stackoverflow.com/questions/6298309). Те. `InMemoryMealRepository` в нашем случае создается тоже только один раз. Далее все наши классы слоев приложения будут создаваться через Spring, бины которого по умолчанию являются синглтонами (в его контексте).  

> `Objects.requireNonNull` в `MealServlet.getId(request)` если у нас нет `id` в запросе бросает NPE (`NullPointerException`). Но оно вылетит и без этого метода. Зачем он нужен и почему мы его не обрабатываем?

`Objects.requireNonNull` - это проверка предусловия (будет подробно на 4-м занятии). Означает что в метод пришел неверный аргумент (должен быть не null) и приложение сообщает об ошибке сразу на входе (а не "может быть где-то потом"). См. [What is the purpose of Objects#requireNonNull](https://stackoverflow.com/a/27511204/548473). Если ее проглатывать или замазывать, то приложение возможно где-то работает неверно (приходят неверные аргументы), а мы об этом не узнаем. Красиво обрабатывать ошибки будем на последних занятиях (Spring Exception Handling).

## Занятие 2:
### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFVDJZVTktQzRYTWc">Библиотека vs Фреймворк. Стандартные библиотеки Apache Commons, Guava</a>
- <a href="http://commons.apache.org/">Apache Commons</a>, <a href="https://github.com/google/guava/wiki">Guava</a>
  - Guava используется на проекте [Многомодульный maven. Многопоточность. XML (JAXB/StAX). Веб сервисы (JAX-RS/SOAP). Удаленное взаимодействие (JMS/AKKA)](http://javaops.ru/reg/masterjava)  
   
### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4. <a href="https://drive.google.com/open?id=1Ve2vLlZAHwOKBfpuOL9X_jbSpQMGsLVP">Многоуровневая(многослойная) архитектура</a>
![Слои приложения](http://javaops.ru/static/images/topjava/top-scheme.jpg)
-  <a href="https://metanit.com/sharp/mvc5/23.5.php">Многоуровневая(многослойная) архитектура</a>
-  <a href="https://ru.wikipedia.org/wiki/Data_Access_Object">Data Access Object</a>
-  <a href="http://martinfowler.com/eaaCatalog/dataTransferObject.html">Паттерн DTO</a>
-  <a href="http://stackoverflow.com/questions/21554977/should-services-always-return-dtos-or-can-they-also-return-domain-models">Should services always return DTOs, or can they also return domain models?</a>
- [Mapping Entity->DTO goes in which application layer: Controller or Service?](http://stackoverflow.com/questions/31644131/spring-dto-dao-resource-entity-mapping-goes-in-which-application-layer-cont/35798539#35798539)
-  Дополнительно:
   -  <a href="http://stackoverflow.com/questions/1612334/difference-between-dto-vo-pojo-javabeans">Value Object и Data Transfer Object</a>
   - <a href="http://stackoverflow.com/questions/6640784/difference-between-active-record-and-dao">Difference between Active Record and DAO</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5. <a href="https://drive.google.com/open?id=1pWsm_fNfxqPB8yygWJsMUpvWMVyRxIqt">Создание каркаса приложения для пользователей</a>

#### Apply 2_3_app_layers.patch
> - Убрал интерфейсы к сервисам. Я всегда предпочитаю писать меньше кода и в случае с одной реализацией можно обходится без них. 
    По поводу инкапсуляции и отделения API от реализации - интерфейсы к сервисам это внутренняя часть приложения с одной реализацией. Меньше кода, проще поддерживать.
> - Переименовал `ExceptionUtil` в `ValidationUtil`
> - Поменял `LoggedUser` на `SecurityUtil`. Это класс, из которого приложение будет получать данные залогиненного пользователя (пока [аутентификации](https://ru.wikipedia.org/wiki/Аутентификация) нет, он реализован как заглушка). Находится в пакете `web`, т.к. аутентификация/[авторизация](https://ru.wikipedia.org/wiki/Авторизация) происходит на слое контроллеров и остальные слои приложения про нее знать не должны.
> - Добавил проверку id пользователя, пришедшего в контроллер ([treat IDs in REST body](https://stackoverflow.com/a/32728226/548473), "If it is a public API you should be conservative when you reply, but accept liberally"). Считаю это важной частью проверки входных данных в контроллере, не забывайте это делать в ваших выпускных проектах. 


## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы

> Почему у `User.registered` тип `Date`, а `Meal.dateTime` `LocalDateTime `?

По логике приложения время регистрации - абсолютное (конкретный момент), а время еды по бизнес логике относительно (те не зависит от часового пояса, завтрак и в Африке должен быть завтраком)

>  Какова цель деления приложения на слои?

Управляемость проекта (особенно большого) повышается на порядок:
- Обеспечивается меньшая связываемость. Допустим если мы меняем что-то в контроллере, то сервис эти изменения не задевают.
- Облегчается тестирование (мы будем тестировать слои сервисов и контроллеров отдельно)
- Четко разделяется функционал - где писать, куда смотреть. Не создаются [God objects](https://ru.wikipedia.org/wiki/Божественный_объект)

> DTO используются когда есть избыточность запросов, которую мы уменьшаем, собрав данные из разных бинов в один? Когда DTO необходимо использовать?

(D)TO может быть как частью одного entity  (набор полей) так и набором нескольких entities.
В нашем проекте для данных, которые надо отдавать наружу и отличающихся от Entiy (хранимый бин), мы будем делать (Data) Transfer Object и класть в отдельный пакет to. Например `MealsTo` мы отдаем наружу и он является Transfer Object, его пернесем в пакет `to`.
На многих проектах (и собеседованиях) практикуют разделение на уровне maven модулей entity слоя от логики и соответствующей конвертацией ВСЕХ Entity в TO, даже если у них те же самые поля.
Хороший ответ когда TO обязательны есть на <a href="http://stackoverflow.com/questions/21554977/should-services-always-return-dtos-or-can-they-also-return-domain-models#21569720">stackoverflow: When to Use</a>.

> Почему контроллеры положили в папку web, а не в controllers?

То же самое что `domain/model` - просто разные названия, которые устоялись в Java. Не придумывайте своих!

> Зачем мы наследуем `NotFoundException` от `RuntimeException`?

Так с ним удобнее работать. И у нас нет никаких действий по восстановлению состояния приложения (no recoverable conditions): <a href="http://stackoverflow.com/questions/6115896/java-checked-vs-unchecked-exception-explanation">checked vs unchecked exception</a>. По последним данным checked exception вообще depricated: <a href="http://blog.takipi.com/ignore-checked-exceptions-all-the-cool-devs-are-doing-it-based-on-600000-java-projects">Ignore Checked Exceptions</a>

> Что такое `ProfileRestController`?

Контроллер, где залогиненный пользователь будет работать со своими данными

> Зачем в `AdminRestController` переопределяются методы родителя с вызовом тех же родительских?

Сделано на будущее, мы будем менять этот код.

> Что лучше возвращать из API: `Collection` или `List`

Вообще, как правило, возвращают `List`, если не просится по коду более общий случай (например возможный `Set` или `Collection`, возвращаемый `Map.values()`). Если возвращается отсортированный список, то `List` будет адекватнее.

> **Вопрос вам (очень важный):** можно ли в `MealRestController` контроллере сделать член класса `private int userId = SecurityUtil.authUserId()` и использовать его в методах контроллера?

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 6. [Что такое Spring Framework](https://www.youtube.com/watch?v=megjriLG35I). 
- [Wiki: Spring Framework](https://ru.wikipedia.org/wiki/Spring_Framework)
- [JVM Ecosystem Report 2020: Spring](https://snyk.io/blog/spring-dominates-the-java-ecosystem-with-60-using-it-for-their-main-applications/)
- [2020 Java Technology Report](https://www.jrebel.com/blog/2020-java-technology-report)
- [Spring Framework Documentation](https://docs.spring.io/spring-framework/docs/current/spring-framework-reference/index.html)
- [Что такое Spring Framework? Внедрение зависимостей](https://habr.com/ru/post/490586/)
- [Евгений Борисов — Spring-построитель](https://www.youtube.com/watch?v=rd6wxPzXQvo)
- [Инверсия управления] (https://ru.wikipedia.org/wiki/Инверсия_управления)
#### Apply 2_4_add_spring.patch

> Сделал рефакторинг конструктора User, чтобы была возможность создавать пользователя без ролей

###  ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 7. [Запуск Spring Application Context](https://drive.google.com/file/d/1y-3ok-6CzhjnR4Rmv3-z4EV4VsElIDn6)
- [Container Overview](https://docs.spring.io/spring-framework/docs/current/spring-framework-reference/core.html#beans-basics)
#### Apply 2_5_add_spring_context.patch

###  ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 8. [Dependency Injection, Annotation_processing](https://drive.google.com/file/d/1Z9cgULTrXxgeaqqnsh7rJtIaD2LSdzHT)
#### Apply 2_6_dependency_injection.patch
- [IoC, DI, IoC-контейнер. Просто о простом](http://habrahabr.ru/post/131993/)
- [Что такое Spring Framework? Внедрение зависимостей](https://habr.com/ru/post/490586/)
- [Перевод "Field Dependency Injection Considered Harmful"](https://habrahabr.ru/post/334636/)
- [Field vs Constructor vs Setter DI](http://stackoverflow.com/questions/39890849/what-exactly-is-field-injection-and-how-to-avoid-it)

#### Apply 2_7_annotation_processing.patch
-  [Spring Auto Scanning Components](http://www.mkyong.com/spring/spring-auto-scanning-components)
-  [Difference between @Component, @Repository & @Service annotations in Spring](http://stackoverflow.com/questions/6827752/whats-the-difference-between-component-repository-service-annotations-in)
-  [Использование аннотации @Autowired](http://www.seostella.com/ru/article/2012/02/12/ispolzovanie-annotacii-autowired-v-spring-3.html)
-  Дополнительное:
   - [Подготовка к Spring Professional Certification. Контейнер, IoC, бины](https://habr.com/ru/post/470305/)
   - [Spring на GitHub](https://github.com/spring-projects)
   - [Spring Annotations](https://dzone.com/refcardz/spring-annotations)

#### Дополнительно видео по Spring
   - [Юрий Ткач: Spring Framework - The Basics](https://www.youtube.com/playlist?list=PL6jg6AGdCNaWF-sUH2QDudBRXo54zuN1t)
   - [Java Brains: Spring Framework](https://www.youtube.com/playlist?list=PLC97BDEFDCDD169D7)
   - [Тимур Батыршинов: Spring Core - основы фреймворка, ядро](https://www.youtube.com/watch?v=CfHDr-19WWY&list=PL8X2nqRlWfaYYP1-qXjdPKE7bXYkl6aL4)
   - [alishev: Spring Framework](https://www.youtube.com/playlist?list=PLAma_mKffTOR5o0WNHnY0mTjKxnCgSXrZ)

## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы
> Что такое схема в spring-app.xml xsi:schemaLocation и зачем она нужна

<a href="https://ru.wikipedia.org/wiki/XML_Schema">XML схема</a> нужна для валидации xml, IDEA делает по ней автозаполнение.

> Что означает для Spring

     <bean class="ru.javawebinar.topjava.service.UserService">
         <property name="repository" ref="inmemoryUserRepository"/>
     </bean> ?

Можно сказать так: создай и занеси в свой контекст экземпляр класса (бин) `UserService` и присвой его проперти `repository` бин `inmemoryUserRepository`, который возьми из своего контекста.

> `SecurityUtil.authUserId()`  и `user.id` это одно и то или это разные вещи?

`User.id` это уникальный идентификатор юзера, которых в приложении много.
`SecurityUtil.authUserId()` это идентификатор `id` залогиненного юзера. Мы можем, например, получить самого залогиненного юзера, выполнив запрос с `User.id==SecurityUtil.authUserId()`
Когда вы логинитесь в свое почтовое приложение, оно отдает вам именно ваши письма на основе вашего `id`, который она определяет и запоминает во время аутентификации (логина).  
У нас пока этого нет и `id` задается константой (хардкодится). Но когда мы сделаем настоящую аутентификацию, все будет работать для любого залогиненного пользователя.

> Как биндинг происходит для `@Autowired`? Как поступать, если у нас больше одной реализации `UserRepository`?

`@Autowired`  инжектит по типу (т.е. ижектит класс который реализует `UserRepository`). Обычно он один. Если у нас несколько реализаций, Spring не поднимится и поругается - `No unique bean`.
 В этом случае <a href="http://www.mkyong.com/spring/spring-autowiring-qualifier-example/">можно уточнить имя бина через @Qualifier</a>. `@Qualifier` обычно добавляют только в случае нескольких реализаций.
См. [Inject 2 beans of same type](https://stackoverflow.com/a/2153680/548473)

> Почему нельзя сервлет помещать в Spring контекст?

Сервлеты- это исключительно классы `servlet-api` (веб контейнера), они инстанциируются Tomcat. Те технически можно (без `init/destroy`), но идеологически - неверно. Cоздастся два сервлета: один настоящий, Tomcat-ом, и второй - нерабочий, Spring-ом. НЕ надо включать сервлет в контекст Spring.

--------------------
- **Еще раз смотрим на [демо приложение](http://topjava.herokuapp.com) и вникаем, что такое пользователь и его еда и что он может с ней сделать. 
Когда пользователь логинится в приложении, его id и норма калорий "чудесным образом" попадают в  `SecurityUtil.authUserId() / SecurityUtil.authUserCaloriesPerDay()`. Как они реально туда попадут будет в уроке  9 (Spring Security, сессия и куки)**
- **Перед началом выполнения ДЗ (если есть хоть какие-то сомнения) прочитайте ВСЕ ДЗ. Если вопросы остаются - то ВСЕ подсказки**. Особенно этот пункт важный, когда будете делать реальное рабочее ТЗ.

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW02
- 1: Имплементировать `InMemoryUserRepository` по аналогии с `InMemoryMealRepository` (список пользователей возвращать отсортированным по имени)
- 2: сделать `Meal extends AbstractBaseEntity`, `MealTo` перенести в пакет `ru.javawebinar.topjava.to` (transfer objects)
- 3: Изменить `MealRepository` и `InMemoryMealRepository` таким образом, чтобы вся еда всех пользователей находилась в одном общем хранилище, но при этом каждый конкретный аутентифицированный пользователь мог видеть и редактировать только свою еду.
  - 3.1: реализовать хранение еды для каждого пользователя можно с добавлением поля `userId` в `Meal` ИЛИ без него (как нравится). Напомню, что репозиторий один и приложение может работать одновременно с многими пользователями.
  - 3.2: если по запрошенному id еда отсутствует или чужая, возвращать `null/false` (см. комментарии в `MealRepository`)
  - 3.3: список еды возвращать отсортированный в обратном порядке по датам
  - 3.4: дополнительно: попробуйте сделать реализацию атомарной  (те учесть коллизии при одновременном изменении еды одного пользователя)
- 4: Реализовать слои приложения для функциональности "еда". API контроллера должна удовлетворять все потребности демо приложения и ничего лишнего (см. [демо](http://topjava.herokuapp.com)). Поиск и изменение порядка сортировки в таблице демо приложения реализованы на клиенте в браузере (плагин DataTables), сейчас делать не нужно.
  - **Смотрите на реализацию слоя для user и делаете по аналогии! Если там что-то непонятно, не надо исправлять или делать по своему. Задавайте вопросы. Если действительно нужна правка - я сделаю и напишу всем.**
  - 4.1: после авторизации (сделаем позднее), id авторизованного юзера можно получить из `SecurityUtil.authUserId()`. Запрос попадает в контроллер, методы которого будут доступны снаружи по http, т.е. запрос можно будет сделать с ЛЮБЫМ id для еды
  (не принадлежащем авторизированному пользователю). Нельзя позволять модифицировать/смотреть чужую еду.
  - 4.2: `SecurityUtil` может использоваться только на слое web (см. реализацию `ProfileRestController`). `MealService` можно тестировать без подмены логики авторизации, поэтому **в методы сервиса и репозитория мы передаем параметр `userId`: id авторизованного пользователя (предполагаемого владельца еды)**.
  - 4.3: если еда не принадлежит авторизированному пользователю или отсутствует, в `MealService` бросать `NotFoundException`.
  - 4.4: конвертацию в `MealTo` можно делать как в слое web, так и в service ([Mapping Entity->DTO: Controller or Service?](http://stackoverflow.com/questions/31644131))
  - 4.5: в `MealService` постараться сделать в каждом методе только одни запрос к `MealRepository`
  - 4.6 еще раз: не надо в названиях методов повторять названия класса (`Meal`).

![image](https://user-images.githubusercontent.com/13649199/121820224-66ffc480-cc9a-11eb-8abb-d1015ec2cb79.png)

- 5: включить классы еды в контекст Spring (добавить аннотации) и вызвать из `SpringMain` любой метод `MealRestController` (проверить что Spring все корректно заинжектил)

### Optional
- 6: в `MealServlet` сделать инициализацию Spring, достать `MealRestController` из контекста и работать с едой через него (**как в `SpringMain`**). `pom.xml` НЕ менять, работаем со `spring-context`. Сервлет обращается к контролеру, контроллер вызывает сервис, сервис - репозиторий. Когда будем работать через Spring MVC, `MealServlet` удалим, останется только контроллер.

![image](https://user-images.githubusercontent.com/13649199/121820239-71ba5980-cc9a-11eb-8c25-54df6f50f43c.png)

- 7: добавить в `meals.jsp` и `MealServlet` фильтрацию еды по дате и по времени (см. [демо](http://topjava.herokuapp.com)). Сброс фильтра делать не надо (реализуем через ajax в HW8). ВНИМАНИЕ: в приложении фильтрация делается не по интервалу дата-время, а отдельно по датам и затем отдельно по времени.
- 8: добавить выбор текущего залогиненного пользователя (имитация аутентификации, сделать [Select](http://htmlbook.ru/html/option) с двумя элементами со значениями 1 и 2 в `index.html` и `SecurityUtil.setAuthUserId(userId)` в `UserServlet`). От выбора user или admin будет зависеть отображение еды: user-а или admin-а.
Настоящая аутентификация будет через Spring Security позже.

----------------------------
### Итоги занятия после выполнения ДЗ: 
Мы создали архитектуру нашего приложения с разделением на слои и внедрили в наш проект фреймворк Spring, который их связывает.  
Далее мы реализовали функционал нашего приложения для работы с едой, как он сделан в [демо приложении](http://topjava.herokuapp.com) (но с фиктивной аутентификацией)

---------------------

### ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Типичные ошибки и подсказки по реализации

- 1: **В реализации `InMemoryUserRepository`**
  - 1.1: `getByEmail` попробуйте сделать через `stream`
  - 1.2: `delete` попробуйте сделать за одно обращение к map (без `containsKey`). При удалении пользователя его еду можно оставить, при реализации в базе будет CASCADE.
  - 1.3: при запросе списка юзеров предусмотрите случай одинаковых `User.name` (порядок должен быть зафиксированным). Поле `User.email`у нас уникально - в базе будет ограничение.
- 2: **В реализации `InMemoryMealRepository`**
  - 2.1: В `Meal`, которая приходит из браузера в контроллер, нет никакой информации о пользователе (еда приходит в контроллер **БЕЗ `user/userId`, она может быть только от авторизированного пользователя**). По id еды и авторизованному пользователю нужно проверить ее принадлежность (его это еда или чужая)
  **Проверьте сценарий: авторизованный пользователь пробует изменить чужую еду (id еды ему не принадлежит).**
  - 2.2: `get\update\delete` - следите, чтобы не было NPE (`NullPointException` может быть, если в хранилище отсутствует юзер или еда).
  - 2.3: Фильтрацию по датам сделать в репозитории т.к. из базы будем брать сразу отфильтрованные по дням записи. Следите чтобы **первый и последний день не были обрезаны, иначе сумма калорий будет неверная**.
  - 2.4: Если запрашивается список и он пустой, не возвращайте NULL! По пустому списку можно легко итерироваться без риска `NullPoinException`.
  - 2.5: Не дублируйте код в `getAll` и метод с фильтрацией
  - 2.6: попробуйте учесть, что следующая реализация (сортировка, фильтрация) будет делаться прямо в базе данных
- 3: Проверьте, что удалили `Meal.id` и связанные с ним методы (он уже есть в базовом `BaseEntity`)
- 4: Проверку `isBetweenHalfOpen` сделать в `DateTimeUtil`. Попробуйте использовать `LocalDateTime` вместо `LocalDate` с прицелом на то, что в DB будет тип даты `timestamp`. Тогда для `LocalTime` и `LocalDateTime` можно использовать один метод проверки полуоткрытого интервала и дженерики (см. [Generics Tutorials](https://docs.oracle.com/javase/tutorial/extra/generics/morefun.html) и [Погружаемся в Java Generics](https://habr.com/ru/company/sberbank/blog/416413/))
- 5: **Реализация 'MealRestController' должен уметь обрабатывать запросы**:
  - 5.1: Отдать свою еду (для отображения в таблице, формат `List<MealTo>`), запрос БЕЗ параметров
  - 5.2: Отдать свою еду, отфильтрованную по startDate, startTime, endDate, endTime
  - 5.3: Отдать/удалить свою еду по id, параметр запроса - id еды. Если еда с этим id чужая или отсутствует - `NotFoundException`
  - 5.4: Сохранить/обновить еду, параметр запроса - Meal. Если обновляемая еда с этим id чужая или отсутствует - `NotFoundException`
  - 5.5: Сервлет мы удалим, а контроллер останется, поэтому возвращать `List<MealTo>` надо из контроллера. И userId принимать в контроллере НЕЛЬЗЯ (иначе - для чего аторизация?). 
  - 5.6: В концепции REST при update дополнительно принято передавать id (см. `AdminRestController.update`)
  - 5.7: Для получения всей своей еды сделайте отдельный `getAll` без применения фильтра
- 6: Проверьте корректную обработку пустых значений date и time (в частности, если все значения пустые, должен выводится весь список)
- 7: `id` авторизированного пользователя получаем так: `SecurityUtil.authUserId()`, cм. `ProfileRestController`
- 8: В `MealServlet`
  - 8.1: Закрывать springContext в сервлете грамотнее всего в `HttpServlet.destroy()`: если где-то в контексте Spring будет ленивая инициализация, метод-фабрика, не синглтон-scope, то контекст понадобится при работе приложения. У нас такого нет, но делать надо все грамотно.
  - 8.2: Не храните параметры фильтра как члены класса сервлета, это не многопоточно! Один экземпляр сервлета используется всеми запросами на сервер, попробуйте дернуть его из 2х браузеров.
  - 8.3: В сервлете нельзя использовать `@Autowired` и `@Component`. См вопрос выше- "Почему нельзя сервлет помещать в Spring контекст?"

#### Если с ДЗ большие сложности, можно получить итоговые Meal интерфейсы для сверки в личке (`@Katherine`, `@Valeria`).
И напоследок история от Татьяны:
> 2.1 По id еды и авторизованному пользователю нужно проверить ее принадлежность.

На примере уточню:
Вася Пупкин нашел неименную банковскую карточку, т.е. номер есть, но имени нет.
Т.к. Вася не очень честный человек, то решил снять деньги с чужой карточки.
Наклеил *стикер со своим именем* на карточку и пришел в банк. Дает свой паспорт и карточку операционисту и просит снять всю наличность.
Варианты:
1. операционист сверяет стикер на карточке и паспорт - все ок, Вася получает наличность
2. операционист не обращает внимания на стикер, *а делает запрос в БД по номеру и сверяет ФИО в БД с паспортом* - ФИО не совпали, Вася в пролете

Кто и так это понимает, тому небольшой спойлер. А кто не понимает, может, переспросят, пообсуждают.

# Стажировка <a href="https://github.com/JavaWebinar/topjava">Topjava</a>
 
## [Материалы занятия](https://drive.google.com/drive/u/0/folders/0B9Ye2auQ_NsFT1NxdTFOQ1dvVnM)  (скачать все патчи можно через Download папки patch)
> **ВНИМАНИЕ! При удалении класса из исходников, его скомпилированная версия все еще будет находиться в target (и classpath). В этом случае (или в любом другом, когда проект начинает глючить) сделайте `mvn clean`.**
### ![correction](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Правки в проекте

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW02
### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. [Реализация репозиториев](https://drive.google.com/file/d/1hZay5jV-mVEByMnDveZ36jUAY0I3WChT)

#### Apply 3_01_HW2_repositories.patch

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. [Фильтрация в репозитории](https://drive.google.com/file/d/1s1tAsopU60gRvMaL53TP9EjS1gap99s3)
Метод `MealRepository.getBetweenHalfOpen` мы используем в следующем патче для фильтрации по целым дням.  
Используем `LocalDateTime` вместо `LocalDate` с прицелом на то, что в DB будем делать тип даты - `timestamp`.

#### Apply 3_02_HW2_repo_filters.patch
> - Исправил багу в `usersMealsMap.computeIfAbsent(userId, ConcurrentHashMap::new)` - в этом случае создается  `new ConcurrentHashMap(userId)`, что неверно
 - [Spring `@Nullable` аннотации](https://www.jetbrains.com/help/idea/nullable-and-notnull-annotations.html)
 
### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. [Meals Layers](https://drive.google.com/file/d/1jwd4Yhdy434fUAQyjpsZOO24XT-4lfp8)
> - В `DateTimeUtil` переименовал методы. Название должно описывать, "что метод делает", а не "зачем его вызывают". 
> - Переименовал `getBetween` для дат. Для времени у нас полуоткрытый диапазон, для дат - закрытый. 

#### Apply 3_03_HW2_meal_layers.patch
- [Should services always return DTOs, or can they also return domain models?](http://stackoverflow.com/questions/21554977/548473)
- [Mapping Entity->DTO goes in which application layer: Controller or Service?](https://stackoverflow.com/a/35798539/548473)

### Рефакторинг InMemory репозиториев
#### Apply 3_04_refactor_repository.patch
- сделал базовый `InMemoryBaseRepository` 
- наследую от него `InMemoryUserRepository`
- использую его в `InMemoryMealRepository` вместо `Map<Integer, Meal>`

Обратите внимание на `InMemoryBaseRepository.counter` - счетчик один, общий для всех хранимых объектов

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4. [HW2 Optional](https://drive.google.com/file/d/1yzNvGBgjgtuKXDFo983OqtTNoHDbyn1z)
#### Apply 3_05_HW2_optional_MealServlet.patch
> - Заменил `@Depricated StringUtils.isEmpty` на `hasLength` (условие приходится инвертировать)
> - Убрал логирование (уже есть в контроллере)
> - `assureIdConsistent` позволяет в контроллере обновлять еду с `id=null`

#### Apply 3_06_HW2_optional_filter.patch
- [JSP Implicit Objects](https://stackoverflow.com/a/1890462/548473)
- [Использование data-* атрибутов](https://developer.mozilla.org/ru/docs/Web/Guide/HTML/Using_data_attributes), имена сделал [low-case через дефисы](https://stackoverflow.com/questions/36176474/548473)
 
#### Apply 3_07_HW2_optional_select_user.patch

### ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Вопросы по HW2

> Что делает `repository.computeIfAbsent / computeIfPresent` ?

Всегда пробуйте ответить на вопрос сами. Достаточно просто зайти по Ctrl+мышка в реализацию и посмотреть javadoc и **их дефолтную реализацию**

> Почему выбрана реализация `Map<userId, Map<mealId,Meal>>` а не `Meal.userId + Map<mealId,Meal>` ?

В данном случае двойная мапа (мультимапа) - самый эффективный способ хранения, который не требует итерирования (перебора всех значений). С другой стороны затраты по памяти в этом решении больше.

## Занятие 3:
### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFOU8wWlpPVE05STA">Коротко о жизненном цикле Spring контекста.</a>
#### Apply 3_08_bean_life_cycle.patch
> **Если у вас JDK больше 8, [добавьте в pom `javax.annotation-api`](https://stackoverflow.com/a/46502132/548473). На JDK 17 перейдем в 5 занятии.** 

-  <a href="http://habrahabr.ru/post/222579/">Spring изнутри. Этапы инициализации контекста.</a>
-  Ресурсы:
   -  <a href="https://www.youtube.com/watch?v=BmBr5diz8WA">Евгений Борисов. Spring, часть 1</a>
   -  <a href="https://www.youtube.com/watch?v=cou_qomYLNU">Евгений Борисов. Spring, часть 2</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png)  6. [Тестирование через JUnit](https://www.youtube.com/watch?v=wSVg6_iK2Aw)
### ВНИМАНИЕ!! Перед накаткой патча создайте каталог test (из корня проекта путь `\src\test` или `\src\test\java`), иначе часть файлов попадет в `src\main`.

> - "Deeply mutable" константы `UserTestData.user/admin` [сделал lowercase](https://google.github.io/styleguide/javaguide.html#s5.2.4-constant-names). 
> - Добавил для тестирования в данные `User guest` без ролей и без еды.

- все классы, которые не нужны при работе приложения переносятся в test (и не включаются в сборку)
- в тестах очень частая ошибка - менять местами `expected` (ожидаемое) и `actual` (фактическое) значения.
- [Регрессионное тестирование](https://ru.wikipedia.org/wiki/Регрессионное_тестирование)
- [Разработка через тестирование](https://ru.wikipedia.org/wiki/Разработка_через_тестирование)
- [Unit тестирование с JUnit](https://devcolibri.com/unit-тестирование-с-junit/)
- [maven-surefire-plugin](https://maven.apache.org/surefire/maven-surefire-plugin/usage.html)
- Дополнительно:
  - [JUnit 4](http://junit.org/junit4)
  - [Тестирование в Java. JUnit](http://habrahabr.ru/post/120101/)
  - [Юнит-тестирование для чайников](https://habr.com/ru/post/169381/)
  - [Тестирование кода Java с помощью фреймворка JUnit](https://www.youtube.com/watch?v=z9jEVLCF5_w) (youtube)

#### Apply 3_09_add_junit.patch

### После патча сделайте `clean` и [обновите зависимости Maven](https://github.com/JavaOPs/topjava/wiki/IDEA#maven_update), чтобы IDEA определила сорсы тестов
#### ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Вопрос: почему проект упадет при попытке открыть страничку еды (в логе смотреть самый верх самого нижнего исключения)?

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 7. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFai1veG9qaFZlZ2s">Spring Test</a>
> - поменял `@RunWith`: `SpringRunner` is an alias for the `SpringJUnit4ClassRunner`
#### Apply 3_10_add_spring_test.patch
-  [Spring Testing](https://docs.spring.io/spring/docs/current/spring-framework-reference/testing.html)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 8. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFVlNYczhnSU9JdXc">Базы данных. Обзор NoSQL и Java persistence solution без ORM.</a>
### Postgres можно установить локально и/или - РЕКОМЕНДУЕТСЯ через Docker, пригодиться!

--------------
### Установка локально:

> **Рекомендуется PostgreSQL 13**
-  <a href="https://ru.wikipedia.org/wiki/PostgreSQL">PostgreSQL</a>.
-  [PostgreSQL JDBC Driver](https://github.com/pgjdbc/pgjdbc)
-  <a href="http://java-course.ru/begin/postgresql/">Установка PostgreSQL</a>.
-  Чтобы избежать проблем с правами и именами каталогов, [**рекомендуют установить postgres в простой каталог, например `C:\Postgresql`**. И при проблемах создать каталог data на другом диске](https://stackoverflow.com/questions/43432713/548473). Если Unix, [проверить права доступа к папке (0700)](http://www.sql.ru/forum/765555/permissions-should-be-u-rwx-0700). Название ПК и имя пользователя должны быть латиницей (или можно устанавливать сервер [отсюда](https://postgrespro.ru/windows))
    - [Установка PostgreSQL в UBUNTU](https://losst.ru/ustanovka-postgresql-ubuntu-16-04)
    - [Install PostgreSQL 13 on Fedora](https://computingforgeeks.com/install-postgresql-13-on-fedora/)
    
> Создать в pgAdmin новую базу `topjava` и новую роль `user`, пароль `password`

![image](https://cloud.githubusercontent.com/assets/13649199/18809406/118f9c48-8283-11e6-8f10-d8291517a497.png)

>  Проверьте, что у user в Privileges есть возможность авторизации (особенно для pgAdmin4)

или в UNIX командной строке:
```
sudo -u postgres psql
CREATE DATABASE topjava;
CREATE USER "user" WITH password 'password';
GRANT ALL PRIVILEGES ON DATABASE topjava TO "user";
```

--------------
### Установка через Docker:
Для работы современного ПО часто требуется большая настроенная инфраструктура: RDBMS, NoSQL, Kafka, RabbitMQ и др. Кроме того, концепция микросервисов подразумевает
запуск каждого сервиса в изолированной среде, их быстрое поднятие и масштабирование. 
Инструмент [Docker](https://ru.wikipedia.org/wiki/Docker) позволяет «упаковать» приложение со всем его окружением и зависимостями в контейнер, который может быть развёрнут на любой Linux-системе, что делает его незаменимым инструментом разработчика.  
Аналогично GitHub, для контейнеров есть репозиторий [DockerHub](https://hub.docker.com/), куда можно публиковать свои контейнеры и откуда можно брать готовые контейнеры со стандартным ПО.
Таким образом Docker служит для:
- Ускорения процесса настройки окружения. Нет нужды в установке сторонних программ вроде PostgreSQL, Redis, Elasticsearch. Они могут быть запущены в контейнерах.
- Удобной инкапсуляция приложений, которые можно представить как единый контейнер, а не набор файлов и инструкций развертывания.
- Одинакового поведения приложений на локальном компьютере и тестовом/прод-сервере.
- Простого и понятного мониторинга.
- Легкого масштабирования. Если вы сделали свое приложение правильно, то оно будет готово к масштабированию не только в Docker.


[**Основы и руководство по Docker**](https://tproger.ru/translations/how-to-start-using-docker/)   
[Docker - понятный туториал](https://badtry.net/docker-tutorial-dlia-novichkov-rassmatrivaiem-docker-tak-iesli-by-on-byl-ighrovoi-pristavkoi/)


##### Для разных ОС установка Docker отличается
- для [Windows без поддержки Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/reference/hyper-v-requirements) требуется Docker Toolbox,
для Windows 10 Pro and Enterprise - Docker Desktop. [Инструкция по проверке виртуализации и установке](https://devconnected.com/how-to-install-docker-on-windows-7-8-10-home-and-pro/)
- На Windows Home можно поставить Docker Desktop, предварительно [установив WSL2 (Windows Subsystem for Linux)](https://docs.microsoft.com/ru-ru/windows/wsl/install)
- Убедитесь, что wsl версии 2: возможно понадобится включить в BIOS виртуализацию (гуглится по материнской плате) и [отключить в Windows гипервизор](https://sysadmintips.ru/kak-vykljuchit-virtualizaciju-hyper-v-windows-10.html#Otklucenie_Hyper-V_v_Windows_10_cerez_Programmy_i_komponenty)
- Команды из cmd/PoswrShell:
```
wsl -l -v : проверить версию
wsl --set-version Ubuntu-20.04 2  : поставить версию 2
wsl : запустить Ubuntu 
```
- [Upgrade version from WSL 1 to WSL 2](https://docs.microsoft.com/en-us/windows/wsl/install#upgrade-version-from-wsl-1-to-wsl-2)
- [Обновление WSL до версии 2](https://docs.microsoft.com/en-us/windows/wsl/install-manual)
```
   sudo service docker status <- проверка статуса
   sudo service docker start  <-старт
   sudo service docker restart <-рестарт
```   
- [Установка для Mac и Linux](https://docs.docker.com/get-started/)
- Установка под Ubuntu: ` sudo apt install docker.io`
  - [How can I use docker without sudo?](https://askubuntu.com/a/477554/1357134)
  
> Docker могут мешать: DrWeb, firewall, анитивирусы

После установки у меня не запускался `Docker Quickstart Terminal`, я запустил Docker Toolbox из `Git Bash`:
- Запустил Git Bash
- Перешел в каталог С:\...\DockerToolbox: `cd /C/../DockerToolbox`
- Запустил `start.sh` 

#### Разворачиваем Postgres:
- загружаем [контейнер с последним postgres](https://hub.docker.com/_/postgres): `docker pull postgres`
- если на локальной машине уже запущен сервис postgres, надо его остановить: для Windows я запустил `C:\Windows\System32\cmd.exe as Admin` и остановил командой `net stop postgresql-x64-10`
- запускаем контейнер с postgres: `docker run -p 5432:5432 -d --name topjava_db -e POSTGRES_USER=user -e POSTGRES_PASSWORD=password -e POSTGRES_DB=topjava postgres`   
  -p: преобразование портов HOST PORT:CONTAINER PORT (или -P: все порты)  
  -d: флаг запускает контейнер в фоновом режиме (как демон)  
  -e: задание переменной окружения   
  --name [имя]: устанавливает имя демона для нового контейнера  

[Основные команды Docker](https://tproger.ru/translations/top-10-docker-commands):
```
docker ps -a : посмотреть все контейнеры
docker stop topjava_db : остановить наш контейнер
docker start topjava_db : запустить его
docker rm topjava_db : удалить
docker help : справка по командам
```

Если Docker установился через Docker Toolbox, он запускается в VirtualBox, необходимо настроить [проброс порта 5432 из VirtualBox на локальную машину](https://losst.ru/probros-portov-virtualbox). Порты можно делать одинаковые: Host Post: 5432, Guets Port: 5432
Проверить postgres порт 5432 можно через
- Unix: `netstat -an |grep 'LISTENING'`
- Windows:  `netstat -an |find /i "listening"`  

Если порт 5432 слушается, можно приконнектится к нему из IDEA, следующее видео.

------------

- <a href="http://habrahabr.ru/post/77909/">Обзор NoSQL систем</a>. <a href="http://blog.nahurst.com/visual-guide-to-nosql-systems">CAP</a>
- <a href="http://db-engines.com/en/ranking">DB-Engines Ranking</a>
- <a href="http://ru.wikipedia.org/wiki/Java_Database_Connectivity">JDBC</a>
- Обзор Java persistence solution без ORM: <a href="http://commons.apache.org/proper/commons-dbutils/">commons-dbutils</a>,
            <a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/data-access.html#jdbc">Spring JdbcTemplate</a>,
            <a href="http://en.wikipedia.org/wiki/MyBatis">MyBatis</a>, <a href="http://www.jdbi.org/">JDBI</a>, <a href="http://www.jooq.org/">jOOQ</a>
- Основы:
  - <a href="https://ru.wikipedia.org/wiki/Реляционная_СУБД">Реляционная СУБД</a>
  - <a href="http://habrahabr.ru/post/103021/">Реляционные базы</a>
  - [Руководство по проектированию реляционных баз данных](https://habr.com/ru/post/193136/)
  - <a href="https://www.youtube.com/playlist?list=PLIU76b8Cjem5qdMQLXiIwGLTLyUHkTqi2">Уроки по JDBC</a>
  - <a href="http://postgresguide.com/">Postgres Guide</a>
  - <a href="http://www.postgresqltutorial.com">PostgreSQL Tutorial</a>
  - <a href="http://java-course.ru/begin/database01/">Базы данных на Java</a>
  - <a href="http://java-course.ru/begin/database02/">Возможности JDBC — второй этап</a>
- Дополнительно:
  - [Документация к PostgreSQL](https://postgrespro.ru/docs/postgrespro)
  - [Книги по PostgreSQL](https://postgrespro.ru/education/books)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 9. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFQWtHYU1qTDlMWVE">Настройка Database в IDEA.</a>
> - Креденшелы к базе Heroku (AWS)  находятся вверху `postgres.properties`. 
> - В новом PostgreSQL для коннекта с базой на Heroku (AWS) добавился параметр `sslmode=require`.
> - В некоторых версиях IDEA необходимо настроить импортируемые схемы (`Schemas -> Current database`)

![image](https://user-images.githubusercontent.com/13649199/60019737-40a08300-9697-11e9-90cf-35675e903a3f.png)
#### Apply 3_11_add_postgresql.patch
-  <a href="http://habrahabr.ru/company/JetBrains/blog/204064/">Настройка Database в IDEA</a> и запуск SQL.

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 10. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFMGNWUXhaVzdlU0k">Скрипты инициализации базы. Spring Jdbc Template.</a>
#### Apply 3_12_db_implementation.patch
> - в `JdbcUserRepository` 
>   - в `getByEmail()` заменил `queryForObject()` на `query()`. Загляните в код: `queryForObject` бросает `EmptyResultDataAccessException` вместо нужного нам `null`.
>   - в `save()` добавил проверку на несуществующей в базе `User.id`
> - в классе `JdbcTemplate` есть настройки (`queryTimeout/ skipResultsProcessing/ skipUndeclaredResults`) уровня приложения (если они будут меняться, то, скорее всего, везде в приложении).
  Мы можем дополнительно сконфигурировать его в `spring-db.xml` и использовать в конструкторах `NamedParameterJdbcTemplate` и в `SimpleJdbcInsert` вместо `dataSource`.

Для запуска скриптов кликнуть правой мышкой на табе скрипта, выбрать Run и в диалоге добавть чз "+" базу

![image](https://user-images.githubusercontent.com/11200258/155393771-3331289b-64bf-4c33-b804-b25d55ffb298.png)
![image](https://user-images.githubusercontent.com/11200258/155394005-6702bd7b-7fa5-411d-93a3-b933c9605211.png)

- Дополнительно:
  - [alishev: Spring Framework. Урок 27: JdbcTemplate](https://www.youtube.com/watch?v=YozbZQ7PxtQ&list=PLAma_mKffTOR5o0WNHnY0mTjKxnCgSXrZ&index=27&ab_channel=alishevalishev)

![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) **Вопрос: почему отображение еды не работает?**

-  Подключение <a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/data-access.html#jdbc">Spring Jdbc</a>.
-  Конфигурирование DataSource. <a href="http://www.mkyong.com/spring/spring-propertyplaceholderconfigurer-example/">Property Placeholder</a>
-  Интеграция `JdbcUserRepository` с DB: [Добавить поддержку DB в JDBC](https://github.com/JavaOPs/topjava/wiki/IDEA#user-content-Добавить-поддержку-db-в-jdbc)

>  Проверьте, что в контекст Spring проекта включены оба файла конфигурации

![image](https://cloud.githubusercontent.com/assets/13649199/24730713/eb21456a-1a6d-11e7-997c-fb4ad728ba45.png)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 11. <a href="https://drive.google.com/open?id=1SPMkWMYPvpk9i0TA7ioa-9Sn1EGBtClD">Тестирование UserService через AssertJ.</a>
#### Apply 3_13_test_UserService.patch
> - В тестах `delete` и `create` проверяю результат напрямую (не через `getAll`)
> - В `UserTestData` добавил вспомогательные `getNew()` и `getUpdated()`
> - При выполнении функционала `create/update` объекты могут измениться, и мы не можем считать их эталонными. Поэтому при сравнении мы создаем эталон еще раз.
> - Поставил `@Ignore` в inmomory тестах

- [Tutorial: testing with AssertJ](http://www.vogella.com/tutorials/AssertJ/article.html)
- [Spring Testing Annotations](https://docs.spring.io/spring/docs/4.3.x/spring-framework-reference/htmlsingle/#integration-testing-annotations-spring)
- [The JPA hashCode() / equals() dilemma](https://stackoverflow.com/questions/5031614/548473)
- [Hibernate: implementing equals() and hashCode()](https://docs.jboss.org/hibernate/orm/current/userguide/html_single/Hibernate_User_Guide.html#mapping-model-pojo-equalshashcode)
- [Junit Matcher for comparators](https://stackoverflow.com/questions/17949752/548473)
- [AssertJ custom comparison strategy](http://joel-costigliola.github.io/assertj/assertj-core-features-highlight.html#custom-comparison-strategy). [AssertJ field by field comparisons](http://joel-costigliola.github.io/assertj/assertj-core-features-highlight.html#field-by-field-comparison)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 12. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFVmZaSm9UMktXUnc">Логирование тестов.</a>
#### Apply 3_14_test_logging.patch
> - Новый PostgreSQL JDBC Driver [логирует через java.util.logging](https://github.com/pgjdbc/pgjdbc#changelog).  [Направил логирование в SLF4J](http://stackoverflow.com/a/43242620/548473)
> - Поменял формат вывода. См. [Logback Layouts](https://logback.qos.ch/manual/layouts.html)

- Ресурсы, которые кладутся в classpath, maven при сборке берет из определенных каталогов `resources` ([Introduction to the Standard Directory Layout](https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html)). Их можно настраивать через [maven-resources-plugin](https://maven.apache.org/plugins/maven-resources-plugin/examples/resource-directory.html), меняем в проекте Masterjava.

#### Apply 3_15_fix_servlet.patch
**Приложение перестало работать, тк. для репозитория мы используем заглушку `JdbcMealRepository`**

## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы
> Что такое REST?

Коротко посмотрите тут: [понимание REST](http://spring-projects.ru/understanding/rest/). Более подробно мы будем разбирать этот архитектурный стиль API на 7-ом занятии.
 
> Какая разница между @BeforeClass and @Before? 

`@BeforeClass` выполняется один раз после загрузки класса (поэтому метод может быть только статический), `@Before` перед каждым тестом.
Также: для чистоты тестов экземпляр тестового класса [пересоздается перед каждым тестом](http://stackoverflow.com/questions/6094081/548473)

> Тесты в классе в каком-то определенном порядке выполняются ("сверху вниз" например)?

Порядок по умолчанию неопределен, каждый тест должен быть автономен и не зависеть от других. [См. также "How to run test methods in specific order in JUnit4?"](http://stackoverflow.com/questions/3693626/548473) 

> Обязательно ли разворачивать postgreSQL?

Желательно: хорошая и надежная ДБ:) Если совсем не хочется - можно работать со своей любимой RDBMS (поправить `initDB.sql`) или работать c postgresql в heroku (креденшелы к нему есть сверху в `postgres.properties`). На следующем уроке добавим HSQLDB, она не требует установки.

> Зачем начали индексацию с 100000?

Так удобно вставлять в базу (если будет потребность) записи вручную не мешая счетчику. Но это не общий принцип, часто нумерация идет с 1.

> Из 5-го видео - "Логика в базе - большое зло". Можно чуть поподробней об этом?

- Есть успешные проекты с логикой в базе. Те все относительно.
- Логика в базе - это процедуры и триггеры. Нет никакого ООП, переиспользовать код достаточно сложно, никагого рефакторинга, поиска по коду и других плюшек IDE. Нельзя делать всякие вещи типа кэширования, хранения в сессии - это все для логики на стороне java. Например json можно напрямую отдать в процедуру и там парсить и вставлять в таблицы или наоборот - собирать из таблиц и возвращать.
А затем потребуется некоторая логика на стороне приложения и все равно придется этот json дополнительно парсить в java.
Я на таком проекте делал специальную миграцию, чтобы процедуры мигрировать не как sql-скрипты, а каждую процедуру хранить как класс с историей изменений. Если логика: триггеры и простые процедуры записи-чтения, которые не требуют переиспользования кода или
проект небольшой - это допустимо, иначе проект становится трудно поддерживать. Также иногда используют [View](http://postgresql.men/gruber/ch20.html) для разграничения доступа. Например, для финансовых систем, таблицы проводок доступны только  для админ учеток, а View просто не дадут увидеть (тем более изменить) данные обычному оператору на уровне СУБД.

> У JUnit есть ассерты и у спринга тоже. Можно ли обойтись без JUnit?

Предусловия Spring `Assert` и JUnit-тесты совершенно разные вещи, один другого не заменит. У нас будут предусловия в следующем уроке.

> Я так понял, что при работе с небольшими записями, VARCHAR быстрее, чем TEXT. Наши записи будут небольшими (255). Почему вы приняли решение перейти на TEXT?

В отличие от MySql, в Postgres  [VARCHAR и TEXT - тоже самое](https://stackoverflow.com/questions/4848964/548473) 

> Зачем при создании таблицы мы создаем `CREATE UNIQUE INDEX` и `CREATE INDEX`. При каких запросах он будет использоваться?

UNIQUE индекс нужен для обеспечения уникальности, DB не даст сделать одинаковый индекс. Индексы используется для скорости выполнения запросов. Обычно они используются, когда в запросе есть условия, на которые сделан индекс. Узнать по конкретному запросу можно  запросив план запроса: см. <a href="https://habrahabr.ru/post/203320">Оптимизация запросов. Основы EXPLAIN в PostgreSQL</a>. На измерение производительности с индексами посмотрим в следующем уроке.

> А это нормально, что у нас в базе у meals есть userId, а в классе - нет?

Ненормально, когда в приложении есть "лишний" код, который не используется. Для ORM он нам понадобится - добавим `Meal.user`.

> Почему мы делаем один sequence на разные таблицы?

Мы будем использовать Hibernate. По умолчанию он делает глобальный sequence на все таблицы. В этом подходе есть [как плюсы, так и минусы](http://stackoverflow.com/questions/1536479/548473).

> Каким образом попадают в тесты классы, расположенные в каталоге `test`, если в конфигурации спринга нет указание на ее сканирование?

Сканируются не папки, а пакеты. Обычно тесты классов располагают в том же самом пакете каталога `test`. Таким образом тесты могут видеть поля классов `main` с видимостью по умолчанию (внутри пакета). При этом классы `test` видят `main`, а наоборот нет. Когда приложение деплоится, в коде тестов быть не должно!

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW03
- 1 Понять, почему перестали работать `SpringMain, InMemoryAdminRestControllerTest, InMemoryAdminRestControllerSpringTest`. Чиним в Optional.
- 2 Дополнить скрипты создания и инициализации базы таблицей `meals`. Запустить скрипты на вашу базу (через Run). Порядок таблиц при DROP и DELETE важен, если они связаны внешними ключами (foreign key, fk). Проверьте, что ваши скрипты работают.
   - 2.1 Сделать индексы к таблице `meals`: запретить создавать у одного и того-же юзера еду с одинаковой dateTime.
Индекс на pk (id) postgres создает автоматически: [Postgres and Indexes on Foreign Keys and Primary Keys](http://stackoverflow.com/questions/970562/548473)
  - [Индекс_базы_данных](https://ru.wikipedia.org/wiki/Индекс_(базы_данных))
  - [PostgreSQL: индексы](https://postgrespro.ru/docs/postgresql/10/indexes-intro)
  - [Postgres Guide: Indexes](http://postgresguide.com/performance/indexes.html)
  - [Оптимизация запросов. Основы EXPLAIN в PostgreSQL](https://habrahabr.ru/post/203320/)
  - [Оптимизация запросов. Часть 2](https://habrahabr.ru/post/203386/)
  - [Оптимизация запросов. Часть 3](https://habrahabr.ru/post/203484/)

> ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Как правильно придумать индекс для базы? Указать в нем все поля, комбинация которых создает по смыслу уникальную запись, или какие-то еще есть условия?

Индекс нужно делать по тем полям, по которым будут искаться записи (участвуют в WHERE, ORDER BY). Уникальность - совсем необязательное условие. Индексы ускоряют поиск по определенным полям таблицы. Они не бесплатные (хранятся в памяти, замедляется вставка), поэтому на всякий случай их делать не надо. Также не строят индексы на колонки с малым процентом уникальности (например поле "М/Ж"). Поля индекса НЕ КОММУТАТИВНЫ и порядок полей в описании индекса НЕОБХОДИМО соблюдать (в силу использования B-деревьев и их производных как поисковый механизм индекса). При построении плана запроса EXPLAIN учитывается количество записей в базе, поэтому вместо индексного поиска (Index Scan) база может выбрать последовательный (Seq Scan). Проверить, работают ли индексы можно <a href="http://stackoverflow.com/questions/14554302/548473">отключив Seq Scan</a>. Также см. <a href="https://dba.stackexchange.com/a/27493/3684">Queries on the first field of composite index</a>

- 3 Реализовать через Spring JDBC Template `JdbcMealRepository`
  - 3.1. сделать каждый метод за один SQL запрос
  - 3.2. `userId` в класс `Meal` вставлять НЕ надо, делаем _foreign key_ только в базе (для UI и REST это лишние данные, userId это id залогиненного пользователя)
  - 3.3. `JbdcTemplate` работает через сеттеры. Вместе с конструктором по умолчанию их нужно добавить в `Meal` 
  - 3.4. Список еды должен быть отсортирован (тогда мы его сможем сравнивать с тестовыми данными). Кроме того это требуется для UI и API: последняя еда наверху.
- 4 Проверить работу MealServlet, запустив приложение

### Optional
- 5 Сделать `MealServiceTest` из `MealService` и реализовать тесты для `JdbcMealRepository`.
> По `Ctrl+Shift+T` (выбрать JUnit4) можно создать тест для конкретного класса, выбрав для него нужные методы. Тестовый класс создастся в папке `test` в том же пакете, что и тестируемый. 
  - 5.1 Сделать тестовые данные `MealTestData` (точно такие же, как вставляем в `populateDB.sql`).
  - 5.2 Сделать тесты на чужую еду (delete, get, update) с тем, чтобы получить `NotFoundException` и `duplicateDateTimeCreate`, аналогичный `duplicateMailCreate`.
- 6 Починить `SpringMain, InMemory*Test`. **InMemory тесты должны использовать реализацию в памяти**

----------------------------
### Итоги занятия после выполнения ДЗ:
Наше приложение стало хранить данные в PostgreSQL.   
Добавили в приложение JUnit тесты.  
Разделили Spring контекст для работы с памятью и с БД. 

----------------------------

### ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Решение проблем

> Из каталога `main` не видятся классы/ресурсы в `test`

Все что находится в `test` используется только для тестов и недоступно в основном коде.  

> Из `IDEA` не видятся ресурсы в каталоге `test`

- Сделайте Reimport All в Maven окне

![image](https://cloud.githubusercontent.com/assets/13649199/18831806/7e43bedc-83f0-11e6-97db-67d4e1a7599f.png)

> В UserService и MealService подчеркнуты красным repository, ошибка: Could not autowire. There is more than one bean of 'MealRepository' type.

- Spring test контекст не надо включать в Spring Facets проекта, там должны быть только `spring-app.xml` и `spring-db.xml`. Для тестовых контекстов поставьте чекбокс `Check test files` в Inspections. 

![image](https://cloud.githubusercontent.com/assets/13649199/18831817/8a858f22-83f0-11e6-837e-bf5317b33b3a.png)

### ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Типичные ошибки и подсказки по реализации

- 1: В `MealTestData` еду делайте константами. Не надо `Map` конструкций!
- 2: SQL case-insensitive, **не надо писать в стиле Camel**. В POSTGRES возможны case-sensitive значения, их надо в кавычки заключать (обычно не делают).
- 3: ЕЩЕ РАЗ: `InMemory` тесты должны идти на `InMemory` репозитории
- 4: **Проверьте, что возвращает `JdbcMealRepository` при обновлении чужой еды**
- 5: В реализации `JdbcMealRepository` одним SQL запросом используйте возвращаемое `update` значение `the number of rows affected`
- 6: При тестировании не портите эталонные тестовые объекты из `MealTestData`
- 7: Проверьте, что все, что относится к тестам, находится в каталоге `test` (не попадает в сборку проекта)
- 8: **Еще раз: в тестах нельзя сравнивать объекты через `JUnit Assert` и `assertThat().isEqualTo`, потому что в этом случае сравнение будет происходить через `AbstractBaseEntity.equals`, который сравнивает объекты только по `id`. Мы не можем переопределять `equals` для объектов модели, тк будем использовать JPA (см. [The JPA hashCode() / equals() dilemma](https://stackoverflow.com/questions/5031614/548473))**
- 9: НЕ делайте склейку SQL запросов вручную из параметров, только через `jdbcTemplate` параметры! См. [Внедрение_SQL-кода](https://ru.wikipedia.org/wiki/Внедрение_SQL-кода)
- 10: Напомню: `BeanPropertyRowMapper` работает через отражение. Ему нужны геттеры/сеттеры и имена полей должны "совпадать" с колонками `ResultSet` (Column values are mapped based on matching the column name as obtained from result set metadata to public setters for the corresponding properties. The names are matched either directly or by transforming a name separating the parts with underscores to the same name using "camel" case).
- 11: Для разделения тестов InMemory и Jdbc можно использовать разные Spring context. В том числе переопределять контест для тестов в `src\test\resources`
- 12: Обязательно протестируйте в `MealServiceTest` нормальное поведение методов (по аналогии с `UserServiceTest`)

# Стажировка <a href="https://github.com/JavaWebinar/topjava">Topjava</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFfkxqbVpwZUd5anQ2TXE4bm5HbXhtVmkxMUxFSjhNQ1hXYVVTTTZEMzkzN2s">Материалы занятия</a>

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW3

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. [HW03: meals + JdbcMealRepository](https://drive.google.com/file/d/1_IIYBP5l2aHxHaY_j1bqFWj1maACvNpa)
- [Последовательность столбцов в составном индексе](https://ru.wikipedia.org/wiki/Индекс_(базы_данных)#Последовательность_столбцов_в_составном_индексе)
- Дополнительно: для `JdbcMealRepository.save` можно использовать [CombinedSqlParameterSource](https://stackoverflow.com/questions/13339171/548473)
- В ответе на [Why is SELECT * considered harmful?](https://stackoverflow.com/questions/3639861) есть случаи, когда она допустима (наш случай): `when "*" means "a row"`

#### `SpringMain, InMemoryAdminRestControllerTest, InMemoryAdminRestControllerSpringTest` починим в патче `4_7_create_inmemory_test_ctx` (видео 4)

#### **Apply 4_1_HW3.patch**]()

### [Сравнение времени выполнения для разных индексов](meals_index.md)
- <a href="http://stackoverflow.com/questions/970562/postgres-and-indexes-on-foreign-keys-and-primary-keys">На id как на primary key индекс создается автоматически</a>
- Все запросы в таблицу meals у нас идут с `user_id`
- По полю `date_time` не только есть запросы, но и сортируем результат. То есть это поле - хороший кандидат для индексирования
- Следует иметь в виду, что индексы ускоряют операции чтения, но замедляют вставку и удаление. Поэтому необходим анализ в реальном приложении
- [Оптимизация запросов. Основы EXPLAIN в PostgreSQL](https://habrahabr.ru/post/203320/)
- [Оптимизация запросов. Часть 2](https://habrahabr.ru/post/203386/)
- [Оптимизация запросов. Часть 3](https://habrahabr.ru/post/203484/)
- [Документация Postgres: индексы](https://postgrespro.ru/docs/postgresql/9.6/indexes.html)

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW3

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. [HW03 Optional: Meals tests](https://drive.google.com/file/d/1RfO0Irz8ayw2ivnjffUol20BQrKpu-jg)

#### **Apply 4_2_HW3_optional.patch**
> Убрал `throws Exception` из тестов. IDEA по умолчанию перестала их добавлять.
> В `MealServiceTest.updateNotOwn` добавил дополнительную проверку, что еда в тесте не модифицировалась.

#### **Apply 4_3_tests_refactoring.patch**
> - Переименовал класс генерации матчеров в `MatcherFactory`
> - Переименовал статический метод генерации ([Блох Джошуа, "Java. Эффективное программирование."](http://javaops.ru/view/books)) на `usingIgnoringFieldsComparator`.

#### **Apply 4_4_HW3_fix_logging.patch**
- [Вызов статического метода из конфигурации спринга](https://stackoverflow.com/a/27296470/548473) 

## Занятие 4:
### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFU005ZzBNZmZnTVU">Методы улучшения качества кода</a>

#### Поменяйте в `readme.md` сверху ссылку на свой `Codacy Badge` с сайта Codacy: `https://app.codacy.com/gh/[github_accaunt]/topjava/settings`

> - Плагины проверки качества кода теперь объединены в один **QAPlug**
> - <a href="https://www.codacy.com">Codacy Check code</a> (проверка стиля и поиск багов в коде).
>    - добавил [Codacy configuration file](https://support.codacy.com/hc/en-us/articles/360005097654-Ignore-files-from-Codacy-analysis) для исключения из проверок содержимого `webapp` и `READ.me` (на нашем проекте он выдает на них кучу ошибок)
>    - после правок паттернов можно сделать [повторный анализ](https://support.codacy.com/hc/en-us/articles/213840489-How-do-I-reanalyze-my-project-), с результатами тормозит  

#### Сделайте `push` для отображения результатов текущего состояния проекта.

#### **Apply 4_5_improve_code.patch**
> - Добавил проверки предусловий `Assert.notNull` в сервисы
> - Добавил конфигурацию `.codacy.yml`
> - Ввел удобный метод `AbstractBaseEntity.id()`
 
- <a href="https://ru.wikipedia.org/wiki/Контрактное_программирование">Контрактное программирование</a>, <a href="http://neerc.ifmo.ru/wiki/index.php?title=Программирование_по_контракту">Программирование по контракту</a>
- <a href="https://www.sw-engineering-candies.com/blog-1/comparison-of-ways-to-check-preconditions-in-java">Comparison Preconditions in Java</a>
- IDEA Settings -> Plugins -> Browse repositories... Add [QAPlug: PMD/FindBugs/Checkstyle/Hammurapi](https://qaplug.com/about/)
  - Tools -> QAPlug -> Analyze Code...
- IDEA [Analyze | Inspect Code](https://www.jetbrains.com/help/idea/running-inspections.html)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4. <a href="https://drive.google.com/open?id=1faq0dtek-RcBENfISkod35PGU5jcuOsB">Spring: инициализация и популирование DB</a>
#### **Apply 4_6_init_and_populate_db.patch**
-  [Инициализация базы при старте приложения](https://docs.spring.io/spring/docs/current/spring-framework-reference/data-access.html#jdbc-initializing-datasource-xml)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFNTNWV04weDBGSmc">Подмена контекста при тестировании</a>
#### **Apply 4_7_create_inmemory_test_ctx.patch**
> Переименовал `mock.xml` в `inmemory.xml`

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 6. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFVWZYcHoyUF9qX2M">ORM. Hibernate. JPA.</a>
![image](https://user-images.githubusercontent.com/13649199/139490982-0e8d6a6a-f1b6-4db0-8c61-f49f2056c274.png)

<a href="https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model">Entity</a>- класс (объект Java), который в ORM маппится в таблицу DB.
> - Убрал дублирование объявления `unique` для `User.email`

[EntityManager](https://jsehelper.blogspot.com/2016/04/java-persistence-api-jpa-2.html) - это по сути прокси-обертка над Hibernate Session, которая создается каждый раз при открытии транзакции.

- ВНИМАНИЕ: патч меняет `postgres.properties`, в котором у вас, возможно, свои креденшелы к базе
- `hibernate-core` с 5.2.x включает `hibernate-entitymanager` и `hibernate-java8`, то есть конверторы Time API уже не нужны
>    -  <a href="http://stackoverflow.com/questions/23718383/jpa-support-for-java-8-new-date-and-time-api">JPA support for Java 8 new date and time API</a>
>    -  <a href="http://stackoverflow.com/questions/31965179/whats-new-in-hibernate-5">What's new in Hibernate 5?</a>
>    -  <a href="http://stackoverflow.com/a/33001846/548473">JPA support for Java 8 new date and time API</a>
- [EL implementation provided by the container. In a Java SE you have to add an implementation as dependency to your POM file](http://hibernate.org/validator/documentation/getting-started/#unified-expression-language-el): добавил `javax.el` зависимость со `scope=provided`

#### **Apply 4_8_add_jpa.patch**
> - **[Настройка JPA в IDEA](https://github.com/JavaOPs/topjava/wiki/IDEA#jpa).   
ПРОВЕРЬТЕ, что у вас не подтянулись Java EE libraries, все зависимости в проект попадают только через Maven! Перед настройкой сначала подтяните его зависимости**
> - `indexes` и `uniqueConstraints` в Entities (у нас `User`) используются только при создании таблицы средствами JPA (автогенерации БД при запуске приложения).
 В случае, если таблицы создаются скриптом, эти опции будут проигнорированы. У нас они дублируют ограничения в `initDB.sql` и будут использоваться, когда мы будем смотреть на автогенерацию DDL по модели на 7-м занятии. 
> - Тесты и приложение ломаются. `MealServiceTest` починится после выполнения HW04 (`JpaMealRepository`)
> - Если вы используете Java 9 и выше, то возникают проблемы с `JAXBException` (пакет `java.xml.bind`). [См. решение](https://www.concretepage.com/forum/thread?qid=531

- [JPQL в JPA](https://russianblogs.com/article/74321542380/)
- Дополнительно:
  -  [ORM](http://ru.wikipedia.org/wiki/ORM)
  -  [JPA и Hibernate в вопросах и ответах](http://habrahabr.ru/post/265061/)
  - [Hibernate — о чем молчат туториалы](https://habr.com/ru/post/416851/)
  - [Наследование в Hibernate: выбор стратегии](https://habrahabr.ru/post/337488/)
  - [Entity Lifecycle Model in JPA & Hibernate](https://thorben-janssen.com/entity-lifecycle-model/)
    - [Field vs property access](http://stackoverflow.com/a/6084701/548473)
    - [Hibernate: введение и написания Hello world приложения](https://web.archive.org/web/20200810114404/http://www.quizful.net/post/Hibernate-3-introduction-and-writing-hello-world-application)
    - [15 reasons why we need to choose Hibernate over JDBC](https://web.archive.org/web/20211201122631/https://habiletechnologies.com/blog/reasons-to-choose-hibernate-over-jdbc/#fin_form_pop)
    - [Hibernate or JDBC](https://stackoverflow.com/questions/1353137/548473)
    -  [Mapping: описание модели Hibernate (hbm.xml/annotation)](http://en.wikibooks.org/wiki/Java_Persistence/Mapping).
    -  [used in Playframework](https://ru.wikipedia.org/wiki/Hibernate_(библиотека)">Hibernate). Другие ORM: [TopLink](http://en.wikipedia.org/wiki/TopLink), [EсlipseLink](http://en.wikipedia.org/wiki/EclipseLink)
    -  [Jakarta Persistence (JPA, english wiki)](https://en.wikipedia.org/wiki/Java_Persistence_API)
    -  [Стратегии генерации PK](http://en.wikibooks.org/wiki/Java_Persistence/Identity_and_Sequencing)
    -  [hibernate-validator](http://validator.hibernate.org).
    -  [Описание связей в модели. Ленивая загрузка объекта.](https://web.archive.org/web/20170514002949/http://java.devcolibri.com:80/post/15)
    -  [JPA definitions](http://docs.jboss.org/hibernate/entitymanager/3.6/reference/en/html/architecture.html#d0e61)
    -  [Spring expressions: выражения в конфигурации](https://docs.spring.io/spring/docs/current/spring-framework-reference/core.html#expressions)
    -  [HQL](https://proselyte.net/tutorials/hibernate-tutorial/hibernate-query-language), [JPQL](http://ru.wikipedia.org/wiki/Java_Persistence_Query_Language)
    -  Динамические запросы (которые формируются в коде): [Unified Queries for Java](http://www.querydsl.com/), [JPA Criteria API](http://www.objectdb.com/java/jpa/query/criteria)
    -  [Using the Java 8 Date Time Classes with JPA](https://web.archive.org/web/20170608194049/https://bitbucket.org/montanajava/jpaattributeconverters)

#### **Apply 4_9_add_named_query_and_transaction.patch**
> Чтобы посмотреть информацию о транзакциях (открытие/закрытие и пр.), можно выставить в конфигурации logback 
`<logger name="org.springframework.orm.jpa.JpaTransactionManager" level="debug"/>`

-  <a href="http://ru.wikipedia.org/wiki/Транзакция_(информатика)">Транзакция. ACID. Уровни изоляции транзакций.</a>
-  <a href="http://www.tutorialspoint.com/spring/spring_transaction_management.htm">Spring Transaction Management</a>
-  <a href="http://habrahabr.ru/post/232381/">`@Transactional` в тестах. Настройка EntityManagerFactory</a>
-  [Эффективное управление транзакциями в Spring](https://habr.com/ru/company/otus/blog/431508/)

> ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png)  Зачем надо начинать транзакцию, если речь идет только о чтении данных? Начало транзакции при выполнении операции чтения всего лишь добавит лишних накладных расходов 
(см. [Стратегии работы с транзакциями, pаспространенные ошибки](http://web.archive.org/web/20170314073834/https://www.ibm.com/developerworks/ru/library/j-ts1/index.html))

Вот ответ от Oliver Drotbohm, автора Spring-Data на предложение работать без транзакций для операций чтения (`propagation=Propagation.SUPPORTS`): [Improve performance with Propagation.SUPPORTS for readOnly operation](https://jira.spring.io/browse/DATAJPA-601). Коротко:
- Статья устаревшая и неверно упрощает многие вещи. Есть множество вещей, которые влияют на производительность
- Без транзакции не будет оптимизации по флагу `readOnly` при выполнении JDBC и в управлении ресурсами Spring's JPA (в том числе выключение `flush`)
См. [Non-transactional data access and the auto-commit mode](https://developer.jboss.org/wiki/Non-transactionalDataAccessAndTheAuto-commitMode)

Справочник:
   - <a href="https://www.youtube.com/watch?v=dFASbaIG-UU">Видео: Вячеслав Круглов — Как начинающему Java-разработчику подружиться со своей базой данных?</a>
   - <a href="http://www.youtube.com/watch?v=YzOTZTt-PR0">Видео: Николай Алименков — Босиком по граблям Hibernate</a>
   - <a href="https://www.youtube.com/watch?v=b52Qz6qlic0">Видео: Николай Алименков — Сделаем Hibernate снова быстрым</a>
   - <a href="https://www.ibm.com/developerworks/ru/library/j-ts2/">Стратегии работы с транзакциями</a>
   - <a href="http://www.byteslounge.com/tutorials/spring-transaction-propagation-tutorial">Spring transaction propagation tutorial</a>
   - <a href="https://dzone.com/refcardz/getting-started-with-jpa">Getting Started with JPA</a>
   - <a href="http://en.wikibooks.org/wiki/Java_Persistence">Java Persistence</a>
   - <a href="https://web.archive.org/web/20220519045236/https://easyjava.ru/category/data/jpa/">Разделы по Java Persistence API</a>
   - <a href="http://docs.spring.io/spring-framework/docs/4.0.x/spring-framework-reference/html/transaction.html">Spring Framework transaction management</a>
   - <a href="http://www.baeldung.com/persistence-with-spring-series/">Spring Persistence Tutorial</a>
   - <a href="http://www.objectdb.com/java/jpa/persistence/managed#Entity_Object_Life_Cycle">Working with JPA Entity Objects</a>
   - <a href="http://habrahabr.ru/post/208400/">Принципы работы СУБД. MVCC</a>
   - <a href="https://ru.wikipedia.org/wiki/MVCC">MVCC</a>


###  ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 7. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFSTJEQ1Rvd3Jvc2c">Добавляем поддержку HSQLDB</a>

#### **Apply 4_10_add_hsqldb.patch**
> - Переделал `jdbc.initLocation`: IDEA не "тупит", если путь к скрипту полностью прописывать в пропертях.    

## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы

>  Есть несколько аналогичных "встроенных" баз данных. H2, HSQLDB, Derby, SQLite. Почему был выбран HSQLDB?

Просто с ней приходилось работать. HSQLDB и H2 наиболее популярны. В миграции на spring-boot будем использовать H2.
Здесь интересное краткое описание <a href="https://web.archive.org/web/20220519045402/https://easyjava.ru/data/vstraivaemye-bazy-dannyx-v-java/">встраиваемых баз данных в Java</a>. 
В HSQLDB нет репликаций, кластеризации и объем данным ограничен несколькими TB. Для большого количества приложений она подходит и для продакшена. См.
- <a href="http://stackoverflow.com/questions/4152911/what-is-hsqldb-limitations">What is HSQLDB limitations?</a>
- <a href="https://habrahabr.ru/sandbox/23199/">HSQLDB в режиме in-process</a>

> Чистого JPA не существует, т. е. это всего лишь интерфейс, спецификация? Говорим JPA, подразумеваем какой-то ORM фрэймворк? А что тогда используют чистый jdbc, Spring-jdbc, MyBatis? MyBatis не реализует JPA?

<a href="https://ru.wikipedia.org/wiki/ORM">ORM</a> это технология связывания БД и объектов приложения, а <a href="https://ru.wikipedia.org/wiki/Java_Persistence_API">JPA</a> - это JavaEE спецификация (API) этой технологии.
Реализации JPA - Hibernate, OpenJPA, EclipceLink, но, например, Hibernate может работать по собственному API (без JPA, которая появилась позже). Spring-JDBC, MyBatis, JDBI не реализуют JPA - это обертки к JDBC. Все ORM и JPA также реализованы поверх JDBC.

> В зависимостях maven `hibernate-entitymanager` тянет за собой `jboss-logging`. Как будет происходить логирование?

<a href="http://stackoverflow.com/questions/11639997/how-do-you-configure-logging-in-hibernate-4-to-use-slf4j">How do you configure logging in Hibernate 4 to use SLF4J</a>: в нашем проекте автоматически подхватывается `logback-classic`.

> В чем преимущество Hibernate?

Hibernate (как любая ORM) реализует мапинг таблиц в объекты Java. Когда мы добавим роли пользователю, вы увидите, насколько код будет проще, чем в jdbc. Также см. <a href="https://www.sitepoint.com/5-reasons-to-use-jpa-hibernate/">5 Reasons to Use JPA / Hibernate</a>

> Чем отличается `@Column(nullable = false)`  от  `@NotNull` и есть ли необходимость указывать обе аннотации ?

`@Column(nullable = false)` - это атрибуты колонки таблицы базы. `@NotNull` - это валидация, которая происходит в приложении перед вставкой в базу. Если колонка ненулевая, то `NOT NULL` обязательна. Валидация опциональна. Также см.
<a href="http://stackoverflow.com/questions/7439504/">@NotNull vs @Column(nullable = false)</a>

> почему мы в бине `entityManagerFactory` не указали диалект базы данных?

Он [автоматически определяется из `DataSource` драйвера](http://stackoverflow.com/a/39817822/548473)

> В чем разница между `persist` и `merge`

<a href="http://stackoverflow.com/questions/1069992/jpa-entitymanager-why-use-persist-over-merge">Подробный ответ со Stackoverflow</a> с объяснением разницы. Упрощенно:
  - `merge`, в отличие от `persist`, делает запрос в базу данных, если entity нет в текущей сессии
  - entity, переданный в `merge`, не меняется. Нужно использовать возвращаемый результат

> `em.merge` при отсутствии старой записи (несуществующий `id`) создает новую. Т. е. в `JpaUserRepository` нарушается логика

В Hibernate есть такая бага: https://hibernate.atlassian.net/browse/HHH-1661, https://stackoverflow.com/questions/34249483
- [Hibernate unexpectedly issues INSERT instead of throwing the javax.persistence.OptimisticLockException, when a nonexistent entity is passed to merge()](https://stackoverflow.com/questions/34249483)
- [Should Hibernate Session#merge do an insert when receiving an entity with an ID?](https://stackoverflow.com/questions/21489300)

Если это действительно наш критичный бизнес-кейс (например, с многопоточным удалением entity), то нужно искать варианты обходного решения.
Если это не бизнес-кейс (попытка поломать или ошибка UI), то оставляем как есть (обычно на практике не парятся).

> Почему в проекте транзакционность сделана в слое репозитория, а не сервиса? Транзакциями удобнее пользоваться на слое сервисов, так как здесь  реализуется бизнес логика и бывает нужно делать несколько операций в одной транзакции.

С классической точки зрения все транзакции действительно объявляются на уровне сервиса. Мы будем использовать в логике сервиса несколько запросов и тогда сделаем дополнительную транзакцию на методе сервисе. Новая транзакция при этом не создается (по умолчанию используется `Propagation.REQUIRED`, который поддерживают существующую), поэтому несколько `@Transactional` аннотаций ведут себя как одна. Я использую подход `spring-data-jpa` (будет на следующем занятии): в репозитории транзакции объявлять удобно, тк не надо думать о них в сервисах.

--------------------

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW4

- 1: Сделать из `Meal` Hibernate entity
  - <a href="http://stackoverflow.com/questions/17137307">Hibernate Validator: @NotNull, @NotEmpty, @NotBlank</a>
  - <a href="https://en.wikibooks.org/wiki/Java_Persistence/ManyToOne">Реализация ManyToOne</a>
- 2: Имплементировать и протестировать `JpaMealRepository`. Проверьте, нет ли в запросах ненужных данный (лишних `JOIN`)

### Optional

- 3: Добавить в тесты `MealServiceTest` функциональность `@Rule`:
  - 3.1: вывод в лог времени выполнения каждого теста
  - 3.2: вывод сводки в конце класса: имя теста - время выполнения
-  <a href="https://github.com/junit-team/junit/wiki/Rules">JUnit @Rules</a>

---------------------
### ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Типичные ошибки и подсказки по реализации
-  1: Т.к. JPA работает с объектами, мы не можем использовать `userId` для сохранения. Можно сделать, например, так:

        User ref = em.getReference(User.class, userId);
        meal.setUser(ref);

   При этом от `User` нам нужен только `id`. Над `id` создается lazy прокси, который обращается к базе при запросе любого поля. Т. е. у нас запроса в базу за юзером не будет: проверьте по логам Hibernate.

**Внимание: проверять запросы Hibernate нужно через run. Если делаете debug и брекпойнт, то могут делаться лишние запросы к базе (дебаггер дергает `toString`)**
   
- 2: В JPQL запросах можно писать: `m.user.id=:userId`
- 3: При реализации `JpaMealRepository` предпочтительно не использовать `try-catch` в логике реализации. Но, если очень хочется, то ловить только специфические исключения (напр. `NoResultException`), чтобы, например, при отсутствии коннекта к базе приложение отвечало адекватно.
- 4: Мы будем смотреть генерацию db-скриптов из модели. Для корректной генерации нужно в `Meal` добавить `uniqueConstraints`
- 5: При записи в базу через `namedQuery` валидация энтити не работает, только валидация в БД.
- 6: Результат `AssertionError` печатает результаты через `toString`, и поля в выводе могут не совпадать с полями сравнения (`toString` одинаковый, при этом сравнение идет по другим полям и вылетает ошибка)
- 7: Если нашему приложению `Meal.user` не требуется, не следует включать его в тесты. В следующем уроке мы потренируемся разными способами доставать зависимости `Meal.user` и `User.meals`

--------------------------------
## [Выпускной проект](graduation.md)
Новая информация плохо оседает в голове, когда дается в виде патчей. Поэтому, чтобы она стала "твоей", нужно еще раз проделать это самостоятельно. Домашнее задание на этом уроке небольшое, а полученных знаний уже достаточно для начала работы над выпускным проектом, основанным на нашем стеке.
Выпускной проект делайте параллельно с нашим: прошли тему занятия - сделали ее в выпускном. Не следует забегать вперед, но и не отставайте!
- Для проекта я взял реальное тестовое задание, поэтому жалоб на неясность формулировок принимать не буду. Сделайте как поняли. Представьте, что это **ваше тестовое задание на работу**
- Общение по выпускному в канале Slack *#graduation*
- **Обязательно проверяйся [по рекомендациям в конце выпускного](graduation.md#-Рекомендации)**
- По завершению вы сможете занести этот проект в свое портфолио и резюме как собственный без всяких оговорок

### Успехов в выполнении!

# Стажировка <a href="https://github.com/JavaWebinar/topjava">Topjava</a>
## <a href="https://drive.google.com/drive/folders/0B9Ye2auQ_NsFfmctT3oyNW1qaVhDb2p0bGpyTFVlaUJ2VVpOdVgtWF9KTUFBMWFaR2xVYVE">Материалы занятия</a>

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. [Обзор JDK 9/11. Миграция Topjava с 1.8 на JDK 17+](http://javaops.ru/view/resources/jdk8+)
### Выбрать можно любую версию 17+. Для JDK 17+ обновите IDEA на последнюю версию и Tomcat на 9.x
> - Проект обновил до JDK 17+. Для запуска Maven или Tomcat переопредели переменную окружения `JAVA_HOME` и переменную `path` на `JAVA_HOME\bin`, чтобы  `java -version` тоже было 17+. Напомню, что IDEA это java процесс. Чтобы новые переменные окружения в ней увиделись, требуется ее перегрузить.

- [API, ради которых наконец-то стоит обновиться с Java 8 (1)](https://habr.com/ru/post/485750)
- [API, ради которых наконец-то стоит обновиться с Java 8 (2)](https://habr.com/ru/post/487636)
- [Руководство по возможностям Java версий 8-16](https://habr.com/ru/post/551590/)

**ВНИМАНИЕ: патч меняет `pom.xml`. Если у вас JDK>1.8 и вы его меняли самостоятельно - [сверьтесь с репозиторием](https://github.com/JavaOPs/topjava/wiki/git#user-content-compare)**
#### Apply 5_1_jdk_17.patch
- [Добавил javax зависимости](https://stackoverflow.com/questions/48204141/replacements-for-deprecated-jpms-modules-with-java-ee-apis)
- Ошибка при сборке (`mvn package`) решается обновлением `maven-war-plugin` (default версия этого плагина, который привязан к package, для новых JDK не подойдет)
- Сделал создание коллекций через фабричные методы `List.of`
- Как пример в `InMemoryMealRepository` использовал *local variable type inference* `var`.
  - [26 рекомендаций по использованию типа var в Java](https://habr.com/ru/post/438206/)
- `switch` в `MealServlet` перевел на новый формат (IDEA сама переводит по Alt+Enter). 
  - [Новые switch выражения](https://habr.com/ru/post/443464/)
- В `JdbcUserRepository.save` использовал [Text Blocks](https://www.infoq.com/articles/java-text-blocks/)
- В JDK 17 вместо `.collect(Collectors.toList())` можно использовать `.toList()`. Посмотрите его реализацию.

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW4

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. [HW4: Meal / JpaMealRepository](https://drive.google.com/file/d/13JJRhLhkn8_C3-xpkyilRxGe_w9_xTF2)
#### Apply 5_2_HW4.patch
 - При сравнении еды тесты падают, т.к. Hibernate делает ленивую обертку к `user`, и если происходит обращение к любому его полю (кроме id) вне транзакции, бросается `LazyInitializationException`.
По логике приложения поле `user` в еде не нужно, и мы не будем его отдавать наружу UI. Более того, включать `user` в запрос будет ошибкой: мы запрашиваем данные, которые приложению не требуются.
В тестах исключаем `user` из сравнения.  
 - [SQL “between” not inclusive](https://stackoverflow.com/questions/16347649/sql-between-not-inclusive/16347680)   

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. [Hibernate issue / HW4 Optional](https://drive.google.com/file/d/1kbb2IO15L9ABJ0-2TFJm8XZU_QUXUdni)

#### Apply 5_3_fix_hibernate_issue.patch
 - Из-за [Hibernate bug with proxy initialization when using `AccessType.FIELD`](https://hibernate.atlassian.net/browse/HHH-3718)
в `JpaMealRepository.get()` делался дополнительный запрос в базу для инициализации прокси `User`, и мы делали хак: доступ к полю `AbstractBaseEntity.id` через `AccessType.PROPERTY`.
С версии `5.2.13.Final` загрузка прокси при обращении к `id` управляется флагом `JPA_PROXY_COMPLIANCE` (по умолчанию запрос не делается)
   - [Call to id getter initializes proxy when using AccessType( "field" ): HHH-3718](https://hibernate.atlassian.net/browse/HHH-3718)
   - [According to JPA, a Proxy should be loaded even when accessing the identifier: HHH-12034](https://hibernate.atlassian.net/browse/HHH-12034)
 - <a href="http://stackoverflow.com/questions/594597/hibernate-annotations-which-is-better-field-or-property-access">Which is better, field or property access?</a>
 - Поправил `equals()` с учетом Lazy-проксирования
   - <a href="http://stackoverflow.com/questions/5031614/the-jpa-hashcode-equals-dilemma">JPA hashCode()/equals() dilemma</a>
   - <a href="https://xebia.com/advanced-hibernate-proxy-pitfalls">Hibernate Proxy Pitfalls</a>

------------------------
> Переопределять `equals()/hashCode()` необходимо, если
> - использовать entity в `Set` (рекомендовано для Many-ассоциаций) либо как ключи в `HashMap`
> - использовать _reattachment of detached instances_ (т.е. манипулировать одним Entity в нескольких транзакциях/сессиях).

> [Implementing equals() and hashCode()](https://docs.jboss.org/hibernate/stable/core.old/reference/en/html/persistent-classes-equalshashcode.html)

> Оптимально использовать уникальные бизнес-поля, но обычно таких нет, и чаще всего используются PK с ограничением, что он может быть `null` у новых объектов, и нельзя объекты сравнивать через `equals() and hashCode()` в бизнес-логике (например, тестах).

> [equals() and hashcode() when using JPA and Hibernate](https://stackoverflow.com/questions/1638723)

------------------------

> ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Почему над `AbstractBaseEntity` стоит `@Access(AccessType.FIELD)` ? Почему при запросе `user.id` нам не нужно вытаскивать его из базы?

`AccessType.FIELD` делает доступ в `AbstractBaseEntity` и всех классах-наследниках по полям. При загрузке `Meal` Hibernate на основе поля `meal.user_id` делает ленивую прокси к `User`, у которой нет ничего, кроме id.

#### Apply 5_4_HW4_optional.patch
- <a href="http://stackoverflow.com/questions/14892125/what-is-the-best-practice-to-determine-the-execution-time-of-the-bussiness-relev#27868954">Stopwatch</a>
- [Logback layouts coloring](https://logback.qos.ch/manual/layouts.html#coloring)
- Дополнительно: [use colored output only when logging to a real terminal](https://stackoverflow.com/questions/31046748)

## Занятие 5:
### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFZENCVEhDMkZiV00">Транзакции</a>
-  <a href="https://ru.wikipedia.org/wiki/Транзакция_(информатика)">wiki Транзакция</a>
-  <a href="https://jira.spring.io/browse/DATAJPA-601">readOnly и Propagation.SUPPORTS</a>
-  [@Transactional In-Depth](https://www.marcobehler.com/guides/spring-transaction-management-transactional-in-depth)
- Ресурсы:
  - [Транзакции в Spring Framework](https://medium.com/@kirill.sereda/%D1%82%D1%80%D0%B0%D0%BD%D0%B7%D0%B0%D0%BA%D1%86%D0%B8%D0%B8-%D0%B2-spring-framework-a7ec509df6d2)
  - <a href="https://dzone.com/articles/how-does-spring-transactional">How does Spring @Transactional Really Work</a>
  - <a href="http://web.archive.org/web/20170314073834/https://www.ibm.com/developerworks/ru/library/j-ts1/index.html">Стратегии работы с транзакциями: распространенные ошибки</a>
  - <a href="http://stackoverflow.com/questions/8490852/spring-transactional-isolation-propagation">Spring @Transactional - isolation, propagation</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFNW0yVWhXcGNPU2M">Профили Maven и Spring</a>
#### Apply 5_5_profiles_connection_pool.patch
> - `SLF4JBridgeHandler` перенес в профиль `postgres` (если логировать драйвер не нужно, то и он не нужен) 
> - **Галочка в XML-профиле влияет только на отображение в IDEA и никак не влияет на выполнение кода.**
> - `Profiles.ACTIVE_DB` задает активный профиль базы (postgres/hsqldb)
> - `Profiles.REPOSITORY_IMPLEMENTATION` определяет реализацию репозитория при запуске приложения (для тестов задаются через `@ActiveProfiles`).

> Для переключения на HSQLDB необходимо:
>  - поменять в окне Maven Projects профиль (Profiles) - выключить `postgres`, включить `hsqldb` -  и сделать `Reimport All Maven Projects` (1-я кнопка)
>  - поменять `Profiles.ACTIVE_DB = HSQLDB`
>  - почистить проект `mvn clean` (фаза `clean` не выполняется автоматически, чтобы каждый раз не перекомпилировать весь проект)

Для корректного отображения неактивного профиля в IDEA проверьте флаг _Inactive profile highlighting_ и сделайте проекту clean
 
![image](https://cloud.githubusercontent.com/assets/13649199/25120020/29935958-2425-11e7-8363-1ff027426f64.png)

> Вопрос: почему после этого патча не поднимается Spring при запуске приложения в Tomcat? (будем чинить в ДЗ, п.6)
 
- <a href="https://dzone.com/articles/using-spring-profiles-xml">Using Spring Profiles in XML Config</a>
- <a href="https://www.mkyong.com/spring/spring-profiles-example/">Spring Profiles example</a>

### Автоматический выбор профиля базы: [`ActiveProfilesResolver`](http://stackoverflow.com/questions/23871255/spring-profiles-simple-example-of-activeprofilesresolver)
#### Apply 5_6_profile_resolver.patch
> Сделал автоматический выбор профиля базы при запуске приложения (тестов) в зависимости от присутствия драйвера базы в classpath (`ActiveDbProfileResolver`). 

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 6. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFTWJOdHduOWtNcTA">Пул коннектов</a>
![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) [Александр Колесников - JDBC Pools Battle](https://www.youtube.com/watch?v=J9GzE2qlNuM&feature=youtu.be&t=2895) (ссылка на выводы)

>  [BoneCP to be deprecated ](https://stackoverflow.com/a/1662916/548473)
-  Выбор реализации пула коннектов: <a href="https://commons.apache.org/proper/commons-dbcp/">Commons Database Connection Pooling</a>, <a href="https://github.com/brettwooldridge/HikariCP">HikariCP</a>
-  <a href="https://habrahabr.ru/post/269023/">Самый быстрый пул соединений на java (читаем комменты)</a>
-  <a href="http://blog.ippon.fr/2013/03/13/improving-the-performance-of-the-spring-petclinic-sample-application-part-3-of-5">Tomcat pool</a>


### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 7. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFYVdyMFYxRUR6bWM">Spring Data JPA</a>

#### Apply 5_7_spring_data_jpa.patch
> - Переименовал классы _Proxy_ на более адекватные _Crud_, убрал _Impl_
> - В `spring-framework-bom` мы уже задали версию Spring. Убрал из остальных зависимостей.
> - В spring-data-jpa 2.x поменялся интерфейс: `T CrudRepository.findOne(ID id)` -> `Optional<T> CrudRepository findById(ID id)`
>   - [Java Optional — Отец холиваров](http://sboychenko.ru/java-optional)
>   - [Java 8 Optional In Depth](https://www.mkyong.com/java8/java-8-optional-in-depth/)
> - Не стал переопределять в `CrudUserRepository` методы `JpaRepository` (для явного указания всех используемых методов). Обычно этого не делают.

### Внимание: при обновлении версий не забудьте обновить зависимости Maven и сделать `clean`.

-  <a class="anchor" id="datajpa"></a><a href="http://projects.spring.io/spring-data-jpa/">Spring Data JPA</a>
-  Замена AbstractDAO: <a href="http://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.repositories">JPA Repositories</a>
-  Разрешение зависимостей: <a href="http://howtodoinjava.com/2014/02/18/maven-bom-bill-of-materials-dependency/">Maven BOM [Bill Of Materials] Dependency</a>
-  <a href="https://habrahabr.ru/post/232381/#datajpa">Делегирование (в конце статьи)</a>
-  <a href="https://spring.io/blog/2011/02/10/getting-started-with-spring-data-jpa">Getting started with Spring Data JPA</a>
-  <a href="http://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.query-methods.query-creation">Query methods</a>
-  <a href="http://jeeconf.com/archive/jeeconf-2013/materials/spring-data/">Spring Data – новый взгляд на persistence (JeeConf)</a>
-  <a href="https://www.youtube.com/watch?v=nwM7A4TwU3M">Евгений Борисов — Spring Data? Да, та!</a>
-  Ресурсы:
   -  <a href="https://github.com/spring-projects?query=spring-data">Github repositories</a>
   -  <a href="http://www.petrikainulainen.net/spring-data-jpa-tutorial">Spring Data JPA Tutorial</a>
   -  [Spring Data JPA with QueryDSL](https://dontpanic.42.nl/2011/06/spring-data-jpa-with-querydsl.html)
   -  [SpEL support in Spring Data JPA @Query](https://spring.io/blog/2014/07/15/spel-support-in-spring-data-jpa-query-definitions)

## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы
> Какой паттерн проектирования применён в классе DataJpaUserRepository (декоратор/адаптер/прокси/другой)?:

Вопрос интересный:) Ближе всего к адаптеру, но по логике композиция с делегированием. Мы просто используем для нашей реализации возможности `data-jpa: CrudUserRepository`.
Делегат интерфейсов не меняет, а прокси похож на делегата, но служит для неявной подмены (часто прямо в рантайм). См. [ПАТТЕРНЫ
ПРОЕКТИРОВАНИЯ](https://refactoring.guru/ru/design-patterns)

> В <a href="https://github.com/spring-projects/spring-petclinic/tree/master/src/main/java/org/springframework/samples/petclinic">spring-petclinic</a> `DataJpa` реализована без дополнительных классов. В таком виде как у них, spring data смотрится, конечно, намного лаконичней других реализаций, но у нас получилось  вдвое больше кода, чем с тем же jpa или jdbc. Плюс только пожалуй в том, что query находятся прямо в репозитории, а  не где-то там в другом пакете. Так что получается, spring data лучше подходит для простейших crud без всяких "фишек"? или в чем его достоинство для больших и сложных проектов?

Достоинства DATA-JPA по сравнению, например, с JPA: есть типизация, готовые реализации типовых методов CRUD, а также paging, data-common. Мы можем переключить реализацию JPA, например, на mongoDb (`PagingAndSortingRepository`, от которого наследуется `JpaRepository`, находится в `spring-data-common`).
Соответственно, его методы будут поддерживаться всеми реализациями `spring-data-common` (JPA - одна из них) и пр. Подробнее о них есть в видео <a href="http://jeeconf.com/archive/jeeconf-2013/materials/spring-data/">Spring Data – новый взгляд на persistence</a>.
Дополнительное проксирование в DATA-JPA - моя "фишка" для устранения минусов этого фреймворка: невозможность дебага, привязка к интерфейсу JpaRepository, перенос логики Repository в слой сервисов.
Для большого приложения выигрыш этого стоит. Для небольших (тестовых) приложений (например выпускного) дополнительных классов делать не нужно.

> Почему мы для InMemory не сделали отдельного профиля? Почему их не удалить вообще?

Реализация InMemory является примером, как в test делать подмену контекста. Для них сделали отдельный `inmemory.xml`, и запускаемый проект ничего не должен о них знать. У нас учебный проект, в котором 4 реализации репозиториев, в реальном такого не будет.

> А как делать транзакционность для реализации jdbc?

Будем делать на следующем уроке.

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 8. [Spring кэш](https://drive.google.com/file/d/1xpuL2YscL1ounS_qFRb1qzLciEOKn9I4/view?usp=sharing)
#### Apply 5_8_spring_cache.patch
- [Wiki Кэш](https://ru.wikipedia.org/wiki/Кэш)
  - [Spring Cache Abstraction](https://docs.spring.io/spring-framework/docs/current/reference/html/integration.html#cache)
  - [ECache](https://www.ehcache.org)
  - [Configuring the Cache Storage](https://docs.spring.io/spring-framework/docs/current/reference/html/integration.html#cache-store-configuration)
- [Spring 3.1 новый механизм кеширования](https://russianblogs.com/article/75981527090/)
- [Spring 4+ with Ehcache 3 – how to](https://imhoratiu.wordpress.com/2017/01/26/spring-4-with-ehcache-3-how-to/)
- [Evict Ehcache elements programmatically, using Spring](https://stackoverflow.com/questions/29557959/evict-ehcache-elements-programmatically-using-spring)
- Дополнительно: [Оптимизация запросов с использованием Spring cache и Bean scope](https://www.youtube.com/watch?v=P7nCQepVk_Y&list=PL6rimDLSyfe947bGsCviqIIYGofeFYQTM)
--------------------

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW05

- 1: Имплементировать `DataJpaMealRepository` и протестировать через `MealServiceTest`. 
#### MealServlet не работает (почему?), чиним в _Optional п.5_
- 2: Разделить реализации Repository по профилям Spring: `jdbc`, `jpa`, `datajpa` (общее в профилях можно объединять, например, `<beans profile="datajpa,jpa">`).
  - 2.1: Профили выбора DB (`postgres/hsqldb`) и реализации репозитория (`jdbc/datajpa/jpa`) независимы друг от друга, и при запуске приложения (тестов) нужно задать тот, и другой.
  - 2.2: Удобно для интеграции с IDEA выставить в `spring-db.xml` справа вверху в `Change Profiles...` профили, например, `datajpa, postgres`. **Это влияет ТОЛЬКО на отображение в IDEA и НИКАК на работу приложения и тестов**
  - 2.3: Общие части для всех в `spring-db.xml` можно оставить как есть без профилей вверху файла **(до первого `<beans profile=` !!!)**.   
Профили делаем в `spring-db.xml` (это не Maven профили, pom.xml не меняем). Здесь мы конфигурируем бины, которые попадут в spring context. Профилями можно переключать, что попадет в context, что нет. Профилями Maven мы меняем в проекте подгружаемые зависимости. Если у вас в `spring-db.xml` что-то красное - значит этих классов нет в зависимостях, это НЕ ошибка. Spring о профилях в Maven НИКАК не догадывается: в IDEA нужно вручную наверху нужные профили задавать, в приложении и тестах - указывать, с какими профилями запускается приложение.
- 3: Сделать тесты всех реализаций (`jdbc, jpa, datajpa`) через наследование (без дублирования).
  -  3.1 **сделать общий базовый класс для `MealServiceTest` и `UserServiceTest`**.
  -  3.2 сводку по времени выполнения тестов также сделать для `user`
- 4: Проверить запуск всех тестов: `mvn test` (в IDEA Maven Lifecycle - `test`, кнопку `skipTest` отжать).
#### `Jdbc` реализация не работает с `hsqldb`. Чиним в _Optional п.6_

### Optional

- 5: Починить `MealServlet` и использовать в `SpringMain` реализацию DB: добавить профили. Попробуйте поднять Spring контекст без использования `spring.profiles.active`.
- 6: Разделить `JdbcMealRepository` для HSQLDB (она не умеет работать с Java8 Time API) и Postgres через `@Profile` (для Postgres оставить `LocalDateTime`). 
  - Цель задания - потренироваться с [паттерном "шаблонный метод"](https://refactoring.guru/ru/design-patterns/template-method) и профилями Spring. 
Какие бины Spring попадут в контекст зависит от выставления активных профилей при запуске (`@ActiveProfiles` в тестах) и конфигурации, где задаются бины для каждого профиля.
Абстрактные классы не создаются и в контекст не попадают. 
  - После выполнения разделения на основе профилей, можно предложить решение проще.
- 7: Сделать и протестировать в сервисах методы (тесты и реализация - только для `DataJpa`):
  - 7.1:  достать по `id` пользователя вместе с его едой
  - 7.2:  достать по `id` и `userId`  еду вместе с пользователем
  - 7.3:  обращения к DB сделать в одной транзакции (можно сделать разные варианты). <a href="https://en.wikibooks.org/wiki/Java_Persistence/OneToMany">Java Persistence/OneToMany</a>

---------------------
### ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Типичные ошибки и подсказки по реализации
- 1: Для того, чтобы не запускались родительские классы тестов, нужно сделать их `abstract`.
- 2: В реализациях `JdbcMealRepository` **код не должен дублироваться**. Если вы возвращаете тип `Object`, посмотрите в сторону <a href="https://web.archive.org/web/20201027090144/http://www.quizful.net/post/java-generics-tutorial">дженериков</a>.
- 3: В `MealServlet/SpringMain` в момент `setActiveProfiles` контекст спринга еще не должен быть инициализирован, иначе выставление профиля уже ни на что не повлияет.
Уметь пользоваться гугл для разработчика, это умение №1. Если застряли- попробуйте например слова: `spring context set profile`
- 4: Если у метода нет реализации, то стандартно бросается `UnsupportedOperationException`. Для уменьшения количества кода при реализации _Optional_ (п. 7, только `DataJpa`) попробуйте сделать `default` метод в интерфейсе.
- 5: В Data-Jpa метод для ссылки на entity (аналог `em.getReference`) - `T getReferenceById(ID id)`  
- 6: Проверьте, что в `DataJpaMealRepository` все обращения к DB для одной операции выполняются в **одной транзакции**.  
(`<logger name="org.springframework.orm.jpa" level="debug"/>` для логирования информации по транзакциям)
- 7: Для 7.1 `достать по id пользователя вместе с его едой` я в `User` добавил `List<Meal> meals`. Учесть, что у юзера может отсутствовать еда. [Ordering a join fetched collection in JPA using JPQL/HQL](http://stackoverflow.com/questions/5903774/ordering-a-join-fetched-collection-in-jpa-using-jpql-hql)
- 8: Проверьте, что все тесты запускаются из Maven (имена классов тестов удовлетворяют соглашению) и итоги тестов класса выводятся корректно (не копятся). По умолчанию [maven-surefire-plugin](http://maven.apache.org/surefire/maven-surefire-plugin/examples/inclusion-exclusion.html) включает в тесты классы, заканчивающиеся на Test.
- 9: Атрибуты `resolver` и `profiles` в одном `@ActiveProfiles` вместе не работают (см. `org.springframework.test.context.support.ActiveProfilesUtils#resolveActiveProfiles`).
`@ActiveProfiles` принимает в качестве параметра строку **либо** массив строк. В тестах можно задавать несколько `@ActiveProfiles` в разных классах, они суммируются
- 10: `<beans profile=` в конфигурации контекста должны находиться **после** всех остальных объявлений.

# Стажировка <a href="https://github.com/JavaWebinar/topjava">Topjava</a>

## <a href="https://drive.google.com/drive/folders/1Urw8CidiVJDIXd9IwyadjBxPmpsL_MCr">Материалы занятия</a>

### ![correction](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Правки в проекте

#### Apply 6_0_fix.patch
Правки и оптимизация кода

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW5

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. [HW5: Spring Profiles. Spring Data JPA](https://drive.google.com/file/d/1dlhXeQr0fi0XymEFyBG-TXv5hpPgXtlT)

<details>
  <summary><b>Краткое содержание</b></summary>
  
Перед просмотром разбора домашнего задания еще раз ознакомьтесь с материалом по ссылке:

- <a href="https://jira.spring.io/browse/DATAJPA-601">readOnly и Propagation.SUPPORTS</a> (без транзакции не будет оптимизации по флагу `readOnly` при выполнении JDBC и в управлении ресурсами Spring's JPA, в том числе выключение `flush`)

В нашем приложении над репозиториями **CrudMealRepository** и **CrudUserRepository** указана аннотация
**@Transactional(readOnly = true)**, что предполагает выполнение всех операций в репозитории внутри транзакции на
чтение. В таком случае, для операций, которые вносят изменения в базу данных, нам необходимо переопределить транзакцию и указать над модифицирующим методом аннотации:
> @Transactional  
> @Modifying

В реализации **SimpleJpaRepository<T, ID>**, которая используется Spring Data JPA, транзакционность описывается точно
так же, как и в нашем приложении (все операции выполняются в транзакции на чтение, а для модифицирующих методов
транзакции переопределяются).

#### Для реализации репозитория для работы с Meal через Spring Data JPA:

1. Создаем интерфейс `CrudMealRepository`, который должен быть унаследован от `JpaRepository<Meal, Integer>`
2. Этот интерфейс помечаем аннотацией `@Transactional(readonly = true)`
3. Основная функциональность репозитория будет реализована прямо в интерфейсе (такой подход называется *интерфейсное
   программирование*) - Spring Data JPA автоматически создаст прокси для нашего интерфейса с реализацией необходимой
   функциональности.
4. По аналогии с `DataJpaUserRepository` создаем класс `DataJpaMealRepository`, который имплементируют `MealRepository`. В
   этот класс через конструктор спрингом будут внедрены `crudMealRepository` и `crudUserRepository`. Все методы
   реализуются по аналогии с `DataJpaUserRepository`. Для сохранения еды в методе `save(Meal mea, int userId)` сначала
   проверяем, что еда принадлежит аутентифицированному пользователю и после этого присваиваем еде ссылку на `User`,
   которому она принадлежит. Чтобы не загружать этого user из базы, используем метод `getById(int id)`, который вернет
   ссылку на прокси-объект user с указанным `id`.

#### Разделение конфигурации на профили

Spring позволяет настроить несколько профилей, которые позволяют переключать его функциональность.  
У нас уже настроено два профиля для переключения между базами данных:

- `postgres` - для работы PostgreSQl
- `hsqldb` - для работы с базой данных в памяти

Для реализаций способа работы с базой данных настроим еще три профиля:

- `jdbc`
- `jpa`
- `dataJpa`

Общие для нескольких профилей свойства можно выносить в общий блок, перечислив в декларации профилей их наименования
через запятую. Следует обратить особое внимание на то, что тег `<beans>` в котором объявляются профили и их
конфигурация, может располагаться только в самом конце файла конфигурации после всех остальных настроек. Intellij Idea
предоставляет интерфейс для переключения между профилями Spring, настроенными в конфигурации (такое переключение влияет
только на отображение файла конфигурации, но не оказывает никакого влияния на запуск и работу приложения).

#### Тесты для всех реализаций репозитория

Все настройки логирования и определения времени выполнения тестов вынесем в общий абстрактный базовый класс
`AbstractServiceTest`, от которого будут унаследованы остальные тестовые классы сервисов. Также над этим суперклассом
указывается аннотация `@ActiveProfiles(resolver = ActiveDbProfileResolver.class)`, которая будет автоматически
определять необходимый профиль базы данных при запуске тестов в зависимости от наличия драйвера БД в classpath.  
Его наследниками будут классы `AbstractMealServiceTest` и `AbstractUserServiceTest`, в которые мы переносим
соответствующие тесты.  
Далее по цепочке наследования создадим тестовые классы для различных реализаций репозитория. Аннотация `@ActiveProfile`
наследуется и может быть дополнена в классах — наследниках, поэтому в созданных тестовых классах `(Jpa | DataJpa |
Jdbc) .. ServiceTest` с помощью этих аннотаций укажем конкретные профили Spring, соответствующие тестируемой
функциональности.
> При изменении профиля maven и изменении иерархии классов, удалении классов — обязательно нужно запускать `mvn clean`

</details>

#### Apply 6_01_HW5_data_jpa.patch

Транзакция начинается, когда встречается первая `@Transactional`. С default propagation `REQUIRED`
остальные `@Transactional` просто участвуют в первой. Поэтому ставим аннотацию сверху `DataJpaMealRepository.save()`,
чтобы все обращения к базе внутри метода были в одной транзакции. Аналогично, если из сервиса собирается несколько
запросов к репозиториям, `@Transactional` ставится над методом сервиса.

#### Apply 6_02_HW5_profile_test.patch

**Для IDEA в `spring-db.xml` не забудьте выставить Spring Profiles. Например `datajpa, postgres`**

> - Заменил `description.getMethodName()` на `getDisplayName()` в выводе результатов тестов. После `printResult()` буфер сбрасывается в 0, чтобы не накапливать изменения.

#### Apply 6_03_extract_rules.patch

> Вынес измерение времени и сводку в отдельный класс `TimingRules`

[JUnit Rules External Resources](https://carlosbecker.com/posts/junit-rules/#external-resources)

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. [HW5: Optional](https://drive.google.com/file/d/1S6gOOzLV9ndSbPiSuyEmqhEy3xZoUpXZ)

<details>
  <summary><b>Краткое содержание</b></summary>

#### Определим профиль Spring в SpringMain:

При создании `XmlApplicationContext`, когда мы в конструктор передаем настройки в xml - Spring сразу считывает и
применяет конфигурации и дальнейшее изменение профилей не оказывает на контекст никакого влияния, поэтому в данном
классе сначала создаем `GenericXmlApplicationContext` без параметров, после чего указываем для него необходимые профили с
помощью

 ```java
 appCtx.getEnviroment().setActoveProfiles(Profiles.POSTGRES,Profiles.DATAJPA)
 ```

Затем передаем контексту наши конфигурации и обновляем его. В данном случае Spring считает конфигурации, и настроит
контекст в соответствии с указанными профилями.

#### Для корректного запуска приложения определим профили Spring в MealServlet:

Профиль Spring можно задать аналогичным способом. Также, вместо `GenericXmlApplicationContext` можно создать
`ClassPathXmlApplicationContext`. Самый короткий способ задать профили — создать `ClassPathXmlApplicationContext`, передав
ему в конструкторе конфигурации и установив флаг конструктора `refresh` в `false`. В данном случае спринг не будет
парсить контекст сразу при инициализации и мы можем задать для него требуемые профили и вручную обновить контекст, после
чего спринг поднимет и настроит контекст соответствующим образом:

 ```java
 springContext=new ClassPathXmlApplicationContext(new String[]{"spring/spring-app.xml","spring/spring-db.xml"}, false);
 ```

Так как HSQLDB (в данной версии) не работает с Java Time API, в отличие от PostgreSQL, необходимо разделить реализации репозитория для
работы в двух различных профилях БД. Для данных профилей будет различаться только способ получения даты и времени
употребления Meal. В соответствии с паттерном Template Method - создадим классы-наследники, где для
соответствующих профилей будет реализовываться абстрактный `protected` метод суперкласса, который будет возвращать
`LocalDateTime` - для PostgreSQL и `TimeStamp` для HSQLDB. Базовый класс `JdbcMealRepository` будет дженериком (типизированным классом),
объект которого возвращается этим `protected` методом. Классы-наследники являются внутренними
статическими классами, они помечены аннотациями `@Repository` и являтются бинами спринга. В `@Profile` над ними мы указываем
соответствующий профиль спринга в зависимости от БД - Spring создаст бин только для тех классов, которые будут относиться к активным профилям.
> последние версии драйвера HSQLDB поддерживает работу с Java Date Time Api, поэтому теперь можно просто обновить версию драйвера в `pom.xml`

#### Получение Meal вместе с User

1. В `MealService` внедряем `UserRepository` и в одной транзакции сначала
   загружаем из БД `Meal`, затем загружаем соответствующего `User` и вручную устанавливаем для еды ее владельца. Так как
   `@Transactional` объявлена на уровне сервиса — несмотря на то, что мы работаем с двумя разными репозиториями, операции
   по получению из базы Meal и User выполнятся в одной транзакции благодаря тому, что аннотация имеет атрибут
   `propagation`, который по умолчанию устанавливается как `required` - то есть, если внутри одной транзакции будет
   исполняться другой транзакционный метод, то для его выполнения не будет открываться новая транзакция — он будет
   выполняться во внешней транзакции.

2. Способ: получение Meal с User в `MealRepository` через `FETCH JOIN`. Так как нам требуется реализовать получение еды с ее
   владельцем только для `DataJpaMealRepository`, в интерфейсе `MealRepository` объявим `default UserMeal getWithUser(...)`,
   который для всех реализаций этого интерфейса при вызове этого метода будет выбрасывать исключение
   `UnsupportedOperationException()`. В `DataJpaMealRepository` переопределим этот дефолтный метод: этот метод пометим
   аннотацией `@Query` и в скобках укажем HQL запрос получения Meal из базы. При этом, так как запрос содержит `JOIN
   FETCH`, таблицы meals и users будут объединяться на уровне базы (обычный JOIN) и Spring Data за один запрос загрузит
   из базы Meal вместе с ее User.

#### Получение User вместе с Meals

Для того чтобы получить из базы User вместе со всеми его Meals, для начала добавим `List<Meal> meals` в класс `User`. 
Эта коллекция будет помечена аннотацией `@OneToMany`, которая говорит об отношении один-ко-многим. Мы видим, что
у Meal есть ссылка на User, а у User есть ссылка на коллекцию его meal, и эти ссылки помечены соответствующими
аннотациями — такое отношение называется BiDirectional. Пользователя с его едой получаем способом, аналогичным
предыдущему шагу - с помощью HQL запроса с применением fetch join. JPA 2.0 позволяет использовать в таких случаях
UniDirectional отношение со стороны
@OneToMany [Unidirectional OneToMany](https://en.wikibooks.org/wiki/Java_Persistence/OneToMany#Unidirectional_OneToMany.2C_No_Inverse_ManyToOne.2C_No_Join_Table_.28JPA_2.x_ONLY.29).
Обратите внимание на то, что нужно **объявлять поле только в том случае, когда ваше приложение их использует!**


#### Проблема **<a href="http://stackoverflow.com/questions/97197/what-is-the-n1-selects-issue">N+1</a>**

Проблема **N + 1** возникает, когда выполняется N дополнительных SQL-запросов для получения тех же данных, которые можно
получить при выполнении одного SQL-запроса. Чем больше значение N, тем больше запросов будет выполнено и тем больше
влияние на производительность. Например, в нашем случае при получении списка пользователей сначала будут загружены все
пользователи, и затем для каждого пользователя будет выполнен запрос в базу для получения его ролей. Таким образом, если
бы у нас было 1000 пользователей, то будет выполнен 1 запрос для получения всех пользователей и дополнительно 1000
запросов для получения ролей каждого пользователя, итого 1000 + 1 запрос.
> Некоторые способы решения проблемы N+1:
> 1. Получать сущность из базы данных через запрос с использованием `JOIN FETCH` - в таком случае таблицы будут объединяться на уровне БД и вся информация будет получена сразу.
> 2. Пометить коллекцию сущности, для получения которой выполняются дополнительные запросы, аннотацией `@Fetch(FetchMode.SUBSELECT)`. В этом случае
     > сначала будет загружена коллекция пользователей и затем будет выполнен один дополнительный запрос, который получит роли всех этих пользователей.
> 3. Пометить коллекцию аннотацией `BatchSize(size = 200)` - в данном случае сначала будет выполнен запрос на получение всех пользователей, и затем дополнительными запросами будут загружаться
     > роли этих пользователей — по 200 пользователей за запрос.
> 4. JPA 2.1 предоставляет для решения этой проблемы функциональность `@EntityGraph` - на уровне сущности мы можем объявить граф полей, которые будут загружаться
     > из базы данных совместно с сущностью. При определении последующих запросов мы можем указать наименование нужного нам Entity Graph, и JPA сформирует запрос в соответствии с этим графом и загрузит только описанные в нем поля.
     `@EntityGraph` можно определять не только на уровне сущности, это можно сделать непосредственно в интерфейсе через параметр аннотации `attributePath`, например: `@EntityGraph(attributePaths = {"meals", "roles"})`
>
</details>

#### Apply 6_04_HW5_optional_fix_jdbc_profiles.patch

- <a href="http://javarticles.com/2013/12/spring-profiles.html">Spring Profiles</a>. <a href="https://www.javacodegeeks.com/2013/10/spring-4-conditional.html">Spring 4 Conditional</a>.
- дополнительно:
    - зайдите в исходники `@Profile` и посмотрите (подебажьте) его реализацию через `@Conditional(ProfileCondition.class)`.
    - [реализация через Java Config и Profiles на уровне методов](http://stackoverflow.com/a/43645463/548473)

#### Apply 6_05_update_hsqldb.patch

В реальном проекте часто проблему можно решить простым обновлением версии: <a href="http://hsqldb.org/">new HSQLDB version supports Java 8 time API</a>

#### Apply 6_06_HW5_optional_fetch_join.patch

> - Добавил проверки и тесты на `NotFound` для `MealService.getWithUser` и  `UserService.getWithMeals`
> - Убрал `CascadeType.REMOVE`, в уроке далее будет про Cascade.

- <a href="http://stackoverflow.com/questions/11938253/jpa-joincolumn-vs-mappedby">JPA JoinColumn vs mappedBy</a>
-  <a href="https://en.wikibooks.org/wiki/Java_Persistence/OneToMany#Unidirectional_OneToMany.2C_No_Inverse_ManyToOne.2C_No_Join_Table_.28JPA_2.x_ONLY.29">Unidirectional OneToMany</a>

#### Apply 6_07_HW5_graph_batch_size.patch
- **<a href="http://stackoverflow.com/questions/97197/what-is-the-n1-selects-issue">N+1 selects issue</a>**

- <a href="https://docs.oracle.com/javaee/7/tutorial/persistence-entitygraphs002.htm">Using Named Entity Graphs</a>
    - [Entity Graph в Spring Data JPA](https://sysout.ru/entity-graph-v-spring-data-jpa/)
    - [`EntityGraphType.FETCH` vs `LOAD`](http://stackoverflow.com/questions/31978011/what-is-the-diffenece-between-fetch-and-load-for-entity-graph-of-jpa)
- <a href="https://dou.ua/lenta/articles/jpa-fetch-types/">Стратегии загрузки коллекций в JPA</a>
- <a href="https://dou.ua/lenta/articles/hibernate-fetch-types/">Стратегии загрузки коллекций в Hibernate</a>

> Когда мы достаем всех юзеров с ролями без `@BatchSize`, делается запрос юзеров (1), и на каждого юзера идет в базу запрос ролей (+N). C `@BatchSize(size = 200)` делается запрос на юзеров (1), и затем роли достаются пачками для 200 юзеров (+ N/200).

## Занятие 6:

### Добавил тесты на валидацию

> - К сожалению, в JUnit <a href="https://github.com/junit-team/junit4/pull/778">нет `ExpectedException.expectRootCause`</a>. `AbstractServiceTest.validateRootCause()` сделал через [JUnit 4.13 assertThrows](https://stackoverflow.com/a/2935935/548473).

> ![](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Откуда у нас берется `ConstraintViolationException` в тестах на валидацию? Для каких наших исключений он является рутом?

Прежде всего - пользуйтесь дебагом! Исключение легко увидеть в методе `getRootCause()`. Если подебажить выполение
Hibernate валидации, то можно найти, где обрабатываются аннотации валидации и место
в `org.hibernate.cfg.beanvalidation.BeanValidationEventListener.validate()`, где
бросается `ConstraintViolationException`.  
Cамое простое - поставить брекпойнт в конструкторах `ConstraintViolationException` или в `ValidationException` и
запустить тест `createWithException` в дебаге.

#### Apply 6_08_add_test_validation.patch

**Тесты валидации для Jdbc не работают, нужно будет починить в HW6 (в реализация Jdbc валидация отсутствует)**

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFeTV0SUFfblk5NE0">Кэш Hibernate</a>

> Кэш мигрировал на 3.x

<details>
  <summary><b>Краткое содержание</b></summary>

#### Уровни кэширования Hibernate

Hibernate cache — это 3 уровня кеширования:

- Кеш первого уровня (First-level cache) - включен по умолчанию всегда, его нельзя отключить, кэширует сущности на
  уровне сессии;
- Кеш второго уровня (Second-level cache) - используется на уровне фабрики сессий, по умолчанию всегда отключен и не
  имеет реализации в Hibernate, для его использования нужно самостоятельно подключать сторонние реализации;
- Кеш запросов (Query cache) - по умолчанию отключен, включается определением дополнительных параметров в
  конфигурационном файле. В нем кэшируются идентификаторы объектов, которые соответствуют совокупности параметров
  совершенного ранее запроса;

Для кэширования определяются 4 стратегии, которые определяют его поведение в определенных ситуациях:

- Read-only
- Read-write
- Nonstrict-read-write
- Transactional

#### Подключение кэш 2 уровня Hibernate

Существует множество сторонних реализаций кэша, которые можно подключить к Hibernate. Мы будем использовать одну из
самых распространенных - EhCache. Для того чтобы подключить к Hibernate EhCache, в файл `pom.xml` нужно добавить
дополнительную зависимость:

````
 <dependency>
         <groupId>org.hibernate</groupId>
         <artifactId>hibernate-jcache</artifactId>
         <version>${hibernate.version}</version>
 </dependency>
````
Теперь кэш подключен и его осталось лишь сконфигурировать в файле spring-db.xml для профилей 
"datajpa, jpa" :
````
<entry key="#{T(org.hibernate.cache.jcache.ConfigSettings).PROVIDER}" value="org.ehcache.jsr107.EhcacheCachingProvider"/>

<!--Кэш может делить свои области на регионы-->
<entry key="#{T(org.hibernate.cfg.AvailableSettings).CACHE_REGION_FACTORY}" value="org.hibernate.cache.jcache.internal.JCacheRegionFactory"/>

<!--Включаем кэш второго уровня (по умолчанию value = false)-->
<entry key="#{T(org.hibernate.cfg.AvailableSettings).USE_SECOND_LEVEL_CACHE}" value="true"/>

<!--Можно подключить кэширование запросов, по умолчанию оно отключено. Оставим отключенным, value = false-->
<entry key="#{T(org.hibernate.cfg.AvailableSettings).USE_QUERY_CACHE}" value="false"/>
````  
Сам кэш более тонко настраивается в отдельном файле `ehcache.xml`. В нем мы указываем какие
таблицы будут кэшироваться, количество элементов, время и множество других параметров.

Чтобы указать Hibernate какие сущности будут кэшироваться, их нужно пометить аннотацией `@Cache` и в скобках
указать необходимую стратегию кэширования. Такая аннотация предоставляется как JPA, так и Hibernate, аннотация 
Hibernate позволяет определять дополнительные параметры кэширования.  
Так как мы пометили User `@Cache`, то сущности будут заноситься в кэш второго уровня, но не будет кэшироваться коллекция
ролей. Чтобы роли тоже кэшировались нужно так же пометить это свойство пользователя аннотацией `@Cache`.  
Теперь, при запуске тестов мы столкнемся с частой проблемой — так как перед каждым тестом мы повторно заполняем базу
тестовыми данными, и делаем мы это в обход Hibernate - содержимое кэша 2 уровня и базы данных будут различаться. 
Поэтому перед каждым тестом дополнительно нужно кэш инвалидировать — специально для этого мы создадим
утильный класс `JpaUtil`, где определим метод, который будет получать текущую Session Factory и инвалидировать кэш Hibernate. 
Объект этого класса внедрили в тесты, и, так как в `spring-db.xml` мы определили, что этот бин будет создаваться только для профилей *jpa, datajpa*, 
тесты для JDBC реализации перестанут работать. `JpaUtil` отсутствует в профиле `jdbc` и не может быть разрезолвен при поднятии Spring контекста.
</details>

#### Apply 6_09_hibernate_cache.patch

**Теперь уже все `JdbcUserServiceTest` тесты поломались (добавил `@Ignore`). Требуется починить в HW6**

- <a href="http://habrahabr.ru/post/135176/">Уровни кэширования Hibernate</a>
- <a href="http://habrahabr.ru/post/136375/">Hibernate Cache. Практика</a>
- <a href="http://www.tutorialspoint.com/hibernate/hibernate_caching.htm">Hibernate - Caching</a>
- Починка тестов: <a href="http://stackoverflow.com/questions/1603846/hibernate-2nd-level-cache-invalidation-when-another-process-modifies-the-databas">инвалидация кэша Hibernate</a>
- [Hibernate User Guide: Caching](http://docs.jboss.org/hibernate/orm/5.2/userguide/html_single/Hibernate_User_Guide.html#caching)
- [Hibernate 5, Ehcache 3.x](https://www.boraji.com/index.php/hibernate-5-jcache-ehcache-3-configuration-example)
- Ресурсы:
   - **<a href="https://www.youtube.com/watch?list=PLYj3Bx1JM6Y7BKivc3eZwRUhWwBmbIFXg&v=V-ljsrVy6pE">Hibernate performance tuning (Mikalai Alimenkou /Igor Dmitriev)</a>**
   -  <a href="http://stackoverflow.com/questions/3663979/how-to-use-jpa2s-cacheable-instead-of-hibernates-cache">JPA2 @Cacheable vs Hibernate @Cache</a>
   -  <a href="http://vladmihalcea.com/2015/06/08/how-does-hibernate-query-cache-work/">How does Hibernate Query Cache work</a>
   -  <a href="https://www.javacodegeeks.com/2014/06/pitfalls-of-the-hibernate-second-level-query-caches.html">Pitfalls of the Hibernate Second-Level / Query Caches</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4. <a href="https://drive.google.com/file/d/0B9Ye2auQ_NsFVmdpNDJSNXRTWUE">Cascade. Auto generate DDL.</a>

<details>
<summary><b>Краткое содержание</b></summary>
При создании таблиц `user_roles` и `meals` для внешнего ключа мы указывали свойство `ON DELETE CASCADE`. Это означает, что при удалении
пользователя база данных автоматически будет удалять все записи, которые на него ссылались по внешнему ключу. Существует также
свойство `ON UPDATE CASCADE`, определив которое, при обновлении первичного ключа пользователя этот ключ обновлялся бы во всех зависимых
таблицах. При каскадных операциях на уровне базы данных могут возникнуть проблемы с консистентностью кэша второго уровня, так как все
операции производятся в обход Hibernate.
Hibernate тоже позволяет указывать `CascadeType` для управляемых сущностей (что не имеет абсолютно никакой связи с таким же свойством в базе данных).
 
> Для Hibernate допускается указывать `CascadeType` только для сущности @OneToMany - со стороны родителя!  
> Для этой цели со стороны дочерней сущности можно указать аннотацию @OnDelete над ссылкой на родительскую сущность.  
> Для коллекций элементов сущности все действия всегда распространяются каскадно!  

Действие, указанное в `CascadeType` при манипулировании сущностью — будут распространяться на все ее дочерние объекты.

> ALL - все возможные каскадные операции, выполняемые над исходной сущностью, применяются к дочерним сущностям.
> MERGE - если исходная сущность объединяется, слияние каскадно передается на дочерние сущности.
> PERSIST - если исходный объект сохраняется, сохранятся каскадно и дочерние объекты.
> REFRESH - если исходная сущность обновляется, каскадно обновятся и дочерние объекты.
> DELETE - при удалении исходной сущности удаляются и дочерние объекты.

Также для аннотации `@OneToMany` существует параметр `orphanRemoval`. Если установить этот параметр в true, то при удалении исходной сущности
все объекты, которые ранее на нее ссылались так же удалятся, если установить это значение в false, то в дочерних сущностях ссылка на 
исходную будет просто обнуляться.  

#### Генерация схемы базы данных по Java Entity
JPA 2.1 предоставляет возможность генерировать базу данных по сущностям. Для этого в spring-db.xml
укажем следующие параметры:  
```
<!--Действие, которое выполнится - схема будет сброшена и создана снова-->
<entry key="#{T(org.hibernate.cfg.AvailableSettings).HBM2DDL_SCRIPTS_ACTION}" value="drop-and-create"/>

<!--Расположение скриптов создания схемы-->
<entry key="#{T(org.hibernate.cfg.AvailableSettings).HBM2DDL_SCRIPTS_CREATE_TARGET}" value="${TOPJAVA_ROOT}/config/ddl/create.ddl"/>

<!--Расположение скриптов сброса схемы-->
<entry key="#{T(org.hibernate.cfg.AvailableSettings).HBM2DDL_SCRIPTS_DROP_TARGET}" value="${TOPJAVA_ROOT}/config/ddl/drop.ddl"/>

<!--Можно настроить автоматическое обновление схемы базы данных при изменении сущностей-->
<entry key="#{T(org.hibernate.cfg.AvailableSettings).HBM2DDL_AUTO}" value="create"/>
```
> Автоматическую генерацию не рекомендуется использовать для реального приложения, так как генерируемые
> команды часто некорректны. Чтобы они были более правильными — нужно указывать дополнительные условия и ограничения
> в аннотациях при описании entity.
</details>

#### Apply 6_10_cascade_ddl.patch

#### Cascading

> Есть SQL ON .. CASCADE, которая выполняется в базе данных, и есть аннотация в Hibernate, исполняемая в приложении

- <a href="http://stackoverflow.com/questions/13027214">Do not use `CascadeType` for @ManyToOne</a>
- <a href="http://stackoverflow.com/questions/836569">CascadeType meaning</a>
- <a href="https://en.wikibooks.org/wiki/Java_Persistence/ElementCollection">No cascade option on an ElementCollection, the target objects are always persisted, merged, removed with their parent.</a>
- <a href="http://stackoverflow.com/questions/21149660">Create ON DELETE CASCADE: `@OnDelete`</a>
- [Сascade for `@ElementCollection`](https://stackoverflow.com/a/62848296/548473)
- <a href="http://stackoverflow.com/questions/3087040">Hibernate second level cache and ON DELETE CASCADE in database schema</a>
- [`orphanRemoval=true` vs `CascadeType.REMOVE`](http://stackoverflow.com/a/19645397/548473)
- [JPA `cascade/orphanRemoval` doesn't work with `NamedQuery`](http://stackoverflow.com/questions/7825484/jpa-delete-where-does-not-delete-children-and-throws-an-exception)

#### Auto schema generation
- <a href="https://www.javacodegeeks.com/2015/03/jpa-database-schema-generation.html">JPA DATABASE SCHEMA GENERATION</a>
- <a href="http://stackoverflow.com/questions/7793395">hbm2ddl.auto and autoincrement</a>
- <a href="http://stackoverflow.com/questions/2585641">Hibernate/JPA DB Schema Generation Best Practices</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5.  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFVE1jWkRucm1UTjA">Spring Web</a>

<details>
  <summary><b>Краткое содержание</b></summary>
Для работы с web с помощью Spring подключим к проекту следующие зависимости:  
 
```
<!--TomCat - web-контейнер. Позволяет работать с jsp, сервлетами -->
<dependency>
     <groupId>org.apache.tomcat</groupId>
     <artifactId>tomcat-servlet-api</artifactId>
     <version>${tomcat.version}</version>
     <scope>provided</scope>
</dependency>

<!--java standart tag library - не предоставляется TomCat, нужно добавлять вручную -->
<dependency>
            <groupId>javax.servlet</groupId>
            <artifactId>jstl</artifactId>
            <version>1.2</version>
        </dependency>
        
<!--Spring библиотека для работы с web -->
<dependency>
     <groupId>org.springframework</groupId>
     <artifactId>spring-web</artifactId>
     <version>${spring.version}</version>
</dependency>
```
При старте web-приложения в контейнере сервлетов требуется инициализировать контекст спринга.  
Запустить Spring можно с помощью `ContextLoaderListener`, который будет отслеживать работу веб-приложение и при инициализации сервлета
поднимать Spring context в методе `contextInitialized` и отключать контекст спринга при остановке
приложения в методе `contextDestroyed`.
Для этого нужно определить этот ContextListener в `web.xml`:

```
 <listener>
        <listener-class>org.springframework.web.context.ContextLoaderListener</listener-class>
    </listener>
```
Чтобы Listener смог поднять контекст спринга — ему нужно указать в `web.xml` путь к конфигурационным файлам и
задать необходимые профили:

```
<context-param>
        <param-name>spring.profiles.default</param-name>
        <param-value>postgres,datajpa</param-value>
    </context-param>

    <context-param>
        <param-name>contextConfigLocation</param-name>
        <param-value>
            classpath:spring/spring-app.xml
            classpath:spring/spring-db.xml
        </param-value>
    </context-param>
```

Для каждого сервлета, при инициализации, после создания запускается метод `init(ServletConfig config)`, где мы можем получить текущий контекст Spring. 
Для web приложений определяется свой собственный `WebApplicationContext`, который может работать с сервлетами.
В `UserServlet` мы можем получить контекст с помощью метода `WebApplicationContextUtils.getRequiredWebApplicationContext(getServletContext())`.
 Из полученного контекста мы можем получать бины Spring, например, объект `UserService`, и работать через него с пользователями.
</details>

#### Apply 6_11_spring_web.patch

> - Для сборки проекта в окне Maven отключите тесты (`Toggele 'Skip Tests' Mode`)
> - В `web.xml` задаются профили запуска по умолчанию: `<param-value>postgres,datajpa</param-value>`. **Если запускаетесь под HSQLDB, надо поменять на `hsqldb,datajpa`**.

- <a href="http://www.mkyong.com/servlet/what-is-listener-servletcontextlistener-example/">ServletContextListener</a>.
- <a href="https://docs.oracle.com/javaee/6/tutorial/doc/bnafi.html">Servlet Lifecycle</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 6.   <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFN3k0ZVk1MnF5TjQ">JPS, JSTL, internationalization</a>

<details>
  <summary><b>Краткое содержание</b></summary>
Ко всему, что находится в папке webapp, можно получить доступ из браузера.   
Для отображения пользователей создадим jsp страницу `userList`. Для работы со специализированными функциями и выражениями на 
странице импортируем некоторые библиотеки jstl(java standard tag library).  

#### Локализация
 - для локализации **стандартными средствами java** можно использовать *Bundle* - это набор файлов properties, 
где определены ключ и значение. В зависимости от локали автоматически будет выбран нужный файл properties, из которого по 
   ключу страница будет получать текст на нужном языке и подставлять в места, где указаны соответствующие ключи.
```html
<fmt:setBundle basename="messages.app"/>
```
 - Для локализации нашего приложения создадим в папке `resources/messages` два файла - `app.properties` и `app_ru.properties`, в которых 
мы и пропишем ключи и соответствующие им значения на русском и английском языках.
При этом нужно иметь в виду, что локализация в jpa/jstl не работает с UTF8, поэтому для отображения текста на кириллице приходится записывать
его в виде набора кодов unicode (intellij idea предоставляет нам удобный функционал для работы с этими кодами).

> **Это было до Java 9. Теперь можно не парится и писать напрямую в UTF-8** 

 - На каждой странице будут дублироваться верхняя часть(header) и нижняя часть(footer), поэтому сделаем их в виде фрагментов, которые будут
включаться в каждую страницу с помощью тега  
   ```< jsp:include page="fragments/bodyHeader.jsp"/ > ``` 
 - Для того чтобы на странице JSP понимало, с каким объектом оно работает (а в IDEA работали автодополнения), мы можем явно указать с каким типом 
объекта мы будем работать. Для этого мы используем тег:
```html
<jsp:useBean id="user" scope="page" type="ru.javawebinar.topjava.model.User"/>
```
После этого на странице мы сможем работать с объектом в java-вставках *< %  >* и с помощью expression language *${ }*.    
Без этого тэга приложение работать тоже будет, не будет IDEA интергации. Не забывайте про getter-ы, JSP обращается к объектам через них!

> Локаль приложения определяется на основе локали операционной системы и свойств браузера. Чтобы проверить работу
> локализации можно из браузера в заголовке запроса указать Content-Language:"en-US". Этот заголовок будет 
> считан в сервлете, и приложение определит требуемую локаль.

</details>

**Убедитесь, что [в настройках IDEA](https://github.com/JavaOPs/topjava/wiki/IDEA#Поставить-кодировку-utf-8) кодировка везде UTF-8</a> до применения патча**
#### Apply 6_12_jsp_jstl_i18n.patch

> - Поменял `users/meals` в ключах локализации на `user/meal`. Понадобится при локализации ошибок (сделаем позже)
> - [Since Java 9 default encoding in properties files is UTF-8](https://docs.oracle.com/javase/9/intl/internationalization-enhancements-jdk-9.htm). Галочка `Transparent` и ASCII кода уже не нужны.


**Для работы с несколькими языками установите плагин `Resource Bundle Editor`**
  
- <a href="http://docs.oracle.com/javaee/1.3/tutorial/doc/JSPIntro8.html">Including Content in a JSP Page</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 7.   <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFLTB3R3pKNFNEQmM">Динамическое изменение профиля при запуске.</a>

<details>
  <summary><b>Краткое содержание</b></summary>

#### Динамическое изменение профиля при запуске
Изначально мы определили профиль спринга в web.xml:
```xml
<context-param>
        <param-name>spring.profiles.default</param-name>
        <param-value>postgres,datajpa</param-value>
    </context-param>
```
При этом приложение будет деплоиться на сервер с указанными в конфигурации профилями.  
Чтобы определить профиль Spring при запуске без перекомпиляции проекта можно использовать системные опции, которые мы можем
задать при запуске проекта, указав их в параметрах запуска (в командной строке, а для Intellij Idea: Edit Run/Debug Configurations - VM options).  
В этом случае конфигурации по умолчанию будут переопределены и будут использованы заданные при запуске системные переменные.

</details>

    -Dspring.profiles.active="postgres,datajpa"

- <a href="http://stackoverflow.com/questions/10041410/default-profile-in-spring-3-1#answer-10041835">Set profiles in Spring 3.1</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 8.   <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFdkFRRFdYa0NoWkU">Конфигурирование Tomcat через maven plugin. Jndi-lookup.</a>

<details>
  <summary><b>Краткое содержание</b></summary>
Многие настройки сервера(web-контейнера) можно вынести в отдельный файл-конфигурацию.
Настройки TomCat определим в отдельном файле `context.xml`

#### Настройка пула TomCat для соединения с базой данных
```xml
<!-- Имя ресурса, к которому мы будем получать доступ из приложения по JNDI
    <Resource name="jdbc/topjava"
              auth="Container"
              type="javax.sql.DataSource"
              
              Настройки подключения к базе данных
              url="jdbc:postgresql://localhost:5432/topjava"
              username="user"
              password="password"
              driverClassName="org.postgresql.Driver"
              
              Настройки пула коннектов к базе данных
              validationQuery="SELECT 1"
              maxTotal="10"
              minIdle="2"
              maxWaitMillis="20000"
              initialSize="2"
              maxIdle="5"
              testOnBorrow="true"
              removeAbandonedOnBorrow="true"
              testWhileIdle="true"/> -->
```
Для того чтобы TomCat при запуске создавал пул коннектов, требуется добавить maven плагин в
секцию **buid**

```xml
    <!-- http://stackoverflow.com/questions/4305935/is-it-possible-to-supply-tomcat6s-context-xml-file-via-the-maven-cargo-plugin#4417945 -->
            <!-- https://codehaus-cargo.github.io/cargo/Tomcat+9.x.html -->
            <plugin>
                <groupId>org.codehaus.cargo</groupId>
                <artifactId>cargo-maven3-plugin</artifactId>
                <version>1.9.5</version>
                <configuration>
                    <container>
                        <containerId>tomcat9x</containerId>
                        <systemProperties>
                            <file.encoding>UTF-8</file.encoding>

                            <!-- Активные профили Spring, с которыми будет запускаться приложение-->
                            <spring.profiles.active>tomcat,datajpa</spring.profiles.active>
                        </systemProperties>

                        <!-- Для создания пула коннектов томкату нужен драйвер postgres, поэтому добавляем его в зависимости-->
                        <dependencies>
                            <dependency>
                                <groupId>org.postgresql</groupId>
                                <artifactId>postgresql</artifactId>
                            </dependency>
                        </dependencies>
                    </container>
                    <configuration>
                        <configfiles>
                            <configfile>
                                
                                <!-- Путь к файлу, в котором определены настройки пула коннектов-->
                                <file>src/main/resources/tomcat/context.xml</file>
                                <todir>conf/Catalina/localhost/</todir>
                                <tofile>${project.build.finalName}.xml</tofile>
                            </configfile>
                        </configfiles>
                    </configuration>
                    <deployables>
                        <deployable>
                            <groupId>ru.javawebinar</groupId>
                            <artifactId>topjava</artifactId>
                            <type>war</type>
                            <properties>
                                <context>${project.build.finalName}</context>
                            </properties>
                        </deployable>
                    </deployables>
                </configuration>
            </plugin>
```  
В `spring-db.xml` создаем новый профиль "tomcat", для него будет создаваться бин `dataSource` с помощью соединения, 
которое будет получено из пула коннектов TomCat по JNDI. При этом в профиле мы можем указать расположение файла свойств,
в котором будут описаны дополнительные параметры пула коннектов контейнера сервлетов - у нас это файл `tomcat.properties`.  

</details>

С плагином мы можем сконфигурировать Tomcat прямо в `pom.xml` и запустить его с задеплоенным туда нашим приложением WAR
из командной строки без IDEA и без инсталляции Tomcat. По умолчанию он скачивает его из центрального maven-репозитория (
можно также указать свой в `<container><home>${container.home}</home></container>`). При запуске Tomcat из IDEA
запускается Tomcat, путь к которому мы прописали в конфигурации запуска (со своими настройками).

#### Apply 6_13_tomcat_pool_jndi_cargo.patch

> - для запуска в Tomcat 9 поменял `tomcat7-maven-plugin` на `cargo-maven3-plugin`.
> - в `pom.xml` вместо `context.xml.default` можно делать [индивидуальный контекст приложения](https://stackoverflow.com/a/60797999/548473)
> - Конфигурация сделана под postgres. Для HSQLDB нужно скорректировать `driverClassName` + `validationQuery="SELECT 1 FROM INFORMATION_SCHEMA.SYSTEM_USERS` в `context.xml` и `dependencies`.

> ![](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Томкат сам управляет пулом коннектов? На каждый запрос в браузере будет даваться свой коннект?
 
Да, в Томкате есть реализация пула коннектов `tomcat-jdbc` (мы его подключаем со `scope=provided`). Если запускаемся с профилем `tomcat`, приложение на каждую транзакцию (или операцию не в транзакции) берет коннект к базе из пула, сконфигурированного в подкладываемом Tomcat `context.xml`.

> ![](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Для чего мы делаем профиль `tomcat`? Возможно два варианта запуска приложения: либо cargo, либо tomcat? И если мы запускаем через tomcat то в `spring-db.xml` через `jee:jndi-lookup` подтягивается конфигурация tomcata из `\src\main\resources\tomcat\context.xml`?

1. Есть `cargo-maven3-plugin` который автоматически запускает Tomcat и деплоит туда наше приложение. Те это тоже деплой
   в Tomcat, но через Maven.
2. В xml конфигурации Tomcat можно настраивать ресурсы (кроме пула коннектов к БД могут быть, например, JMS или
   настройки Mail). Это никак не связано с `cargo` плагином. В Spring этот сконфигурированный ресурс контейнера
   сервлетов подлючается через `jee:jndi-lookup`. Тк у нас несколько вариантов конфигурирования `DataSource`, мы этот
   вариант сделали в `spring-db.xml` в профиле `tomcat`.
3. Плагин cargo позволяет задавать xml конфигурацию запускаемого Tomcat (у нас `src/main/resources/tomcat/context.xml`).
   И в параметрах запуска мы задаем активные профили Spring `tomcat,datajpa` через `spring.profiles.active`. Таким
   образом мы в плагине конфигурируем Tomcat, деплоим в него приложение и задаем приложению активные профили Spring
   для `DataSource` из конфигурации Tomcat.

Еще раз: плагин `cargo` и JNDI - это две не связанные между собой вещи, просто мы добавили их в проект в одном патче.   
Плагин запускается **после сборки проекта**. Запуск из командной строки:

     mvn clean package -DskipTests=true org.codehaus.cargo:cargo-maven3-plugin:1.9.5:run

Приложение деплоится в application context topjava: [http://localhost:8080/topjava](http://localhost:8080/topjava)

- <a href="https://codehaus-cargo.github.io/cargo/Maven+3+Plugin.html">Cargo Maven3 plugin</a>
- <a href="http://stackoverflow.com/questions/4305935/is-it-possible-to-supply-tomcat6s-context-xml-file-via-the-maven-cargo-plugin#4417945">Кастомизация context.xml в cargo-maven2-plugin</a>
- <a href="https://tomcat.apache.org/tomcat-8.0-doc/jndi-resources-howto.html"/>Tomcat JNDI Resources</a>
- <a href="https://commons.apache.org/proper/commons-dbcp/configuration.html">BasicDataSource Configuration</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 9. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFQThUX2VyQXNiTHM">Spring Web MVC</a>

<details>
  <summary><b>Краткое содержание</b></summary>

Работа Spring MVC основана на паттерне Front Controller (Единая точка входа). 
Все запросы поступают в единый собственный сервлет Spring, в котором происходит его перенаправление на нужный сервлет приложения.  
Для работы со Spring MVC нужно заменить зависимость `spring-web` на `spring-webmvc`:  
```xml
 <dependency>
    <groupId>org.springframework</groupId>
    <artifactId>spring-webmvc</artifactId>
</dependency>
```  
После этого в `web.xml` необходимо сконфигурировать единую точку входа - Spring `DispatcherServlet`, в который будут поступать все запросы 
к приложению:  
```xml
<servlet>
        <servlet-name>mvc-dispatcher</servlet-name>
        <servlet-class>org.springframework.web.servlet.DispatcherServlet</servlet-class>
        <init-param>
            <!--Spring MVC имеет собственный контекст, контексты объединяются в цепочке. 
            В итоге у нас будет два контекста - первый - контекст web-приложения, в котором находятся контроллеры
            и который обрабатывает запросы к приложению, второй - основной контекст приложения, в котором происходит 
            бизнес-логика. Ниже мы указываем путь к конфигурации web-контекста приложения-->
            <param-name>contextConfigLocation</param-name>
            <param-value>classpath:spring/spring-mvc.xml</param-value>
        </init-param>
        <load-on-startup>1</load-on-startup>
</servlet>

<!--Все запросы к приложения будут поступать в "/", этот сервлет-->
    <servlet-mapping>
        <servlet-name>mvc-dispatcher</servlet-name>
        <url-pattern>/</url-pattern>
    </servlet-mapping>
```  
> Различные контексты не имеют доступа к бинам друг друга (исключение - дочерние контексты могут получать доступ к бинам родителя, но не наоборот),
> каждый контекст поднимает для себя свои собственные экземпляры, поэтому нужно следить за конфигурацией бинов и поднимать их в соответствующем контексте.

Конфигурацию webmvc контекста и диспетчер-сервлета определим в файле `spring-mvc.xml`.

#### Сценарий обработки запроса
 1. Запрос поступает в dispatcher-servlet, в нем определен набор Handler Mappings - классы, которые обрабатывают запросы в зависимости от их типа.
- Соответствующий запросу Handler делегирует обработку запроса нужному контроллеру
- Контроллер необходимым образом обрабатывает запрос и возвращает View
- View отображает результат выполнения запроса

В нашем приложении будет два вида контроллеров: одни — работают с User Interface и отображают результат работы приложения в браузере, 
другие — работают по REST-интерфейсу. Контроллеры помечаются аннотацией `@Controller`.  
Паттерн и тип HTTP метода, по которым мы можем получить доступ к методу контроллера конфигурируются
с помощью аннотации `@RequestMapping(value = "/users", method = RequestMethod.GET)`.

> **В последних версиях Spring можно сделать проще: `@GetMapping("/users")`**

При этом Spring внедрит в метод объект `Model`, в который мы можем добавлять атрибуты и передавать их из слоя контроллера в слой представления.

Чтобы Spring MVC контекст мог осуществлять роутинг запросов по этим аннотациям, в конфигурации `spring-mvc.xml` нужно 
вручную включить поддержку аннотаций: 
```xml
<mvc:annotation-driven/>
```

Методы контроллера, помеченные аннотацией `@RequestMapping` (а также `@GetMapping, @PostMapping, @PutMapping, ..`) после обработки запроса должны возвращать имя представления, в которое
будет передана Model. Эта View отобразится как результат выполнения запроса. Чтобы в этих методах возвращать только название нужной View, в конфигурации нужно
определить `ViewResolver`, который автоматически к этому названию добавит путь к view в приложении и суффикс — формат view:  
```xml
  <bean class="org.springframework.web.servlet.view.InternalResourceViewResolver"
          p:prefix="/WEB-INF/jsp/"
          p:suffix=".jsp"/>
```

Для того чтобы приложение имело доступ к статическим ресурсам (например, стили) - нужно добавить дополнительную конфигурацию 
в `spring-mvc.xml`:
```xml
    <mvc:resources mapping="/resources/**" location="/resources/"/>
```
> Spring MVC имеет конфигурацию по умолчанию. Если в `spring-mvc.xml` мы не укажем никаких Handlers, то их стандартный набор
> будет создан автоматически и приложение будет работать. Как только мы добавляем собственные Handlers в конфигурацию — настройки
> по умолчанию переопределяются и будут созданы только те бины, которые мы определили, стандартные Handlers созданы не будут.

</details>

#### Apply 6_14_spring_webmvc.patch

Обработка запросов переезжает в `RootController`, сервлеты уже не нужны
> - Починил [путь к корню](http://stackoverflow.com/questions/10327390/how-should-i-get-root-folder-path-in-jsp-page)
> - В Spring 4.3 ввели новые аннотации `@Get/Post/...Mapping` (сокращенный вариант `@RequestMapping`)

-  <a class="anchor" id="mvc"></a><a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html#mvc">Spring Web MVC</a>
- [ContextLoaderListener vs DispatcherServlet](https://howtodoinjava.com/spring-mvc/contextloaderlistener-vs-dispatcherservlet/)
-  <a href="http://design-pattern.ru/patterns/front-controller.html">Паттерн Front Controller</a>
-  <a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html#mvc-servlet-context-hierarchy">Иерархия контекстов в Spring Web MVC</a>
-  <a href="http://www.tutorialspoint.com/spring/spring_web_mvc_framework.htm">Сценарий обработки запроса</a>. <a href="https://web.archive.org/web/20130708211855/https://www.studytrails.com/frameworks/spring/spring-mvc.jsp">HandlerMappings</a>
-  <a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html#mvc-viewresolver">View Resolution</a>: прячем jsp под WEB-INF.
-  HandlerMapping: <a href="http://www.mkyong.com/spring-mvc/spring-mvc-simpleurlhandlermapping-example/">SimpleUrlHandlerMapping</a>, <a href="http://www.mkyong.com/spring-mvc/spring-mvc-beannameurlhandlermapping-example/">BeanNameUrlHandlerMapping</a>
-  <a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html#mvc-caching-static-resources">Маппинг ресурсов.</a>
-  Ресурсы:
  -  <a href="http://www.mkyong.com/spring-mvc/spring-mvc-hello-world-example/">Spring MVC hello world</a>
  -  <a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html#mvc-servlet-special-bean-types">Special bean types in the WebApplicationContext</a>

> Настройки `Project Structure->Modules->Spring`:

![image](https://user-images.githubusercontent.com/11200258/112018359-8aa1eb80-8b3f-11eb-942f-a8eb7938de41.png)

> ![](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) В `web.xml` мы инициализируем `DispatcherServlet`, передавая ему параметром `spring-mvc.xml`. Получается, что `DispatcherServlet` парсит `spring-mvc.xml` и находит в нем context?

Да, можно подебажить родителя (`FrameworkServlet.initWebApplicationContext()`). После инициализации
сервлет `DispatcherServlet` раскидывает все запросы по контроллерам (бинам контекста Спринга).
См. <a href="http://design-pattern.ru/patterns/front-controller.html">паттерн Front Controller</a>.

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 10. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFUEctTkRSMWNvRjg">Spring Internationalization</a>

<details>
  <summary><b>Краткое содержание</b></summary>

Spring нормально работает с кириллицей, замена русских символов на их коды уже не требуется (как и с JDK 9).
Spring также автоматически может изменять локаль приложения, для этого в конфигурации `spring-mvc.xml` ему нужно
определить `ReloadableResourceBundleMessageSource`, который будет отвечать за локализацию и указать для него путь к Bundles с локализованными данными.  
В страницах JSP мы также должны указать, что теперь будем работать не через JSTL, а через Spring локализацию.
Для этого в страницах удаляем тег `fmt:setBundle`. Теперь Spring автоматически будет подставлять сообщения в зависимости от локали.
  Но сейчас Spring работает на основании JDK `ResourceBundle` и он игнорирует свойство *p:cacheSeconds="5"*, так как ресурсы
интернационализации будут кэшироваться Java. Чтобы ресурсы не кэшировались нужно использовать бин `ReloadableResourceBundleMessageSource` с путем к локализации, отличным от classpath приложения.

```xml
<bean id="messageSource" class="org.springframework.context.support.ReloadableResourceBundleMessageSource"
        p:cacheSeconds="5"
        p:defaultEncoding="UTF-8">
    <property name="basenames" value="file:///#{systemEnvironment[TOPJAVA_ROOT]}/config/messages/app"/>
    <property name="fallbackToSystemLocale" value="false"/>
    </bean>
```
Теперь ресурсы интернационализации не будут кэшироваться и их можно будет менять во время работы приложения "на ходу". 
</details>

#### Apply 6_15_spring_i18n.patch

**Внимание: проверьте, что переменная окружения `TOPJAVA_ROOT` настроена!**
> - В локализации поменял <a href="https://stackoverflow.com/questions/4441682/what-to-use-for-localization-in-jsps-with-spring">`fmt:message` на `spring:message`</a>
> - Выбор языка зависит от языка операционной системы и заголовка `Accept-Language`. Добавил в `spring-mvc.xml` `messageSource` параметр [`fallbackToSystemLocale`](http://stackoverflow.com/questions/4281504/spring-local-sensitive-data).
Он управляет выбором, куда переключаться при выборе `en` и отсутствии `app_en.properties`: локаль операционной системы или `app.properties` (`fallbackToSystemLocale=false`). Переключение локалей будем реализовывать в конце проекта.  

#### Для тестирования локали [можно поменять `Accept-Language`](https://stackoverflow.com/questions/7769061/how-to-add-custom-accept-languages-to-chrome-for-pseudolocalization-testing). Для Хрома в `chrome://settings/languages` перетащить нужную локаль наверх или поставить [плагин Locale Switcher](https://chrome.google.com/webstore/detail/locale-switcher/kngfjpghaokedippaapkfihdlmmlafcc)

-  <a href="http://learningviacode.blogspot.ru/2012/07/reloadable-messagesources.html">Reloadable MessageSources</a>
-  <a href="http://nginx.com/resources/admin-guide/serving-static-content/">nginx: Serving Static Content</a>

## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы
>  Кэш hibernate надстраивается над ehcache или живет самостоятельно?

- <a href="https://akorsa.ru/2016/11/kak-rabotaet-kesh-v-hibernate/">Understanding Hibernate Caching</a>:
Hibernate supports following open-source cache implementations out-of-the-box: EHCache (Easy Hibernate Cache), OSCache (Open Symphony Cache), Swarm Cache, and JBoss Tree Cache.

> Где конфигурируется интернализация для jstl (т.е. файл, где задаются app, app_ru.properties)? Достаточно указать в страницах bundle и путь в ресурсы?

`<fmt:setBundle basename="messages.app"/>` означает, что ресурсы будут искаться в `classpath:messages/app(_xx)/properties`:
<a href="http://docs.oracle.com/javaee/5/jstl/1.1/docs/tlddocs/fmt/setBundle.html">Tag setBundle</a>: fully-qualified resource name, which has the same form as a fully-qualified class name.
После сборки проекта maven их можно найти в `target/classes` или `target/topjava/WEB-INF/classes`.

> Отлично, что она все пишет на том языке, который пришел в заголовке запроса. А если я хочу выбрать?

Выбор языка зависит от языка операционной системы и заголовка `Accept-Language`. Параметр `fallbackToSystemLocale`, который управляет выбором, когда с `Accept-Language: en,en-US;` не находится локализация `app_en.properties`. Для переключения локали используется <a href="http://www.codejava.net/java-ee/jstl/jstl-format-tag-setlocale">JSTL Format Tag fmt:setLocale</a>. Мы будем реализовывать переключение локалей в Spring i18n в конце проекта.

> Мы создаем бин, где получаем dataSource по имени `<jee:jndi-lookup id="dataSource" jndi-name="java:comp/env/jdbc/topjava"/>`.
Но там не указан класс, как в других dataSource. Получается, по имени jdbc/topjava нам уже отдается готовый объект dataSource, и мы как бы помещаем его в бин?

Здесь используется namespace `jee:jndi-lookup`, который прячет под собой классы реализации. JNDI объект DataSource конфигурируется в `src/main/resources/tomcat/context.xml`

> В плагине прописан профиль `<spring.profiles.active>tomcat,datajpa</spring.profiles.active>`, а в web.xml `<param-value>postgres,datajpa</param-value>`.
Какой же реально отрабатывает?

См. видео урока "Динамическое изменение профиля при запуске". В плагине мы задаем параметры JVM запуска Tomcat

> A `@NamedQuery` или `@Query` подвержены кэшу запросов? Т.е. если мы поставим _USE_QUERY_CACHE_value_="true", будет ли Hibernate их кэшировать?

Чтобы запрос кэшировался, кроме true в конфигурации [нужно еще явно выставить запросу _setCacheable_](http://vladmihalcea.com/2015/06/08/how-does-hibernate-query-cache-work/).    
По поводу кэширования `@NamedQuery` нашел [`@QueryHint`](https://docs.jboss.org/jbossas/docs/Clustering_Guide/5/html/ch04s02s03.html)

> Почему messages мы кладем в config и используем system environment? Разве так делают в реальном проекте? Не будешь же вписывать на сервере эти переменные каждый раз, если проект куда-то будет переезжать. Можно по-другому, кроме systemEnvironment['TOPJAVA_ROOT'], задать путь от корня проекта?

1. messages нам нужны в runtime (при работе приложения). Проект к собранному и задеплоенному в Tomcat war отношения никакого уже не имеет и на этом сервере он обычно не находится. Если ресурсы нужны только при сборке и тестировании, то путь к корню для одномодульного maven проекта можно задать как `${project.basedir}`, но для многомодульного проекта (а все реальные проекты многомодульные) это путь к корню своего модуля.
2. В "реальном приложении" делается совершенно по-разному:
  - нести с собой в classpath, но ресурсы нельзя будет динамически (без передеплоя) обновлять
  - класть в war (не в classpath) и обновлять в развернутом TOMCAT_HOME/webapps/[appname]/...
  - класть в зафиксированное определенное место (например, в home: `~` или в путь от корня `/app/config`). Можно задавать фиксированный пусть в пропертях профиля maven и фильтровать ресурсы (maven resources), чтобы они попали в проперти проекта.
  - делать через переменную окружения, как у нас
  - задавать в параметрах запуска JVM как системную переменную через -D..
  - располагать в преференсах (для unix это home, для windows - registry): <a href="http://java-course.ru/articles/preferences-api/">использование Preferences API</a>
  - держать настройки в DB

   Часто в одном приложении используют несколько способов для разных видов конфигураций.

> Не происходит ли дублирования при кэшировании пользователей чрез Hibernate и `@Cacheable`?

`@Cacheable` кэширует результат запроса `getAll()`, т.е. список юзеров. Hibernate кэширует юзеров по отдельности, т.е., грубо говоря, делает мапу id->User. Можно назвать это дублированием. Нужно ли будет такое в реальном приложении? Все смотрится из логики запросов и их частоты, вполне вероятно, что нет. Как-то мы писали приложение для Дойчебанка (аналог skype на GWT, т.е. на экране небольшое окошко) - там было 5(!!!) уровней кэширования, первый вообще в базе.

> У меня стоит Томкат 8-й версии, в помнике у нас 9-й прописан, но всё работает. Почему?

В `pom.xml` мы подключаем `tomcat-servlet-api` со `scope=provided`, что означает, что он используется только для компиляции и не идет в war. Т.к. мы не используем никаких фич Tomcat 9.x, то наш код совместим с Tomcat 8.x. При запуске через `cargo-maven2-plugin` Tomcat 9 загружается из maven-репозитория.

> Откуда `@Transactional` вытягивает класс для работы с транзакцией, в составе какого бина он идет?

1. Если в контексте Spring есть `<tx:annotation-driven/>`, то подключается `BeanPostProcessors`, который проксирует классы (и методы), помеченные `@Transactional`.
2. По умолчанию для TransactionManager используется бин с `id=transactionManager`

---------------------------

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW06
- 1.1 Починить тесты `InMemoryAdminRestControllerSpringTest/InMemoryAdminRestControllerTest`  (добавлять `spring-mvc.xml` в контекст не стоит, т.к. в новой версии Spring для этого требуется `WebApplicationContext`. Можно просто поправить `inmemory.xml`) + перевести `SpringMain` тоже на реализацию `inmemory`.
- 1.2 Починить тесты Jdbc (исключить валидацию в тестах Jdbc)
  - <a href="http://iliachemodanov.ru/ru/blog-ru/12-tools/57-junit-ignore-test-by-condition-ru">org.junit.Assume</a>
  - [How to get active Profiles in Spring Application](https://stackoverflow.com/questions/9267799/548473)
- 1.3 Перенести функциональность `MealServlet` в `JspMealController` контроллер (по аналогии с `RootController`).
`MealRestController` у нас останется, с ним будем работать позже. 
  - 1.3.1 разнести запросы на update/delete/.. по разным методам (попробуйте вообще без параметра `action=`). Можно по аналогии с `RootController#setUser` принимать `HttpServletRequest request` (аннотации на параметры и адаптеры для `LocalDate/Time` мы введем позже). 
  - 1.3.2 в одном контроллере нельзя использовать другой. Чтобы не дублировать код, можно сделать наследование контроллеров от абстрактного класса.
  - 1.3.3 добавить локализацию и `jsp:include` в `mealForm.jsp / meals.jsp`

### Optional
- 2.1 Добавить транзакционность (`DataSourceTransactionManager`) в Jdbc-реализации  
- 2.2 Добавить еще одну роль к юзеру Admin (будет 2 роли: `USER, ADMIN`).
- 2.3 В `JdbcUserRepository` добавить реализацию ролей юзера (добавлять можно одним запросом с JOIN и `ResultSetExtractor/ RowCallbackHandler`, либо двумя запросами (отдельно `users` и отдельно `roles`). [Объяснение SQL JOIN](http://www.skillz.ru/dev/php/article-Obyasnenie_SQL_obedinenii_JOIN_INNER_OUTER.html)
  - 2.3.1 В реализации `getAll` НЕ делать запрос ролей для каждого юзера (N+1 select)
  - 2.3.2 При save посмотрите на <a href="https://www.mkyong.com/spring/spring-jdbctemplate-batchupdate-example/">batchUpdate()</a>
- 2.4 Добавить проверку ролей в `UserTestData.USER_MATCHER.assertMatch` и починить ВСЕ тесты (тесты должны проходить для юзера с несколькими ролями)  
- 2.5 Добавить валидацию для `Jdbc..Repository` через Bean Validation API (для JPA это делается автоматически при сохранении в базу, для Jdbc мы должны это делать вручную).  Оптимизировать код.
   - Валидацию `@NotNull` для `Meal.user` пока можно закомментировать. На 10-м уроке решим проблему через [Jackson JSON Views](http://www.baeldung.com/jackson-json-view-annotation)
   - [Валидация данных при помощи Bean Validation API](https://alexkosarev.name/2018/07/30/bean-validation-api/) 

### Optional 2 (повышенной сложности)
- 3 Отключить Spring кэш в `UserService` в тестах через `NoOpCacheManager` и для кэша Hibernate 2-го уровня `hibernate.cache.use_second_level_cache=false`. 
  - [JPA 2.0 disable session cache for unit tests](https://stackoverflow.com/a/58963737/548473)
  - [Example of PropertyOverrideConfigurer](https://www.concretepage.com/spring/example_propertyoverrideconfigurer_spring)
  - [Spring util schema](https://docs.spring.io/spring/docs/current/spring-framework-reference/core.html#xsd-schemas-util)      

---------------------
## ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Подсказки по HW06
- 1: Неверная кодировка UTF-8 с Spring обычно решается фильтром `CharacterEncodingFilter`:
```
    <filter>
        <filter-name>encodingFilter</filter-name>
        <filter-class>org.springframework.web.filter.CharacterEncodingFilter</filter-class>
        <init-param>
            <param-name>encoding</param-name>
            <param-value>UTF-8</param-value>
        </init-param>
        <init-param>
            <param-name>forceEncoding</param-name>
            <param-value>true</param-value>
        </init-param>
    </filter>
    <filter-mapping>
        <filter-name>encodingFilter</filter-name>
        <url-pattern>/*</url-pattern>
    </filter-mapping>
```
- 2: **Если не поднимается контекст Spring, смотрим причину вверху самого нижнего исключения.** Все ошибки на отсутствия бина в контексте или его нескольких реализациях относятся к пониманию основ: Spring application context. Если нет понимания этих основ, двигаться дальше нельзя, нужно вернуться к видео Спринг, где объясняется, что это такое. Также пересмотрите видео [Тестирование UserService через AssertJ](https://drive.google.com/file/d/1SPMkWMYPvpk9i0TA7ioa-9Sn1EGBtClD). Начиная с 11.30 как раз разбираются подобные ошибки.
- 3: Если неправильно формируется url относительно контекста приложения (например, `/topjava/meals/meals`), посмотрите на
  -  <a href="http://stackoverflow.com/questions/4764405/how-to-use-relative-paths-without-including-the-context-root-name">Relative paths in JSP</a>
  -  <a href="http://docs.spring.io/spring/docs/3.2.x/spring-framework-reference/html/mvc.html#mvc-redirecting-redirect-prefix">Spring redirect: prefix</a>
- 4: При проблемах с запуском Томкат проверьте запущенные процессы `java`, нет ли в `TOMCAT_HOME\webapps` приложения каталога `topjava`, логи tomcat (нет ли проблем с доступом к каталогам или контекстом Spring)
- 5: Если создаете неизменяемые List или Map, пользуйтесь `List.of()/ Map.of()`
- 6: В MealController общую часть `@RequestMapping(value = "/meals")` лучше вынести на уровень класса
- 7: Проверьте `@Transactional(readOnly = true)` сверху `Jdbc..Repository`
- 8: Проверьте, что `config\messages\app_ru.properties` у вас в кодировке UTF-8 (в любом редакторе/вьюере или при отключенном [Transparent native-to-ascii conversion](https://github.com/JavaOPs/topjava/wiki/IDEA#%D0%9F%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C-%D0%BA%D0%BE%D0%B4%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D1%83-utf-8) в IDEA).
- 9: Учтите, что роли у юзеров можно менять/добавлять/удалять
- 10: Убедитесь, что все методы UserService корректно работают с юзерами, у которых несколько ролей (**запусти наши тесты для Admin с 2-мя ролями**)

# Стажировка <a href="https://github.com/JavaOps/topjava">Topjava</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFfjVnUVhINEg0d09Nb3JsY2ZZZmpsSWp3bzdHMkpKMmtPTlpjckxyVzg0SWc">Материалы занятия</a>

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW6

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. <a href="https://drive.google.com/open?id=1luHTJOXQW-BWyueqsfzzAeiP8lUTZkje">HW6</a>

#### Apply 7_01_HW6_fix_tests.patch

<details>
  <summary><b>Краткое содержание</b></summary>

#### Починить InMemory и JDBC тесты

InMemory-тесты перестали работать, т.к ранее мы перенесли сканирование каталога `web` из `spring-app.xml` в конфигурацию `spring-mvc.xml`, которой нет в тестах. В результате контроллеры перестали
попадать в спринг-контекст тестов. Для восстановления добавим сканирование каталога `web` в конфигурацию `inmemory.xml`. Теперь в классах, которые работают с InMemory-реализацией, для создания
контекста можно оставить импорт только конфигурации
`spring/inmemory.xml`.

JDBC-тесты перестали работать, т.к в конфигурации `spring-db.xml` мы объявили бин `JpaUtil` только для профилей jpa и dataJpa, для других профилей (jdbc) этот бин создаваться не будет.  
JDBC-тесты мы запускаем с профилем jdbc, но в абстрактном классе AbstractUserServiceTest (общем для всех тестов сервисного слоя User) для всех профилей мы указали необходимость создания переменной
типа `JpaUtil`. Соответственно, для профиля jdbc в контексте спринга будет отсутствовать этот бин, и спринг не сможет запустить приложение из-за неразрешенной зависимости.

Чтобы спринг смог поднять контекст в профиле JDBC, нужно указать над переменной `jpaUtil`
аннотацию `@Autowired(required = false)` - мы указываем спрингу, что эта зависимость не является обязательной и можно ее проигнорировать.

> В новой версии заменил аннотацию на ленивую инициализацию `@Lazy`

И в `@Before` методе тестов используем этот бин только для JPA реализаций.  
Для этого создадим утильный метод `isJpaBased()`, который будет проверять, относится ли текущая реализация к jpa. Чтобы проверить, с какими профилями запущен Spring, нам придется внедрить
в `AbstractServiceTest`
бин класса `Environment`. Это класс спринга, который позволит получить доступ к информации о том, с какими параметрами он был запущен, с помощью
```env.acceptsProfiles(org.springframework.core.env.Profiles.of(Profiles.JPA, Profiles.DATAJPA))```
С помощью этого же утильного метода теперь мы можем проверить, что для `MealServiceTest` тесты на валидацию `validateRootCause()` будут выполняться только для jpa/dataJpa профилей (если этот тест
запустить для профиля jdbc, то он упадет, т.к. пока в JDBC у нас нет валидации).

#### Локализация, jsp:include для meal*.jsp

1. В файлы интернационализации `app.properties` добавляем дополнительные пары ключ-значение для русского и английского языка. В JSP страницах вместо текста, по аналогии со страницами для User,
   указываем ключи, вместо которых спринг должен подставить локализованные сообщения.
2. Для каждой JSP страницы для включения фрагментов указываем теги:

`<jsp:include page="fragments/headTag.jsp"/>` - в нем определены title страницы, ссылка на статические ресурсы и базовая ссылка на корень приложения.

`<jsp:include page="fragments/bodyHeader.jsp"/>` - верхняя часть страниц, в ней определены ссылки для навигации по приложению.  
И в самом низу страниц:  
`<jsp:include page="fragments/footer.jsp"/>`

Так как мы локализуем приложение с помощью Spring, на страницах нужно удалить тег:
`<fmt:setBundle basename="messages.app"/>` - с ним работает только jstl.

3. Для того, чтобы на страницах получить доступ к корню приложения, используется
   `"${pageRequest.request.contextPath}"` - эту ссылку на root удобнее вынести в `headTag` в виде [`<base href>` элемента](https://stackoverflow.com/a/40228804/548473), чтобы она вместе с этим
   фрагментом добавлялась к каждой странице, и не требовалось бы ее везде дублировать.

4. Чтобы видеть, к каким URL были привязаны контроллеры во время работы приложения, в `logback.xml` настроим уровень логирования для Spring web:  
   `<logger name="org.springframework.web" level="DEBUG"/>`

#### Перенести функциональность из `MealServlet` в контроллеры

Чтобы не дублировать одну и ту же функциональность для REST- и JSP-контроллеров, создадим абстрактный
`AbstractMealController` (от него будут наследоваться остальные Meal-контроллеры), куда перенесем все методы из
`MealRestController`. JSP-контроллер будет работать с jsp-страницами. Каждый метод этого контроллера будет делегировать основную функциональность в родительский абстрактный контроллер.

> **Внимание!**. Не делайте без нужды абстрактных контроллеров в своих выпускных проектах!

Так как каждый метод этого контроллера должен отвечать за единственное действие, разнесем функциональность по разным методам, а доступ к самим методам разделим с помощью
аннотации `@RequestMapping (@GetMapping / @PostMapping)`, в их параметрах укажем путь к endpoint, по которому можно обратиться к методу.

При этом для всего контроллера также зададим `@RequestMapping("/meals")` (`value=` - параметр по умолчанию, можно не указывать). Это префикс запроса для всех методов контроллера.

> Один из признаков "хорошего" контроллера, где не смешивается разная функциональность, - этот общий url. Для каждой функциональности в выпускных создавайте свой собственный контроллер!

Для доступа к определенному методу контроллера нужно будет указать уникальный для нашего приложения "путь + http-метод", который складывается из маппинга к контроллеру, маппинга к нужному методу и
http-метода, например:  
`GET {корень приложения} + "/meals" + "/delete"`
`GET {корень приложения} + "/meals"`
`POST {корень приложения} + "/meals"`
Для `mealList.jsp` теперь не нужно с запросом дополнительно передавать тип действия, которое мы хотим совершить с едой, мы можем просто обратиться к нужному методу по его уникальному пути (endpoint,
url).

Если на этом шаге запустить приложение, то мы столкнемся с проблемой: при выполнении манипуляций и переходе по ссылкам путь портится.

- путь к ресурсу по этой ссылке строится не от корня приложения (application context - topjava), а от текущего контекста сервлета (servlet context), например:  
  `localhost:8080/topjava/meals'+'/meals`
  Также перестали работать стили, так как путь к статическим ресурсам тоже определяется неверно (посмотрите вкладку *Network* браузера).   
  Чтобы это исправить, добавим базовый URL в `headTag`:  
  `base href = "${pageContext.request.contextPath}/"`. **Теперь это станет url, от которой будут строиться все относительные ссылки на страницах**.

Также некоторые методы контроллера в результате работы должны не просто вернуть название view, который Spring MVC должен отобразить, а совершить *redirect*. Для этого при возврате имени view
дополнительно укажем ключевое слово `redirect:`, например, `redirect: /meals`.

Последняя проблема — некорректное отображение текста в кодировке UTF-8. Spring предоставляет для ее решения стандартный фильтр, который будет перехватывать все запросы и ответы сервера и устанавливать
им нужную кодировку: в `web.xml` подключим `encodingFilter`.

</details>

> Инжекцию в `AbstractUserServiceTest.jpaUtil` сделал [`@Lazy`: не иннициализировать бин до первого использования](https://www.logicbig.com/tutorials/spring-framework/spring-core/lazy-at-injection-point.html).

#### Apply 7_02_HW6_meals.patch

> сделал фильтрацию еды через `get`: операция идемпотентная, можно делать в браузере обновление по F5

### Внимание: чиним пути в следующем патче

При переходе на AJAX `JspMealController` удалим за ненадобностью, возвращение всей еды `meals()` останется в `RootController`.

#### Apply 7_03_HW6_fix_relative_url_utf8.patch

- <a href="http://stackoverflow.com/questions/4764405/how-to-use-relative-paths-without-including-the-context-root-name">
  Relative paths in JSP</a>
- <a href="http://docs.spring.io/spring/docs/3.2.x/spring-framework-reference/html/mvc.html#mvc-redirecting-redirect-prefix">
  Spring redirect: prefix</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFaXViWkkwYkF0eW8">HW6 Optional</a>

<details>
  <summary><b>Краткое содержание</b></summary>

#### Добавление еще одной роли для Admin

1. В файле популирования базы данных `populateDB.sql` добавим для admin дополнительную роль `ROLE_USER`.

2. В тестовых данных для него также добавим аналогичную роль.

> После этого тесты, которые связаны с методом `getAll()`, перестали работать, потому что для получения
> списка всех пользователей с их ролями в именованном запросе мы использовали **LEFT JOIN FETCH**.  
> Происходит объединение таблиц, в результирующей таблице вместо одной записи для админа появляются дублирующие записи для одного и того же пользователя.
> - простой способ решения - исключить из запроса **LEFT JOIN FETCH**. Роли все равно будут загружены, так как они FetchType.EAGER.
> - также можно добавить в запрос ключевое слово **DISTINCT(u)** - теперь в результирующей таблице будут содержаться только уникальные записи.

#### Добавление транзакционности в JDBC реализацию репозитория

Чтобы аннотация `@Transactional` стала работать во всех профилях Spring - в файле `spring-db.xml` вынесем из профиля jpa, dataJpa в общую конфигурацию для всех профилей тег:
```<tx:annotation-driven/>```

Для профиля jdbc настроим DatasourceTransactionManager, который будет управлять транзакциями:  
``
<bean id="transactionManager" class="org.springframework.jdbc.datasource.DataSourceTransactionManager">
<property name="dataSource" ref="dataSource" />
</bean>
``
После этого в JDBC-репозитории мы можем расставить аннотации `@Transactional` аналогично jpa репозиториям, и действия станут выполняться транзакционно (
напомню: `<logger name="org.springframework.orm.jpa" level="debug"/>` для логирования информации по транзакциям)

#### Чтобы JDBC репозиторий смог работать с множественными ролями пользователя:

У пользователя добавим сеттер для его ролей. Для JDBC-репозитория создадим вспомогательные методы для записи ролей в базу и их считывания из базы и установления пользователю. Запись ролей в базу будем
производить методом
`JdbcTemplate#batchUpdate`, в таком случае не будет обращения в базу для записи каждой конкретной роли, команды для записи ролей будут накоплены в один пакет и выполнятся за одно обращение к БД. Для
удобства работы с batch Spring предоставляет нам интерфейс `BatchPreparedStatementSetter`, с помощью которого мы определяем как будут устанавливаться параметры для запроса и количество запросов в
одном пакете. Также создадим метод `deleteRoles`, в котором будем удалять роли пользователя из базы (для обновления ролей в базе мы делаем просто: сначала удалим старые из базы и запишем туда новые).

> PS: в JPA с `@ElementCollection` и с параметром *cascade* в `@OneToMany` слияние (merge) изменений в связанных коллекциях происходит автоматически.

Если мы будем получать всех пользователей вместе с их ролями из базы с помощью JOIN, мы столкнемся с проблемой Декартова произведения: для каждого уникального пользователя количество записей в
результирующей таблице будет повторяться столько раз, сколько у него было ролей. Чтобы этого избежать, отдельным запросом получим из базы все роли, и сгруппируем их в `Map` по `userId`, где ключом
будет являться `userId`, а значением — набор ролей пользователя. После чего пройдемся по всем пользователям, загруженным из базы, и установим каждому его роли.
</details>

#### Apply 7_04_HW6_optional_add_role.patch

> - Для доставания ролей у нас дублируется `fetch = EAGER` и `LEFT JOIN FETCH u.roles` (можно делать что-то одно). Запросы выполняются по-разному: проверьте.

- Отключил `JdbcUserServiceTest` - роли не работают. Будем чинить в `7_06_HW6_jdbc_transaction_roles.patch`
- `DataJpaUserServiceTest.getWithMeals` не работает для admin (у админа 2 роли, и еда при JOIN дублируется). Чиним в следующем патче.

#### Apply 7_05_HW6_fix_hint_graph.patch

- В `DataJpaUserServiceTest.getWithMeals()` при дублировании еды `DISTINCT` при нескольких JOIN не помогает, оставил в `@EntityGraph` только `meals`.
- В `JpaUserRepositoryImpl.getByEmail` и `CrudUserRepository.getByEmail` DISTINCT попадает в запрос, хотя он там не нужен. Это просто указание Hibernate не дублировать данные. Для оптимизации можно
  указать Hibernate делать запрос без distinct: [15.16.2. Using DISTINCT with entity queries](https://docs.jboss.org/hibernate/orm/5.2/userguide/html_single/Hibernate_User_Guide.html#hql-distinct)
- Бага [HINT_PASS_DISTINCT_THROUGH does not work if 'hibernate.use_sql_comments=true'](https://hibernate.atlassian.net/browse/HHH-13280). При `hibernate.use_sql_comments=false` все работает - в SELECT
  нет DISTINCT.

Еще один вариант решения - в `User` сделать `Set<Meals>`. Интересно, что в ее реализации `PersistentSet`порядок соблюдается и `@OrderBy` работает.

#### Apply 7_06_HW6_jdbc_transaction_roles.patch

> - в `JdbcUserRepositoryImpl.getAll()` собираю роли из `ResultSet` напрямую в `map`
> - в `insertRoles` поменял метод `batchUpdate` и сделал проверку на empty
> - в `setRoles` достаю роли через `queryForList`

Еще интересные JDBC реализации:

- в `getAll()/ get()/ getByEmail()` делать запросы с `LEFT JOIN` и сделать реализацию `ResultSetExtractor`
- подключить зависимость `spring-data-jdbc-core`. Там есть готовый `OneToManyResultSetExtractor`. Можно посмотреть, как он реализован.
- реализация, зависимая от БД: доставать агрегированные роли и делать им `split(",")`. В этой реализации есть ограничение - одно поле из зависимой таблицы.

```
SELECT u.*, string_agg(r.role, ',') AS roles
FROM users u
  JOIN user_roles r ON u.id=r.user_id
GROUP BY u.id
```

### Валидация для `JdbcUserRepository` через Bean Validation API

#### Apply 7_07_HW6_optional_jdbc_validation.patch

- [Валидация данных при помощи Bean Validation API](https://alexkosarev.name/2018/07/30/bean-validation-api/).

На данный момент у нас реализована валидация сущностей только для jpa- и dataJpa-репозиториев. При работе через JDBC-репозиторий может произойти попытка записи в БД некорректных данных, что приведет
к `SQLException` из-за нарушения ограничений, наложенных на столбцы базы данных. Для того, чтобы перехватить невалидные данные еще до обращения в базу, воспользуемся API *javax.validation* (ее
реализация `hibernate-validator` используется для проверки данных в Hibernate и будет использоваться в Spring Validation, которую подключим позже). В `ValidationUtil` создадим один потокобезопасный
валидатор, который можно переиспользовать (см. *javadoc*).  
С его помощью в методах сохранения и обновления сущности в jdbc-репозиториях мы можем производить валидацию этой сущности: `ValidationUtil.validate(object);`
Чтобы проверка не падала, `@NotNull Meal.user` пришлось пока закомментировать. Починим в 10-м занятии через `@JsonView`.

### Отключение кэша в тестах:

Вместо наших приседаний с `JpaUtil` и проверкой профилей мы можем отключить Spring-кэш в тестах, подменив `spring-cache.xml` на тестовый (положив его в ресурсы тестов).   
Отключить кэширование можно через пустую реализацию `NoOpCacheManager` или, как сейчас, не включая `cache:annotation-driven`, который подключает обработку `@Cache`-аннотаций.   
Кэш Hibernate второго уровня отключаем через переопределение свойства `entityManagerFactory.jpaPropertyMap: hibernate.cache.use_second_level_cache=false` (кроме стандартного использования файла
пропертей, можно задать их прямо в конфигурации, через автодополнение в xml можно смотреть все варианты). Подкладываем новый `spring-cache.xml` в ресурсы тестов, он перекроет настройки кэша в
приложении. Остается удалить наши уже ненужные `JpaUtil` и `AbstractServiceTest.isJpaBased()`

#### Apply 7_08_HW06_optional2_disable_tests_cache.patch

- [Example of PropertyOverrideConfigurer](https://www.concretepage.com/spring/example_propertyoverrideconfigurer_spring)
- [Spring util schema](https://docs.spring.io/spring/docs/current/spring-framework-reference/core.html#xsd-schemas-util)

## Занятие 7:

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFQXhBN1pqa3FyOUE">Тестирование Spring MVC</a>

<details>
  <summary><b>Краткое содержание</b></summary>

#### Тестирование Spring MVC

Для более удобного сравнения объектов в тестах мы будем использовать библиотеку *Harmcrest* с Matcher'ами, которая позволяет делать сложные проверки. С *Junit* по умолчанию подтягивается *Harmcrest
core*, но нам потребуется расширенная версия:
в `pom.xml` из зависимости Junit исключим дочернюю `hamcrest-core` и добавим  `hamcrest-all`.

Для тестирования web создадим вспомогательный класс `AbstractControllerTest`, от которого будут наследоваться все тесты контроллеров. Его особенностью будет наличие `MockMvc` - эмуляции Spring MVC для
тестирования web-компонентов. Инициализируем ее в методе, отмеченном `@PostConstruct`:

 ```
mockMvc = MockMvcBuilders.webAppContextSetup(webApplicationContext).addFilter(CHARACTER_ENCODING_FILTER).build();
 ```

Для того, чтобы в тестах контроллеров не популировать базу перед каждым тестом, пометим этот базовый тестовый класс аннотацией `@Transactional`. Теперь каждый тестовый метод будет выполняться в
транзакции, которая будет откатываться после окончания метода и возвращать базу данных в исходное состояние. Однако теперь в работе тестов могут возникнуть нюансы, связанные с пропагацией транзакций:
все транзакции репозиториев станут вложенными во внешнюю транзакцию теста. При этом, например, кэш первого уровня станет работать не так, как ожидается. Т.е при таком подходе нужно быть готовыми к
ошибкам: мы их увидим и поборем в тестах на обработку ошибок на последних занятиях TopJava.

#### UserControllerTest

Создадим тестовый класс для контроллера юзеров, он должен наследоваться от `AbstractControllerTest`. В `MockMvc`
используется [паттерн проектирования Builder](https://refactoring.guru/ru/design-patterns/builder).

 ```
    mockMvc.perform(get("/users"))        // выполнить HTTP метод GET к "/users"
        .andDo(print())                   // распечатать содержимое ответа
        .andExpect(status().isOk())       // от контроллера ожидается ответ со статусом HTTP 200(ok)
        .andExpect(view().name("users"))  // контроллер должен вернуть view с именем "users"
        .andExpect(forwardedUrl("/WEB-INF/jsp/users.jsp")) // ожидается, что клиент должен быть перенаправлен на "/WEB-INF/jsp/users.jsp"
        .andExpect(model().attribute("users", hasSize(2))) // в модели должен быть атрибут "users" размером = 2
        .andExpect(model().attribute("users", hasItem(     // внутри которого есть элемент ...
        allOf(                                             
        hasProperty("id", is(START_SEQ)),                  // ...  с аттрибутом id = START_SEQ
        hasProperty("name", is(USER.getName()))            //...   и name = user
    )
   )));
}
 ```

В параметры метода `andExpect()` передается реализация `ResultMatcher`, в которой мы определяем как должен быть обработан ответ контроллера.

</details>

#### Apply 7_09_controller_test.patch

> - в `MockMvc` добавился `CharacterEncodingFilter`
> - поменял реализацию `ActiveDbProfileResolver`: в профили аттрибута `@ActiveProfiles(profiles=..)` он добавляет `Profiles.getActiveDbProfile()`
> - сделал вспомогательный метод `AbstractControllerTest.perform()`

- <a href="https://github.com/hamcrest/hamcrest-junit">Hamcrest</a>
- <a href="http://www.petrikainulainen.net/programming/spring-framework/unit-testing-of-spring-mvc-controllers-normal-controllers/">Unit Testing of Spring MVC Controllers</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png)  4. [Миграция на JUnit 5](https://drive.google.com/open?id=16wi0AJLelso-dPuDj6xaGL7yJPmiO71e)

<details>
  <summary><b>Краткое содержание</b></summary>

Для миграции на 5-ю версию JUnit в файле `pom.xml` поменяем зависимость `junit`
на `junit-jupiter-engine` ([No need `junit-platform-surefire-provider` dependency in `maven-surefire-plugin`](https://junit.org/junit5/docs/current/user-guide/#running-tests-build-maven)). Актуальную
версию всегда можно посмотреть [в центральном maven репозитории](https://search.maven.org/search?q=junit-jupiter-engine), берем только релизы (..-Mx означают предварительные milestone версии)
Изменять конфигурацию плагина `maven-sureface-plugin` в новых версиях JUnit уже не требуется. Junit5 не содержит в себе зависимости от *Harmcrest* (которую нам приходилось вручную отключать для JUnit4
в предыдущих шагах), поэтому исключение `hamcrest-core` просто удаляем. В итоге у нас останутся зависимости JUnit5 и расширенный Harmcrest.  
Теперь мы можем применить все нововведения пятой версии в наших тестах:

1. Для всех тестов теперь мы можем удалить `public`.
2. Аннотацию `@Before` исправим на `@BeforeEach` - теперь метод, который будет выполняться перед каждым тестом, помечается именно так.
3. В Junit5 работа с исключениями похожа на Junit4 версии 4.13: вместо ожидаемых исключений в параметрах аннотации `@Test(expected = Exception.class)` используется метод `assertThrows()`, в который
   первым аргументом мы передаем ожидаемое исключение, а вторым аргументом — реализацию функционального интерфейса `Executable` (кода теста, в котором ожидается возникновение исключения).
4. Метод `assertThrows()` возвращает исключение, которое было выброшено в переданном ему коде. Теперь мы можем получить это исключение, извлечь из него сообщение с помощью
   `e.getMessage()` и сравнить с ожидаемым.
5. Для теста на валидацию при проверке предусловия, только при выполнении которого будет выполняться следующий участок кода (например, в нашем случае тесты на валидацию выполнялись только в jpa
   профиле), - теперь нужно пользоваться утильным методом `Assumptions` (нам уже не требуется).
6. Проверку Root Cause - причины, из-за которой было выброшено пойманное исключение, мы будем делать позднее, при тестах на ошибки.
7. Из JUnit5 исключена функциональность `@Rule`, вместо них теперь нужно использовать `Extensions`, которые могут встраиваться в любую фазу тестов. Чтобы добавить их в тесты, пометим базовый тестовый
   класс аннотацией `@ExtendWith`.

JUnit предоставляет нам набор коллбэков — интерфейсов, которые будут исполняться в определенный момент тестирования. Создадим класс `TimingExtension`, который будет засекать время выполнения тестовых
методов.  
Этот класс будет имплементировать маркерные интерфейсы — коллбэки JUnit:

- `BeforeTestExecutionCallback` - коллбэк, который будет вызывать методы этого интерфейса перед каждым тестовым методом.
- `AfterTestExecutionCallback` - методы этого интерфейса будут вызываться после каждого тестового метода;
- `BeforeAllCallback` - методы перед выполнением тестового класса;
- `AfterAllCallback` - методы после выполнения тестового класса;

Осталось реализовать соответствующие методы, которые описываются в каждом из этих интерфейсов, они и будут вызываться JUnit в нужный момент:

- в методе `beforeAll` (который будет вызван перед запуском тестового класса) создадим спринговый утильный секундомер `StopWatch` для текущего тестового класса;
- в методе `beforeTestExecution` (будет вызван перед тестовым методом) - запустим секундомер;
- в методе `afterTestExecution` (будет вызван после тестового метода) - остановим секундомер.
- в методе `afterAll` (который будет вызван по окончанию работы тестового класса) - выведем результат работы этого секундомера в консоль;

8. Аннотации `@ContextConfiguration` и `@ExtendWith(SpringExtension.class)` (замена `@RunWith`) мы можем заменить одной `@SpringJUnitConfiguration` (в старых версиях IDEA ее не понимает)

</details>

#### Apply 7_10_JUnit5.patch

- [No need `junit-platform-surefire-provider` dependency in `maven-surefire-plugin`](https://junit.org/junit5/docs/current/user-guide/#running-tests-build-maven)
- [Наконец пофиксили баг с `@SpringJUnitConfig`](https://youtrack.jetbrains.com/issue/IDEA-166549)
- Добавил [`junit-platform-launcher` в pom для запуска JUnit 5 тестов из IDEA](https://youtrack.jetbrains.com/issue/IDEA-231927)
- [JUnit 5 homepage](https://junit.org/junit5)
- [Overview](https://junit.org/junit5/docs/snapshot/user-guide/#overview)
- [Миграция с JUnit4 на JUnit5: важные отличия и преимущества](https://topjava.ru/blog/migratsiya-s-junit4-na-junit5)
- [10 интересных нововведений](https://habr.com/post/337700)
- Дополнительно:
    - [Extension Model](https://junit.org/junit5/docs/current/user-guide/#extensions)
    - [A Guide to JUnit 5](http://www.baeldung.com/junit-5)
    - [Migrating from JUnit 4](http://www.baeldung.com/junit-5-migration)
    - [Before and After Test Execution Callbacks](https://junit.org/junit5/docs/snapshot/user-guide/#extensions-lifecycle-callbacks-before-after-execution)
    - [Conditional Test Execution](https://junit.org/junit5/docs/snapshot/user-guide/#writing-tests-conditional-execution)
    - [Third party Extensions](https://github.com/junit-team/junit5/wiki/Third-party-Extensions)
    - [Реализация assertThat](https://stackoverflow.com/questions/43280250)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5. [Принципы REST. REST контроллеры](https://drive.google.com/open?id=1e4ySjV15ZbswqzL29UkRSdGb4lcxXFm1)

<details>
  <summary><b>Краткое содержание</b></summary>

#### Принципы REST, REST-контроллеры

> [REST](http://spring-projects.ru/understanding/rest/) - архитектурный стиль проектирования распределенных систем (типа клиент-сервер).

Чаще всего в REST сервер и клиент общаются посредством обмена JSON-объектами через HTTP-методы GET/POST/PUT/DELETE/PATCH.  
Особенностью REST является отсутствие состояния (контекста) взаимодействий клиента и сервера.

В нашем приложении есть контроллеры для Admin и для User. Чтобы сделать их REST-контроллерами, заменим аннотацию `@Controller` на `@RestController`

> Не поленитесь зайти чз Ctrl+Click в `@RestController`: к аннотации `@Controller` добавлена `@ResponseBody`. Т.е. ответ от нашего приложения будет не имя View, а данные в теле ответа.

В `@RequestMapping`, кроме пути для методов контроллера (`value`) добавляем параметр `produces = MediaType.APPLICATION_JSON_VALUE`. Это означает, что в заголовки ответа будет добавлен
тип `ContentType="application/json"` - в ответе от контроллера будет приходить JSON-объект.

> Чтобы было удобно использовать путь к этому контроллеру в приложении и в тестах,
> выделим путь к нему в константу REST_URL, к которой можно будет обращаться из других классов

1. Метод `AdminRestController.getAll` пометим аннотацией `@GetMapping` - маршрутизация к методу по HTTP GET.

2. Метод `AdminRestController.get` пометим аннотацией `@GetMapping("/{id}")`.  
   В скобках аннотации указано, что к основному URL контроллера будет добавляться `id` пользователя - переменная, которая передается в запросе непосредственно в URL.  
   Соответствующий параметр метода нужно пометить аннотацией `@PathVariable` (если имя в URL и имя аргумента метода не совпадают, в параметрах аннотации дополнительно нужно будет уточнить имя в URL.
   Если они совпадают, [этого не требуется](https://habr.com/ru/post/440214/).

3. Метод создания пользователя `create` отметим аннотацией `@PostMapping` - маршрутизация к методу по HTTP POST. В метод мы передаем объект `User` в теле запроса (аннотация `@RequestBody`) и в формате
   JSON (`consumes = MediaType.APPLICATION_JSON_VALUE`). При создании нового ресурса правила хорошего тона - вернуть в заголовке ответа URL созданного ресурса. Для этого возвращем не `User`,
   а `ResponseEntity<User>`, который мы можем с помощью билдера `ServletUriComponentsBuilder` дополнить заголовком ответа `Location` и вернуть статус `CREATED(201)`
   (если пойти в код `ResponseEntity.created` можно докопаться до сути, очень рекомендую смотреть в исходники кода).

4. Метод `delete` помечаем `@DeleteMapping("/{id}")` - HTTP DELETE. Он ничего не возвращает, поэтому помечаем его аннотацией `@ResponseStatus(HttpStatus.NO_CONTENT)`. Статус ответа будет HTTP.204;

5. Над методом обновления ставим `@PutMapping` (HTTP PUT). В аргументах метод принимает `@RequestBody User user` и `@PathVariable int id`.

6. Метод поиска по `email` также помечаем `@GetMapping`, и, чтобы не было конфликта маршрутизации с методом `get()`, указываем в URL добавку "/by". В этот метод `email` передается как параметр
   запроса, аннотация `@RequestParam`.

> **Все это СТАНДАРТ архитектурного стиля REST. НЕ придумывайте ничего своего в своих выпускных проектах! Это очень большая ошибка - не придерживаться стандартов API.**

7. `ProfileRestController` выполняем аналогичным способом с учетом того, что пользователь имеет доступ только к своим данным.

Если на данном этапе попытаться запустить приложение и обратиться к какому-либо методу контроллера, сервер ответит нам ошибкой со статусом 406, так как Spring не знает, как преобразовать объект User в
JSON...

</details>

#### Apply 7_11_rest_controller.patch

> - Переделал URL поиска по email на `/by-email`

- <a href="http://spring-projects.ru/understanding/rest/">Понимание REST</a>
- <a href="https://ru.wikipedia.org/wiki/JSON">JSON (JavaScript Object Notation)</a>
- [15 тривиальных фактов о правильной работе с протоколом HTTP](https://habrahabr.ru/company/yandex/blog/265569/)
- [10 Best Practices for Better RESTful](https://medium.com/@mwaysolutions/10-best-practices-for-better-restful-api-cbe81b06f291)
- [Best practices for rest nested resources](https://stackoverflow.com/questions/20951419/what-are-best-practices-for-rest-nested-resources)
- <a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html#mvc-ann-requestmapping">
  Request mapping</a>
- [Лучшие практики разработки REST API: правила 1-7,15-17](https://tproger.ru/translations/luchshie-praktiki-razrabotki-rest-api-20-sovetov/)
- Дополнительно:
    - [Подборка практик REST](https://gist.github.com/Londeren/838c8a223b92aa4017d3734d663a0ba3)
    - <a href="http://www.infoq.com/articles/springmvc_jsx-rs">JAX-RS vs Spring MVC</a>
    - <a href="http://habrahabr.ru/post/144011/">RESTful API для сервера – делаем правильно (Часть 1)</a>
    - <a href="http://habrahabr.ru/post/144259/">RESTful API для сервера – делаем правильно (Часть 2)</a>
    - <a href="https://www.youtube.com/watch?v=Q84xT4Zd7vs&list=PLoij6udfBncivGZAwS2yQaFGWz4O7oH48">И. Головач. RestAPI</a>
    - [value/name в аннотациях @PathVariable и @RequestParam](https://habr.com/ru/post/440214/)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 6. [Тестирование REST контроллеров. Jackson.](https://drive.google.com/open?id=1aZm2qoMh4yL_-i3HhRoyZFjRAQx-15lO)

<details>
  <summary><b>Краткое содержание</b></summary>

Для работы с JSON добавляем в `pom.xml` зависимость `jackson-databind`.    
Актуальную версию библиотеки можно посмотреть в [центральном maven-репозитории](https://search.maven.org/artifact/com.fasterxml.jackson.core/jackson-databind).  
Теперь спринг будет автоматически использовать эту библиотеку для сериализации/десериализации объектов в JSON (найдя ее в *classpath*).  
Если сейчас запустить приложение и обратиться к методам REST-контроллера, то оно выбросит `LazyInitializationException`. Оно возникает из-за того, что у наших сущностей есть лениво загружаемые поля,
отмеченные `FetchType.LAZY` - при загрузке сущности из базы, вместо этого поля подставится Proxy, который и должен вернуть реальный экземпляр этого поля при первом же обращении. Jackson при
сериализации в JSON использует все поля сущности, и при обращении к *Lazy* полям возникает исключение, так как сессия работы с БД в этот момент уже закрыта, и нужный объект не может быть
инициализирован. Чтобы Jackson игнорировал эти поля, пометим их аннотацией `@JsonIgnore`.

Теперь при запуске приложения REST-контроллер будет работать. Но при получении JSON объектов мы можем увидеть, что Jackson сериализовал объект через геттеры (например в ответе есть поле `new` от
метода `Persistable.isNew()`). Чтобы учитывались только поля объектов, добавим над `AbstractBaseEntity`:

````java
@JsonAutoDetect(fieldVisibility = ANY, // jackson видит все поля
        getterVisibility = NONE, // ... но не видит геттеров
        isGetterVisibility = NONE, //... не видит геттеров boolean полей
        setterVisibility = NONE) // ... не видит сеттеров
````

Теперь все сущности, унаследованные от базового класса, будут сериализоваться/десериализоваться через поля.

</details>

#### Apply 7_12_rest_test_jackson.patch

- [Jackson databind github](https://github.com/FasterXML/jackson-databind)
- [Jackson Annotation Examples](https://www.baeldung.com/jackson-annotations)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 7. [Кастомизация Jackson Object Mapper](https://drive.google.com/open?id=1CM6y1JhKG_yeLQE_iCDONnI7Agi4pBks)

<details>
  <summary><b>Краткое содержание</b></summary>

Сейчас, чтобы не сериализовать *Lazy* поля, мы должны пройтись по каждой сущности и вручную пометить их аннотацией `@JsonIgnore`. Это неудобно, засоряет код и допускает возможные ошибки. К тому же,
при некоторых условиях, нам иногда нужно загрузить и в ответе передать эти *Lazy* поля.  
Чтобы запретить сериализацию Lazy полей для всего проекта, подключим в `pom.xml` библиотеку `jackson-datatype-hibernate`.  
Также изменим сериализацию/десериализацию полей объектов в JSON: не через аннотацию `@JsonAutoDetect`, а в классе `JacksonObjectMapper`, который унаследуем от `ObjectMapper` (стандартный Mapper,
который использует Jackson) и сделаем в нем другие настройки. В конструкторе:

- регистрируем `Hibernate5Module` - модуль `jackson-datatype-hibernate`, который не делает сериализацию ленивых полей.
- модуль для корректной сериализации `LocalDateTime` в поля JSON - `JavaTimeModule` модуль библиотеки `jackson-datatype-jsr310`
- запрещаем доступ ко всем полям и методам класса и потом разрешаем доступ только к полям
- не сериализуем null-поля (`setSerializationInclusion(JsonInclude.Include.NON_NULL)`)

Чтобы подключить наш кастомный `JacksonObjectMapper` в проект, в конфигурации `spring-mvc.xml` к настройке `<mvc:annotation-driven>` добавим `MappingJackson2HttpMessageConverter`, который будет
использовать наш маппер.

</details>

#### Apply 7_13_jackson_object_mapper.patch

- Сериализация hibernate lazy-loading с помощью <a href="https://github.com/FasterXML/jackson-datatype-hibernate">
  jackson-datatype-hibernate</a>
- <a href="https://geowarin.github.io/jsr310-dates-with-jackson.html">Handle Java 8 dates with Jackson</a>
- Дополнительно:
    - <a href="https://www.sghill.net/how-do-i-write-a-jackson-json-serializer-deserializer.html">Jackson JSON Serializer & Deserializer</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 8. [Тестирование REST контроллеров через JSONassert и Матчеры](https://drive.google.com/open?id=1oa3e0_tG57E71g6PW7_tfb3B61Qldctl)

<details>
  <summary><b>Краткое содержание</b></summary>

Сейчас в тестах REST-контроллера мы проводим проверку только на статус ответа и тип возвращаемого контента. Добавим проверку содержимого ответа.

#### 7_14_json_assert_tests

Чтобы сравнивать содержимое ответа контроллера в виде JSON и сущность, воспользуемся библиотекой
`jsonassert`, которую подключим в `pom.xml` со scope *test*.

Эта библиотека при сравнении в тестах в качестве ожидаемого значения ожидает от нас объект в виде JSON-строки. Чтобы вручную не преобразовывать объекты в JSON и не хардкодить их в виде строк в наши
тесты, воспользуемся Jackson.  
Для преобразования объектов в JSON и обратно создадим утильный класс `JsonUtil`, в котором с помощью нашего `JacksonObjectMapper` и будет конвертировать объекты.  
И мы сталкиваемся с проблемой: `JsonUtil` - утильный класс и не является бином спринга, а для его работы требуется наш кастомный маппер, который находится под управлением спринга и расположен в
контейнере зависимостей. Поэтому, чтобы была возможность получить наш маппер из других классов - сделаем его синглтоном и сделаем в нем статический метод, который будет возвращать его экземпляр.
Теперь `JsonUtil` сможет его получить.  
И нам нужно указать спрингу, чтобы он не создавал второй экземпляр этого объекта, а клал в свой контекст существующий. Для этого в конфигурации `spring-mvc.xml` определим factory-метод, с помощью
которого спринг должен получить экземпляр (instance) этого класса:

```xml

<bean class="ru.javawebinar.topjava.web.json.JacksonObjectMapper" id="objectMapper" factory-method="getMapper"/>
```  

а в конфигурации `message-converter` вместо создания бина просто сошлемся на сконфигурированный `objectMapper`.

Метод `ContentResultMatchers.json()` из `spring-test` использует библиотеку `jsonassert` для сравнения 2-х JSON строк: одну из ответа контроллера и вторую - JSON-сериализация `admin` без
поля `registered` (это поле инициализируется в момент создания и отличается). В методе `JsonUtil.writeIgnoreProps` мы преобразуем объект `admin` в мапу, удаляем из нее игнорируемые поля и снова
сериализуем в JSON.

Также сделаем тесты для утильного класса `JsonUtil`. В тестах мы записываем объект в JSON-строку, затем конвертируем эту строку обратно в объект и сравниваем с исходным. И то же самое делаем со
списком объектов.

#### 7_15_tests_refactoring

**`RootControllerTest`**

Сделаем рефакторинг `RootControllerTest`. Ранее мы в тесте получали модель, доставали из нее сущности и с помощью `hamcrest-all`
производили по одному параметру их сравнение с ожидаемыми значениями. Метод `ResultActions.andExpect()` позволяет передавать реализацию интерфейса `Matcher`, в котором можно делать любые сравнения.
Функциональность сравнения списка юзеров по ВСЕМ полям у нас уже есть - мы просто делегируем сравнение объектов в `UserTestData.MATCHER`. При этом нам больше не нужен `harmcrest-all`, нам достаточно
только `harmcrest-core`.

**`MatcherFactory`**

Теперь вместо `jsonassert` и сравнения JSON-строк в тестах контроллеров сделаем сравнения JSON-объектов через `MatcherFactory`. Преобразуем ответ контроллера из JSON в объект и сравним с эталоном
через уже имеющийся у нас матчер.  
Вместо сравнения JSON-строк в метод `andExpect()` мы будем передавать реализации интерфейса `ResultMatcher` из `MATCHER.contentJson(..)`.

`MATCHER.contentJson(..)` принимают ожидаемый объект и возвращают для него `ResultMatcher` с реализацией единственного метода `match(MvcResult result)`, в котором делегируем сравнение уже существующим
у нас матчерам. Мы берем JSON-тело ответа (`MatcherFactory.getContent`), десериализуем его в объект (`JsonUtil.readValue/readValues`) и сравниваем через имеющийся `MATCHER.assertMatch`
десериализованный из тела контроллера объект и ожидаемое значение.

> Методы из класса `TestUtil` перенес в `MatcherFactory`, лишние удалил.

**`AdminRestControllerTest`**

- `getByEmail()` - сделан по аналогии с тестом `get()`. Дополнительно нужно дополнить строку URL параметрами запроса.
- `delete()` - выполняем HTTP.DELETE. Проверяем статус ответа 204. Проверяем, что пользователь удален.

> Раньше я получал всех users из базы и проверял, что среди них нет удаленного. При этом тесты становятся чувствительными ко всем users в базе и ломаются при добавлении-удалении новых тестовых данных.

- `update()` - выполняем HTTP.PUT. В тело запроса подаем сериализованный `JsonUtil.writeValue(updated)`. После выполнения проверяем, что объект в базе обновился.
- `create()` - выполняем HTTP.POST аналогично `update()`. Но сравнить результат мы сразу не можем, т.к. при создании объекта ему присваивается `id`.  
  Поэтому мы извлекаем созданного пользователя из ответа (`MATCHER.readFromJson(action)`), получаем его `id`, и уже с этим `id` эталонный объект мы можем сравнить с объектом в ответе контроллера и со
  значением в базе.
- `getAll()` - аналогично get(). Список пользователей из ответа в формате JSON сравниваем с эталонным списком (`MATCHER.contentJson(admin, user)`).

Тесты для `ProfileRestController` выполнены аналогично.

</details>

#### Apply 7_14_json_assert_tests.patch

> - В `JsonUtil.writeIgnoreProps` вместо цикла по мапе сделал `map.keySet().removeAll`

- [JSONassert](https://github.com/skyscreamer/JSONassert)
- [Java Code Examples for ObjectMapper](https://www.programcreek.com/java-api-examples/index.php?api=com.fasterxml.jackson.databind.ObjectMapper)

#### Apply 7_15_tests_refactoring.patch

> - Сделал внутренний класс `MatcherFactory.Matcher`, который возвращается из фабрики матчеров.
> - Методы из класса `TestUtil` перенес в `MatcherFactory`, лишние удалил.
> - Раньше в тестах я для проверок получал всех users из базы и сравнивал с эталонным списком. При этом тесты становятся чувствительными ко всем users в базе и ломаются при добавлении-удалении новых тестовых данных.

- [Java @SafeVarargs Annotation](https://www.baeldung.com/java-safevarargs)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 9. [Тестирование через SoapUi. UTF-8](https://drive.google.com/open?id=0B9Ye2auQ_NsFVXNmOUdBbUxxWVU)

<details>
  <summary><b>Краткое содержание</b></summary>

SOAP UI - это один из инструментов для тестирования API приложений, которые работают по REST и по SOAP.  
Он позволяет нам по HTTP протоколу дернуть методы нашего API и увидеть ответ контроллеров.

Если в контроллер мы добавим метод, который в теле ответа будет возвращать текст на кириллице, то мы увидим кодировка теряться. Для сохранения кодировки используем `StringHttpMessageConverter`,
который конфигурируем в `spring-mvc.xml`. При этом мы должны явно указать, что конвертор будет работать только с текстом в кодировке *UTF-8*.

</details>

#### Apply 7_16_soapui_utf8_converter.patch

- Инструменты тестирования REST:
    - <a href="https://www.soapui.org/downloads/soapui/">SoapUi</a>
    - [Что такое Curl? Как работает эта команда?](https://highload.today/curl/)
    - <a href="http://rus-linux.net/lib.php?name=/MyLDP/internet/curlrus.html">Написание HTTP-запросов с помощью Curl</a>.  
      Для Windows 7 можно использовать Git Bash, с Windows 10 v1803 можно прямо из консоли. Возможны проблемы с UTF-8:
        - [CURL doesn't encode UTF-8](https://stackoverflow.com/a/41384903/548473)
        - [Нстройка кодировки в Windows](https://support.socialkit.ru/ru/knowledge-bases/4/articles/11110-preduprezhdenie-obnaruzhenyi-problemyi-svyazannyie-s-raspoznavaniem-russkih-simvolov)
    - **[IDEA: Tools->HTTP Client->...](https://www.jetbrains.com/help/idea/rest-client-tool-window.html)**
    - <a href="https://www.getpostman.com/">Postman</a>
    - [Insomnia REST client](https://insomnia.rest/)

**Импортировать проект в SoapUi из `config\Topjava-soapui-project.xml`. Response смотреть в формате JSON.**

> Проверка UTF-8: <a href="http://localhost:8080/topjava/rest/profile/text">http://localhost:8080/topjava/rest/profile/text</a>

[ResponseBody and UTF-8](http://web.archive.org/web/20190102203042/http://forum.spring.io/forum/spring-projects/web/74209-responsebody-and-utf-8)

## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы

> Зачем у нас и UIController'ы, и RestController'ы? То есть в общем случае backend-разработчику недостаточно предоставить REST-api и RestController?

Часто используются и те и другие. REST обычно используют для отдельного UI например на React или Angular или для интеграции / мобильного приложения.
У нас REST контроллеры используются только для тестирования. UI мы используем для нашего приложения на JSP шаблонах.
Таких сайтов без богатой UI логики тоже немало. Например https://javaops.ru/ :)  
Разница в обработке запросов:

- из UI контроллеров возвращаются как готовые HTML странички, так и данные в формате JSON (будет для AJAX запросов в следующих занятиях)
- для UI мы используем только GET и POST запросы
- при создании-обновлении в UI мы принимаем данные из формы `application/x-www-form-urlencoded` (посмотрите вкладку `Network`, не в формате JSON)
- для REST запросы GET, POST, PUT, DELETE, PATCH и возвращают только данные (обычно JSON)

И в способе авторизации:

- для RESТ у нас будет базовая авторизация
- для UI - через cookies

Также часто бывают смешанные сайты - где есть и отдельное JS приложение и шаблоны.

> При выполнении тестов через MockMvc никаких изменений на базе не видно, почему оно не сохраняет?

`AbstractControllerTest` аннотируется `@Transactional` - это означает, что тесты идут в транзакции, и после каждого теста JUnit делает rollback базы.

> Что получается в результате выполнения запроса `SELECT DISTINCT(u) FROM User u LEFT JOIN FETCH u.roles ORDER BY u.name, u.email`? В чем разница в SQL без `DISTINCT`.

Запросы SQL можно посмотреть в логах. Т.е. `DISTINCT` в `JPQL` влияет на то, как Hibernate обрабатывает дублирующиеся записи (с `DISTINCT` их исключает). Результат можно посмотреть в тестах или
приложении, поставив брекпойнт. По поводу `SQL DISTINCT` не стесняйтесь пользоваться google, например, [оператор SQL DISTINCT](http://2sql.ru/novosti/sql-distinct/)

> В чем заключается расширение функциональности hamcrest в нашем тесте, что нам пришлось его отдельно от JUnit прописывать?

`hamcrest-all` используется в проверках `RootControllerTest`: `org.hamcrest.Matchers.*`. JUnit 4 включает в себя `hamcrest-core`, в JUnit 5 его нужно подключать отдельно.

> Jackson мы просто подключаем в помнике, и Spring будет с ним работать без любых других настроек?

Да, Spring смотрит в classpath и если видит там Jackson, то подключает интеграцию с ним.

> Где-то слышал, что любой ресурс по REST должен однозначно идентифицироваться через url без параметров. Правильно ли задавать URL для фильтрации в виде `http://localhost/topjava/rest/meals/filter/{startDate}/{startTime}/{endDate}/{endTime}` ?

Так делают, только при отношении <a href="https://ru.wikipedia.org/wiki/Диаграмма_классов#.D0.90.D0.B3.D1.80.D0.B5.D0.B3.D0.B0.D1.86.D0.B8.D1.8F">
агрегация</a>, например, если давать админу право смотреть еду любого юзера, URL мог бы быть похож на `http://localhost/topjava/rest/users/{userId}/meals/{mealId}` (не рекомендуется, см ссылку ниже).
В случае критериев поиска или страничных данных они передаются как параметр. Смотри также:

- [15 тривиальных фактов о правильной работе с протоколом HTTP](https://habrahabr.ru/company/yandex/blog/265569/)
- <a href="https://medium.com/@mwaysolutions/10-best-practices-for-better-restful-api-cbe81b06f291">10 Best Practices for Better RESTful
- [REST resource hierarchy (если кратко: не рекомендуется)](https://stackoverflow.com/questions/15259843/how-to-structure-rest-resource-hierarchy)

> Что означает конструкция в `JsonUtil`: `reader.<T>readValues(json)`;

См. <a href="https://docs.oracle.com/javase/tutorial/java/generics/methods.html">Generic Methods</a>. Когда компилятор не может вывести тип, можно его уточнить при вызове generic метода. Неважно,
static или нет.

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW07

- 1: Добавить тесты контроллеров:
    - 1.1 `RootControllerTest.getMeals` для `meals.jsp`
    - 1.2 Сделать `ResourceControllerTest` для `style.css` (проверить `status` и `ContentType`)
- 2: Реализовать `MealRestController` и протестировать его через `MealRestControllerTest`
    - 2.1 следите, чтобы url в тестах совпадал с параметрами в методе контроллера. Можно добавить логирование `<logger name="org.springframework.web" level="debug"/>` для проверки маршрутизации.
    - 2.2 в параметрах `getBetween` принимать `LocalDateTime` (конвертировать через <a href="http://blog.codeleak.pl/2014/06/spring-4-datetimeformat-with-java-8.html">@DateTimeFormat with Java 8
      Date-Time API</a>), пока без проверки на `null` (используя `toLocalDate()/toLocalTime()`, см. Optional п.3). В тестах передавать в формате `ISO_LOCAL_DATE_TIME` (
      например `'2011-12-03T10:15:30'`).

### Optional

- 3: Переделать `MealRestController.getBetween` на параметры `LocalDate/LocalTime` c раздельной фильтрацией по времени/дате, работающий при `null` значениях (см. демо и `JspMealController.getBetween`)
  . Заменить `@DateTimeFormat` на свои LocalDate/LocalTime конверторы или форматтеры.
    -  [Spring Type Conversion and Field Formatting — пишем первый конвертер или форматтер](https://habr.com/ru/post/703402/)
- 4: Протестировать `MealRestController` (SoapUi, curl, IDEA Test RESTful Web Service, Postman). Запросы `curl` занести в отдельный `md` файл (или `README.md`)
- 5: Добавить в `AdminRestController` и `ProfileRestController` методы получения пользователя вместе с едой (`getWithMeals`, `/with-meals`).
    - [Jackson – Bidirectional Relationships](https://www.baeldung.com/jackson-bidirectional-relationships-and-infinite-recursion)

### Optional 2

- 6: Сделать тесты на методы контроллеров `getWithMeals()` (п.5)

**На следующем занятии используется JavaScript/jQuery. Если у вас там пробелы, <a href="https://github.com/JavaOPs/topjava#html-javascript-css">пройдите его основы</a>**

---------------------

## ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Типичные ошибки и подсказки по реализации

- 1: Ошибка в тесте _Invalid read array from JSON_ обычно расшифровывается немного ниже: читайте внимательно.
- 2: <a href="https://urvanov.ru/2016/12/03/jackson-и-неизменяемые-объекты/">Jackson и неизменяемые объекты</a> (для сериализации MealTo)
- 3: Если у meal, приходящий в контроллер, поля `null`, проверьте `@RequestBody` перед параметром (данные приходят в формате JSON)
- 4: При проблемах с собственным форматтером убедитесь, что в конфигурации `<mvc:annotation-driven...` не дублируется
- 5: Тесты сервисов у нас идут на все профили работы с БД (JDBC, JPA и DATAJPA), а контроллеров - только на Profiles.REPOSITORY_IMPLEMENTATION.
Проверьте выполнение тестов контроллера через _maven test_ для каждого из профилей (JDBC, JPA и DATAJPA). Обратите внимание, что `getWithMeals()` реализован только для DATAJPA, для JDBC и JPA тесты  `getWithMeals()` должны игнорироваться. Также, в случае проблем, проверьте, что не портите эталонный образец из `MealTestData`
- 6: `@Autowired` в тестах нужно делать в том месте, где класс будет использоваться. Общий принцип: не размазывать код по классам, объявление переменных держать как можно ближе к ее использованию,
  группировать (не смешивать) код с разной функциональностью.
- 7: Попробуйте в `RootControllerTest.getMeals` сделать сравнение через `model().attribute("meals", expectedValue)`. Учтите, что вывод результатов через `toString` к сравнению отношения не имеет.

# Стажировка <a href="https://github.com/JavaWebinar/topjava">Topjava</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFfkpMd2UyWjBsc2JsSE4tRDFkU3BvMktFQkhUN1J6VExxSUUzOHlSR0RhNm8">Материалы занятия</a>

- **Браузер кэширует javascript и css. Если изменения не работают, обновите приложение в браузере (в хроме `Ctrl+F5`)**
- **При удалении файлов не забывайте делать clean: `mvn clean`**
 
### ![correction](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Правки в проекте

#### Apply 8_0_fix.patch
- Время еды приходит с UI с точностью до минут
- Профили в `SpringMain` больше не нужны

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW7

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. [HW7](https://drive.google.com/file/d/1h6wg2V9yZoNX7fA7mNA7w7Kxp8IACsIJ)

  <details>
  <summary><b>Краткое содержание</b></summary>

#### Тесты ResourceController
Прежде всего в настройках логирования для класса `ExceptionHandlerExceptionResolver`
установим уровень "debug". Теперь в логах мы сможем увидеть запросы, у которых проблемы с маппингом.  
Чтобы протестировать доступ к ресурсам, создадим `ResourceControllerTest` с единственным тестовым методом.
Класс `MediaType` позволяет указать требуемый тип с помощью фабричного метода `valueOf`.  
Начиная с [Spring 4.3 ожидаемый тип ответа нужно сравнивать с помощью `contentTypeCompatibleWith`](https://github.com/spring-projects/spring-framework/issues/19041), а не `contentType`
(в этом случае кодировка UTF-8 в типе ответа не учитывается в сравнении).

#### Тесты для RootController на еду
Для `RootController` тесты на еду делаем точно так же, как и на `User`, с небольшим отличием.  
Так как `MealTo` - это транспортный объект, который не является Entity и не находится под управлением
JPA, у него нет ограничений по методам `equals / hashCode`, и мы можем
добавить свои (сгенерировать с помощью IDEA). Теперь в тестах объекты `MealTo` мы можем сравнивать
через `equals()`.  
Чтобы убедиться что два списка `MealTo` - ожидаемый, и полученный от контроллера, сравниваются поэлементно
через `equals`, мы можем установить в сравнении брекпоинт и запустить тест в режиме дебага.

#### Реализовать MealRestController
`MealRestController` реализуем аналогично контроллерам пользователей.
В метод `MealRestController#getBetween` с параметрами запроса нужно передать
время и дату начала и конца диапазона, для которого будет найдена еда. Это можно сделать с помощью аннотации `@DateTimeFormat(iso = DateTimeFormat.ISO.DATE_TIME)`.
Spring автоматически конвертирует параметры запроса в объекты типа `LocalDateTime`.

В `MealRestControllerTest` нужно обратить внимание на тесты
для методов `get` и `getBetween` контроллера, так как они возвращают список `MealTo`, а не `Meal`.  
Поэтому для сравнения списков еды создадим отдельный `TO_MATCHER` с помощью статического фабричного метода `usingEqualsComparator(MealTo.class)`:
```
public static MatcherFactory.Matcher<MealTo> TO_MATCHER = MatcherFactory.usingEqualsComparator(MealTo.class)
```  
Он будет сравнивать `MealTo` уже не рекурсивно, а с помощью `MealTo#equals()` &mdash; сравнения в методах `assertMatch` переделал с использованием реализаций интерфейса `BiConsumer`:
*assertion* и *iterableAssertion*.  Получается очень гибко (привет, паттерн "стратегия"): для создания матчера мы можем использовать любые собственные реализации сравнений.

Для того чтобы для тестов создать объекты `MealTo`, используем утилитный метод `MealsUtil#createTo`, изменив у него модификатор доступа на *public*.

Для некоторых методов с переменным количеством аргументов IDEA сообщает о небезопасности типов. Чтобы подавить эти
предупреждения, над методами у нас стоят аннотации `@SafeVarargs` (для использования этой аннотации метод должен быть `final`).

Чтобы Jackson мог сериализовать/десериализовать объекты `MealTo`, нам нужно сделать для этого класса сеттеры, или создать конструктор, помеченный специальной аннотацией `@ConstructorProperties`,
в параметры которой передаем поля объекта json, соответствующие аргументам конструктора.

</details>



#### Apply 8_01_HW07_controller_test.patch

- [Persistent classes implementing equals and hashcode](https://docs.jboss.org/hibernate/orm/4.3/manual/en-US/html_single/#persistent-classes-equalshashcode): переопределять `equals()/hashCode()`
  необходимо, если
    - использовать Entity в `Set` (рекомендовано для many-ассоциаций) либо как ключи в `HashMap`
    - использовать _reattachment of detached instances_ (т.е. манипулировать одним Entity в нескольких транзакциях/сессиях).
- Оптимально использовать уникальные неизменяемые бизнес-поля, но обычно таких нет, и чаще всего используется суррогатный PK с ограничением, что он может быть `null` у новых объектов и нельзя объекты сравнивать
  через `equals` в бизнес-логике (например, в тестах).
- [Equals() and hashcode() when using JPA and Hibernate](https://stackoverflow.com/questions/1638723)

------------------------

#### Apply 8_02_HW07_rest_controller.patch
> - В `MealTo` вместо изменяемых полей и конструктора без параметров сделал [`@ConstructorProperties`](https://www.logicbig.com/tutorials/misc/jackson/constructor-properties.html). `Immutable` классы
    всегда предпочтительнее для данных.
- [Паттерн стратегия](https://refactoring.guru/ru/design-patterns/strategy).

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFLXZ3OHdac18yZlk">HW7 Optional</a>

  <details>
  <summary><b>Краткое содержание</b></summary>

#### Собственный Spring-конвертер (форматтер) для даты и времени
Spring фраймворк с помощью встроенных конвертеров (реализующих интерфейс `org.springframework.core.convert.converter.Converter`) и форматтеров (интерфейс `org.springframework.format.Formatter`) делает автоматическое преобразование параметров запроса из одного типа в другой.  
В нашем случае параметры фильтрации еды - дата и время - по REST приходят в виде строки, и мы можем добавить свой конвертер или форматтер, чтобы он автоматически приводил их к нужному нам типу.
> - Конвертер Spring преобразует объект одного типа в объект другого типа
> - Форматер преобразует объект типа String в объект нужного типа (при этом может поддерживать локаль)

Сделаем собственные форматтеры для преобразования строки в дату и время `DateTimeFormatters`, добавим в `spring-mvc.xml` бин `conversionService` с перечнем наших форматтеров и сделаем на него ссылку:
```
<mvc:annotation-driven conversion-service="conversionService">
```  
`LocalTimeFormatter` и `LocalDateFormatter` - наши кастомные форматтеры, которые будут парсить строку параметра. Для этого они должны реализовывать
интерфейс `Formatter<Целевой тип>` и переопределять его методы `#parse` и `#print`. Теперь мы можем убрать аннотации `@DateTimeFormat` из аргументов `MealRestController#getBetween`. `conversionService` будет
искать среди форматеров или конвертеров те, которые смогли бы преобразовать параметр-строку в объект соответствующего типа, объявленный в методе контроллера, и в результате будут использованы наши кастомные форматеры.  
Для новой реализации метода `getBetween` теперь создадим несколько тестов - с различным набором параметров (в том числе и с пустыми параметрами).

#### Протестировать сервисы с помощью SoapUI
Помимо SoapUI, для тестирования REST можно использовать команду *curl* через *Git Bash* (этот способ имеет свои недостатки - не поддерживается UTF8).
Для запросов требуется указывать Content-Type, иначе контроллер не сможет обработать запрос.  
Также популярными средствами тестирования REST являются *Postman* и в IDEA: *Tools->HTTP Client*.
> Для тестирования REST у вас должен быть запущен Tomcat с вашим приложением!

</details>


#### Apply 8_03_HW07_formatters.patch

> - Перенес форматтеры в подпакет `web`, т.к. они используются Spring MVC
> - Заменил `@RequestParam(required = false)` на `@RequestParam @Nullable`

#### Apply 8_04_HW07_soapui_curl.patch

> Добавил примеры запросов curl в `config/curl.md`

- <a href="http://rus-linux.net/lib.php?name=/MyLDP/internet/curlrus.html">Написание HTTP-запросов с помощью Curl</a> (для Windows можно использовать Git Bash)
- В IDEA появился отличный инструмент тестирования запросов. Для конвертации
  в [Tools->HTTP Client->Test RESTful Web Service](https://www.jetbrains.com/help/idea/http-client-in-product-code-editor.html) скопируйте curl без флага `-s`

### Внимание! curl команды, требуемые в ТЗ к выпускному проекту, сделайте в `readme.md`, НЕ НАДО делать в выпускном проекте отдельный `curl.md`.

###  ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. [HW7 Optional: getWithMeals + тесты](https://drive.google.com/file/d/13cjenXzWDr52HTTzleomOd-yjPAEAbOA)

  <details>
  <summary><b>Краткое содержание</b></summary>

В нашем приложении у `Meal` есть ссылка на `User`, а в `User` есть ссылка на коллекцию `Meal`.
Таким образом, мы имеем дело с *BiDirectional* циклической зависимостью. При сериализации через Jackson у нас возникнут проблемы, так как он перейдет в
бесконечный цикл при переходе по ссылкам сущностей друг на друга.  
Возможно следующее разрешение циклических зависимостей:

- над полем `Meal.user` добавить аннотацию `@JsonBackReference`, теперь для еды это поле не будет сериализоваться в json;
- над коллекцией `User.meals` добавить аннотацию `@JsonManagedReference`, поле будет сериализоваться.

Теперь для получения пользователя с едой в методах контроллера можно просто вызвать соответствующий метод сервиса.

Для новой функциональности создадим дополнительные тесты. В тестовых данных для пользователей заполним поля *meals*.  
Чтобы сразу проверять пользователя вместе с его едой, создадим дополнительный `UserTestData.WITH_MEALS_MATCHER`, который будет сравнивать сущности с помощью переданных ему интерфейсов сравнения.
Коллекции пользователей с едой мы не реализуем, поэтому `iterableAssertion` также делать не нужно, бросаем `UnsupportedOperationException`.

Так как метод получения пользователя с едой у нас реализован только в профиле datajpa, в тестах перед выполнением метода нужно проверить, что текущий профиль Spring  - `dataJpa`, тесты будут пропускаться для других профилей.
Такую функциональность мы ранее уже реализовывали - внедряем в тестовый класс `Environment` и проверяем активный профиль с помощью `Assumptions#assumeTrue`.

</details>

#### Apply 8_05_HW07_with_meals.patch
#### Apply 8_06_HW07_test_with_meals.patch
> Изменения в AssertJ: `ignoringAllOverriddenEquals` для рекурсивных сравнений не нужен. См. [overridden equals used before 3.17.0](https://assertj.github.io/doc/#assertj-core-recursive-comparison-ignoring-equals)

## Занятие 8:

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4.  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFUmVsM3V6djMzYmc">WebJars. jQuery and JavaScript frameworks</a>

  <details>
  <summary><b>Краткое содержание</b></summary>

**WebJars** — библиотеки на стороне клиента (JavaScript библиотека и/или CSS модуль), упакованные в JAR.

Добавим в наш проект в `pom.xml` дополнительные зависимости - библиотеки JavaScript и css:
- *jQuery* - самая распространенная утилитная JavaScript-библиотека;
- *Bootstrap* - фреймворк CSS-стилей;
- *Datatables* - плагин для отрисовки таблиц;
- *datetimepicker* - плагин для работы с датой и временем;
- *noty* - для работы с уведомлениями;

</details>

#### Apply 8_07_webjars.patch

> - Обновил jQuery до 3.x, Bootstrap до 4.x
    >   - <a href="https://tproger.ru/translations/new-features-of-jquery-3/">Новое в jQuery 3</a>
> - УБРАЛ из проекта <a href="http://dandelion.github.io">Dandelion обертку к Datatables</a>
    >   - не встречал нигде, кроме Spring Pet Clinic;
    >   - поддержка работы с Datatables через Dandelion оказалось гораздо более трудоемкой, чем работа с плагином напрямую.
> - Исключил ненужные зависимости

- Подключение веб-ресурсов. <a href="http://www.webjars.org/">WebJars</a>.
- <a href="http://www.jamesward.com/2012/04/25/introducing-webjars-web-libraries-as-managed-dependencies">Introducing WebJars</a>
- <a href="https://ru.wikipedia.org/wiki/Document_Object_Model">Document Object Model (DOM)</a>
- <a href="https://css-tricks.com/dom/">What is the DOM?</a>
- <a href="https://ru.wikipedia.org/wiki/JQuery">jQuery</a>
- <a href="http://stackoverflow.com/questions/7062775/is-jquery-a-javascript-library-or-framework">Is jQuery a javascript library or framework</a>
- <a href="https://www.datatables.net/">DataTables</a>
- <a href="http://www.sitepoint.com/working-jquery-datatables/">Working with jQuery DataTables</a>

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5. [Bootstrap](https://drive.google.com/file/d/1RHtzw8OQt6guCu6xe3apT7F9EfiX96tr)

  <details>
  <summary><b>Краткое содержание</b></summary>

Front-end нашего приложения будет строиться на основе фреймворка Bootstrap.
> В новой версии Bootstrap 5 из зависимостей исключена библиотека jQuery, и весь необходимый функционал Bootstrap делается на простом JavaScript. Однако JQuery нам нужна для *Datatables* и плагинов, поэтому не стал переходить на 5-ю версию.

По ссылке [Bootstrap Examples](https://getbootstrap.com/docs/4.6/examples/) приведены примеры сайтов на Bootstrap. Из перечня уже готовых шаблонов можно выбрать
подходящий шаблон, скопировать из его исходного кода стили, форматирование и использовать в своем проекте.
- В `spring-mvc.xml` мы должны явно указать маппинг на *WebJars*-ресурсы, с которыми будет работать приложение:
````xml
    <mvc:resources mapping="/webjars/**" location="classpath:/META-INF/resources/webjars/"/>
````  
- В `headTag.jsp`, который у нас сейчас добавляется через `jsp:include` в начало каждой JSP страницы, подтягиваем из *WebJars* нужные нам *css*-ресурсы и иконку для нашего приложения.
- Для отрисовывания стандартных иконок подключается ресурс `<link rel="stylesheet" href="webjars/noty/3.1.4/demo/font-awesome/css/font-awesome.min.css">`.  
  В класс иконок `.fa` добавим `cursor: pointer` - это курсор-рука, который обычно используется для кнопок.
- В стили добавим sticky-footer - это footer, который будет включаться в конце JSP-страниц и приклеиваться к нижней части экрана.
- JSP-страницу со списком пользователей оформим с использованием элементов Bootstrap и добавим иконки на кнопки.
- на странице `index.jsp` форму выбора пользователя поместим в класс Bootstrap *jumbotron* - крупный выносной элемент с большим текстом и большими отступами
- таблицей пользователей в `users.jsp` поместим в аналогичный элемент *jumbotron*
</details>

#### Apply 8_08_bootstrap4.patch

> - [WIKI Bootstrap](https://ru.wikipedia.org/wiki/Bootstrap_(фреймворк))
> - Добавил <a href="https://www.w3schools.com/icons/fontawesome_icons_intro.asp">Font Awesome</a>
    >   - [Map glyphicon icons to font-awesome](https://gist.github.com/blowsie/15f8fe303383e361958bd53ecb7294f9)
> - В `headTag.jsp` в ссылку на `style.css` добавил `?v=2`. Стили изменились, изменяя версию в параметре мы заставляем браузер не брать их из кэша, а загружать заново.

- [Bootstrap](https://getbootstrap.com/)
    - [Navbar](https://getbootstrap.com/docs/4.1/components/navbar/)
    - [Spacing](https://getbootstrap.com/docs/4.1/utilities/spacing/)
    - [Forms](https://getbootstrap.com/docs/4.1/components/forms/)
    - [Sticky footer](https://getbootstrap.com/docs/4.1/examples/sticky-footer/)
- [Документация Bootstrap на русском](https://bootstrap-4.ru/)
- Дополнительно
    - <a href="http://www.tutorialrepublic.com/twitter-bootstrap-tutorial/">Twitter Bootstrap Tutorial</a>
    - <a href="https://www.youtube.com/playlist?list=PLVfMKQXDAhGUxJ4prQSC2K13-YlYj8LgB">Видеоуроки Bootstrap 4</a>
    - [Bootstrap верстка современного сайта за 45 минут](https://www.youtube.com/watch?v=46q2eB7xvXA)

## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы

> А где реально этот путь "classpath:/META-INF/resources/webjars"?

Внутри подключаемых webjars ресурсы лежат по пути `/META-INF/resources/webjars/...` Не поленитесь посмотреть на них через `Ctrl+Shift+N`. Все подключаемые jar попадают в classpath, и ресурсы доступны
по этому пути.

> У меня webjars-зависимость лежит внутри ".m2\repository\org\webjars\". С чем это может быть связано?

Maven скачивает все зависимости в local repository, который по умолчанию находится в `~/.m2`. Каталог по умолчанию можно переопределить в `APACHE-MAVEN-HOME\conf\settings.xml`,
элемент `localRepository`.

> WEBJARS лежат вообще в другом месте WEB-INF\lib\. Биндим mapping="/webjars/*" на реальное положение jar в war-e, откуда Spring знает, где искать наш jQuery?

В war в `WEB-INF/lib/*` лежат все jar, которые попадают к classpath. Spring при обращении по url `/webjars/` ищет по пути
биндинга `<mvc:resources mapping="/webjars/ " location="classpath:/META-INF/resources/webjars/"/>`
по всему classpath (то же самое, как распаковать все jar в один каталог) в `META-INF/resources/webjars/`. В этом месте во всех jar, которые мы подключили из webjars, лежат наши ресурсы.

> Оптимально ли делать доступ к статическим ресурсам (css, js, html) через webjars ?

На продакшене под нагрузкой статические ресурсы лучше всего держать не в war, а снаружи. Доступ к ним делается либо
через <a href="https://www.techsupper.com/2017/05/serve-static-resources-from-external-folder-outside-webapps-tomcat.html">конфигурирование Tomcat</a>.  
Но чаще всего для доступа к статике ставят прокси, например <a href="https://nginx.org/ru/">Nginx</a>

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 6. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFcGs4b1IyWWF2S2c">AJAX. Datatables. jQuery</a>

<details>
  <summary><b>Краткое содержание</b></summary>

**AJAX** (асинхронный JavaScript и XML) — подход к построению интерактивных пользовательских интерфейсов веб-приложений, заключающийся в "фоновом" обмене данными браузера с веб-сервером.

#### AdminUIController
У нас будут отдельные от REST UI-контроллеры, так как в них будут отличаться обработка исключений, некоторая логика и авторизация.  
В `AdminUIController` метод `#create` будет использоваться как для создания, так и для обновления пользователя в зависимости от значения `id`.

#### Список пользователей
Оформляем таблицу пользователей с помощью js/css библиотеки `Datatables`. Таблица должна иметь id (в нашем случае "datatable"), чтобы к ней можно было обращаться.  
Также на страницу добавляем форму, с помощью которой будем редактировать и добавлять пользователей.
Форма имеет скрытое поле `id`, которое будет использоваться в наших js-скриптах.

#### topjava.users.js
> Код по сравнению с видео изменился! Про изменения я говорю в конце видео и перечислил их после *Краткого содержания*

Для работы AJAX объявляем переменные:
- *ajaxUrl* - адрес нужного endpoint контроллера
- *datatableApi* - объект таблицы `datatable`

Страница html имеет определенный жизненный цикл, в процессе которого с ней совершаются какие-то действия.  
Одно из таких действий - загрузка, после которого мы можем производить какие-то манипуляции на странице.  
С помощью jQuery мы определяем коллбэк-метод, который будет вызываться после загрузки страницы:
```
$(function () {
   ...
```
Строчка
```
datatableApi = $("#datatable").DataTable(
``` 
преобразует HTML-элемент c *id=datatable* в javaScript-объект с помощью метода `DataTable` библиотеки *Datatables*.
Параметр этого метода - объект-конфигурация, который задает опции отображения таблицы и в "columns" задает соответствие колонок таблицы полям приходящего с сервера JSON-объекта пользователей.
Внизу конфигурации добавляется сортировка таблицы по первому столбцу.
После этого вызывается метод `makeEditable()` (он находится в `topjava.common.js`).

#### topjava.common.js

- В `makeEditable` к событию *click* всех объектов HTML c классом *delete* привязываем вызов метода `deleteRow`. Параметром берем аттрибут `id` текущего элемента `$(this)`.

- Метод `add` вызывается из `users.jsp` по нажатию на кнопку "Добавить":  `onclick="add()"`. В нем
    - обнуляются все поля `input` формы `detailsForm`:  `$("#detailsForm").find(":input").val("")`
    - вызывается входящий в Bootstrap метод `modal()`, который преобразует HTML-элемент `id=editRow` в модальное окно. [Botstrap4 Modal](https://getbootstrap.com/docs/4.6/components/modal)

- В методе `deleteRow` делаем AJAX-запросы к серверу и по после их успешного выполнения вызываем обновление таблицы.

- В `updateTable` по AJAX запрашиваем с сервера массив пользователей, в случае успеха очищаем таблицу и заполняем ее данными, полученными с сервера.

- В `save` средствами jQuery сериализуем форму `id=detailsForm` в JSON-объект и методом POST отдаем эти данные. После успешного выполнения запроса закрываем модальное окно и обновляем таблицу.

Intellij IDEA предоставляет нам возможность дебага кода JavaScript. См. видео для примера.

#### Загрузка HTML
По умолчанию при стандартной загрузке страницы с js-скриптами браузер будет:
- Парсить нужную HTML-страницу;
- Как только браузер сталкивается с тегом `<script>`, он останавливает отрисовку страницы и подгружает нужные скрипты. Далее продолжает загружать страницу, останавливаясь на загрузку скриптов, которые
  ему будут встречаться. Пока все скрипты не будут отработаны, браузер всю страницу не отрисует.

Поэтому определение css-стилей обычно размещают в самом начале HTML документа, а JavaScript - в конце документа, чтобы пользователь увидел отрисованную страницу, не дожидаясь загрузки скриптов.
Но более современный подход - загружать JavaScript асинхронно, в фоне. Чтобы скрипты загружались асинхронно, используется специальный атрибут тега *async* -
тогда скрипты и HTML-страница будут загружаться одновременно. Если необходимо соблюдать порядок загрузки скриптов, который определен на странице, вместо
атрибута *async* используется атрибут *defer*. У нас загрузка скриптов сделана через *defer* и вынесена во фрагмент `headTag` - скрипты будут загружаться в
фоне, и это не будет тормозить загрузку страницы.
Для корректного отображения Datatables в Bootstrap добавлены дополнительные `dataTables.bootstrap4`-стили и js-скрипты.

Для удобства дебага js-скрипты вынесены в отдельные файлы и сделан небольшой рефакторинг.
</details>


JSP полезны, если надо с сервера отдать статический html с серверной логикой (условия, циклы), сформированный на основе модели. Для динамической отрисовки таблицы мы будем использовать AJAX запрос в 9-м уроке (работа с Datatables через AJAX).

По дебагу JavaScript из IDEA проверьте:

- в IDEA плагин `JavaScript Debugger`
- [Chrome extension is not required for debugging since 2017.3](https://intellij-support.jetbrains.com/hc/en-us/community/posts/360010507240-where-is-JETBRAINS-IDE-SUPPORT-chrome-extension-it-cant-be-found-anywhere-now-on-the-internet)
- при проблемах с портами [удалите в настройках IDEA файлы `~\AppData\Roaming\JetBrains\IntelliJIdea2020.x\options\web-browsers.xml` и `other.xml`](https://intellij-support.jetbrains.com/hc/en-us/community/posts/360009567459-Webstorm-2020-2-1-Remote-Debugging-do-not-work)

#### Apply 8_09_ajax_datatables.patch

> - Переименовал js-скрипты по [javascript filename naming convention](https://stackoverflow.com/questions/7273316/what-is-the-javascript-filename-naming-convention)
> - `reset()` не чистит скрытые (hidden) поля формы. Сделал очистку полей через `form.find(":input").val("")`
> - Поменял форматирование модального окна: [Botstrap4 Modal](https://getbootstrap.com/docs/4.6/components/modal/)
> - URL с  `/ajax/admin/users` поменял на `/admin/users`

JavaScript

- <a href="https://ru.wikipedia.org/wiki/AJAX">AJAX</a>
- <a href="https://learn.javascript.ru/introduction-browser-events">Введение в браузерные события</a>
- [Скрипты: async, defer](https://learn.javascript.ru/script-async-defer)
- [With defer, in the head](https://flaviocopes.com/javascript-async-defer/#with-defer-in-the-head)
- <a href="http://stackoverflow.com/questions/436411/where-should-i-put-script-tags-in-html-markup/24070373#24070373">JavaScript loading modern approach</a>

jQuery

- <a href="http://ruseller.com/jquery.php?id=124">Событие $(document).ready</a>.
- <a href="http://anton.shevchuk.name/jquery/">jQuery для всех</a>.
- <a href="http://anton.shevchuk.name/javascript/jquery-for-beginners-ajax/">jQuery для начинающих. AJAX</a>.
- <a href="http://anton.shevchuk.name/javascript/jquery-for-beginners-selectors/">jQuery для начинающих. Селекторы</a>.
- [jQuery task from freecodecamp](https://www.freecodecamp.org/map-aside#nested-collapsejQuery)
- <a href="http://api.jquery.com/">jQuery API</a>

DataTables/Bootstrap

- <a href="http://datatables.net/reference/api/">DataTables API</a>
- <a href="http://bootstrap-ru.com/203/javascript.php">Javascript плагины для Bootstrap</a>
- <a href="https://datatables.net/examples/styling/bootstrap4">DataTables/Bootstrap 4 integration</a>
- <a href="https://datatables.net/upgrade/1.10-convert">Converting parameter names for 1.10</a>
- <a href="http://stackoverflow.com/questions/25207147/datatable-vs-datatable-why-is-there-a-difference-and-how-do-i-make-them-w">dataTable() vs. DataTable()</a>

## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы

> Что делает код?

```
$('.delete').click(function () {
        deleteRow($(this).attr("id"));
    });
```

На все элементы DOM с классом `delete` вешается обработчик события `click` который вызывает функцию `deleteRow`. См. [селекторы в jQuery](http://anton.shevchuk.name/javascript/jquery-for-beginners-selectors/)

> Как в таблицу `<table id="datatable">` из JSP вставляются дополнительные `div`, поле для поиска, стрелочки для сортировки и т.д. (видны в браузере через `Inspect (Ctrl+Shift+I)` в хроме) ?

JSP отдает html на клиента, в браузере исполняется скрипт `$("#datatable").DataTable(..)`, который модифицирует элемент таблицы и вставляет туда (в элементы DOM html документа) все табличные плюшки.

> Как выполняется сценарий по запросу `http://localhost:8080/topjava/users` ?

**Обязательно смотрите в браузере вкладку Networks**

1. `RootController` принимает GET-запрос, достает из репозитория юзеров и отдает их `users.jsp` для формирования таблицы. На следующем занятии мы поменяем сценарий - данные для таблицы для
   первоначальной отрисовки будут доставаться по AJAX.
2. Сформированный `users.jsp` отдается в браузер клиента.
3. Страница и js-скрипты, подключенные в `users.jsp`, загружаются в браузер.
4. После загрузки страницы по событию `onload` вызывается `$(function ()` из `topjava.users.js`. В ней компонент `#datatable` делается табличкой `DataTable` и вызывается `makeEditable()`
   из `topjava.common.js`.
5. В `makeEditable()` вешается `click` на элементы с классом `.delete`

Все. Приложение ждет дальнейших запросов от клиента.

> Тянет ли Bootstrap за собой jQuery?

Да, до версии 5 Bootstrap зависит от jQuery: http://stackoverflow.com/questions/14608681/can-i-use-twitter-bootstrap-without-jquery#answer-14608772  
В новой Bootstrap 5 он реализует функционал (например модальное окно) без jQuery, собственным JavaScript. Но нам jQuery нужен для таблицы и плагинов.

#### Apply 8_10_refactor_js.patch
>  - Сделал [объект `ctx` (контекст) для глобальных переменных](https://stackoverflow.com/a/5064235/548473)
>  - `datatableApi` присваиваю в функции `makeEditable`, куда ее передаю параметром
>  - Вынес переменную `form = $('#detailsForm')` (инициализирую только один раз)
>  - При удалении строки добавил [подтверждение confirm](https://stackoverflow.com/questions/10462839/how-to-display-a-confirmation-dialog-when-clicking-an-a-link)
>  - [В `jquery.ajax` заменил depricated `success` на `done()`](http://api.jquery.com/jquery.ajax/#jqXHR)
>  - В HTML атрибут id у каждого элемента документа должен быть уникален, а у нас в `users.jsp` дублировались `id`. Переместил атрибут `id` в тэг `<tr>` и в `makeEditable` достаю его через селектор jQuery `closest('tr')`.

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 7. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFMTVWaXdWRUZsUEE"> Notifications</a>

  <details>
  <summary><b>Краткое содержание</b></summary>

#### Отрисовка всплывающих подсказок
В `topjava.common.js` создадим всплывающие подсказки. При успешном событии вызывается `successNoty`, при ошибке - `failNoty`.
Ошибку не будем закрывать автоматически, как успешные события, а будем хранить в переменной `failNote`.
Она закрывается по клику на сообщение и при любом успешном событии через вызов `closeNote`.  
В функциях по удалению и сохранению пользователей добавили вызов успешного уведомления.

На случай, если AJAX-запрос завершится неуспешно (например, произойдет исключение на сервере), помимо действия *succes/done* в AJAX-запросе мы можем определить и действие *fail*, которое выполнится при статусе ответа, отличном от 2xx.
Исключения для всех AJAX запросов мы будем обрабатывать одинаково, поэтому, чтобы не дублировать код в каждой функции, определим общую функцию `fail`, которая будет срабатывать для
всех неуспешных AJAX ответов:
```
$(document).ajaxError(function (event, jqXHR, options, jsExc) {
    failNoty(jqXHR);
})
```
</details>


#### Apply 8_11_notification.patch

> - Сделал [защиту от кэширование AJAX запросов в IE](https://stackoverflow.com/a/4303862/548473)
> - Обновил API Noty (3.x), добавил в сообщения font-awesome
> - [Tomcat 8.5.x перестал отдавать в заголовке `statusText`](http://tomcat.apache.org/tomcat-8.5-doc/changelog.html). Отображаем просто `status`
    >   - RFC 7230 states that clients should ignore reason phrases in HTTP/1.1 response messages. Since the reason phrase is optional, Tomcat no longer sends it (statusText).

- <a href="http://ruseller.com/jquery.php?id=2">Обработка ajaxError</a>.
- <a href="http://ned.im/noty/">jQuery notification</a>

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 8. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFRVkzcFMwc0hrYmM">Добавление Spring Security</a>

  <details>
  <summary><b>Краткое содержание</b></summary>

Прежде всего в файл `pom.xml` нужно подключить зависимости `spring-security-web` и `spring-security-config`.  
Чтобы Spring Security смог перехватывать и проверять все запросы к серверу, в `web.xml` нужно добавить дополнительный фильтр - `springSecurityFilterChain`.  
Spring Security может работать не только на уровне web, но и на уровне всего приложения, поэтому в `spring-app.xml` импортируем конфигурацию `spring-security.xml`, в которой
описаны настройки безопасности и сконфигурированы бины Spring Security.

В конфигурации `spring-security.xml`:
```xml
<http pattern="/resources/**" security="none"/> <!--отключаем security для статических ресурсов..-->
<http pattern="/webjars/**" security="none"/> <!-- и библиотек webjars -->

        <!--Для всех запросов, которые будут соответствовать паттерну "/rest/**" (запросы к REST контроллерам)-->
        <!--включаем авторизацию, включаем возможность использования expressionLanguage для проверки доступа -->
        <!--и отключаем создание сессии (сессия будет использоваться для UI контроллеров, будем смотреть на нее позже) -->
    <http pattern="/rest/**" use-expressions="true" name="restSecurityFilterChain" create-session="stateless">
        <http-basic/> <!--Будет использоваться базовая авторизация, логин и пароль будут передаваться в заголовке запроса, закодированные в Base64 (открыто) -->

        <!--Чтобы обратиться к endpoint с паттерном "/rest/admin/**", пользователь должен иметь роль ADMIN-->
        <intercept-url pattern="/rest/admin/**" access="hasRole('ADMIN')"/>

        <!--Ко всем остальным endpoint будут иметь доступ только аутентифицированные пользователи-->
        <intercept-url pattern="/**" access="isAuthenticated()"/>

        <!--Выключаем защиту от межсайтовой подделки запросов, будем смотреть на нее и включим позже-->
        <csrf disabled="true"/>
    </http>

        <!-- Конфигурируем хранение пароля в открытом виде (сделаем шифрацию позднее) -->
    <beans:bean name="noopEncoder" class="org.springframework.security.crypto.password.NoOpPasswordEncoder"/>

        <!--Настройка аутентификации пользователей -->
    <authentication-manager>
        <authentication-provider>
            
            <!-- Кодировщик паролей -->
            <password-encoder ref="noopEncoder"/>
            
            <!-- Явно задаем данные пользователей в конфигурации (изменим на следующем уроке на реальные, из базы) -->
            <user-service>
                <user name="user@yandex.ru" password="password" authorities="ROLE_USER"/>
                <user name="admin@gmail.com" password="admin" authorities="ROLE_ADMIN"/>
            </user-service>
        </authentication-provider>
    </authentication-manager>
</beans:beans>
```  
Теперь обратиться к REST-контроллерам приложения можно только с логином и паролем пользователей, которых мы прописали в конфигурации.
Чтобы отправить запрос к REST-контроллеру из любого клиента, нужно к запросу добавить заголовок `Authorization` c логином и паролем в формате login:password, закодированными в формате Base64
или же в `curl` передавать их через параметр *--user*.

</details>

Картинка
https://bs-uploads.toptal.io/blackfish-uploads/uploaded_file/file/412345/image-1602672495860.085-952930c83f53503d7e84d1371bec3775.png

> - Правка к видео: путь в `intercept-url` должен быть полный: `pattern="/rest/admin/**"`
> - В Spring Security 4.x по умолчанию включен CSRF (защита от <a href="https://ru.wikipedia.org/wiki/Межсайтовая_подделка_запроса">межсайтовой подделки запроса</a>). Выключил, включим на 10-м занятии.
> - В Spring Security 5.x по умолчанию пароль кодируется. Выключил, включим на 10-м занятии.

- [Adding a Password Encoder](https://docs.spring.io/spring-security/reference/servlet/appendix/namespace/authentication-manager.html#nsa-password-encoder)

#### Apply 8_12_add_security.patch

> Обновил версии Spring и Spring Data JPA, не забудьте кнопку *Reload All Maven Projects* и `mvn clean`   
> Недавно вышла новая версия Spring 6.0, Spring Data JPA 3.0. Они все используют пакет _jakarta_ и включены в недавний релиз Spring Boot 3.0.
> В конце курса мы мигрируем наше приложение на последний Spring Boot 3.0   

- <a href="http://projects.spring.io/spring-security/">Spring Security</a>
- <a href="https://ru.wikipedia.org/wiki/Протокол_AAA">Протокол AAA</a>
- <a href="https://ru.wikipedia.org/wiki/Аутентификация_в_Интернете">Методы аутентификации</a>.
- <a href="https://en.wikipedia.org/wiki/Basic_access_authentication">Basic access authentication</a>
- <a href="http://articles.javatalks.ru/articles/17">Использование ThreadLocal</a>
- <a href="http://www.baeldung.com/security-spring">Security with Spring</a>
- [Decode/Encode Base64 online](http://decodebase64.com/)

#### Вместо

`curl -v -H 'Authorization: Basic dXNlckB5YW5kZXgucnU6cGFzc3dvcmQ=' http://localhost:8080/topjava/rest/profile/meals`

#### в выпускных проектах используйте эквивалентный

`curl -v --user user@yandex.ru:password http://localhost:8080/topjava/rest/profile/meals`

## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы

> Как можно в браузере сбросить введенный пароль базовой авторизации?

Проще всего делать новый запрос в новой анонимной вкладке (`Ctrl+Shift+N` в Chrome)

> Как по REST определяется залогиненный юзер? Аутентификация происходит при каждом запросе?

<a href="http://stackoverflow.com/questions/319530/restful-authentication">Способы RESTful Authentication</a>. Мы будем использовать 2:
- Basic Authentication для REST контроллеров с аутентификацией при каждом запросе
- cookie + http session для UI-контроллеров на следующем уроке

> Почему при выполнении тестов `AdminRestControllerTest` не задействуется Spring Security?

Для этого в `MockMvc` надо явно добавлять security filter. Будем делать на следующем уроке.

> Почему `@RequestParam` не работает в запросах PUT и DELETE?

По спецификации Servlet API параметры в теле для методов PUT, DELETE, TRACE не обрабатываются (только в url). Можно:
- использовать POST
- передавать параметры в url
- использовать `HttpPutFormContentFilter` фильтр
- настроить Tomcat в обход спецификации.
  См. <a href="http://stackoverflow.com/a/14568899/548473">Handle request parameters for an HTTP PUT method</a>

> Данные между браузером и AJAX гоняются в виде json? Почему в `AdminUIController`  у методов `delete` и `create` нет в аннотациях параметра `consumes = MediaType.APPLICATION_JSON_VALUE` ?

Посмотреть на данные между приложением и браузером можно (**и нужно!**) в браузере (вкладка Network в Инструментах разработчика, F12 в Хроме). Формат зависит от того,
как они отправляются из браузера и из приложения. Данные формы обычно передаются просто параметрами. `APPLICATION_JSON_VALUE` в контроллере нужно, только если параметры отдаются/принимаются в формате JSON.

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW08

- 1: Перевести `meals` на `Datatables` (изменить `meals.jsp`, вместо `JspMealController` будет `MealUIController`).
    - 1.1 Реализовать добавление записи еды через модальное окно Bootstrap и удаление еды по AJAX (БЕЗ редактирования).
    - 1.2 При вставке данных по AJAX пропадает все JSP-форматирование, чинить перерисовку НЕ надо. Следующий урок - будем делать Datatables по AJAX и форматирование на стороне клиента.

### Optional
- 2: Перевести работу фильтра на AJAX.
    - [Руководство по выбору между GET и POST](https://handynotes.ru/2009/08/get-versus-pos.html)
- 3: Сделать кнопку сброса фильтра.
- 4: Реализовать `enable/disable` юзера
    - 4.1 Через checkbox в `users.jsp` с сохранением в DB. Неактивных пользователей выделить css стилем. Проверьте, как у вас первоначально (или по F5) отображаются неактивные пользователи (если
      меняете css при `enable/disable`)
    - 4.2 Добавить метод `enable` в `AdminRestController` и протестировать его в `AdminRestControllerTest` и в сервисах

### Optional 2
- 5: Попробуйте после модификации таблицы (например, после добавления записи) обновлять ее также с учетом фильтра (как в [демо](http://topjava.herokuapp.com/)).
---------------------

## ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Подсказки по HW08

- 1: `enable/disable` можно реализовать как на уровне репозитория, так и на уровне сервиса через несколько SQL, которые должны быть в одной транзакции (`@Transactional`)
- 2: в `topjava.common.js` следует вынести только общие скрипты (cкрипты еды размещайте в  `topjava.meals.js`, пользователей - в `topjava.users.js`)
- 3: если в контроллер приходит `null`, проверьте в `Network`-вкладке DevTools браузера, в каком формате приходят данные и в каком формате в контроллере вы их принимаете (`consumes`)
- 4: при реализации `enable/disable` лучше явно указывать нужное состояние, чем переключать на противоположное. Если параллельно кто-то изменит состояние, то будет несоответствие UI и DB
 - 5: Ошибка в браузере _DataTables warning: ... Requested unknown parameter ..._ может иметь несколько причин:
   - названия столбца в конфигурации таблицы и поля в json ответе от REST контроллера не совпадают. Проверьте имя в конфигурации DataTable `"columns" [{"data": "..."}, ...` и JSON ответ контроллера 
   - у вас неверный маппинг. При запросе по ajax данных для отрисовки `DataTables` должны приходить JSON данные таблицы, а у вас вместо JSON приходит ,нарпимер, HTML страничка с UI контроллера
   - неверный формат даты - должен быть `DateTimeFormat.ISO.DATE_TIME` с "T" разделителем  
**Смотрим ответ сервера во вкладке _Network_ браузера (F12->Network в Хроме)**  

# Стажировка <a href="https://github.com/JavaWebinar/topjava">TopJava</a>

## <a href="https://drive.google.com/drive/folders/0B9Ye2auQ_NsFVWRGbEw1RjJrMjg">Материалы занятия</a>

- **[Запускать браузер с чистым кэшем в режиме ингогнито](https://github.com/JavaOPs/topjava/wiki/IDEA#cache)**
- **При удалении файлов не забывайте делать clean: `mvn clean package`**

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW8

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. [HW8 + Optional 2,3](https://drive.google.com/file/d/1ZxmXrhz3K4V-mLkOOrH-JVtl5x0KSpIj)

<details>
  <summary><b>Краткое содержание</b></summary>

#### Перевод таблицы еды на Datatables

- Для удаления и обновления еды мы будем использовать иконки - теперь мы можем удалить `delete` и `update` из файлов локализации.
- Создавать/редактировать еду будем в модальном окне - удаляем форму `mealForm.jsp`
- Для полей фильтрации будем использовать форму Bootstrap "Grid System", поэтому css стили для формы фильтра (`dl, dd, dt`) также можем удалить.

Вместо того, чтобы в `makeEditable` вешать обработчики событий на все элементы страницы с классом `delete`, сделаем обработчик события прямо в JSP: `onclick="deleteRow(${user.id})"`. Функция будет
вызываться при нажатии на кнопку и в нее автоматически будет передаваться `id` пользователя или еды.

> Возможно тут мой выбор расходится с распространенным, где положено отделять html от JavaScript. Я опять склоняюсь в сторону KISS.

Для таблицы еды, в отличие от таблицы пользователей, требуется обновление с учетом параметров фильтрации (*Optional2*), поэтому мы используем различные стратегии обновления для этих таблиц. Функции
обновления таблицы инициализируются в контексте `ctx.updateTable` и вызываться в `topjava.common.js`. Из `updateTable` будем вызывать функцию `updateTableByData(data)`, которая обновляет таблицу
переданными ей данными.  
В `topjava.users.js` код

```
    updateTable: function () {
        $.get(userAjaxUrl, updateTableByData);
    }
```

через jQuery делает AJAX GET запрос и полученные данные автоматически передает в `updateTableByData`. Для еды (в`topjava.meals.js`) `updateTable` по `id=filter` получает форму фильтрации, с помощью jQuery `serialize()`
сериализует ее поля и отправляет запросом GET в `MealUIController#getBetween`. Отфильтрованную еду в коллбэке `done` передаем в `updateTableByData`. Функцию `ctx.updateTable()` вешаем на `onclick`
кнопки фильтрации в `meals.jsp`. И она же будет вызываться из `topjava.common.js` при любом обновлении таблицы.

Вместо `MealJspController` используем `MealUiController`, он маппиться по URL `/profile/meals`, так как еда принадлежит конкретному пользователю (находится в его профиле).

> **Внимание! Не делайте в выпускном проекте путь `/profile/...` к ресурсам, которые НЕ принадлежат пользователю.**

`MealUiController` будет реализован так же, как и `MealRestController`, за некоторыми исключениями:

- для создания или обновления еды будет использоваться метод `#createOrUpdate`, который принимает информацию о еде в параметрах запроса `@RequestParameter`, приходящих из формы
- авторизации у этих контроллеров будут отличаться (будет ниже в этом занятии)

`meals.jsp` изменяем по аналогии с `users.jsp`. Отличие этих страниц - для еды будет использоваться форма фильтрации таблицы, которую создадим с помощью Bootstrap Grid System

> [Bootstrap Grid System](https://getbootstrap.com/docs/4.6/layout/grid/) - экран разбивается на 12 колонок и для каждого элемента страницы мы можем задать сколько колонок он может занимать. Колонки можно настраивать (отступы и т.д...)

По 3 колонки на `startDate` и `endDate` (`col-3`), затем будет 2 колонки отступа (`offset-2`), и далее по 2 колонки на `startTime` и `endTime` (`col-2`).

### Кнопка сброса фильтра

В форму фильтрации добавим кнопку очистки формы. При нажатии на нее будет вызываться функция `clearFilter()`.  
В `$('#filter')[0].reset()` берем массив всех элементов с указанным `id=filter` (нам вернется массив из одного элемента - нашей формы) и сбрасываем все ее поля через `reset()`. После этого обновляем
таблицу еды без учета фильтрации.

</details>

#### Apply 9_01_HW8.patch

- [Grid system](https://getbootstrap.com/docs/4.1/layout/grid/)
- [Difference among col-* in Bootstrap](https://stackoverflow.com/a/19865627/548473)
- [Bootstrap forms](https://getbootstrap.com/docs/4.1/components/forms/)

#### ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Вопрос:

> Можно ли было удаление делать без перезагрузки таблицы (удалением строки) и для редактирования брать данные со страницы, а не с сервера?

В многопользовательском приложении принято при изменении данных подтягивать все изменения с базы, иначе может быть несогласованность базы и UI (например когда пользователей редактируют несколько
администраторов одновременно). Для еды доставать из базы данные при редактировании нет необходимости, но лучше делать все универсально. В таблице часто представлены не все данные, которые можно
редактировать. Дополнительная нагрузка на базу тут совсем небольшая. Для еды нам при каждом добавлении-удалении-редактировании еще необходимо пересчитывать превышение `excess`.

#### Apply 9_02_HW8_clear_filter.patch

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. [HW8 Optional: enable/disable](https://drive.google.com/file/d/1-2ekRtwd60Cbqq4LPEQ_MOsqWcR7d04a)

<details>
  <summary><b>Краткое содержание</b></summary>

Сделаем в `UserService` метод `enable`, который принимает `boolean` (вкл./выкл. пользователя). В методе загружаем из базы нужного пользователя, устанавливаем ему значение `enabled` и записываем
обновленного пользователя обратно в базу. `repository.save(user)` нужен только для JDBC реализации, в JPA изменения сущностей в `@Transactional` методах попадают в базу автоматически. Метод помечен
аннотацией `@Transactional`, чтобы все действия в методе выполнялись в одной транзакции.

> Внимание! Не забываем в выпускных проектах ставить `@Transactional` над методами сервиса, где есть несколько обращений к базе.

Теперь можно вызвать этот метод из контроллеров. В отличие от UI, в REST контроллере используем `@PatchMapping` - сущность изменяется не полностью, а частично.

На странице `users.jsp` для строки таблицы пользователей добавляем атрибут `data-userEnabled`. Для случая, когда этот атрибут будет `false`, в css добавим еще один стиль - теперь строки для неактивных
пользователей будут становиться полупрозрачными.  
На событие `onlick` на чекбокс вешаем функцию `enable($(this), ${user.id})`. В эту функцию передается `this` элемент - чекбокс и `id` пользователя. В функции получаем галочку флага `:checked`, и
передаем ее в POST запросе в контроллер. После успешного выполнения запроса меняем для текущей строки таблицы атрибут `data-userEnabled`, чтобы изменился стиль ее отображения и выводим уведомление.

> Добавил коллбэк `fail` - если обновить базу не удалось, возвращаем флаг в прежнее положение.

### Тесты для REST контроллера и сервиса

Создадим тест `AbstractUserServiceTest#enable`: в нем сначала деактивируем пользователя, получаем его из базы и проверяем что он действительно не активен. Затем активируем этого же пользователя и
снова проверяем - теперь он должен быть активным.

В тесте `AdminRestControllerTest#enable` делаем PATCH запрос деактивации, проверяем статус ответа и отсутствие контента. После чего получаем этого пользователя из базы и проверяем, что он
действительно деактивирован.

</details>

#### Apply 9_03_HW8_enable_disable.patch

>  В тестах сервисов `AbstractServiceTest` базу восстанавливаем после теста (при старте приложения она популируется, если последний тест в сервисах ее меняет, тесты контроллеров могут не пройти)

Примечание: [в публичном API выполнять PATCH с параметрами нельзя](https://stackoverflow.com/questions/64390768/can-i-use-query-parameters-with-http-patch-method). But in a situation where your API is
only used by front ends that you control (for example, only called via your java script client downloaded from your web servers), and if you don't need to use any intermediate components (like a web
cache) in the middle, then you might get away with it (данные у нас не кешируются).

## Занятие 9:

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3.  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFYlRkc2NGRGVydk0">Spring Binding</a>

<details>
  <summary><b>Краткое содержание</b></summary>

Spring Data Binding - функциональность Spring преобразовывать данные в параметрах или теле запроса в экземпляры класса. Формат данных может быть как `application/x-www-form-urlencoded` (из html формы), так и
JSON.  
Для удобства обмена данными между frontend и сервером применяется объект (и паттерн) Transfer Objects. Объект TO содержит только те поля, которые нужны UI и в процессе работы приложения происходит
конвертация entity в TO и обратно.  
Создадим объект `UserTo` только с теми полями, которые может редактировать администратор и пользователь
(ввод ролей админом у нас не будет реализован, по окончанию стажировки можете доработать наше приложение самостоятельно). В `AdminUIController#create` вместо набора параметров будем принимать `UserTo`

- Spring автоматически извлечет из запроса нужные данные и, используя отражение, сделает из них объект. Для этого **объект должен иметь конструктор без параметров и сеттеры**.

</details>

#### Apply 9_04_binding.patch

> Перенес `ru.javawebinar.topjava.util.MealsUtil.DEFAULT_CALORIES_PER_DAY` в `ru.javawebinar.topjava.util.UserUtil`

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4.  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFd2ZvcS1pSjdMQlU">Реализация update</a>

<details>
  <summary><b>Краткое содержание</b></summary>

Записи в таблице будут обновляться с помощью js функции `updateRow`. В этой функции:

- Запрашиваем у сервера данные о редактируемой сущности (на случай если к этому моменту данные уже были кем-то изменены).
- Функцией `.each` проходимся по всем полям принятых JSON данных, ищем в форме модального окна (`form = $('#detailsForm')`) соответствующие `input` элементы:
  `form.find("input[name='" + key + "']")`
- Присваиваем полям значения `.val(value)`. Таким образом мы заполняем форму актуальными данными пользователя.
- Открываем модальное окно с нашей формой

Переименовываем `AdminUIController#create` в `createOrUpdate`. Если в пришедшем объекте `id = null`, в базе создается новая сущность, иначе обновляем существующую с пришедшим `id`.  
Дополнительно создаем `UserUtil#updateFromTo`, который обновляет сущность данными TO.

В `topjava.common.js` методе `save` после обновления или добавления пользователя в базу в коллбэке `done` повторно запрашиваем с сервера список всех пользователей и обновляем таблицу.

</details>

#### Apply 9_05_update.patch

> - Сделал интерфейс `HasId` от которого наследуются `BaseTo` и `AbstractBaseEntity`
> - Сделал проверку `id` в `ValidationUtil` на основе `HasId`
> - Сделал в `ProfileRestController` обновление своего профиля через `UserTo` (нельзя изменять себе роли) и поправил тест

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5.  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFLXp5MTFDMEY5WFE">Spring Validation</a>

<details>
  <summary><b>Краткое содержание</b></summary>

Проверка на корректность данных задается с помощью аннотаций валидации над полями объекта. Для большинства таких аннотаций в скобках можно указать дополнительные параметры, по которым будет
осуществляться проверка. Также можно переопределить стандартное уведомление, которое будет сообщать о неверных данных. Эти аннотации нельзя использовать непосредственно при вводе данных, так как формы
ввода данных находится на стороне клиента, а проверка происходит на сервере.  
В `AdminUIController#createOrUpdate` перед `UserTo` укажем аннотацию `@Valid` (запустить функционал валидации) и добавим параметр `BindingResult` - результат валидации. Если в результате есть ошибки,
склеим их в строку и отдадим клиенту со статусом `UNPROCESSABLE_ENTITY`. На стороне клиента в `failedNote` будет выведено сообщение об ошибке (обработчик всех ошибок по AJAX задаем
в `$(document).ajaxError`), к тексту уведомления добавим ответ сервера.

</details>

#### Apply 9_06_validation.patch

> - `responseJSON` не выводится в случае его отсутствия (например при попытке добавить пользователя с дублирующимся email)

- <a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/core.html#validation-beanvalidation">Spring Validation.</a>
- <a href="http://beanvalidation.org/">Bean Validation</a>
- <a href="https://spring.io/blog/2012/08/29/integrating-spring-mvc-with-jquery-for-validation-rules">Валидация формы по AJAX.</a>
- <a href="http://stackoverflow.com/questions/14730329/jpa-2-0-exception-to-use-javax-validation-package-in-jpa-2-0#answer-17142416">JSR-303, 349</a>
- <a href="https://dzone.com/articles/spring-31-valid-requestbody">@Valid @RequestBody + Error handling</a>
- [Java Bean Validation Basics](https://www.baeldung.com/javax-validation)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 6.  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFcW1qeTVFdS1BdHM">Перевод DataTables на Ajax</a>

<details>
  <summary><b>Краткое содержание</b></summary>

В методе `DataTables` есть параметр конфигурации `ajax.url`. Если он присутствует, по этому URL выполнится AJAX запрос и таблица будет инициализирована полученными данными.

- При этом JSP больше не требуется данные для таблицы (модели в контроллерах)
- Отрисовывать таблицу в JSP тоже больше не нужно, она строится автоматически, используя конфигурацию `DataTables`.
- В конфигурацию `DataTables` добавляем  `ajax.url` - ендпойнт, по которому запрашиваются данные
- В `columns` добавляем метод `render` - функция отображения содержимого ячейки таблицы. Так как с сервера дата `registered` приходит в формате ISO, при отображении содержимого ячейки нужно
  предварительно произвести ее конвертацию.
- Функции отрисовки кнопок удаления `renderDeleteBtn` и редактирования `renderEditBtn` будут общими для страниц пользователей и еды.
- В конфигурации `DataTable` можно настроить функцию отображения всей строки `createdRow`. Если пользователь в этой строке неактивен, задаем ей соответствующий css стиль.

</details>

#### Apply 9_07_datatable_via_ajax.patch

> - Перешли на [параметры Datatables в формате 1.10](https://datatables.net/upgrade/1.10-convert)
> - В `makeEditable()` больше нет манипуляций c DOM, которые требуются делать ПОСЛЕ отработки плагина `datatables`, поэтому нам не обязательно вызывать ее в коллбэке `initComplete`. Отображения строки меняем в параметре конфигурации `createdRow`

- [DataTables Ajax](https://datatables.net/manual/ajax)

#### ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Вопрос:

> Что за дополнительный параметр (который каждый раз инкрементируется) появляется при запросе datatables данных по ajax (например `http://localhost:8080/topjava/ajax/admin/users/?_=1496156621129`) ?

Это защита `datatables` от кэширования запроса браузером. При изменении js, css и других статический ресурсов, также полезно добавлять в запрос версию, чтобы данные не брались из кэша (особенно когда
приложение уже вышло в продакшен).

#### Apply 9_08_js_i18n.patch

> - Добавил [простую интернационализацию в JavaScript](https://stackoverflow.com/questions/6218970/resolving-springmessages-in-javascript-for-i18n-internationalization).

- на стороне сервера формируется `i18n` JavaScript массив с значениями, который затем используется для интернационализации в браузере

> - в модальном окне заголовок подменяется через `$('#modalTitle').html(..title)`

> Для тестирования локали
> - [можно поменять `Accept-Language`](https://stackoverflow.com/questions/7769061/how-to-add-custom-accept-languages-to-chrome-for-pseudolocalization-testing). Для хрома в `chrome://settings/languages` перетащить нужную локаль наверх.
> - можно поставить [Locale Switcher](https://chrome.google.com/webstore/detail/locale-switcher/kngfjpghaokedippaapkfihdlmmlafcc) хром плагин

- <a href="http://stackoverflow.com/a/6242840/548473">JavaScript internationalization</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 7.  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFUmhUTms1WnhTeHc">Форма логина / логаут.</a>

<details>
  <summary><b>Краткое содержание</b></summary>

Добавляем в `spring-security.xml` еще одну security-конфигурацию `<http>`. URL `/admin/**` будет доступен только с ролью `ADMIN`, все остальные URL будут доступны только аутентифицированным
пользователям. В конфигурации указываем, что аутентификация будет проходить через Spring стандартные login и logout формы.  
`RootControllerTest` перестал работать - Spring Security при каждом запросе к контроллеру будет делать перенаправление на страницу `login` - вместо ожидаемого в тестах статуса ответа HTTP.200 с
сервера будет возвращаться ответ со статусом HTTP.302 - redirect. Исправим тесты, указав ожидаемый `forwardedUrl`.

#### Своя страница login

Страница логина должна быть доступна для любого не аутентифицированного пользователя. Для этого в `spring-security.xml` добавляем путь `"/login"` с доступом для всех: `permitAll`.  
И настраиваем `form-login`:

- указываем ссылку на страницу логина;
- стандартные страницы, на которые будет осуществляться переход после успешного или неуспешного логина
- `login-processing-url` - это путь, по которому Spring будет обрабатывать запросы на сервер от формы логина.

Cоздадим собственную страницу логина по Bootstrap шаблону - `login.jsp`. На ней расположена форма логина, в `action` которой указываем `login-processing-url` - путь к обработке Spring Security POST
запроса.  
На странице сделаем элемент для отображения информации об ошибке в случае неправильных аутентификационных данных. Spring Security кладет в HTTP сессию сообщения об ошибке и при неуспешном
логине (`authentication-failure-url="/login?error=true"`) оно отображается на странице.  
В `RootController#root` перенаправим запросы пользователей к руту ("/") на страницу еды: `redirect:meals`. Чтобы такие запросы обрабатывались корректно и при обращении к корню происходил редирект,
нужно удалить или переименовать `index.html/index.jsp`.  
И еще добавим пример обработки статических ресурсов - `test.html`. Чтобы обратиться к нему из браузера, в `spring-mvc.xml` добавим `<mvc:default-servlet-handler/>`, который мапить запросы к
статическим html страницам.   
В `RootController` добавляем метод, который будет обрабатывать запросы по url-паттерну "/login" и перенаправлять их на страницу `login.jsp`. Информацию о неуспешной аутентификации или сообщения вместо
атрибутов передаем в параметрах запроса (`param.error/message`).

</details>

#### Apply 9_09_min_form_login.patch

> Добавил функциональность logout

- [Минимальный form-login](https://docs.spring.io/spring-security/reference/servlet/configuration/xml-namespace.html#ns-minimal)
- <a href="https://docs.spring.io/spring-security/site/migrate/current/3-to-4/html5/migrate-3-to-4-xml.html#m3to4-xmlnamespace-form-login">Migrating &lt;form-login&gt;</a>

#### ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Мои вопросы:

- Почему при логине как admin еда отдаются для user?
- Почему при логине как user не отображается список пользователей?
- Почему еда не редактируется?

> Подсказка: поглядите вкладку Network в браузере.

#### Apply 9_10_jsp_form_login.patch

> Рефакторинг
> - В `login.jsp` вместо атрибутов достаю параметры запроса (`param.error/message`).
> - Сделал i18n описания приложения
> - При нажатии кнопок `Зайти как ...` сделал вход в приложение

- [Собственный form-login](https://docs.spring.io/spring-security/reference/servlet/authentication/passwords/form.html#servlet-authentication-form-custom)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 8. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFYTA4aVN4bWxzbEU">Реализация собственного провайдера авторизации.</a>

<details>
  <summary><b>Краткое содержание</b></summary>

#### Реализация собственного провайдера авторизации.

Сейчас пользователи приложения и их аутентификационные данные жестко прописаны в конфигурации `spring-security.xml`, приемлимо только для тестового использования.  
Чтобы получать данные креденшелов из базы вместо простого `user-service` настроим `jdbc-user-service`.  
Для этого прямо в конфигурации указываем SQL запросы, которые Spring будет выполнять к базе для получения креденшелов и данных аутентифицированного пользователя.  
Если аутентификация прошла успешно, Spring Security в `ThreadLocal` (стратегия хранения по умолчанию) сохраняет для текущего потока объект `Authentication`. Данные аутентифицированного пользователя
можно достать из `ThreadLocal` с помощью `SecurityContextHolder.getContext().getAuthentication()`.  
Раньше в проекте для получения этих данных использовался утильный класс `LoggedUser`, теперь он переименован в `SecurityUtil`. В этом классе определены методы доступа к залогированному пользователю:

- `safeGet()` - возвращается или `AuthorizedUser` или `null`, если аутентифицированного пользователя нет.

Заменим `jdbc_user_service` и SQL в конфигурации `spring-security.xml` кодом Java: в `<authentication-provider user-service-ref="userService">`
задаем бин, который реализует интерфейс Spring Security `UserDetailsService` и реализуем его метод `#loadUserByUserName`. В этот метод передается значение `username` из формы логина - в нашем
приложении это `email`. Если через `UserRepository#getByEmail` пользователь не найдется в базе, выбросим стандартное Spring Security исключение `UsernameNotFoundException`. Метод `#loadUserByUserName`
должен возвратить класс - данные аутентифицированного пользователя - который имплементирует Spring Security интерфейс `UserDetails`. Вместо самостоятельной реализации всех методов
интерфейса `UserDetails` проще всего сделать класс (`AuthorizedUser`), отнаследовав его от стандартной Spring Security имплементации этого
интерфейса `org.springframework.security.core.userdetails.User`
и в конструкторе передав ему все необходимые данные.   
Роли он принимает как `Collection<? extends GrantedAuthority> authorities`, поэтому `enum Role` отнаследуем от `GrantedAuthority` и реализуем его метод `getAuthority()`:
[права на основе ролей принято задавать с префиксом "ROLE_"](https://stackoverflow.com/a/19542316/548473). 
Класс `AuthorizedUser` задает в нашем приложении аутентифицированного пользователя и мы будем хранить в нем `UserTo` - данные, которых нет в
стандартном `org.springframework.security.core.userdetails.User`, в частности `id` и `caloriesPerDay`.  
Есть еще много разных способов реализации `UserDetails`, которые можно найти в интернете. На мой взгляд наше текущее решение самое простое.

Еще - объект `AuthorizedUser` будет хранится в сессии (про нее видео ниже) и для этого ему требуется сериализация средствами Java. Это наследование его и всех классов-полей от маркерного
интерфейса `Serializable` и необязательный, но желательный `serialVersionUID`.

> **Будьте внимательны в выпускных проектах с `Serializable`. Им нужно помечать ТОЛЬКО объекты, которые будут храниться в сессии**

</details>

#### Apply 9_11_auth_via_user_service.patch

> - В `UserService` добавил `@Scope(proxyMode = ScopedProxyMode.TARGET_CLASS)`, т.к. без этой аннотации для кэширования создается прокси над интерфейсом `UserDetailsService` (см. следующее видео по типам проксирования Spring). Можете проверить, что без этой аннотации приложение не поднимется.
> - `GrantedAuthority` это "разрешение" или "право". Если оно дается на основе роли, в Spring Security принято использовать префикс `ROLE_`. При этом сама роль не должна иметь префикс.
>    - [Role and GrantedAuthority](https://stackoverflow.com/a/19542316/548473)

- [UserDetailsService](https://docs.spring.io/spring-security/reference/servlet/authentication/passwords/user-details-service.html)
- [serialVersionUID value](https://stackoverflow.com/a/605832/548473)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 9.  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFT2Qya2V4N0kzWWM">Принцип работы Spring Security. Проксирование.</a>

<details>
  <summary><b>Краткое содержание</b></summary>

### Принцип работы Spring Security. Проксирование.

Одна из основных функциональностей Spring Core, кроме IOC контейнера и связываний, это проксирование. Чаще всего оно задается аннотациями: при поднятии приложения и создании контекста на основе
пре-процессоров Spring анализирует аннотации бинов и, находя указание к проксированию, создает прокси (обертку) над исходным объектом. В контекст Spring попадает уже не исходный инстанс класса, а его
прокси. В Spring используется две стратегии проксирования:

- на основе JDK 4 [Dynamic Proxy API](https://docs.oracle.com/javase/8/docs/technotes/guides/reflection/proxy.html) - прокси-объект создаются как обертка ко всем интерфейсам, которые имплементирует
  сервис.
- на основе CGLib - когда нет интерфейсов, прокси объект создается на уровне модификации байт-кода класса.

По умолчанию, если класс имплементирует интерфейсы, проксирование происходит по стратегии Dynamic Proxy и в прокси мы имеем только методы интерфейсов. Стратегию проксирования можно поменять на CGLib, задав явно в
конфигурациях параметра `proxy-target-class` или, как сделали мы, аннотацию `@Scope(proxyMode = ScopedProxyMode.TARGET_CLASS)`. В результате прокси нашего `UserService` сделано через CGLib ив нем доступны все его методы.
Второй путь - создать и реализовать интерфейс, в котором есть всем методы класса.

Работа Spring Security основывается на цепочке Security-фильтров. HTTP запрос, перед тем как поступить в Dispatcher Servlet проходит цепочку фильтров (стандартная функциональность Servlet API). Spring
предоставляет собственную цепочку стандартных фильтров и возможность отключать/заменять любые фильтры из этой цепочки или внедрять в нее собственные фильтры.

</details>

- <a href="https://ru.wikibooks.org/wiki/Spring_Security/Технический_обзор_Spring_Security">Технический обзор Spring Security</a>
- <a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/core.html#aop-proxying">Типы проксирования</a>
- <a href="http://samolisov.blogspot.ru/2010/04/proxy-java.html">Dynamic Proxy API</a>
- [Security фильтры](https://docs.spring.io/spring-security/reference/servlet/configuration/xml-namespace.html#filter-stack)
- [Основы работы с Spring Security от Eugene Suleimanov](https://www.youtube.com/watch?v=7uxROJ1nduk)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 10. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFU3hMR0o4eGNoUmc">Spring Security Test</a>

<details>
  <summary><b>Краткое содержание</b></summary>

### Spring Security Test

Для тестирования контроллеров, к запросам которого требуется аутентификация, будем использовать библиотеку `spring-security-test`. Для этого в `pom.xml` подключим эту зависимость и в `MockMvc`
добавить аналог цепочки security-фильтров: `.apply(springSecurity())`. Если сейчас запустить тесты, то они упадут, потому что в `mockMvc` происходит аутентификация, а в запросах, которые тесты
посылают серверу креденшелов пользователя нет.  
Чтобы пройти аутентификацию в REST контроллерах, в каждом запросе укажем креденшелы пользователя через `...with(userHttpBasic(ADMIN))`.
`TestUtil#userHttpBasic` - наш утильный метод, который добавляет к запросу базовую аутентификацию (заголовок `Authorization` с данными *логина:пароля*).

</details>

#### Apply 9_12_spring_security_test.patch

> - Cделал "честную" аутентификацию для `RootControllerTest` (через `TestUtil#userAuth`)
> - Cделал `mockAuthorize` для `SpringMain`, в который не попадают фильтры

- [Spring Security Testing](https://docs.spring.io/spring-security/reference/servlet/test/index.html)
- [Setting Up MockMvc and Spring Security](https://docs.spring.io/spring-security/reference/servlet/test/mockmvc/setup.html)
- [HttpBasic авторизация](https://docs.spring.io/spring-security/reference/servlet/test/mockmvc/http-basic.html)
- [Тестирование контроллеров в Spring Boot](https://javaops.ru/view/bootjava/lesson06#test)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 11. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFUzNFanF6MGZGNHc">Cookie. Session.</a>

<details>
  <summary><b>Краткое содержание</b></summary>

### Cookie. Session.

Если в браузере с помощью инструментов разработчика внимательно посмотреть на запросы, которые уходят от клиента на сервер - можно увидеть что к каждому запросу прикрепляется Cookie `JSESSIONID`. 
Эта Cookie - ключ к мапе, которая хранится в сессии и содержит аутентификационные данные. При аутентификации клиента в приложении создается объект `Authentication`, генерируется ключ, по нему объект кладется в сессию (мультимапа) и
этот ключ возвращается клиенту в ответе как значение cookie `JSESSIONID`. 
Браузер хранит cookie на основе домена сайта и прикрепляет их ко всех запросам к этому домену. По значению cookie `JSESSIONID` Spring Security
хранит в сессии `Authentication`, из котрого мы уже можем достать нашего `AuthorizedUser`.  

Для REST контроллеров в конфигурации мы указали `create-session="stateless"` - при обращении к ним приложение
не будет создаваться HTTP сессии и сookie. В каждом запросе клиента к REST контроллеру вместо cookie есть заголовок `Authorization` с данными *логина:пароля* клиента. Каждый запрос проходит цепочку
Security фильтров и для базовой аутентификации при каждом запросе будет происходить обращение к БД для получения пользователя по email и проверка его креденшелов из заголовок `Authorization`.  

При некоторых условиях Tomcat сохраняет данные сессии и ему требуется возможность их сериализации, поэтому объекты в сеcсии (и объекты, которые в них содержатся) обязательно должны имплементировать
интерфейс `Serializable` (в нашем случае `AuthorizedUser` и `UserTo`).

</details>

- <a href="https://ru.wikipedia.org/wiki/HTTP_cookie">HTTP cookie</a></h3>
- <a href="http://stackoverflow.com/questions/595872/under-what-conditions-is-a-jsessionid-created">Under what conditions is a JSESSIONID created?</a>
- <a href="http://halyph.blogspot.ru/2014/08/how-to-disable-tomcat-session.html">Tomcat Session Serialization</a>

### Дополнительно: ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 12. [Новое в Spring 5. Миграция проекта](https://javaops.ru/view/resources/spring5)

## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы

> В куки попадает обычная строка JSESSIONID. Куда сериализуется объект User?

Для хранения состояния сессии (например корзины покупателя) в Servlet API есть механизм хранения объектов сессии (грубо - мультимапмапа, которая достается из хранилища по ключу). При создании сессии
на стороне сервера (через `request.getSession`) создается кука `JSESSIONID`, которая передается между клиентом и сервером в каждом запросе и является ключом в хранилище объектов сессий.
См. <a href="http://javatutor.net/books/tiej/servlets#_Toc39472970">обработка сессий с помощью сервлетов</a>

> В `login.jsp` есть форма `<form:form action="spring_security_check" ..>` Где такой url используется?

Он задается в `login-processing-url` конфигурации `spring-security.xml` и определяет URL к Spring Security, который принимает данные авторизационной формы (`username` и `password`).

> Если не пользовать js, а писать UI на JSP, сообщения между ui и сервером будут в формате json? Это же будет JSON API?

Есть данные, которые передаются между клиентом и сервером в формате json или get/post с параметрами, есть стили взаимодействия клиента и сервера (<a href="https://ru.wikipedia.org/wiki/REST">REST</a>
, <a href="http://jsonapi.org/">JSON API</a>, <a href="https://ru.wikipedia.org/wiki/JSON-RPC">JSON-RPC</a>) и есть средства генерации HTML: JSP, Javascript фреймворк, Thymleaf и пр. Не надо эти вещи
путать между собой.

> По умолчанию спринг работает с `UserDetailsService#loadUserByUsername`, который должен возвращать `UserDetails`. Но мы не хотим стандартные, мы хотим свои, поэтому просто наследуем наши `UserService` и `AuthorizedUser` от соответствующих интерфейсов и реализуем недостающие методы, которые spring security и будет использовать?

В прошлых выпусках я сам реализовывал интерфейс `UserDetails`. Сейчас я считаю проще отнаследовать `AuthorizedUser` от `org.springframework.security.core.userdetails.User`, который уже имеет реализацию.
А в `UserService` мы реализуем `UserDetailsService#loadUserByUsername` и указываем этот сервис в `spring-security.xml` `<authentication-provider user-service-ref="userService">`.
Также есть его стандартные реализации, которые использовались до нашей кастомной `UserService`, например `jdbc-user-service` использует реализацию `JdbcUserDetailsManager`

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW9

- 1: Реализовать для meal Binding/ Update/ Validation. Проверить работу при пустом значении `calories`.
- 2: Перевести `meals.jsp` на работу по ajax. Стиль строки таблицы сделать в зависимости от `excess`, время отображать без `T`. Добавить i18n.
- 3: Починить meals тесты, добавить тест на неавторизованный доступ.

### Optional

- 4: Подключить datetime-picker к фильтрам и модальному окну добавления/редактирования еды
    - <a href="http://xdsoft.net/jqplugins/datetimepicker/">DateTimePicker jQuery plugin</a>
    - [jQuery: конверторы](https://jquery-docs.ru/jQuery.ajax/#using-converters)

- Попробуйте при запросах по REST оставить стандартный ISO формат (с разделителем `T`). То есть:
    - Отображение и редактирование еды на UI происходит без `T` (формат значений на UI можно увидеть во вкладке браузера Network)
    - Когда мы работаем по REST, в json и запросах формат даты ISO (с разделителем `T`)
    - Напомню, что параметры методов контроллера (в том числе собранные в объекты через Binding) парсятся конверторами спринга (`@DateTimeFormat`), а объекты json парсится Jackson и они никак не
      влияют друг на друга.

## ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Проверка в HW09

- 1: Проверьте, что при добавлении и редактировании пользователя и еды у вас корректно отображаются заголовки модального окна:
  "Добавить/Редактировать еду пользователя"
- 2: Не дублируйте

```
<c:forEach var='key' ...
i18n['${key}'] = ...
```

- 3: Для подключения css и js datetimepicker-а посмотрите в его jar (или поищите в проекте по Ctrl+Shift+N: `datetimepicker`). При ошибке в datetimepicker javascript, обратите внимание на **имя
  javascript файла** в [DateTimePicker](https://xdsoft.net/jqplugins/datetimepicker/) "How do I use it?"
- 4: datetimepicker работает корректно в Хроме, если убрать в `type` в `<input type="date/time/datetime-local" ..`
- 5: Если появляются проблемы с JS типа `... is not defined` - обратите внимание на порядок загрузки скриптов и атрибут `defer`. Скрипты должны идти в нужном порядке. Если определяете скрипт прямо в
  jsp, он выполняется до `defer` скриптов.
- 6: Не дублируйте обработку ошибок в `BindingResult` в ajax контроллерах
- 7: Проверьте редактирование еды: открыть на редактирование и сохранить не должно приводить к ошибкам с форматом времени.
- 8: Проверьте в `RootController.meals()`, его нужно тоже поправить
- 9: При решении с jQuery конвертором: он создает поле `responseJSON`, если внутри не вылетает по эксепшену. См.
  также [hasOwnProperty()](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty)  

# Стажировка <a href="https://github.com/JavaWebinar/topjava">TopJava</a>

## [Материалы занятия](https://drive.google.com/open?id=0B9Ye2auQ_NsFfk43cG91Yk9pM3JxUHVhNFVVdHlxSlJtZm5oY3A4YXRtNk1KWEZxRlFNeW8)

### ![correction](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Правки в проекте

#### Apply 10_0_fix.patch
- Переименовал `UserUtil` в `UsersUtil`

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW9

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFZnQ2dDZsT0dvYjQ">HW9</a>

<details>
  <summary><b>Краткое содержание</b></summary>

Создаем `MealUIController`, `MealTo` у нас используется только в списке еды для выбора цвета строки в зависимости от `MealTo.excess`. 
Для полей `Meal` добавляем аннотацию форматирования даты `@DateTimeFormat`.
Валидация в приложении происходит после биндинга - сначала из параметров запроса через сеттеры собирается объект, затем делается проверка на поля объекта.
Чтобы валидация калорий на null работала, меняем тип `calories` на `Integer` и не забываем менять тип в `setCalories` -
тогда при `calories=null` объект соберется без `NullPointerException (NPE)`.  

Для работы по Ajax в `MealUIController` добавим GET метод получения еды по ее `id`. Метод 
`#createOrUpdate` реализован так же, как и в `AdminUIController` - метод
принимает `@Valid Meal` и результат валидации `BindingResult`.  

Так как в `RootController` при запросе в методах теперь просто происходит
перенаправление на нужную JSP-страницу, а `Datatables` сама получает необходимые
данные - удалим из параметров и тела `getMeals` ненужные больше `Model` и операции с ней.  

Конфигурация отрисовки таблицы еды в `topjava.meals.js` аналогична `topjava.users.js`.
Так как с сервера `dateTime` в списке еды приходит в формате ISO, 
для отображения ее в таблице определим функцию, которая будет заменять буквау `Т` в 
строке с датой на пробел и отрезать секунды.
В функции отрисовки строки `createdRow` добавим к каждой строке атрибут `data-meal-excess` со значением `excess` - по нему в `style.css` определяется цвет.  

Теперь в `meals.jsp` можно удалить таблицу, она будет отрисовываться с помощью `dataTables`.  
В форме создания и редактирования еды нужно обратить внимание на то, что атрибут `name`
поля формы и название полей `Meal` должны строго
совпадать, иначе биндинг для этих полей происходить не будет.

В js я сделал рефакторинг - вынес общую часть конфигурации и создание `DataTable` в `topjava.common.js`. Теперь в `makeEditable` я передаю не объект `DataTable`, а часть ее конфигурации,
которая склеивается с общей частью через [`jQuery $.extend`](https://api.jquery.com/jquery.extend/#jQuery-extend-deep-target-object1-objectN)

### Тесты
В `RootControllerTest.getMeals` добавляем авторизацию и убираем проверку модели.
Во всех тестовых методах `MealRestControllerTest` к запросам добавляем авторизацию 
(по аналогии с тестами пользователей). Также добавляем тест на неавторизованный доступ - 
в нем проверяем, что запрос без авторизации вернет статус `status().isUnauthorized`.  

### Datetime-picker  
Из примера по ссылке к домашнему заданию возьмем пример реализации `datetime-picker`. 
Адаптируем его к нашей странице - отдельно вынесем `start/end` переменные и добавим параметр `formatDate`.  
Чтобы в форме создания и редактирования еды дата отображалась не в формате ISO (без буквы "T"),
в `topjava.common#updateRow` добавим проверку и JSON поле данных `dateTime` форматируем через `formatDate` (вынесли в отдельную функцию).  
Дата из формы будет приходить в параметрах POST в `MealUIController#createOrUpdate` также не в ISO. Поменяем формат в `@DateTimeFormat` на "yyyy-MM-dd HH:mm" 
</details>

#### Apply 10_01_HW9_binding_ajax.patch

Datatables перевели на ajax (`"ajax": {"url": ajaxUrl, ..`), те при отрисовке таблица сама по этому url запрашивает данные. Поэтому в методе `RootController.meals()` нам нужно только возвратить view "meals" (`meals.jsp`) которому уже не нужны данные в атрибутах.

> - JavaScript `i18n[]` локализацию перенес в `i18n.jsp` и передаю туда `page` как параметр
>   - [JSP include action with parameter example](https://beginnersbook.com/2013/12/jsp-include-with-parameter-example)
> - Вынес общий код в `ValidationUtil.getErrorResponse()` и сделал обработку через `stream()`
> - Вместо контекста передаю в `makeEditable` опции `DataTable`.
> - Вынес создание `DataTable` в `topjava.common.js`. В параметр конфигурации добавляю общие опции используя [jQuery.extend()](https://api.jquery.com/jquery.extend/#jQuery-extend-deep-target-object1-objectN)

#### Apply 10_02_HW9_test.patch

#### Apply 10_03_HW9_datetimepicker.patch
> - Вынес форматирование даты в `topjava.common.formatDate()` 
> - Изменил формат ввода dateTime в форме без 'T': при биндинге значений к полям формы в `topjava.common#updateRow()` для поля `dateTime` вызываю `formatDate()`.  
    REST интерфейс по прежнему работает в стандарте ISO-8601
> - В новой версии `datetimepicker` работает ограничение выбора времени `startTime/endTime`
> - Добавил `autocomplete="off"` для выключения автоподстановки (у некоторых участников мешает вводу, у меня не воспроизводится)

- <a href="http://xdsoft.net/jqplugins/datetimepicker/">DateTimePicker jQuery plugin</a>
- <a href="https://github.com/xdan/datetimepicker/issues/216">Datetimepicker and ISO-8601</a>

## Занятие 10:

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. [Дополнительно: кастомизация JSON (@JsonView) и валидации (groups)](https://drive.google.com/file/d/0B9Ye2auQ_NsFRTFsTjVHR2dXczA)

<details>
  <summary><b>Краткое содержание</b></summary>

В `MealRestController` мы принимаем Meal с датой в формате ISO, а на страницах пользовательского интерфейса нам приходится вручную заменять букву "Т" в дате на пробел, а при биндинге
использовать не-ISO форматтер.  
Решим эту проблему через [JSON Views](http://www.baeldung.com/jackson-json-view-annotation) - с помощью view-аннотаций в контроллерах будет возвращаться даты в разных форматах: поле `dateTime` в формате ISO будет
использоваться для REST, а `dateTimeUI` в формате "yyyy-MM-dd HH:mm" для UI.

Создадим два маркерных интерфейса (у них нет методов, служат лишь для маркировки объектов):
- `View.JsonREST` - для REST контроллера;
- `View.JsonUI` - для UI контроллера;

В `Meal` и `MealTo` сделаем геттеры `getDateTimeUI` с аннотациями `@JsonView(View.JsonUI.class)` и `@JsonFormat(pattern = DateTimeUtil.DATE_TIME_PATTERN)`. В сериализованном с `View.JsonUI` объекте не
будет поля `dateTime`, а будет `dateTimeUI`. И наоборот, при `View.JsonREST` будет только поле `dateTime` в формате ISO. Тк. в `Meal` мы принимаем
данные с UI, сделаем сеттер - также поле `dateTimeUI` в формате  "yyyy-MM-dd HH:mm".   
В `MealUIController` в методах, где мы отдаем или принимаем JSON объект укажем `View.JsonUI` - сериализация/десериализация объектов будет делаться через `View.JsonUI`.

По умолчанию в `JsonObjectMapper` включим REST view: `#setConfig(getSerializationConfig().withView(View.JsonREST.class))`. Оно будет применяться везде в контроллерах, где view не указано явно.  

Jackson будет:
- сериализовывать все поля, не помеченные аннотациями;
- поля с аннотациями сериализовывать в зависимости от наличия совпадающих аннотаций в контроллерах;
- если в контроллере view аннотаций нет - использовать сконфигурированный по умолчанию `View.JsonREST`;

Теперь в страницах для еды мы можем удалить функции изменения даты (где "Т" заменялась на пробел).  
В форме создания и редактирования еды атрибуты name поля должны строго соответствовать полям объекта в json - для даты нужно поставить `name="dateTimeUI"` и в `DataTable columns` также поменять
`dateTime` на `dateTimeUI`.

Для кастомных мапперов добавим дополнительные тесты:

- в `JsonUtil` добавим метод, который будет сериализовывать объект с помощью `ObjectWriter`;
- в `JsonUtilTest` добавим тест, который получает `ObjectWriter` для `View.JsonUI.class`, сериализует `adminMeal1` и проверяет наличие в JSON `"datetimeUi"`.

### Кастомизация валидации

Из формы `meals.jsp` данные приходят без поля `user`, и нам пришлось убрать на это поле валидацию `@NotNull`. 
В Spring с версии 3.0 появилась возможность создавать группы валидации - проводить проверку в зависимости от заданной группы. 
Для этого в контроллерах вместо `@Valid` нужно использовать `@Validated` с параметром группы валидации - маркерного интерфейса `ValidateUI.class`.
В `Meal` для всех полей, кроме `user`, в аннотациях валидации укажем эту группу. Эти же аннотации используются при сохранении в базу, поэтому они должны выполняться по умолчанию - 
добавим в группу аннотаций через запятую `Default.class`. Для аннотации `@NotNull` над полем `user` будет применятся только валидация по умолчанию.

</details>

### ВНИМАНИЕ! Патчи `10_04_opt` и `10_05_opt` - не обязательные! Если будете делать- то в отдельной ветке (у меня `opt_view_group`). Это варианты решений, которые не идут в `master`

**Можно не делать в своих выпускных проектах вью и группы валидации. Это усложняет код, который в тестовом задании должен быть простым и понятным для ревью**

- [Что возвращать: Entity или DTOs](https://stackoverflow.com/a/21569720/548473)

#### Apply 10_04_opt_json_view.patch

- [Jackson Annotation ](http://www.baeldung.com/jackson-annotations)
    - [Jackson JSON Views](http://www.baeldung.com/jackson-json-view-annotation)
- [@JsonView: фильтруем JSON](https://habrahabr.ru/post/307392/)
- [Jackson set default view](https://stackoverflow.com/questions/22875642/548473)

#### Apply 10_05_opt_validated_groups.patch

- [Validation Group in SpringMVC](https://narmo7.wordpress.com/2014/04/26/how-to-set-up-validation-group-in-springmvc/)
- [@Validated and Default group](http://web.archive.org/web/20170826153901/http://forum.spring.io/forum/spring-projects/web/117289-validated-s-given-groups-should-consider-default-group-or-not)

> **Починил тесты JDBC, добавив при проверке группы валидации.**

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. [Рефакторинг: jQuery конверторы и группы валидации по умолчанию](https://drive.google.com/file/d/1tOMOdmaP5OQ7iynwC77bdXSs-13Ommax)

<details>
  <summary><b>Краткое содержание</b></summary>

Чтобы отображать дату и время на страницах в UI формате "yyyy-MM-dd HH:mm", сделаем ее форматирование на стороне клиента с помощью jQuery AJAX конвертера. 
Объекты с сервера приходят в тела запроса (текст), jQuery конвертирует их в JSON объект и добавляет поле `responseJSON` в объект AJAX ответа. 
Стандартный конвертер `JSON.parse(stringData)` мы можем заменить на свой, добавим его в `topjava.meal.js`. 
В нем парсим тело ответа, и, если это объект, для каждого составного объекта в нем (список в json выглядит как массив, нам надо выполнить операцию для каждого элемента массива) через jQuery функцию `each` 
проверяем на наличие в объекте поля `dateTime`. Если поле есть - форматируем его в формат UI. Этот конвертер будет исполняться для всех AJAX запросов "text->json" в первую очередь и поле `dateTime` везде будет попадать в javascript в UI формате.  

### Валидация для сохранения в БД через JPA

Для JPA можно задать группу валидацию, которая будет управлять валидацией перед сохранением в БД. Создадим маркерный интерфейс `View.Persist extends Default` и 
в `spring-db.xml` сконфигурируем `entityManagerFactory`, задав ему эту группу для `pre-persist` и `pre-update`.
Теперь, перед любым сохранением в ДБ, Hibernate будет валидировать все дефолтные поля (тк мы отнаследовались от `Default`), и, дополнительно к ним, поля, помеченные нашим маркерным `View.Persist`,
а в контроллерах будут валидироваться только дефолтные поля. Поле `Meal#user` пометим `@NotNull(View.Persist.class)` - теперь оно будет валидироваться только при сохранении в БД.

</details>

### ВНИМАНИЕ! далее патчи идут после `10_03_HW9_datetimepicker` в ветке `master`

#### Apply 10_04_jquery_converters.patch

- [jQuery: типы данных](https://jquery-docs.ru/jQuery.ajax/#data-types)
- [jQuery: конверторы](https://jquery-docs.ru/jQuery.ajax/#using-converters)

> В конвертере добавил дополнительную проверки `typeof json === 'object'` и `hasOwnProperty('dateTime')`, т.к. [при исключении не переопределяется `jqXHR.responseJSON`](https://stackoverflow.com/questions/48229776/548473)

#### Apply 10_05_persist_validate_group.patch

- [Default Hibernate validation](https://stackoverflow.com/a/16930663/548473). Т.к.  `Persist` наследуется от `javax.validation.groups.Default`, при сохранении учитываются все непомеченные аннотации
  валидации (`Default`) + помеченные `Persist`.

> ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png)
При `NotNull(groups = View.Persist.class)` валидация происходит непосредственно перед созданием или редактированием на уровне репозиториев? А если бы мы установили без группы то проверка была сразу после получения с UI?

Если `View` никаких нет (что равнозначно `javax.validation.groups.Default`), то бины, в которых есть аннотации валидации, проверяются Spring в контроллерах (если перед параметром стоит `@Valid`) и
Hibernate перед сохранением и обновлением. Через `View` мы можем управлять валидацией. В нашем случае мы включили в `spring-db.xml` указание Hibernate валидировать поля с `View.Persist`. Так
как `View.Persist` наследуется от `Default`, то Hibernate будет также валидировать и поля, на которых нет View.

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFTVZyQnBlYUtkNms">Spring Security Taglib. Method Security Expressions.</a>

<details>
  <summary><b>Краткое содержание</b></summary>

Модуль Spring Security Taglib содержит набор тегов для jsp-страниц, добавляем в `pom.xml` зависимость `spring-security-taglibs`.
Теперь в jsp появилась возможность через security tag управлять отображением контента в зависимости от авторизированного пользователя.  
- В `bodyHeader.jsp`
  - оставляем доступ к управлению юзерами только для админов - `hasRole('ADMIN')` 
  - делаем `logout` доступным только для авторизированных пользователей
  - переносим сюда из `login.jsp` заголовок для неавторизированных пользователей
- В `login.jsp` кнопки логина "User" и "Admin" отображаем только для неавторизированных пользователей (защита от Back в истории браузера после логина)

Чтобы не-администратор не имел прав к методу `RootController#getUsers` (страница управления пользователями), над соответствующим методом поставим аннотацию `@Secured("ROLE_ADMIN")`.
Вместо нее можно использовать аннотацию `@PreAuthorize("HasRole('ROLE_ADMIN')")`, которая предоставляет более широкие возможности настройки доступа с помощью expression language.  
Попробуйте теперь войти в приложение как пользователь и дернуть страничку [http://localhost:8080/topjava/users](http://localhost:8080/topjava/users).
Чтобы эти аннотации учитывались Spring при поднятии контекста, нужно в `spring-mvc.xml` настроить препроцессор:   
```xml
<global-method-security secured-annotations="enabled" pre-post-annotations="enabled"/>
```
Если мы настроим препроцессор в `spring-security.xml`, который импортируется в `spring-app.xml`, то он не будет работать для классов контроллера. 
Препроцессоры для контроллеров следует задавать в `spring-mvc.xml`.

</details>

#### Apply 10_06_secure_tag_annotation.patch

> - Сделал общий `bodyHeader.jsp` с разделением `isAnonymous/isAuthenticated`
> - В `login.jsp` кнопки входа отображаю только для `isAnonymous`

- [Spring Security Taglib](https://docs.spring.io/spring-security/reference/servlet/integrations/jsp-taglibs.html)
- [Introduction to Spring Method Security](https://www.baeldung.com/spring-security-method-security)

#### ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Вопрос:

> У нас в `sprng-mvc` подключается `spring-app`, в который подключается `spring-security`. Т.о. `spring-mvc`  в себе содержит код `spring-app` и `spring-security`. Почему тогда аннотация `<security:global-method-security...` из `spring-security` не видна для контроллера из `spring-mvc`?

1. Подключаем один контекст внутрь другого: это про import а не про наследование (тоже самое что скопипастить сюда xml из подключаемого import файла). Наследование означает, что поиск бина, если он не
   найден, происходит в родителе.
2. При создании контекста аннотация `<security:global-method-security...` говорит про то, что все бины текущего контекста, у которых есть аннотации авторизации (`@PreAuthorize/ @Secured/ ..`) будут
   проксироваться с проверкой авторизации. Контексты родителей и детей создаются сами по себе и препроцессоры у них собственные.

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5.  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFc1JMTE4xVG0zN0U">Interceptors. Редактирование профиля. JSP tag files.</a>

<details>
  <summary><b>Краткое содержание</b></summary>

В заголовке каждой страницы будем отображать данные текущего пользователя. Чтобы не добавлять эти данные в каждом методе контроллера, сделаем interceptor: 
в пакете `web` создадим подпакет `interceptor` с классом `ModelInterceptor`. Если в ответе от Spring MVC есть непустое view и пользователь авторизован, он добавляется в модель.
Interceptor конфигурируем в `spring-mvc.xml`, а в `bodyHeader.jsp` добавляем кнопку профиля пользователя.   

В `profile.jsp` будет форма для редактирования данных пользователя, `userTo` попадает в модель jsp через `ModelInterceptor`. 
Для валидации полей пользователя и отображения ошибок биндинга на jsp странице сделаем [JSP custom tags](http://www.techrepublic.com/article/an-introduction-to-jsp-20s-tag-files/) `inputField.tag`.
Его импорт происходит через `<%@ taglib prefix="topjava" tagdir="/WEB-INF/tags" %>`     
Создаем `ProfileUIController`, который возвращает view `profile` по кнопке из `bodyHeader.jsp` и сохраняет пользователя в методе `updateProfile`. 
Если проверка не прошла, мы возвращаемся обратно в профиль.  
Магия красивого отображение ошибок в форме работает через [Spring MVC Form Validation](http://www.codejava.net/frameworks/spring/spring-mvc-form-validation-example-with-bean-validation-api) - тэги `form:form` в `profile.jsp` и `spring:bind / form:input` в `inputField.tag`. 

В профиле мы можем менять `caloriesPerDay`: добавляем на него сеттер и поле в конструктор и данные пользователя. 
</details>

#### Apply 10_07_interceptor.patch

- <a href="http://www.mkyong.com/spring-mvc/spring-mvc-handler-interceptors-example/">Spring interceptors</a>.

#### Apply 10_08_profile_jsptag.patch

**Глюк Хрома - у меня поле `email` у User показывается неверно (как для admin). В другом браузере, анонимном окне и коде страницы (Ctrl+U) все ок. Я решил локально обновлением Хрома. Еще решения:**

- [В своем браузере](https://www.howtogeek.com/425270/how-to-disable-form-autofill-in-google-chrome)
- [Chrome ignores autocomplete=“off”](https://stackoverflow.com/questions/12374442/548473)
- [Disabling Chrome Autofill](https://stackoverflow.com/questions/15738259/548473)

> - Создал отдельный `ProfileUIController` для операций с профилем (вместо `RootController`)
> - Упростил: в `inputField.tag`: передаю для label код локализации и убрал ветвление
> - В профиль добавил кнопку "Cancel"

- [Bootstrap 4 form validation example](http://nicesnippets.com/snippet/bootstrap-4-form-validation-with-form-all-input-example)
- <a href="http://www.techrepublic.com/article/an-introduction-to-jsp-20s-tag-files/">Делаем jsp tag для ввода поля формы</a>.
- <a href="http://www.codejava.net/frameworks/spring/spring-mvc-form-validation-example-with-bean-validation-api">Spring MVC Form Validation</a>
- <a href="http://www.mkyong.com/spring-mvc/spring-mvc-form-check-if-a-field-has-an-error/">Spring MVC Form: check if a field has an error</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 6. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFNWpUNktMeGJURmM">Форма регистрации.</a>

<details>
  <summary><b>Краткое содержание</b></summary>

На странице `login.jsp` добавим кнопку регистрации, а в `ProfileUIController` добавим метод `register`, который будет возвращать форму регистрации. 
В `spring-security` этот url делаем доступным для всех пользователей (не перепутайте настройки авторизации REST и UI). 
Для регистрации будем использовать существующую форму `profile.jsp`, куда будем передавать пустой `userTo` и аттрибут `"register"=true`. 
В форму регистрации добавим условие - если флаг установлен, то введенные данные POST запросом уходят на `profile/register` и обрабатываются в `ProfileUIController#saveRegister`.
Если данные успешно прошли валидацию, новый пользователь сохраняется в БД и идет перенаправление на страничку логина с сообщением `app.registered`.

Добавим также регистрацию в `ProfileRestController` и тест на нее: `ProfileRestControllerTest#register`. Обратите внимание, что регистрация делается неавторизированным пользователем:
в настройках REST авторизации в `spring-security.xml` добавляем:
```xml
<intercept-url pattern="/rest/profile" method="POST" access="isAnonymous()"/>
```
</details>

#### Apply 10_09_registration.patch

> - Добавил локализацию
> - При регистрации передаю `username` в `login.jsp` как параметр и делаю `setCredentials` (пароль вводится скрыто, поэтому его не передаю из соображений безопасности). Т.к `setCredentials` требует jQuery, убрал для него `defer`
> - Поменял путь регистрации с `/registered` на `/profile/registered` (в `ProfileUIController` вместо `RootController`)
> - Добавил регистрацию пользователя по REST: `ProfileRestController.register`, тест и пример `curl`. Обратите внимание на хедер `Location`, он отличается от `AdminRestController.createWithLocation`

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 7. <a href="https://drive.google.com/file/d/0B9Ye2auQ_NsFZ19lU29VVDRfNXM">Обработка исключений в Spring.</a>

<details>
  <summary><b>Краткое содержание</b></summary>

Spring MVC предоставляет возможность стандартной обработки исключений.  
Для нашего исключения `NotFoundException` добавим аннотацию:

```java
@ResponseStatus(value = HttpStatus.UNPROCESSABLE_ENTITY, reason = "No data found")
```  

Теперь, при возникновении этого исключения, Spring MVC будет генерировать ответ с указанным в аннотации статусом.  
Добавим тесты, где проверяем статус возврата ответов с `NotFoundException`.

Для обработки исключений в контроллерах создадим `GlobalExceptionHandler`, помеченный аннотацией `@ControllerAdvice` - глобальный обработчик исключений.
В методе `defaultErrorHandler` будем обрабатывать все исключения приложения - помечаем его аннотацией `@ExceptionHandler(Exception.class)`.
В методе мы делаем логирование и передаем на страничку `exception.jsp` модель c причиной (`rootCause`), сообщением и статусом.  
Стек-трейс исключения отобразим в блоке комментариев `<!-- ... -->` - такие комментарии не будут видны пользователю, но их можно будет увидеть в исходном коде страницы
(решение скорее для тестового приложения, тк на продакшене обычно скрываются детали реализации).

### Обработка исключений REST и UI контроллеров

Для REST запросов в случае возникновения исключения будем возвращать информацию о нем в формате json. Для этого создадим класс `ErrorInfo` - он будет представлять информацию об исключении в ответе клиенту.  
Для обработки исключений REST и UI контроллеров, помеченных аннотацией  `@RestController` создадим `ExceptionInfoHandler`.
Аннотация `@RestControllerAdvice` - это комбинация `@ControllerAdvice` and `@ResponseBody` (будут возвращаться не view, а тело ответа). Параметр `annotations = RestController.class` означает, что будут обрабатываться только эксепшены от контроллеров `@RestController`.
Создадим методы для обработки различных типов исключений, которые указываем параметрами аннотации`@ExceptionHandler` над методами.
В методах получаем объект запроса и исключение, логируем исключение и возвращаем созданный `ErrorInfo`. 
Теперь для исключений, возникших по ajax-запросу клиенту будет возвращаться информация в виде json, и ее нужно корректно отобразить в сообщениях UI:
в `failedNoty` принимаем объект `errorInfo` и выводим на экран детали исключения.

</details>

#### Apply 10_10_not_found_422.patch

> [Поменял код 404 (URL not found) на 422 (Unprocessable Entity)](http://stackoverflow.com/a/22358422/548473)

- [Обработка исключений в контроллерах Spring](https://habr.com/ru/post/528116/)
- <a href="http://spring.io/blog/2013/11/01/exception-handling-in-spring-mvc#using-http-status-codes">Используем HTTP status code</a>

#### Apply 10_11_global_exception.patch

> - Перед отображением exception предварительно делаю `ValidationUtil.getRootCause`
> - Добавил локализацию
> - Добавил общий статус `500` в ответ `GlobalExceptionHandler` (на следующем уроке будем его менять, в зависимости от типа ошибки)

- <a href="http://spring.io/blog/2013/11/01/exception-handling-in-spring-mvc#global-exception-handling">Global Exception Handling</a>

#### Apply 10_12_controller_advice_exception.patch

**Отображение валидации для формы еды и юзера пропало (`TODO` в коде для HW10). Можно посмотреть сериализацию в `ErrorInfo` при попытке добавить юзера с дублирующимся email.**

> - Добавил в `ErrorInfo` тип ошибки `ErrorType`
> - Добавил обработку неверного запроса (`IllegalRequestDataException`)
> - `@ResponseBody` над методами `ExceptionInfoHandler` заменил на `@RestControllerAdvice`
> - В `ExceptionInfoHandler` удалил `@Order` над методами и добавил над классом:

```
  Methods are matched by closest exception in
  *  @see  org.springframework.web.method.annotation.ExceptionHandlerMethodResolver#getMappedMethod
  *  164: Collections.sort(matches, new ExceptionDepthComparator(exceptionType))
```

> - Добавил в `curl.md` пример с возвращением `ErrorInfo`. Локализация ошибок будет на последнем занятии

- <a href="http://spring.io/blog/2013/11/01/exception-handling-in-spring-mvc#errors-and-rest">Errors and REST</a>
- <a href="http://spring.io/blog/2013/11/01/exception-handling-in-spring-mvc#controller-based-exception-handling">Exception Handling на уровне контроллера</a>
- <a href="https://www.javacodegeeks.com/2013/11/controlleradvice-improvements-in-spring-4.html">@ControllerAdvice improvements in Spring 4</a>
- <a href="https://dzone.com/articles/spring-31-valid-requestbody">@Valid @RequestBody + Error handling</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 8. <a href="https://drive.google.com/file/d/1XZXvOThinzPw4EhigAUdo8-MWT_g8wOt">Encoding password. Json READ/WRITE access</a>

<details>
  <summary><b>Краткое содержание</b></summary>

#### Encoding password

Все кодировщики паролей, которые может использовать спринг, должны реализовывать интерфейс `PasswordEncoder`. Этот интерфейс объявляет два метода - `#encode` - для кодировки исходного пароля, и `#matches` - чтобы сравнить исходный пароль с закодированным (хранящимся в БД).

В последних версиях Spring рекомендуется использовать `DelegatingPasswordEncoder`, который по префиксу в начале пароля определяет, 
по какому алгоритму зашифрован хранящийся в базе пароль и делегирует его обработку соответсвующему PasswordEncoder-у. В `spring-security.xml` меняем `NoOpPasswordEncoder` на `DelegatingPasswordEncoder`. 

> Для тестовых данных в паролях пользователей мы можем указать пароль в незашифрованном виде с добавлением префикса `{noop}` - шифрование не используется

При обновлении или сохранении пользователя нам нужно шифровать пароль и сохранять его в базу в зашифрованном виде: делаем `UserUtil#prepareToSave`, в котором:
- шифруем пароль
- переводить `email` в lowerCase, чтобы он сохранялись в БД в нижнем регистре  

`UserUtils` не является бином Spring, а в методе ему нужен спринговый `PasswordEncoder`, передаем его в параметрах из `UserService`.

> Убрал проверку на пустой пароль - `password` валидируется через `@NotBlank` и не может быть пустым 

В тестах пользователей исключим пароли из сравнения, т.к. один и тот же пароль каждый раз может кодироваться в различные последовательности символов при одном и том же алгоритме шифрования.

#### Json READ/WRITE access

У сущности `User` есть поля:
- `password` - его не нужно отдавать в ответах, но нужно получать из json объекта при создании или обновлении пользователя
- `registered` - его нужно отдавать в ответах, но не нужно считывать из json объекта при создании или обновлении пользователя.

Для этих целей будем использовать специальные аннотации Jackson.  
Над полем `password` ставим `@JsonProperty(access = JsonProperty.Access.WRITE_ONLY)`, а над полем `registered` - `@JsonProperty(access = JsonProperty.Access.READ_ONLY)`.

Тест на создание пользователя не пройдет, так как в пароль теперь не сериализуется (его не будет в `newUser`), а он валидируется в контроллере через `@NotBlank`. 
Специально для тестов создадим утильный метод `UserTestData#jsonWithPassword`, который в `JsonUtil#writeAdditionProps` добавляет пароль в сериализованный json.  
Добавим `JsonUtilTest#writeOnlyAccess` тест на `WRITE_ONLY` пароль, в котором проверяем отсутствие пароля в json при сериализации через `JsonUtil#writeValue` и присутствие его через `UserTestData#jsonWithPassword`.

</details>

#### Apply 10_13_password_encoding.patch

> - Добавил утильный метод `UserService.prepareAndSave`
> - Для InMemory тестов добавил `passwordEncoder` в  `inmemory.xml`

- [Password Encoding](https://docs.spring.io/spring-security/reference/servlet/authentication/passwords/password-encoder.html)

#### Apply 10_14_read_write_access.patch

> - Добавил методы сериализации в json `JsonUtil.writeAdditionProps` с дополнительными полями и `UserTestData.jsonWithPassword` для того, чтобы передавать в контроллер пользователя с паролем (который теперь не сериализуется)

### В реальном приложении для управления паролем необходим отдельный UI интерфейс с подтверждением старого пароля - одна из ваших доработок проекта по окончанию стажировки

- [@JsonProperty READ_ONLY / WRITE_ONLY](https://stackoverflow.com/a/12505165/548473)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 9. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFNDlPZGdUNThzNUU">Межсайтовая подделка запроса (CSRF).</a>

<details>
  <summary><b>Краткое содержание</b></summary>

В конфигурации `spring-security.xml` ранее мы принудительно отключили защиту от CSRF.
Удалим или закомментируем эту строчку. Теперь Spring Security добавит дополнительный `CsrfFilter` в свою цепочку. 
Этот фильтр для каждого не-(GET, HEAD, TRACE, OPTIONS) запроса будет проверять наличие специального заголовка или скрытого поля. 
Чтобы видеть, как обрабатываются запросы, в настройках логирования для класса `CsrfFilter` установим уровень *debug*.  
В `bodyHeader.jsp` для `logout` заменим тип запроса с GET на POST, чтобы для него действовала защита от CSRF (невозможно злонамеренно разлогинить). 
Для POST запросов из JSP форм, вместо добавления в форму поля CSRF токена, мы можем использовать тег Spring `form:form` - Spring Security добавит это поле сам.

Для добавления CSRF токена в AJAX запросы в `headTag.jsp` объявим тэги `meta` с `name="csrf"` и `name= "csrf_header"`, в аттрибуты `content` поместим значения, которые нам предоставляет Spring Security.
Чтобы к каждому AJAX запросу не добавлять CSRF header, в `topjava.common.js`  настроим через jQuery сразу все AJAX запросы. 
Заголовок и токен получим из тэгов `meta` которые мы определили в `headTag.jsp`.

Запросы, которые отправляются на сервер через POST с типом `MediaType.APPLICATION_JSON_VALUE` также защищены в браузере правилом *same origin policy*: 
невозможно сделать из браузера POST запрос с типом "application/json" на сайт с другим доменным именем без специального разрешения. См. также вопрос ниже.

</details>

#### Apply 10_15_csrf.patch

> Убрал `form:form` из ajax запросов: там CSRF работает через header. Проверьте во вкладке браузера `Network`.

**Поломалась UTF-8 кодировка в редактировании профиля и регистрациию (если по умолчанию не UTF-8). В Optional HW10 нужно будет починить.**

- <a class="anchor" id="csrf"></a><a href="https://ru.wikipedia.org/wiki/Межсайтовая_подделка_запроса">Межсайтовая подделка запроса (CSRF)</a>
- [Using Spring Security CSRF Protection](https://docs.spring.io/spring-security/reference/servlet/exploits/csrf.html#servlet-csrf-using)
- [Ajax and JSON Requests](https://docs.spring.io/spring-security/reference/servlet/exploits/csrf.html#servlet-csrf-include-ajax)
- <a href="http://blog.jdriven.com/2014/10/stateless-spring-security-part-1-stateless-csrf-protection/">Stateless CSRF protection</a>
- Ресурсы:
    - <a href="http://habrahabr.ru/post/264641/">Spring Security 4 + CSRF</a>
    - <a href="http://stackoverflow.com/questions/11008469/are-json-web-services-vulnerable-to-csrf-attacks">Are JSON web services vulnerable to CSRF attacks</a>
    - <a href="https://ru.wikipedia.org/wiki/Правило_ограничения_домена">Правило ограничения домена (SOP)</a>
    - <a href="https://ru.wikipedia.org/wiki/Cross-origin_resource_sharing">Cross-origin resource sharing (CORS)</a>

## ![question](https://cloud.githubusercontent.com/assets/13649199/13672858/9cd58692-e6e7-11e5-905d-c295d2a456f1.png) Ваши вопросы

> В чем отличие между аннотоацией `@PreAuthorize("hasRole('ADMIN')")` и конфигурацией в jsp: `<sec:authorize access="isAuthenticated()">`, `<sec:authorize access="hasRole('ADMIN')">` ?

Анотация `@PreAuthorize` обрабатывается Spring анологично `@Transactional`, `@Cacheable` - класс проксируется и до-после вызова метода добавляется функциональность. В данном случае перед вызовом
метода проверяются роль залогиненного юзера. JSTL тэг `authorize` выполняет проверку условия в залогиненном юзере внутри jsp.

> Еще раз: почему не нужен csrf для REST и нельзя подделать JSON запрос с вредоносного сайта?

Попробуйте выполнить AJAX запрос из вашего js скрипта на url, домен которого отличается от вашего (например 'http://topjava.herokuapp.com/meals/ajax/admin/users/{id}'). В консоли браузера
будет `XMLHttpRequest cannot load`... - <a href="https://developer.chrome.com/extensions/xhr">нарушение same origin policy</a>. Формам же разрешается делать submit (через `action=..`) на другой домен,
но невозможно cделать `Content-Type`, отличный от <a href="http://htmlbook.ru/html/form/enctype">стндартных enctype</a> и методов <a href="http://htmlbook.ru/html/form/method">кроме get и post</a>.
Таким образом `consumes = MediaType.APPLICATION_JSON_VALUE` для POST защищает приложение от CSRF.

> Почему использован `BCryptPasswordEncoder`а не `hash(password+salt)`?

[`BCryptPasswordEncoder` automatically generates a salt and concatenates it with the hash value in a single String](http://stackoverflow.com/a/8528804/548473).

> Когда запускается в `GlobalExceptionHandler` метод `defaultErrorHandler`? Когда как в него исключение попадает? Как выбирается, кто обрабатывает исключения: `ExceptionInfoHandler` или `GlobalExceptionHandler`?

`GlobalExceptionHandler` попадает в контекст спринг (через `@ControllerAdvice` его находят в пакете `web`). Далее спринг перехватывает исключения и отправляет в подходящий по исключению
метод `GlobalExceptionHandler`. `ExceptionInfoHandler` помечен `@RestControllerAdvice(annotations = RestController.class)`, он обрабатывает только ошибки из всех контроллеров с
аннотацией `RestController`.

> Откуда берутся в валидации сообщения на русском "должно быть между 10 и 10000"?

Локализация встроена в Hibernate Validation. Смотрите `Ctrl+Shift+N` и `ValidationMessages_ru.properties`.

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW10

- 1: Сделать валидацию в `AdminUIController/MealUIController` через `ExceptionInfoHandler`. Вернуть клиенту `ErrorInfo` и статус `HttpStatus.UNPROCESSABLE_ENTITY` (тип методов контроллеров
  сделать `void`). Ошибки валидации отобразить на клиенте красиво (так, как это сделано в [demo](http://topjava.herokuapp.com), без локализации полей)
- 2: Сделать валидацию принимаемых json объектов в REST контроллерах через `ExceptionInfoHandler`. Добавить для Rest контроллеров тесты для невалидных данных.
    - <a href="https://dzone.com/articles/spring-31-valid-requestbody">@Valid @RequestBody + Error handling</a>
- 3: Сделать обработку ошибки при дублирования email (вывод сообщения "User with this email already exists") для:
    - 3.1 регистрации / редактирования профиля пользователя
    - 3.2 добавления / редактирования пользователя в таблице
    - 3.3 REST контроллеров  
      Варианты выполнения:
        - через `catch DataIntegrityViolationException`
        - обработку ошибок в  `@ExceptionHandler`(https://stackoverflow.com/a/42422568/548473)
        - более сложная реализация - [собственный валидатор](https://coderlessons.com/articles/java/spring-mvc-validator-i-initbinder)
    - Опционально - [сделать локализацию выводимой ошибки](https://www.logicbig.com/tutorials/spring-framework/spring-core/message-sources.html)

### Optional

- 4: Сделать обработку ошибки при дублирования dateTime еды. Сделать тесты на дублирование email и dateTime.
    - [Тесты на DB exception c @Transactional](http://stackoverflow.com/questions/37406714/548473)
    - [Сheck String in response body with mockMvc](https://stackoverflow.com/questions/18336277/548473)
- 5: Сделать в приложении выбор локали (см. http://topjava.herokuapp.com/)
    - [Internationalization](https://terasolunaorg.github.io/guideline/5.0.x/en/ArchitectureInDetail/Internationalization.html)
    - <a href="http://www.mkyong.com/spring-mvc/spring-mvc-internationalization-example">Spring MVC internationalization sample</a>
    - <a href="https://www.concretepage.com/spring-4/spring-mvc-internationalization-localization">Spring 4 MVC Internationalization</a>
- 6: Починить UTF-8 в редактировании профиля и регистрации, если кодировка по умолчанию у вас не UTF-8 - в форме регистрации введи юзера с русским именем и посмотри на него.
-------

## ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Типичные ошибки и подсказки по реализации

- 1: `ErrorInfo` просто бин для передачи информации на клиента. Кода возврата и ответ настраиваются в `ExceptionInfoHandler`.
- 2: Не дублируйте обработку ошибок `BindingResult`: `result.getFieldErrors()..`
- 3: Можно не создавать собственные эксепшены, а в `ExceptionInfoHandler` ловить стандартные
- 4: `MethodArgumentNotValidException` наследуется от `BindException`. Обратите внимание на импорт класса: `javax.validation.BindException`, не `java.net.BindException`
- 5: Не дублируйте код переключения локали на странице логина и в приложении
- 6: При проблемах с валидацией `Meals` в `MealRestController`, посмотрите на валидацию в `MealUIController.updateOrCreate`

# Стажировка <a href="https://github.com/JavaWebinar/topjava">Topjava</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFSzlObk8tbHdtcXc">Материалы занятия</a>

### Все материалы проекта (в том числе и будущие обновления) останутся доступны без органичения по времени в [Google Drive](https://drive.google.com/drive/u/0/folders/0B9Ye2auQ_NsFflp6ZHBLSFI2OGVEZ2NQU0pzZkx4SnFmOWlzX0lzcDFjSi1SRk5OdzBYYkU)

### ![correction](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Правки в проекте

#### Apply 11_0_fix.patch
Поправил модификаторы доступа (`private` и `protected`) и имена методов

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Разбор домашнего задания HW10

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFX2V5eHRsa09IWHc">HW10</a>

<details>
  <summary><b>Краткое содержание</b></summary>

Если для вашей операционной системы по умолчанию не установлена кодировка UTF-8
и при запуске JDK не задан параметр `-Dfile.encoding=UTF8`,
в тестах и в приложении данные, введенные кириллицей, будут отобращаться неверно.  

Это связано с тем, что ранее в `web.xml` к проекту мы подключили CSRF-фильтр.
**Обратите внимание, что этот фильтр в конфигурации объявлен до encoding-фильтра.** 
CSRF фильтр открывает поток для чтения из HTTP запроса заголовков и параметров,
после открытия потока кодировку сменить уже невозможно.  Исправить просто - в `web.xml`
объявим encoding-фильтр до security фильтра, чтобы он обрабатывал запрос первым.  

### Перенос валидации в ExceptionInfoHandler  
- Для валидации в REST-контроллерах, перед `@RequestBody` ставим аннотацию `@Valid`.  
- В UI контроллерах убираем обработку `BindingResult` - при неверных данных из метода бросается исключение `BindException`, 
  обработку которого Spring MVC делегирует в `ExceptionInfoHandler`. 
- В `ExceptionInfoHandler.bindValidationError` из `BindingResult` получаем массив ошибок валидации и в объекте `ErrorInfo` отдаем эти данные клиенту со статусом `HTTP.UNPROCESSABLE_ENTITY`
  (в  `ErrorInfo` вместо `String details` сделал массив ошибок).  
Начиная со Spring 5.3 `MethodArgumentNotValidException` наследует `BindException`, и можно его
отдельно не выделять — оставим в параметрах аннотации метода только `@ExceptionHandler(BindException.class)`.
- Так как для отображения на фронтенд мы передаем уже не строку, а массив с ошибками
валидации, в `topjava.common.js` для функции отображения уведомления об ошибке 
`failNoty` сделаем склейку элементов этого массива через тег перевода строки `<br>`.  
- Чтобы проверить обработку исключений для `ProfileRestControllerTest`, `AdminRestControllerTest` и
`MealRestControllerTest` создадим тесты, в которых попытаемся отправить запросы на создание
и обновление сущности с невалидными полями.  
В тестах будем проверять:
     - статус ответа `HTTP.UNPROCESSABLE_ENTITY`;
     - тип ошибки `ErrorType.VALIDATION_ERROR`.   
`ErrorInfo` в теле ответа приходит в формате JSON, для проверки его полей подключим в `pom.xml` библиотеку `json-path`.
Достаем из json элемент `type` и проверяем его значение на соответствие `ErrorType.VALIDATION_ERROR.name()`.

### Обработка ошибки дублирования email  
- В файлы локализации добавим сообщения об ошибке.  
- В `AbstractUserController` добавим константу `EXCEPTION_DUPLICATE_EMAIL = "exception.user.duplicateEmail"` - код ошибки в локализации. 
- В методах создания и обновления пользователей отлавливаем и обрабатываем `DataIntegrityViolationException`- нарушение уникальности при сохранении в БД.
- Обработка неверных данных будет отличаться - в `ProfileUIController` у нас данные приходят из формы Spring (`form:form` в `profile.jsp`), в методе можем принять объект `BindingResult`, в котором есть поддержка сообщений об ошибке.
В `AdminUIController` данные приходят из обычной формы (в модальном окне), поддержки обработки ошибок нет,
поэтому используем Spring класс поддержки локализации `MessageSource messageSource`. 
В методе `ProfileUIController.saveRegister` для повторной регистрации восстанавливаем ` model.addAttribute("register", true)`.
  
### Обработка ошибки дублирования dateTime еды
- В файлы локализации добавим сообщения об ошибке, которая будет выводиться в случае дублирования `dateTime` еды.  
- Делаем обработку ошибок в `ExceptionInfoHandler.conflict`: ищем в сообщениях об ошибке название DB constraints 
  и выводим соответствующее ему сообщение об ошибке (в мапе `CONSTRAINTS_I18N_MAP` ключами являются имена DB constraints, значениями - код в локализации,
`toLowerCase()` для сообщения из DB нужен для HSQLDB).
- Делаем тесты на дублирование `email` и `dateTime`. Обратите внимание, что 
для корректной работы этих тестов нам надо отключить rollback (`@Transactional` в `AbstractControllerTest`): ставим над тестами аннотацию `@Transactional(propagation = Propagation.NEVER)`.  
- Общие методы проверки содержимого `ErrorInfo` выносим в `AbstractControllerTest`

### Валидация email в собственном валидаторе
- Чтобы проверка email происходила при валидации с остальными полями, а не при попытке записи в БД, создадим Spring `@Component` - собственный валидатор `UniqueMailValidator`. 
Он должен имплементировать интерфейс `org.springframework.validation.Validator`: 
   - `#boolean supports(Class<?> clazz)` - поддерживает ли валидатор обработку экземпляров класса;  
   - `#validate(Object target, Errors errors)` - экземпляр объекта для проверки и класс для рапорта об ошибке 
   
- Для универсальной обработки `User` и `UserTo` создадим над ними интерфейс `HasIdAndEmail extends HasId` - валидатор будет обрабатывать все реализующие его классы.  
- В `AbstractUserController.initBinder` добавим наш `UniqueMailValidator` - теперь он будет вызываться Spring MVС наряду со всеми остальными валидаторами. 
- Поправим тесты (при дублирующемся email будет возвращаться статус `HTTP.UNPROCESSABLE_ENTITY`).
- Для корректной работы `UniqueMailValidator` требуется `id` в объекте - добавим скрытое поле в `profile.jsp`
</details>

#### Apply 11_01_HW10_fix_encoding.patch
> - Выставлять кодировку `-Dfile.encoding=UTF-8` лучше в _Help menu -> Edit Custom VM Options_
> - Советы по дополнительным настройкам: 
>   - [Customize IntelliJ IDEA Memory](http://tomaszdziurko.com/2015/11/1-and-the-only-one-to-customize-intellij-idea-memory-settings)
>   - [Increase IDE memory limit in IntelliJ IDEA](https://stackoverflow.com/questions/13578062/how-to-increase-ide-memory-limit-in-intellij-idea-on-mac)
>   - [Slow startup time on Windows](https://youtrack.jetbrains.com/issue/IDEA-211178#focus=streamItem-27-3412218.0-0)

#### Apply 11_02_HW10_validation.patch
> - В [соответствии со спицификацией](http://stackoverflow.com/a/22358422/548473) для поменял `HTTP 400` (ошибка в структуре сообщения) на `HTTP 422` (ошибка в содержании)
> - Сделал тесты и проверку типа ошибки [через jsonPath](https://www.petrikainulainen.net/programming/spring-framework/integration-testing-of-spring-mvc-applications-write-clean-assertions-with-jsonpath/)

#### Apply 11_03_HW10_duplicate_email.patch
> - сделал код(ключ) i18n константой (`EXCEPTION_DUPLICATE_EMAIL`)
> - в `GlobalExceptionHandler` добавил логирование и общий код вынес в `ValidationUtil`

#### Apply 11_04_HW10_duplicate_datetime.patch
> - Реализовать обработку дублирования `user.email` и `meal.dateTime` можно по разному
>   - через [поиск в сообщении `DataIntegrityViolationException` имени DB constrains](https://stackoverflow.com/a/42422568/548473)
>   - через [Controller Based Exception Handling](https://spring.io/blog/2013/11/01/exception-handling-in-spring-mvc#controller-based-exception-handling)

Первый самый простой и расширяемый (хотя зависить от базы), выбрал его. Для работы с HSQLDB сделал `toLowerCase`.

> - Для работы с i18n использую `MessageSourceAccessor`.
>   - [get error text from BindingResult](https://stackoverflow.com/questions/2751603/548473)
> - Добавил тесты на дублирование. Отключил транзакционность в тестах на дублирование через `@Transactional(propagation = Propagation.NEVER)`.
>   - [Решение проблемы с транзакционными тестами](https://stackoverflow.com/a/46415060/548473)

#### Apply 11_05_HW10_binder_validation.patch
> - Добавил корректный способ проверки email своим валидатором: проверка делается в контроллерах, а не при сохранении.
>   - [Spring MVC: валидатор и @InitBinder](https://coderlessons.com/articles/java/spring-mvc-validator-i-initbinder)

> Проблема: при REST update нам могут приходить `User/UserTo` без `id` (он корректируется уже после валидации через `ValidationUtil.assureIdConsistent`)
> Для UI мы в профиль добавили скрытый `id`, для REST проблема осталась.
> Для проверки сообщений в тестах в `ExceptionInfoHandler#bindValidationError` сделал `messageSourceAccessor::getMessage` и из сообщений ошибок ушли поля. Починим в патче `11_08_i18n`

#### Apply 11_06_HW10_fix_update_duplicate.patch
Когда в REST запросе приходит `User` без `id`, `UniqueMailValidator` не справляется - `ValidationUtil.assureIdConsistent` вызывается уже после валидации
(добавил в тесты условия, при которых это происходит). Вариантов решения проблемы несколько: 
например выполнять валидацию самостоятельно вручную (при этом приходится переделывать код контроллеров).
Я выбрал вариант без переделки контроллеров - workaround, когда мы в `UniqueMailValidator` дополнительно проверяем путь запроса, 
который можно получить из внедряемого `HttpServletRequest`.

###  ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFYms4YUxEMHdxZHM">HW10 Optional: change locale</a>

<details>
  <summary><b>Краткое содержание</b></summary>

- Возможность выбрать локаль должна быть доступна на всех страницах нашего приложения,
сделаем ее выбор в `bodyHeader.jsp`, который включается везде:
в  `navbar` добавим выпадающий список `nav-item dropdown`. Текущую локаль получаем через `${pageContext.response.locale}`.
- Настроим `spring-mvc.xml`: информацию о выбранной локали будет храниться в Cookie - `localeResolver` и 
переключать локаль запросом с параметром `lang` - `localeChangeInterceptor`.
Чтобы при переключении локали оставаться на той же самой странице, используем ссылку `${requestScope['javax.servlet.forward.request_uri']}?lang=..`  
- Сделал js переменную `localeCode`, которая хранит текущую локаль и использую ее для локализации `datetimepicker`
</details>

#### Apply 11_07_HW10_change_locale.patch
- Добавил локализацию календаря `$.datetimepicker.setLocale(localeCode)`
- Вместо смены локали в `lang.jsp` через javascript сделал `href=${requestScope['javax.servlet.forward.request_uri']}?lang=..`
- Добавил [Collapsing The Navigation Bar](https://www.w3schools.com/bootstrap4/bootstrap_navbar.asp)

## Заключительное 11-е занятие

### Локализация:
#### Apply 11_08_i18n.patch
 - Добавил [локализацию Search в datatable](https://datatables.net/reference/option/language)
 - Сделал локализацию ошибок валидации:
    - [MessageSourceAccessor](https://stackoverflow.com/a/20550627/548473)
 - Добавил локализацию `ErrorInfo.type` (код локализации в `ErrorType` и поле `ErrorInfo.typeMessage`)
 - В выводе AJAX ошибки вывожу `errorInfo.typeMessage`
 - [Увеличил ширину высплывающего noty](https://stackoverflow.com/a/53855189/548473) 
 
### [Обработка ошибок 404 (NotFound)](https://stackoverflow.com/questions/18322279/spring-mvc-spring-security-and-error-handling)

Сейчас, при отправке неправильного запроса, сервер отвечает стандартным HTTP.404. 
Настроим `mvc-dispatcher`, чтобы вместо этого генерировалось исключение:
```xml
<init-param>
    <param-name>throwExceptionIfNoHandlerFound</param-name>
    <param-value>true</param-value>
</init-param>
```
Теперь при неправильном запросе сервер будет выбрасывать `NoHandlerFoundException`, который
мы можем обработать в `GlobalExceptionHandler`.  Добавим новый тип `ErrorType.WRONG_REQUEST` и сообщение в файлы локализации.

#### Apply 11_09_404.patch

### Доступ к AuthorizedUser
Сейчас авторизованного пользователя в контроллерах мы получаем из `SecurityContext` с помощью утильных методов `SecurityUtil` 
и отображаем его в `bodyHeader.jsp` из модели, которая добавляется в `ModelInterceptor`-е.
Spring позволяет получить доступ к авторизованному пользователю не обращаясь напрямую к `SecurityContext`:
для его передачи в метод контроллера есть специальная аннотация `@AuthenticationPrincipal`. 
Чтобы Spring обрабатывал эту аннотацию, в `spring-mvc.xml` добавляем специальный резолвер: `AuthenticationPrincipalArgumentResolver`.
Сделал контроллеры профиля юзера через `@AuthenticationPrincipal`.   

Также Spring позволяет доставать авторизированного пользователя в JSP, в `bodyHeader.jsp` будем использовать `sec:authentication property="principal"`.
`ModelInterceptor` больше не нужен, удаляем.

#### Apply 11_10_auth_user.patch
- [@AuthenticationPrincipal](https://docs.spring.io/spring-security/reference/servlet/integrations/mvc.html#mvc-authentication-principal)
  - не стал делать автоподстановку по всем контроллерам (в абстрактных контроллерах проще работать с `SecurityUtil`, чем получать его через `@AuthenticationPrincipal` и передавать параметром)
- [В JSP: the authentication Tag](https://docs.spring.io/spring-security/reference/servlet/integrations/jsp-taglibs.html#_the_authentication_tag)
  - авторизованный пользователь доступен в JSP через tag `authentication`, интерсептор становится не нужным
  
### Кастомизация статуса ошибки
Кастомизируем статус ответа сервера в зависимости от ошибки -  добавим `ErrorType.status` и будем использовать его для 
статуса ответа в `GlobalExceptionHandler`: `ModelAndView.setStatus` и в `ExceptionInfoHandler`: `ResponseEntity.status`.

#### Apply 11_11_error_status.patch

### Защита от XSS (Cross Site Scripting)
> **Попробуйте ввести в любое текстовое поле редактирования `<script>alert('XSS')</script>` и сохранить.**

- <a href="https://forum.antichat.ru/threads/20140/">XSS для новичков</a>
- <a href="https://habrahabr.ru/post/66057/">XSS глазами злоумышленника</a>

Раньше я [реализовывал XSS защиту через `@SafeHtml`](https://stackoverflow.com/a/40644276/548473), пока его не [удалили из hibernate validator](https://hibernate.org/validator/documentation/migration-guide/).
Пришлось сделать собственную аннотацию `@NoHtml` на основе [Sanitizing User Input](https://thoughtfulsoftware.wordpress.com/2013/05/26/sanitizing-user-input-part-ii-validation-with-spring-rest/)
  и [jsoup - Sanitize HTML](https://www.tutorialspoint.com/jsoup/jsoup_sanitize_html.htm)
Все классы, относящиеся к валидации перенес в пакет `ru.javawebinar.topjava.util.validation`
- `password` проверять не надо, т.к. он не выводится в html, а [email надо](https://stackoverflow.com/questions/17480809)
- Сделать общий интерфейс валидации `View.Web` и `@Validated(View.Web.class)` вместо `@Valid` для проверки содержимого только на входе UI/REST. 
При сохранении в базу проверка на безопасный html контент (XSS) повторно не делается.
- [Validation groups in Spring MVC](https://blog.codeleak.pl/2014/08/validation-groups-in-spring-mvc.html)

#### Apply 11_12_XSS.patch

### Swagger2

Swagger это фреймворк для автоматического создания REST-API документации по аннотациям контроллеров Spring MVC. 
Подключим зависимость `springfox-swagger2` и `springfox-swagger-ui` в `pom.xml`.
Сразу же в проект подключается Swagger UI интерфейс, который позволяет отправлять запросы к эндпоинтам REST-API и просматривать документацию.  

Настройка swagger производится в конфигурации `spring-mvc.xml` подключением бина `Swagger2DocumentationConfiguration`.
Чтобы смотреть REST-API документацию мог любой пользователь, в `spring-security.xml` доступ к эндпоинтам Swagger UI открываем всем: 
```xml
<intercept-url pattern="/swagger-ui.html" access="permitAll()"/>
<intercept-url pattern="/swagger-resources/**" access="permitAll()"/>
<intercept-url pattern="/v2/api-docs/**" access="permitAll()"/>
```
`AuthorizedUser authUser` не является реальным параметром методов контроллера, который передается клиентом.
Это авторизированный пользователь, который резолвится Spring Security через `@AuthenticationPrincipal`.
Убираем его из документации запросов через `@ApiIgnore`: Swagger будет игнорировать такие параметры при генерировании документации.
UI контроллеры также исключаем из REST-API, пометив их `@ApiIgnore` на уровне класса.  

Создадим на `login.jsp` кнопку "Swagger REST Api Documentation".

**Внимание: Swagger подключается в проект ОЧЕНЬ просто, а пользу от него для ревью трудно переоценить. Вместо примеров `curl` в выпускных проектах 
предлагаю вам подключить Swagger и в `readme.md` дать ссылку на сгенерированную REST API документацию.** 

- [Setting Up Swagger 2 with a Spring REST API](https://www.baeldung.com/swagger-2-documentation-for-spring-rest-api)
- [Swagger 2 Configuration With Spring (XML)](https://medium.com/@andreymamontov/swagger-2-configuration-with-spring-xml-3cd643a12425)
- [Hiding Endpoints From Swagger Documentation](https://www.baeldung.com/spring-swagger-hiding-endpoints)
> В версиях выше 2.10 и 3.0 появились проблемы с маппингом. Вариант документации c OpenAPI 3.0 смотрите в [Spring Boot курсе](https://javaops.ru/view/bootjava)

#### Apply 11_13_swagger2.patch

---------------------
### ДЗ Optional 2

Обратите внимание в Swagger UI на `Example Value` при
- `POST /rest/admin/users (createWithLocation)` - здесь не должно быть поля `meals`. Пользователь создается без еды, еда управляется своими запросами.
- `POST /rest/profile/meals (createWithLocation)` - здесь не должно быть поля `user`.
Нужно поправит `Example Value`. При этом учтите, что в API у нас есть метод  
`GET /rest/admin/users/{id}/with-meals (getWithMeals)` - вернуть пользователя с едой.

[Hide a Request Field in Swagger API](https://www.baeldung.com/spring-swagger-hide-field)

-----------------------

Платформа Heroku стала платной, вместо нее мы предлагаем зарегистрировать и задеплоиться на собственный выделенный хостинг.  
Тарифы хостингов сейчас самые демократичные: собственный Ubuntu сервер с доступом по ssh: от 130 руб./месяц.  

### Ограничение модификации пользователей
Наше [демо-приложение](http://javaops-demo.ru/topjava) доступно любому и нам нужно защитить стандартные учетные записи User и Admin от попыток их
модификации. Сделаем новый профиль `VDS` и в `UserService` введем флаг `modificationRestriction` - нужна ли нам такая проверка.
Через `Environment` проверяем активный профиль и для профиля `VDS` устанавливаем флаг в *true*.
В методах, изменяющих пользователя, проверяем этот флаг и `id` изменяемой сущности, и, попытке несанкционированных изменений, бросаем `UpdateRestrictionException`.
Отнаследовал это исключение от `ApplicationException` - универсального исключения нашего приложения, в котором можно задавать тип и код локализации ошибки.
В `GlobalExceptionHandler` и `ExceptionInfoHandler` создаем обработчики `ApplicationException`.
Для тестирования исключения при попытке изменение пользователя и админа для профиля `VDS` делаем `VdsRestControllerTest`: 
задаем профиль запуска `@ActiveProfiles(VDS)`, делаем модификацию и проверяем исключение.

#### Apply 11_14_vds_restrict_modification.patch

 - В `UserService` добавил защиту от изменения `Admin/User` для профиля `VDS` (в `UserService` заинжектил `Environment` и сделал проверку на наличие профиля `VDS`)
 - **В выпускном проекте, если только не выставляете его в облако для показа, это НЕ требуется**.   
 - Чтобы тесты были рабочими, ввел профиль `VDS`, работающий так же, как и `POSTGRES`.
 - Добавил универсальный `ApplicationException` для работы с ошибками с поддержкой i18n в приложении (от него отнаследовал `UpdateRestrictionException`)

> Для тестирования с профилем vds добавьте в VM options: `-Dspring.profiles.active=datajpa,vds`

### Деплой приложения на Выделенный сервер

Наше [демо-приложение](http://javaops-demo.ru/topjava) теперь хостится на <a href="https://firstvds.ru/?from=1119260">FirstVDS</a> (SSD диск вместо NVMe)   
Первое открытое занятие [курса Startup](https://javaops.ru/view/startup) обучает регистрации хостинга, установке ПО и деплою приложения

### [Открытое занятие курса Startup](https://github.com/JavaOPs/startup)

#### Apply 11_15_vds.patch
Файл пропертей с паролями не принято держать в репозитории (даже если репозиторий _private_).  
Поэтому вам необязательно комитить его, просто скопируйте на сервер по инструкции в разделе урока "_Деплой war на сервер_"  

#### Apply [11_16_HW_fix_swagger.patch](https://drive.google.com/file/d/1A76XXvZdZCKxeKnVjZ2VkrWAHEQ1iof2)
- Скрываем необязательные поле `id` при POST и PUT запросах через `@ApiModelProperty(hidden = true)` в примерах запроса Swagger. При этом передавать поле в запросе можно.
- `Meal.user` отсутствует в REST API, можно игнорировать: `@JsonIgnore`
- `User.meals` можно было сделать `JsonProperty.Access.READ_ONLY`, но при этом не пройдут тесты `getWithMeals` (maels не будет сериализоваться из ответа сервера для сравнения). Скрыл также через `@ApiModelProperty(hidden = true)`
- Также можно было скрыть нулевое поле `User.meals` при выводе через `@JsonInclude(JsonInclude.Include.NON_EMPTY)`. Но при этом поле исчезнет при запросе `getWithMeals` пользователя с пустым списком еды (например для Guest). Все зависит от бизнес-требований приложения (например насколько API публично и должно быть красивым). Можете попробовать самостоятельно скрыть это поле из вывода для запросов без еды через `View` (или отдельный TO).

----------------------

###  ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png)  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFQVc2WUdCR0xvLWM">Собеседование. Разработка ПО</a>
- [Темы/ресурсы тестового собеседования](http://javaops.ru/interview/test.html)
- [Составление резюме, подготовка к интервью, поиск работы](https://github.com/JavaOPs/topjava/blob/master/cv.md)
- [Слайды](https://docs.google.com/presentation/d/18o__IGRqYadi4jx2wX2rX6AChHh-KrxktD8xI7bS33k), [Книги](http://javaops.ru/view/books)
- [Jenkins/Hudson: что такое и для чего он нужен](https://habrahabr.ru/post/334730/)

###  ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png)  [Вебинар: Составление резюме и поиск работы в IT](https://www.facebook.com/watch/live/?v=2789025168007756)
###  ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png)  <a href="https://drive.google.com/open?id=1QtHfavgIeLEnKA2Yt58XzKOouiLhg6qX">Разбор типовых собеседований (необработанный вебинар)</a>
###  ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png)  <a href="http://javaops.ru/view/resources/fromStudyToJob">Вебинар выпускников</a>

-----------------------

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png)  Домашнее Задание:
### **Опционально: [зарегистрировать хостинг и задеплоить в него свое приложение](https://github.com/JavaOPs/startup)** 
   
### **Пройдите основы Spring Boot по курсу [BootJava](https://javaops.ru/view/bootjava)**
- **Занятие по миграция на BootJava будет в начале следующей недели**

### **[Выполнить выпускной проект](https://github.com/JavaWebinar/topjava/blob/doc/doc/graduation.md)**
   - Сроки сдачи указан в выпускном.
   - Если есть проверка или Диплом, после выполнения выпускного [заполни форму проверки](https://docs.google.com/forms/d/1G8cSGBfXIy9bNECo6L-tkxWQYWeVhfzR7te4b-Jwn-Q) 
   - Если проверки или Диплома нет, заполнять не нужно. 
   -  **Возможно [доплатить за ревью выпускного отдельно из JavaOPs профиля](https://javaops.ru/auth/payonline?payId=OG), как за тестовое собеседование: 3450р**

### **Сделать / обновить резюме (отдать на ревью в канал #hw11 группы slack)**
- **Вставь ссылку на свой сертификат [из личного профиля](http://javaops.ru/auth/profile#finished), немного досрочно:)**
   - [Загрузка сайта на GitHub. Бесплатный хостинг и домен.](https://vk.com/video-58538268_456239051?list=661b165047264e7952)
   - [CSS theme for hosting your personal site, blog, or portfolio](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/)

#### ![error](https://cloud.githubusercontent.com/assets/13649199/13672935/ef09ec1e-e6e7-11e5-9f79-d1641c05cbe6.png) Замечания по резюме:
   -  **если нет опыта в IT, обязательно вставь [участие в стажировке Topjava](https://github.com/JavaOPs/topjava/blob/master/cv.md#Позиционирование-проекта-topjava). Весь не-IT опыт можно кратко.**
   -  варианты размещения: Pdf в любом облаке, [Google Doc](https://docs.google.com/), LinkedIn, HH,  [еще варианты и рекомендации](https://github.com/JavaOPs/topjava/blob/master/cv.md#составление-резюме)  
Хорошо, если будет в html или pdf формате (например в https://pages.github.com/). [Например так](https://gkislin.github.io/), [на github](https://github.com/gkislin/gkislin.github.io/blob/master/index.html). Возраст и день рождения писать не обязательно
   -  [все упоминания Junior убрать!!](https://vk.com/javawebinar?w=wall-58538268_1589)
   -  линки делай кликабельными (если формат поддерживает)
   -  всю выгодную для себя информацию (и важную для HR) распологайте вверху. Название секций в резюме и их порядок относительно стандартный и важный
   - **Резюме на hh или других ресурсах ДОЛЖНО БЫТЬ ОТКРЫТО ДЛЯ ПРОСМОТРА и иметь телефон для связи**
   - Заполните контакты `skype/telegram/whatsapp`, HR ими пользуется! Почта как контакт очень медленная, телефон может быть не всегда удобен. Вообще `skype/telegram` для программиста - **Must have**.
   - **Добавьте в резюме ссылки на свои проекты в `GitHub` и на задеплоенные на ваш сервер. Не забудьте про выпускной!**.
   - Диплом РФ от Виакадемии о [профессиональной переподготовке](https://ru.wikipedia.org/wiki/Профессиональная_переподготовка) приравнивается ко второму высшему образованию.  В резюме, полагаю, можно указать в высшем образовании
   - Заполнить в [своем профиле Java Online Projects](http://javaops.ru/auth/profileER) ссылку на резюме и информацию по поиску работы (если конечно актуально): резюме, флаги рассматриваю работу, готов к релокации и информация для HR.
   - **Рассылку обновления базы соискателей по HR буду делать в конце января, можно не спешить**

### **После ревью резюме - опубликовать на ресурсах IT вакансий**
 - [Основные сайты поиска работы](https://github.com/JavaOPs/topjava/blob/master/cv.md#основные-сайты-поиска-работы)

### **Получить первое открытое занятие МНОГОПОТОЧНОСТЬ и пройти эту важную тему в [проекте Masterjava](http://javaops.ru/view/masterjava)**
   - Обучение на MasterJava идет в индивидуальном режиме без проверки ДЗ: старт в любой момент, время прохождение ничем не ограничено
   - Проект, патчи, группа Slack, занятия и видео, разбор ДЗ аналогичны проекту Topjava. 
   - **До 20.01 на курс MasterJava для выпускников действует специальная цена** 

#### Возможные доработки приложения:
-  Разделить `Meal.dateTime` на `date` и `time` и выполнять запрос целиком в SQL
-  Для редактирования паролей сделать отдельный интерфейс с запросом старого пароля и кнопку сброса пароля для администратора.
-  Добавление и удаление ролей для пользователей в админке.
-  Перевести UI на Angular / <a href="https://vaadin.com/elements">Vaadin elements</a> /GWT /GXT /Vaadin / ZK/ [Ваш любимый фреймворк]..
-  Перевести шаблоны с JSP на <a href="http://www.thymeleaf.org/doc/articles/petclinic.html">Thymeleaf</a>
-  Сделать авторизацию в приложение по OAuth 2.0 (<a href="http://projects.spring.io/spring-security-oauth/">Spring Security OAuth</a>,
<a href="https://vk.com/dev/auth_mobile">VK auth</a>, <a href="https://developer.github.com/v3/oauth/">github oauth</a>, ...)
-  Сделать отображение еды постранично, с поиском и сортировкой на стороне сервера.
-  Перевод проекта на https
-  Сделать desktop/mobile приложение, работающее по REST с нашим приложением.
-  <a href="http://spring.io/blog/2012/08/29/integrating-spring-mvc-with-jquery-for-validation-rules/">Показ ошибок в модальном окне редактирования таблицы так же, как и в JSP профиля</a>
-  <a href="http://www.mkyong.com/spring-security/spring-security-limit-login-attempts-example">Limit login attempts example</a>
-  Сделать авторизацию REST по <a href="https://en.wikipedia.org/wiki/JSON_Web_Token">JWT</a>

#### Доработки участников прошлых выпусков:
- [Авторизация в приложение по OAuth2 через GitHub](http://rblik-topjava.herokuapp.com)
  - [GitHub, ветка oauth](https://github.com/rblik/topjava/tree/oauth)
- [Авторизация в приложение по OAuth2 через GitHub/Facebook/Google](http://tj9.herokuapp.com)
  - [GitHub](https://github.com/jacksn/topjava)
- [Angular 2 UI](https://topjava-angular2.herokuapp.com)
  - [tutorial по доработке](https://github.com/Gwulior/article/blob/master/article.md)
  - [ветка angular2 в гитхабе](https://github.com/12ozCode/topjava08-to-angular2/tree/angular2)
- [Отдельный фронтэнд на Angular 2, который работает по REST с авторизацией по JWT](https://topjava6-frontend.herokuapp.com)
  - [ветка development фронтэнда](https://github.com/evgeniycheban/topjava-frontend/tree/development)
  - [ветка development бэкэнда](https://github.com/evgeniycheban/topjava/tree/development)
  - в <a href="https://en.wikipedia.org/wiki/JSON_Web_Token">JWT токенен</a> приложение topjava передает email, name и роль admin как boolean true/false,
на клиенте он декодируется и из него получается auth-user, с которым уже работает фронтэнд

#### Жду твою доработку из списка!

### Ресурсы по Проекту
-  <a href="https://webformyself.com/urok-1-frejmvork-bootstrap-4-chto-takoe-bootstrap-otlichiya-bootstrap-3-ot-bootstrap-4/">Уроки Bootstrap 4</a>
-  <a herf="http://www.tutorialspoint.com/spring/index.htm">Spring at tutorialspoint</a>
-  <a href="http://www.codejava.net/frameworks/spring">Articles in Spring</a>
-  <a href="http://www.baeldung.com/learn-spring">Learn Spring on Baeldung</a>
-  <a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/html/index.html">Spring Framework
            Reference Documentation</a>
-  <a href="http://hibernate.org/orm/documentation">Hibernate Documentation</a>
-  <a href="http://java-course.ru/student/book2/">Java Course (книга 2)</a>
-  <a href="http://design-pattern.ru/">Справочник «Паттерны проектирования»</a>
-  <a href="http://martinfowler.com/eaaCatalog/">Catalog of Patterns of Enterprise Application Architecture</a>

# Стажировка <a href="https://github.com/JavaWebinar/topjava">Topjava</a>

## [Патчи занятия](https://drive.google.com/drive/u/1/folders/1ZsPX879m6x4Va0Wy3D1EQIBsnZUOOvao)

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Финальные правки:

Один из вариантов сокрытия полей в примерах Swagger - сделать специальный TO класс. Но можно сделать проще через специальные аннотации: [Hide a Request Field in Swagger API](https://www.baeldung.com/spring-swagger-hide-field)
- Скрываем необязательные поле `id` при POST и PUT запросах через `@ApiModelProperty(hidden = true)` в примерах запроса Swagger. При этом передавать поле в запросе можно.
- `Meal.user` отсутствует в REST API, можно игнорировать: `@JsonIgnore`
- `User.meals` можно было сделать `JsonProperty.Access.READ_ONLY`, но при этом не пройдут тесты `getWithMeals` (maels не будет сериализоваться из ответа сервера для сравнения). Скрыл также через `@ApiModelProperty(hidden = true)`
- Также можно было скрыть нулевое поле `User.meals` при выводе через `@JsonInclude(JsonInclude.Include.NON_EMPTY)`. Но при этом поле исчезнет при запросе `getWithMeals` пользователя с пустым списком еды (например для Guest). Все зависит от бизнес-требований приложения (например насколько API публично и должно быть красивым). Можете попробовать самостоятельно скрыть это поле из вывода для запросов без еды через `View` (или отдельный TO).

#### Apply [11_16_HW_fix_swagger.patch](https://drive.google.com/file/d/1A76XXvZdZCKxeKnVjZ2VkrWAHEQ1iof2)

## Миграция на Spring Boot
За основу взят финальный код проекта BootJava с миграцией на Spring Boot 3.0 - это первый патч открытого урока курса [CloudJava](https://javaops.ru/view/cloudjava/lesson01),
ветка [_patched_](https://github.com/JavaOPs/cloudjava/tree/patched).
Вычекайте в отдельную папку (как отдельный проект) ветку `spring_boot` нашего проекта (так удобнее, не придется постоянно переключаться между ветками):
```
git clone --branch spring_boot --single-branch https://github.com/JavaWebinar/topjava.git topjava_boot
```  
Если будете его менять, [настройте `git remote`](https://javaops.ru/view/bootjava/lesson01#project)  
> Если захотите сами накатить патчи, сделайте ветку `spring_boot` от первого `initial` и в корне **создайте каталог `src\test`**  

----

#### Apply 12_1_init_boot_java
Оставил как в TopJava:
- название приложения  `Calories Management`
- имя базы `topjava`
- пользователей:  `user@yandex.ru`, `admin@gmail.com`, `guest@gmail.com`
- Swagger открывается из `localhost:8080` через конфигурацию `springdoc.swagger-ui.path: /`
- в `AppConfig` сохранение `objectMapper` должно проходить только после регистрации `Hibernate5Module` - объединил их в `configureAndStoreObjectMapper`
- для регистрации выделил отдельный контроллер `RegisterController`
####  Обновление на Spring Boot 3
- Spring 6, Hibernate 6.1, Hibernate Validator 7, R2DBC 1.0, JPA 3.1, Tomcat 10
- Java 17 – минимальная версия
- Генерация нативных образов GraalVM
- Улучшения в observability через Micrometer и Micrometer Tracing
- Переход от Java EE к Jakarta EE. Jakarta EE 9 – минимальная версия, поддержка Jakarta EE 10
- [Spring Boot 3.0 Goes GA](https://spring.io/blog/2022/11/24/spring-boot-3-0-goes-ga)
- [What's New in Spring Framework 6.x](https://github.com/spring-projects/spring-framework/wiki/What%27s-New-in-Spring-Framework-6.x/)
- [Spring Boot 3.0 Goes GA](https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-3.0-Release-Notes)
- [Get ready for Spring Boot 3.0](https://www.springcloud.io/post/2022-05/springboot-3-0)
- [The best way to do the Spring 6 migration](https://vladmihalcea.com/spring-6-migration/)

---------------------

-  В `pom.xml` обновляем версии Spring и Springdoc
-  [Мигрируем Springdoc на 2.x](https://github.com/springdoc/springdoc-openapi-demos/wiki/springdoc-openapi-2.x-migration-guide): меняется зависимости и пакет `GroupedOpenApi`.
-  Меняем зависимость `jackson-datatype-hibernate5` на `jackson-datatype-hibernate5-jakarta` и в `AppConfig` заменяем `Hibernate5Module` на `Hibernate5JakartaModule`
-  В security `antMatchers` меняется на `requestMatchers` и нужно явно исключать _swagger-ui_ из авторизации
-  `ResponseEntityExceptionHandler` теперь поддерживает спецификацию [RFC-7807](https://www.rfc-editor.org/rfc/rfc7807.html) - описание ошибок, перешел на нее в исключениях. В класс описания ошибок ProblemDetail можно добавлять свои поля: в `GlobalExceptionHandler#handleMethodArgumentNotValid()` добавил поле `invalid_params`. Однако при сериализации Jackson через поля, как у нас, в ответе это поле дублируется. Пришлось делать workaround: класс `AppConfig.MixIn`.
   -  [Spring ProblemDetail and ErrorResponse](https://howtodoinjava.com/spring-mvc/spring-problemdetail-errorresponse/)
-  В `AdminUserControllerTest` не идут тесты на запросы со слешем в конце. Сделал отдельную переменную `REST_URL_SLASH`

#### Apply 12_2_add_calories_meals

Добавил из TopJava: 
- Еду, калории
- Таблицы назвал в единственном числе: `user_role, meal` (кроме `users`, _user_ зарезервированное слово)
- Общие вещи (пусть небольшие) вынес в сервис : `MealService`
- Проверку принадлежности еды делаю в `MealRepository.checkBelong` с исключением `DataConflictException` (не зависит от `org.springframework.web`)
- Вместо своих конверторов использую `@DateTimeFormat`
- Мигрировал все тесты контроллеров. В выпускном проекте столько тестов необязательно! Достаточно нескольких, на основные юзкейсы.
- Кэширование в выпускном желательно. 7 раз подумайте, что будете кэшировать! **Максимально просто, самые частые запросы, которые редко изменяются**.
- **Добавьте в свой выпускной OpenApi/Swagger - это будет большим плюсом и избавит от необходимости писать документацию**.

### За основу выпускного предлагаю взять этот код миграции, сделав свой выпускной МАКСИМАЛЬНО в этом стиле.
### Успехов с выпускным проектом и в карьере! 
