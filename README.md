# Проект Яндекс.Самокат (manual testing)

Яндекс.Самокат - сервис аренды самокатов.

## Задачи

<details>
  <summary>Веб-приложение</summary>

1. Изучить требования к веб-приложению Яндекс.Самокат
2. Составить чек-лист по требованиям к экрану «Статус заказа»
3. Для экрана «Сделать заказ» составь проверки на валидацию полей
4. Провести тестирование всей функциональности не только по получившимся чек-листам и таблицам, но и по остальным макетам и требованиям (кроме главной страницы)

</details>

<details>
  <summary>Мобильное приложение для курьеров</summary>

  1. Изучить требования к мобильному приложению Яндекс.Самокат
  2. Спроектировать тест-кейсы для проверки нотификаций и отсутствия интернет-соединения
  3. Протестировать функциональность 

</details>

<details>
  <summary>API</summary>

1. Изучить требования к бэкенду и документацию к API
2. Разработать чек-лист для проверки создания курьера, удаления курьера, получения заказа по номеру
3. Протестировать API

</details>

## Требования и макеты

<details>
  <summary>Веб-приложение</summary>
  
  [Требования к веб-приложению](docs/requirements_web_app_1.1.pdf)

  [Макеты веб-приложения](https://www.figma.com/design/vHgTVzFac8zyxhMZ2o4b2m/web?node-id=0-1&p=f)
  
</details>

<details>
  <summary>Мобильное приложение для курьеров</summary>

  [Требования к мобильному приложению](docs/requirements_mob_app.pdf)

  [Макеты мобильного приложения](https://www.figma.com/design/kqLqPvSvjLVLomkdadkAnk/mobile?node-id=0-1&p=f)
  
</details>

<details>
  <summary>API</summary>

  [Требования к бэкенду приложения](docs/requirements_backend.pdf)

  [Документация API](docs/Ez-scooter.pdf)
  
</details>

## Ход работы
<details>
  <summary>Веб-приложение</summary>

1. Проведен тест-анализ и декомпозиция текстовых требований и макетов в Figma; уточнены «серые зоны».
2. Спроектирована тестовая документация с применением техник тест-дизайна: разбиение на классы эквивалентности, выделение граничных значений, позитивное и негативное тестирование. В результате составлены:
* чек-лист по требованиям к экрану «Статус заказа»,
* проверки на валидацию полей для экрана «Сделать заказ».
3. Проведено тестирование по подготовленным сценариям.
4. Выполнено исследовательское тестирование оставшейся функциональности приложения (кроме главной страницы).
5. Заведены баг-репорты по результатам тестирования.
  
</details>

<details>
  <summary>Мобильное приложение для курьеров</summary>

1. Изучены текстовые требования и макеты экранов в Figma к мобильному приложению Яндекс.Самокат; уточнены «серые зоны».
2. Спроектированы тест-кейсы для проверки нотификаций и сценариев при отсутствии интернет-соединения.
3. Проведено тестирование функциональности приложения в эмуляторе Android Studio.
4. Заведены баг-репорты по результатам тестирования.
 
</details>

<details>
  <summary>API</summary>

1. Изучены требования к бэкенду и документация к API в Apidoc.
2. Разработан чек-лист для проверки создания и удаления курьера, получения заказа по номеру.
3. Проведено тестирование API в Postman: проверены коды и статусы ответов, структура ответов и корректность изменения данных в базе (с помощью SQL-запросов).
4. Заведены баг-репорты по результатам тестирования.

</details>

## 🔧 Инструменты  

[![Figma](https://img.shields.io/badge/Figma-000000?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com)
[![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)](https://docs.google.com/spreadsheets)
[![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)](https://developer.android.com/studio)
[![Chrome DevTools](https://img.shields.io/badge/Chrome_DevTools-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://developer.chrome.com/docs/devtools)
[![apiDoc](https://img.shields.io/badge/apiDoc-000000?style=for-the-badge&logo=swagger&logoColor=white)](https://apidocjs.com/)
[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://www.postman.com)
[![Charles Proxy](https://img.shields.io/badge/Charles_Proxy-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.charlesproxy.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org)


