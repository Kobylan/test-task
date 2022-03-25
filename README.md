## Тестовое задание на вакансию Frontend разработчика

### Задание
Создать React приложение с двумя страницами:
* страница входа.
* страница списка сайтов, только для авторизованных пользователей.

### Данные для входа:
```
{
  email: user@example.com
  password: user123#
}
```
[GraphQL API](https://tsarka-frontend-test.herokuapp.com/frontend/task/graphql) \
[GraphQL Schema](https://tsarka-frontend-test.herokuapp.com/frontend/task)

### Пример авторизации
<img width="1680" alt="image" src="https://user-images.githubusercontent.com/51407033/160105854-be7862b5-f714-4116-b585-86aa7ad6de9a.png">

### Пример получения списка сайтов
<img width="1680" alt="image" src="https://user-images.githubusercontent.com/51407033/160105934-76e8e7f6-fed0-4e88-bc63-55d2b6de4e3e.png">

* Запрос требует `Authorization` в `Headers` с `Bearer [accessToken]`
<img width="1500" alt="image" src="https://user-images.githubusercontent.com/51407033/160106132-baf3e1fc-4df7-4dae-ab2b-722ae0aa649a.png">

***

### Требования

### Дизайн
* на ваше усмотрение, но тоже учитывается

#### HTML
* Семантичная адаптивная верстка.
* Валидация формы.

#### CSS
* Tailwind CSS.

#### JS
* React Router v6.
* GraphQL client на ваше усмотрение.

### Бонусное задание
Реализовать обновление `accessToken` при ошибки запроса `INVALID_TOKEN` с помощью `refreshToken`

***

Результат вашей работы можете опубликовать на одном из предложенных ресурсов - github pages, surge, vercel, heroku или netlify.

***

В случае крайней необходимости, по техническим вопросам, можете обратиться [сюда](https://t.me/macmeharder)
