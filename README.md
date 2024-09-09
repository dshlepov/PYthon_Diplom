# PYthon_Diplom
Дипломная работа. Архитектура фреймворка.

Проект По автоматизации тестирвоания API и UI тестирования на python для сервиса Интернет-магазин книг.
Интернет-магазин «Читай-город» – один из ведущих в России книжных магазинов. Здесь можно купить книги всех направлений и стилей по выгодным ценам с бесплатной доставкой.


Зависимости:
- selenium;
- requests;
- pytest;
- allure.

Шаги:
1. Создать удаленный репозиторий в github;
2. Установить зависимости;
3. запустить тесты с указанием пути к директории результатов тестирования pytest --alluredir allure-result;
4. Сформировать отчет --allure serve allure-result.

СтруктураЖ
1. requirements.txt - файл с зависимостями;
2. test_ui.py - UI тесты;
3. test_api.py -API тесты;
4. MainPage.py - файл с методами для UI тестирования.