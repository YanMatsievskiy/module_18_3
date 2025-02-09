# Домашнее задание по теме "Базовые HTML тэги в шаблонах"

Если вы решали старую версию задачи, проверка будет производиться по ней.

Ссылка на старую версию тут.

Цель: применить изученные теги HTML, написав многостраничный проект.

Задача "Первичная структура":

Основной задачей будет написание сайта из 3-х страниц: главной и двух вторичных.

Тематику для сайта можете выбрать самостоятельно.

На рисунках будут изображены страницы на тематику "Игровая платформа".

Основные правила:

1. Все шаблоны сохраняйте в templates/third_task.
2. Для представлений создайте отдельное приложение task3.
3. Все маршруты прописывайте в urls.py проекта.

Главная страница:

1. Должна содержать самый большой заголовок "Главная страница"
2. Небольшое меню, в котором есть: переход на саму главную страницу (заглушка) и ещё 2 ссылки, по которым будет осуществляться переход на вторичные страницы.

![image](https://github.com/user-attachments/assets/e53b7784-db30-4625-baec-bb5a7a0939de)

Первая доп. страница (Магазин):

1. Заголовок с названием подстраницы.
2. Должна содержать список минимум из 3 пунктов. У каждого пункта списка создайте кнопки. У этих кнопок нет функционала.
3. После списка создайте кнопку, которая перенаправляет вас на главную страницу.

В реализации обязательно используйте словарь со значениями пунктов и передавайте его в шаблон при помощи параметра context.

![image](https://github.com/user-attachments/assets/f8aad89d-856f-4da1-a34a-ce55e5d55734)

Вторая доп. страница (Корзина):

1. Любая информация соответствующая тематике. Здесь даётся воля вашей фантазии, реализуйте что захотите.
2. В конце создайте кнопку, которая перенаправляет вас на главную страницу.

![image](https://github.com/user-attachments/assets/9d2b2993-686e-445d-bb8c-089d6fe7dc50)

Пример итоговой иерархии директорий:

![image](https://github.com/user-attachments/assets/901dc40f-dffa-4b72-a4ee-a4fab3a3d28b)

Примечания:

1. Взять пример в качестве выполняемого задания можно.

2. Для написания абсолютных путей относительно корневого в href тега a необходимо писать ссылку со слэшем перед названием. В противном случае строка присоединиться к текущему адресу.
