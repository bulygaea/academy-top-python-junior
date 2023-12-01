<h1>Курс Python Junior</h1> 
<h2>Ссылки на установщики необходимых программ</h2>
<ul>
  <li>Язык Python: <a href="https://www.python.org/ftp/python/3.12.0/python-3.12.0-amd64.exe">Windows Installer (64-bit)</a></li>
  <li>Если понадобится, ссылка на главную страницу Python: <a href="https://www.python.org/">python.org</a></li>
  <li>PyCharm Community: <a href="https://www.jetbrains.com/pycharm/download/download-thanks.html">Download</a></li>
  <li>Github Desktop: <a href="https://desktop.github.com/">Download</a></li>
</ul>
<h2>Указания к работе с репозиторием</h2>
<p>На уроке нами сделан форк данного репозитория. Теперь вы можете создать свою ветку для внесения предложений по изменению моего репозитория. Эти предложения назвают Pull Request. Я могу их принять (Merge) или отклонить. Вы можете вносить в один пулл реквест новые изменения, а чтобы сохранить их делаем, Commit.</p>
<p>Для удобной работы в разных группах вам необходимо после клонирования репозитория создать в нем папку с названием своей группы, затем папку, у котрой названием - ваши фамилия и имя. В ней должны лежать две папки: "Уроки" и "Домашние задания". В каждой из этих папок также будут папки, названием которых будет являться число - номер урока или домашнего задания.</p>
<p><b>Например, это может выглядеть так: С2311\Булыга Екатерина\Уроки\1\Задача 1</b></p>
<p>Пулл реквесты называем следующим образом: <b>Фамилия_Имя_Группа_Урок1</b> или <b>Фамилия_Имя_Группа_ДЗ1</b></p>
<p>В данном файле README.md я буду добавлять вам теоретические материалы, а также условия задач для классной и домашней работ.</p>
<h2>Уроки</h2>
<h3>Ввод-вывод данных</h3>
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
<p>Переменная - это такое название ячейки памяти, с помощью которого мы сможем в нее что-то сохранять или извлекать из нее то, что уже в ней лежит. Для того, чтобы сохранить в нее что-то, используется знак <b>равно</b>. Например,</p>
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
<b>Домашнее задание: </b>
<h3>Арифметические операции</h3>
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

<b>Домашнее задание: </b>
<h3>Условный оператор</h3>
<b>Домашнее задание: </b>
<h3>Черепашья графика</h3>
<b>Домашнее задание: </b>
<h3>Цикл while</h3>
<b>Домашнее задание: </b>
<h3>Цикл for</h3>
<b>Домашнее задание: </b>
<h3>Списки</h3>
<b>Домашнее задание: </b>
