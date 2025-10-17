Курсовая работа
Тема: Создание персонального сайта на MkDocs
Проект: проект "Расскажи о себе"
Автор: Лейсан Сакурова
Группа: U4225
Курс: Introduction in Web Technologies
Год: 2025/2026

#### Введение

Курсовая работа направлена на разработку персонального демонстрационного сайта с использованием технологии MkDocs и темы Material for MkDocs. 

Цель работы

Целью данной курсовой работы является разработка статического веб-сайта, включающего информационные разделы, навигацию, брендинг и техническую документацию, а также освоение работы с MkDocs, Git и GitHub.

### Этап 1. Подготовка проекта
Установлены программы: Python, MkDocs, тема Material

Для выполнения курсовой работы создана папка проекта my-personal-site внутри репозитория. Было настроено виртуальное окружение Python и установлены инструменты MkDocs и Material for MkDocs.

<img width="301" height="324" alt="image" src="https://github.com/user-attachments/assets/bc77b08f-d8bb-4a60-abee-e29af16935af" />

### Этап 2. Настройка конфигурации MkDocs
Создана следующая структура файлов:
<img width="853" height="752" alt="image" src="https://github.com/user-attachments/assets/8c17dcae-46b6-49d3-b20f-8a3c1a227090" />

Настроtys базовые параметры:
site_name - название сайта
site_description - описание сайта
site_author - мое имя
site_url - URL сайта
Добавлена тема Material: yaml theme: name: material features: - navigation.tabs - navigation.sections - navigation.top - search.highlight - search.share
<img width="1400" height="712" alt="image" src="https://github.com/user-attachments/assets/615c9552-c4ca-411d-a133-d8deb555660c" />

Настройка навигации:

Создана структуру навигации в mkdocs.yml
Добавлены разделы: Главная, О себе, Проекты, Контакты
<img width="1391" height="118" alt="image" src="https://github.com/user-attachments/assets/6d622a20-deac-4b49-aeaf-91be8d01fd24" />

### Этап 3: Создание контента
Главная страница (index.md):
<img width="1368" height="657" alt="image" src="https://github.com/user-attachments/assets/bbd59c57-6620-45eb-9092-4d06f57b7968" />

Страница "О себе" (about.md):
<img width="1409" height="716" alt="image" src="https://github.com/user-attachments/assets/31d39e08-eaa5-403d-a7fd-59aa1b3d9f38" />

Страница "Проекты" (projects.md):
<img width="1394" height="708" alt="image" src="https://github.com/user-attachments/assets/e16b4be5-d342-4c06-8c3e-211e85f2e3cd" />

<img width="1393" height="713" alt="image" src="https://github.com/user-attachments/assets/491f648f-3f78-440d-a633-e1d48ab962a7" />

Страница "Контакты" (contacts.md):
<img width="1404" height="708" alt="image" src="https://github.com/user-attachments/assets/5d827a40-3f68-4d97-a0b4-e68ccef59923" />

### Этап 4: Дополнительные возможности
Добавление изображений: 
Добавила свое фото
<img width="1395" height="700" alt="image" src="https://github.com/user-attachments/assets/c3627b24-e73a-45ae-859e-0b7f36a3c528" />

Создана папку docs/images/
<img width="300" height="93" alt="image" src="https://github.com/user-attachments/assets/9ed48d38-2a28-43ad-a49f-f0bd23af50ea" />

Настройка поиска:
поиск включен в конфигурации
<img width="255" height="159" alt="image" src="https://github.com/user-attachments/assets/567dd5f1-649f-4aca-a7be-eddd2fb8d071" />

Протестирован функциональность поиска
<img width="1405" height="715" alt="image" src="https://github.com/user-attachments/assets/4f13b889-b8b6-4fc7-86bd-53429df98eb7" />

### Этап 5: Стилизация и кастомизация

Настройка цветовой схемы:
Выбрать цветовую палитру в mkdocs.yml
Настроить primary и accent цвета
<img width="847" height="743" alt="image" src="https://github.com/user-attachments/assets/aa1ba811-80c3-4e80-b79b-3b1e051e9fe2" />

### Этап 6: Тестирование и публикация
Локальное тестирование:
Запустиkf локальный сервер: mkdocs serve
Провериkf все страницы и ссылки

Сборка сайта:

Создала статические файлы: mkdocs build
Проверила содержимое папки site/
<img width="893" height="313" alt="image" src="https://github.com/user-attachments/assets/61618f4c-f8e0-4a8c-893c-f36d2a3b9411" />
