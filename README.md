# Тестирование Gorest API

## Описание задания
[Ссылка на задание](https://drive.google.com/file/d/18yI9W06HoojsLLJ9WpyKTtGCtgvEzU6i/view?usp=drive_link)

Необходимо составить позитивные и негативные тест-кейсы для следующего API-эндпоинта:

- URL: https://gorest.co.in/public-api/users
- Метод: POST

### Авторизационный токен (Auth)
- Сгенерировать авторизационный Bearer токен на https://gorest.co.in/access-token (доступно после успешного входа на сайт).

### Заголовки запроса (Headers)
Запрос включает следующие заголовки:
- "Accept" = "application/json"
- "Content-Type" = "application/json"

### Тело запроса (Body)
Пример JSON:
```json
{
  "name": "Leia Organa",
  "gender": "Female",
  "email": "leiasemaill@organa.com",
  "status": "Active"
}
```

## Решение
- [Позитивные и негативные тест-кейсы](https://docs.google.com/spreadsheets/d/13BgfOf58U0-u0-TV6TCn1evDrUusYYFX6AELCjqTC30/edit?usp=sharing)
- [Баг-репорты](https://drive.google.com/drive/folders/12JQXfSMpree_d_z3hQ-zJgXxy1MSBpMd?usp=drive_link)
- [Коллекция в Postman](https://www.postman.com/speeding-astronaut-865015/workspace/public-gorest/collection/28194799-dff9d752-7c0b-41f1-a3db-6191cb54f395?action=share&creator=28194799)

