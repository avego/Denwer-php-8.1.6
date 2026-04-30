<h1>Denwer SE — локальный веб-стек для Windows (Apache, PHP /5.6-8.5/, MySQL 5.7 / MariaDB 11.8.6)</h1>

<p><em>Неофициальная сборка для сообщества, с панелью Denwer SE (Denwer Second Edition).</em></p>
<p>Denwer SE — это обновлённый комплект Denwer для локальной разработки под Windows: Apache, PHP (несколько версий в одной установке), MySQL и/или MariaDB, вспомогательные утилиты и универсальная панель запуска DenwerSE (исполняемый файл DenwerSE.exe). Сборка неофициальная; её можно свободно использовать в личных и рабочих целях на свой страх и риск, как и предыдущие публикации команды Seditio.</p>
<p><img height="657" src="https://seditio.org/datas/users/1-1777030295f8b-image.png" width="656"></p>
<hr>
<h3>Что в этой сборке</h3>
<ul>
  <li>
    <p><strong>Панель Denwer SE (</strong><em>Denwer Second Edition</em><strong>) </strong>— окно с кнопками и иконка в трее: запуск и остановка Apache и СУБД, полный цикл «Запустить всё» / «Остановить всё» (виртуальный диск, hosts, сервисы), автогенерация виртуальных хостов по содержимому&nbsp;home\, переключение версии PHP и движка БД.</p>
  </li>
  <li>
    <p><strong>Apache 2.4.58</strong>&nbsp;(Win64, сборка Apache Lounge).</p>
  </li>
  <li>
    <p><strong>PHP</strong>&nbsp;— в комплекте версии&nbsp;<span style="color:#e74c3c;"><strong>5.6, 7.1, 7.4, 8.1, 8.3, 8.4, 8.5</strong></span>; по умолчанию в конфиге выставлена PHP 8.3.30</p>
  </li>
  <li>
    <p><strong>СУБД</strong>: <span style="color:#e74c3c;"><strong>MySQL 5.7</strong></span> и <span style="color:#e74c3c;"><strong>MariaDB 11.8.6</strong></span> (оба присутствуют в&nbsp;usr\local\db\; активный вариант задаётся в&nbsp;configuration.txt; по умолчанию в репозитории указан MySQL 5.7).</p>
  </li>
  <li>
    <p><strong>phpMyAdmin 5.2.3</strong>&nbsp;(в&nbsp;home\localhost\www\Tools\phpMyAdmin) и <strong>phpMyAdmin 5.2.0&nbsp;</strong>(в&nbsp;home\localhost\www\Tools\phpMyAdmin5).</p>
  </li>
  <li>
    <p>В&nbsp;home\&nbsp;по-прежнему лежит демо-сайт Seditio (виртуальный хост&nbsp;seditio.local) для быстрого теста движка без отдельной установки.</p>
  </li>
</ul>
<hr>
<h3>Отличия от публикации «PHP 8.3.1 + MySQL 8.3.0 + Apache 2.4.53» (март 2024)</h3>
<ul>
  <li>
    <p>Обновлены Apache, PHP (несколько версий), phpMyAdmin и сама панель до версии 1.2.0&nbsp;с доработанным сценарием запуска и конфигурации (см.&nbsp;Readme.txt&nbsp;в корне стека).</p>
  </li>
  <li>
    <p>Вместо одного MySQL 8.3 в этой ветке стека акцент на MySQL 5.7 и параллельно поставляемую MariaDB 11.8.6; переключение — правкой&nbsp;mysql_dir&nbsp;/&nbsp;mysql_exe&nbsp;и перезапуском (подробности в&nbsp;Readme.txt, раздел про MySQL и MariaDB).</p>
  </li>
</ul>
<hr>
<h3>Системные требования</h3>
<ul>
  <li>
    <p>Windows 64-bit, права администратора там, где это нужно для&nbsp;subst, правки&nbsp;hosts&nbsp;и запуска серверов.</p>
  </li>
  <li>
    <p>Достаточно места на диске под архив и распакованный стек.</p>
  </li>
</ul>
<h2><a href="https://seditio.org/dev/denwer-se-lokalnyj-veb-stek-dlya-windows-apache-php-mysql-mariadb/download">Скачать Denwer SE 1.2.4</a></h2>

