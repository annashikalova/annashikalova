[AB_test.ipynb](AB_test.ipynb)
## Проект по А/B-тестированию
В исследовании оценена корректность проведения теста, проанализированы результаты A/B-теста.  
  
**Исходные данные:** датасет с информацией о датах проведени AB тестов в компании, датасет с данными о пользователях, действиями пользователей, вспомогательный датасет.

**Техническое задание**
- Название теста: recommender_system_test;
- Группы: А (контрольная), B (новая платёжная воронка);
- Дата запуска: 2020-12-07;
- Дата остановки набора новых пользователей: 2020-12-21;
- Дата остановки: 2021-01-04;
- Ожидаемое количество участников теста: 15% новых пользователей из региона EU;
- Назначение теста: тестирование изменений, связанных с внедрением улучшенной рекомендательной системы;
- Ожидаемый эффект: за 14 дней с момента регистрации в системе пользователи покажут улучшение каждой метрики не менее, чем на 5 процентных пунктов:
  * конверсии в просмотр карточек товаров — событие product_page
  * просмотры корзины — product_cart
  * покупки — purchase.
