- Запустить все тесты через консоль, если настроен pytest.ini
[pytest]

- Запустить все тесты, если в pytest.ini не указаны параметры папки и параметры удаления
[pytest --alluredir=allure-results]

- Сгенерировать allure-отчёт (локальный) - Windows в корне проекта в папке allure-results
[allure.bat serve allure-results]

- pytest.ini
Не добавлять в .gitignore

-Создать PERSONAL_TOKEN в гитхабе
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens


