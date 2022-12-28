1. Перейдите на [страницу регистрации приложения]({{ ya-client-app }}) в Яндекс ID и авторизуйтесь.
1. В поле **Название приложения** введите название для генерируемого токена.
1. В блоке **Платформы** выберите **Веб-сервисы**.
1. В появившемся поле **Callback URI** укажите адрес `{{ ya-oauth }}`.
1. В блоке **Доступы** разверните пункт **Яндекс Диск REST API (cloud_api)** и выберите все предложенные доступы.
1. Нажмите кнопку **Создать приложение**.

Сохраните идентификатор приложения (`ClientID`) и секретный ключ (`Client secret`), они понадобятся при подключении к Яндекс Диску.