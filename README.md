# backend_test_homework

## Описание
Тестовый репозиторий, с которого всё началось.

### Работа с репозиторим
1. Клонируем репозиторий на локальный компьютер:
```
git clone git@github.com:ваш-аккаунт-на-гитхабе/backend_test_homework.git # ссылку берем во вкладке SSH на GitHub
```
2. Переходим в терминале в папку с проектом:
```
cd backend_test_homework/
```
3. Проверяем, что все файлы из удалённого репозитория были клонированы успешно:
```
ls # должны получить список файлов
```
4. Развёртываем виртуальное окружение (работаем в VSCode):
* для Mac или Linux:
  ```
  $ python3 -m venv venv
  ```
* для Windows:
  ```
  $ python -m venv venv
  ```
5. Запускаем виртуальное окружение:
* для Mac или Linux:
  ```
  $ source venv/bin/activate
  ```
  
* для Windows:
  ```
  $ source venv/Scripts/activate
  ```
6. Устанавливаем pytest и проверяем его версию:
```
$ pip install pytest
$ pytest --version
```
7. Запускаем тесты:
```
$ pytest
```

### Технологии:
* Python 3.7
* Pytest
