<h1>Курс Python Junior</h1>
<nav>
  <h2>Содержание</h2>
  <ol>
    <li><a href="#urls">Ссылки на установщики необходимых программ</a></li>
    <li><a href="#rules">Указания к работе с репозиторием</a></li>
    <li><a href="#help">Полезные материалы</a></li>
    <li><a href="#lessons">Уроки</a></li>
    <ul>
      <li><a href="#input-output">Ввод-вывод данных</a></li>
      <li><a href="#operations">Арифметические операции</a></li>
      <li><a href="#if-else">Условный оператор</a></li>
      <li><a href="#turtle">Черепашья графика</a></li>
      <li><a href="#while">Цикл while</a></li>
      <li><a href="#for">Цикл for</a></li>
      <li><a href="#list">Списки</a></li>
    </ul>
  </ol>
</nav>

<h2 id="urls">Ссылки на установщики необходимых программ</h2>
<ul>
  <li>Язык Python: <a href="https://www.python.org/ftp/python/3.12.0/python-3.12.0-amd64.exe">Windows Installer (64-bit)</a></li>
  <li>Если понадобится, ссылка на главную страницу Python: <a href="https://www.python.org/">python.org</a></li>
  <li>PyCharm Community: <a href="https://www.jetbrains.com/pycharm/download/download-thanks.html">Download</a></li>
  <li>Github Desktop: <a href="https://desktop.github.com/">Download</a></li>
</ul>

<h2 id="rules">Указания к работе с репозиторием</h2>
<p>На уроке нами сделан форк данного репозитория. Теперь вы можете создать свою ветку для внесения предложений по изменению моего репозитория. Эти предложения назвают Pull Request. Я могу их принять (Merge) или отклонить. Вы можете вносить в один пулл реквест новые изменения, а чтобы сохранить их делаем, Commit.</p>
<p>Для удобной работы в разных группах вам необходимо после клонирования репозитория создать в нем папку с названием своей группы, затем папку, у котрой названием - ваши фамилия и имя. В ней должны лежать две папки: "Уроки" и "Домашние задания". В каждой из этих папок также будут папки, названием которых будет являться число - номер урока или домашнего задания.</p>
<p><b>Например, это может выглядеть так: С2311\Булыга Екатерина\Уроки\1\Задача 1</b></p>
<p>Пулл реквесты называем следующим образом: <b>Фамилия_Имя_Группа_Урок1</b> или <b>Фамилия_Имя_Группа_ДЗ1</b></p>
<p>В данном файле README.md я буду добавлять вам теоретические материалы, а также условия задач для классной и домашней работ.</p>

<h2 id="help">Полезные материалы</h2>
<ol>
  <li>Статьи базово-среднего уровня: <a href="https://younglinux.info/python/programminglanguage">Лаборатория Линуксоида: Python. Введение в программирование</a></li>
  <li>Статьи средне-сложного уровня: <a href="https://education.yandex.ru/handbook/python">Яндекс Хендбук</a></li>
  <li>Пошаговый запуск программ: <a href="https://clck.ru/YiaNn">pythontutor.com</a></li>
</ol>

<h2 id="lessons">Уроки</h2>
<h2 id="input-output">Ввод-вывод данных</h3>
<p>Для того, чтобы вывести что-то на экран в языке Python используется функция <b>print()</b>. Что такое функция? Функция - это команда, которая умеет выполнять некое действие. Она всегда пишется со скобками - именно они "заставляют" ее что-то делать. В скобках у функции <b>print()</b> мы можем передать значения. Значения - это данные, которые имеют определенные типы. Например, мы будем часто взаимодействовать с такими типами, как <b>строки (str)</b>, <b>целые числа (int)</b> и <b>дробные числа (float)</b>.</p>
<p>Для того, чтобы вывести на экран строку, необходимо написать, например, <b>print('Hello, World!')</b>. Обратите внимание на кавычки. Я указала одинарные, но можно также использовать двойные - значения это не имеет, хотя одинарные ставить быстрее. Строка - это набор символов. Под символами понимают всё, что угодно, что можно напечатать с клавиатуры и еще специальные символы, о которых мы узнаем чуть позже.</p>
<pre data-lang="python">
  <code>
print('Hello, World!')
  </code>
</pre>

<p>Отлично! Теперь мы умеем приветствовать мир!</p>
<p>Но как бы нам приветствовать нашего пользователя? Похоже, что нам понадобится: 1) узнать имя пользователя, 2) куда-то запомнить его, 3) использовать при печати в консоль приветствия.</p>
<p>Итак, чтобы считать какие-то данные с клавиатуры, необходимо использовать функцию <b>input()</b>, а затем эти данные нужна куда-то сохранить. Хранить данные мы будем в <b>переменных</b>. Слово очень напоминает слово из математики, когда мы решаем уравнения.</p>
<p>Переменная - это такое название ячейки памяти (усл.), с помощью которого мы сможем в нее что-то сохранять или извлекать из нее то, что уже в ней лежит. Для того, чтобы сохранить в нее что-то, используется знак <b>равно</b>. Например,</p>
<pre data-lang="python">
  <code>
print('Введите свое имя')
name = input()
  </code>
</pre>

<p>А теперь нам нужно вывести слово "Привет," и имя, которое хранится в ячейке памяти под названием <b>name</b>. Сделать мы это можем благодаря возможности в функции <b>print()</b> перечислять бесконечное количество <b>параметров, или аргументов</b> через запятую. Например, </p>
<pre data-lang="python">
  <code>
print('Введите свое имя')
name = input()
print('Привет,', name)
  </code>
</pre>

<p>Обратите внимание на запятые: одна в кавычках, другая - нет. Попробуйте самостоятельно удалить одну и проверить, что произойдет, а затем и другую - протестируйте. Вы заметите, что одна из запятых влияет только на результат на экране, а другая на в целом выполнение программы.</p>
<p><b>Не бойтесь ошибок!</b> Вы всегда можете скопировать последнюю строку ошибки и погуглить ее. Скорее всего ваш вопрос уже решен. Не бойтесь также пытаться разобраться в ответах на английском языке с переводчиком и без.</p>
<p><a href="https://clck.ru/36uHTV">Домашнее задание 1</a></p>

<h2 id="operations">Арифметические операции</h3>
<p>Попробуйте запустить код ниже. Что особенного происходит?</p>
<pre data-lang="python">
  <code>
print('1' + '2')
print(1 + 2)
  </code>
</pre>
<p>Итак, мы видим в целом похожий код, однако в первом случае числа написаны в кавычках, а во втором - без. В чем различие? Различие в <b>типах данных</b> и, соответственно, операциях, которые нам доступны.</p>
<p>Давайте подумаем, какие арифметические операции мы используем в обычной жизни. Скорее всего вы вспомните сложение, вычитание, умножение и деление. Действительно! В языке Python можно выполнять все эти действия.
Давайте попробуем запустить следующий код в PyCharm.</p>
<pre data-lang="python">
  <code>
print(22 + 3)
print(22 - 3)
print(22 * 3)
print(22 / 3)
print(22 // 3)
print(22 % 3)
print(22 ** 3)
  </code>
</pre>

<p>Что выполняют операции /, //, % и **?</p>
<p>Обратите внимание, что все числа написаны без кавычек! Это важно. Если вы попробуете написать то же, но каждое число в кавычках, то, начиная с какой-то операции, программа завершится с ошибкой.</p>
<p>Хорошо, но что если в задаче требуется вывести строку следующего вида: <code>Привет, %name%!</code>. Обращаем внимание на восклицательный знак в конце. Попробуем написать следующий код:</p>
<pre data-lang="python">
  <code>
name = input()
print('Привет,', name, '!')
  </code>
</pre>
<p>Обратите внимание, что при запуске программа словно зависает, но на самом деле она просто ждет, когда вы что-нибудь введете и нажмете на Enter.</p>
<p>Что мы видим? Между именем и восклицательным знаком вставился пробел... Не то чтобы это было правильно... Но вот что вспомнилось, мы можем склеивать строки! Попробуем изменить код:</p>
<pre data-lang="python">
  <code>
name = input()
print('Привет,' + name + '!')
  </code>
</pre>
<p>Заметьте, что имя, введенное с клавиатуры, "склеилось" с запятой. Подумайте, куда нужно вставить пробел, чтобы "расклеить" их.</p>
<p>Хотелось бы отсюда сделать такой вывод: функция <b>input()</b> считывает <b>строку</b>, имеется в виду тип данных. Это же можно проверить, запустив следующий код (попробуйте также заменить умножение на плюс).</p>
<pre data-lang="python">
  <code>
a = input()
print(a * 5)
  </code>
</pre>
<p>Но что если наш пользователь будет вводить только числа, а мы хотим с его числами производить вычисление - например, сделать калькулятор? В таком случае нам понадобится еще одна функция - <b>int()</b>. В скобках мы можем указать какое-нибудь число в кавычках (т.е. число, но строкового типа данных). Например, <code>int('5')</code> в результате даст просто 5, а это мы уже можем сохранить в переменную.</p>
<p>Давайте запомним, что код <code>int(input())</code> <b>всегда</b> считывает числа. Если вы попытаетесь ввести абракадабру, то программа завершится с ошибкой.</p>
<p>Попробуйте запустить следующий код:</p>
<pre data-lang="python">
  <code>
a = int(input())
b = int(input())
print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a // b)
print(a % b)
print(a ** b)
  </code>
</pre>

<p><a href="https://clck.ru/36tuJu">Домашнее задание 2</a></p>
<h2 id="if-else">Условный оператор</h3>
<b>Домашнее задание: </b>
<h2 id="turtle">Черепашья графика</h3>
<b>Домашнее задание: </b>
<h2 id="while">Цикл while</h3>
<b>Домашнее задание: </b>
<h2 id="for">Цикл for</h3>
<b>Домашнее задание: </b>
<h2 id="list">Списки</h3>
<b>Домашнее задание: </b>
