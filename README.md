# Работа приложения "Цифровая библиотека"

## Файловая структура приложения:
Название файла  | Содержание файла
----------------|----------------------
1. каталог css  - Каталог файлов каскадных таблиц стилей, в которых производится сборка необходимых стилей элементов приложения
 + style.css    - Файл каскадной таблицы стилей, описывающий основные стили элементов
 + bootstrap.css- Библиотека каскадных таблиц стилей, содержащая удобные для применения шаблоны стилей
2. каталог elems- Подключаемые части кода и модули
 + head.php     - "Шапка" сайта с мета-тегами и путями подключения внешних файлов
 + info.php     - PHP cценарий "флеш-сообщения" с результатами добавления/изменения данных приложения
 + init.php     - PHP файл с данными инициализирующими связь с MySQL базой данных
 + layot.php    - Подключаемый шаблон содержащий структуру кода главной страницы сайта
3. htaccess     - файл для настройки перенаправлений и управления конфигурацией сервера
4. add.php      - PHP сценарий отвечающий за ввод новых данных в приложение
5. edit.php     - PHP сценарий отвечающий за внесение изменений в приложение
6. index.php    - PHP сценарий главной страницы сайта позволяющий размещать, редактировать и удалять данные в приложении
7. pagination.php- PHP сценарий пагинации
8. books.sql    - dump базы данных, содержащий sql запросы для ее создания и ввода данных

### Порядок настройки приложения: 
1. Выгрузка каталогов и файлов с репозитория "library" на github
2. Размещение всех выгруженных файлов приложения на локальном либо ином сервере в отдельном каталоге
3. Создание базы данных приложения посредством импорта dump файла books.sql в новый сервер БД 
4. Запуск приложения посредством ввода в адресную строку адреса приложения
5. При необходимости настройка файла htaccess в зависимости от конфигурации нового сервера

#### Требования:
1. Сервер Apache 2.4
2. PHP 7.3
3. MySQL-5.7
