# ИдеАтом 2024

В прошлом году подразделение перешло к принципам продуктового управления, но опыт работы с инструментами продуктового подхода пока в стадии накопления. Требуются эффективные средства оценки и приоритезации разработок, оценки их эффективности и коммуникации с бизнес-заказчиком на основе понятных критериев.
Решение кейса должно включать: методологию расчета метрик, модель юнит-экономики продукта; методологию тестирования гипотез; рекомендации по построению отчетов по метрикам; прочие рекомендации.

https://ideatom.ru/

## Проблема

В прошлом году ЦК САП перешел к принципам продуктового управления, но опыт работы с инструментами продуктового подхода пока в стадии накопления. Продукт ВДНМ/СВК был изначально разработан на импортной платформе, но сейчас начаты работы по его импортозамещению. Краткое описание продукта ВДНМ/СВК – система агрегации налоговой и финансовой отчетности, где пользователями являются как представители налогового органа, так и пользователи предприятий и ОЦО.

Кроме налоговой отчетности, это мастер-система по налоговым и финансовым рискам и контрольным процедурам. Также система интегрирована с системой ФНС «АИС Налог-3», чтобы проверяющие органы могли находить интересующие данные не вручную, а по унифицированным сценариям взаимодействия.

Требуются эффективные средства оценки и приоритезации разработок, оценки эффективности функциональных доработок и коммуникации с бизнесзаказчиком на основе понятных критериев.


Для продукта ВДНМ 2.0 необходимо:


 1) Выполнить предварительный анализ предметной области
 2) Разработать метрики по для продукта ВДНМ 2.0, их классификацию, взаимосвязь, обосновать их ценность и приоритеты.
 3) Разработать модель экономики продукта на основе метрик.
 4) Предложить способы поиска и формулирования гипотез, разработать подходы к тестированию гипотез.
 5) Разработать набор отчетов (макеты и методологию сбора) для мониторинга метрик.
 6) Разработать набор рекомендаций по приоритезации требований заказчика и взаимодействия с заказчиком на основе метрик.


## 1. Разработай метрики по для продукта ВДНМ 2.0, их классификацию, взаимосвязь, обосновать их ценность и приоритеты.

#### Разработка метрик для продукта ВДНМ 2.0

##### 1. Метрики:
- Пользовательская активность: количество активных пользователей, время, проведенное в приложении.
- Конверсия: процент пользователей, завершивших целевое действие (регистрация, покупка).
- Удовлетворенность пользователей: результаты опросов и отзывов, NPS (Net Promoter Score).
- Финансовые показатели: доход от подписок, средний доход на пользователя (ARPU).
- Технические метрики: скорость загрузки, время ответа сервера, количество ошибок.

##### 2. Классификация метрик:
- Метрики активности: отражают взаимодействие пользователей с продуктом.
- Метрики эффективности: показывают, насколько успешно достигаются бизнес-цели.
- Метрики качества: оценивают уровень удовлетворенности и техническую стабильность.

##### 3. Взаимосвязь метрик:
- Пользовательская активность напрямую влияет на конверсию.
- Высокая удовлетворенность пользователей может увеличить повторные покупки и улучшить финансовые показатели.
- Технические метрики влияют на пользовательский опыт и, как следствие, на общую удовлетворенность.

##### 4. Обоснование ценности:
- Метрики позволяют отслеживать успех продукта и выявлять области для улучшения.
- С их помощью можно оперативно реагировать на проблемы и оптимизировать пользовательский опыт.
- Они являются основой для принятия обоснованных бизнес-решений.

##### 5. Приоритеты:
- Оценка и улучшение пользовательской активности должна быть первоочередной.
- Следующий этап — работа над повышением конверсии.
- Удовлетворенность пользователей и технические показатели должны постоянно мониториться для поддержания высокого качества продукта.

Таким образом, разработанные метрики помогут эффективно управлять продуктом ВДНМ 2.0 и достигать поставленных целей.

## 2. Разработать модель экономики продукта на основе метрик

#### 2.1. Основные компоненты модели экономики

##### 2.1.1. Доходы
- Подписки: Основной источник дохода от пользователей, которые платят за доступ к продукту.
- Реклама: Выручка от размещения рекламы в приложении (если применимо).
- Дополнительные услуги: Доходы от дополнительных платных функций или пакетов.

##### 2.1.2. Затраты
- Разработка: Затраты на команду разработчиков, дизайн и тестирование.
- Маркетинг: Затраты на привлечение новых пользователей (реклама, продвижение).
- Технические затраты: Хостинг, поддержка сервера, лицензии.
- Обслуживание пользователей: Затраты на поддержку клиентов, управление отзывами и обратной связью.

#### 2.2. Ключевые метрики

##### 2.2.1. Пользовательские метрики
- Количество активных пользователей (MAU/DAU): Отражает активность и вовлеченность пользователей.
- Частота конверсии: Процент пользователей, которые становятся платящими клиентами.
- Средняя сумма дохода на пользователя (ARPU): Совокупный доход, деленный на количество пользователей.

##### 2.2.2. Метрики удовлетворенности
- NPS (Net Promoter Score): Оценивает лояльность и готовность рекомендовать продукт.
- Уровень удержания пользователей: Процент пользователей, которые продолжают использовать продукт через определённый период времени.

##### 2.2.3. Технические метрики
- Скорость загрузки: Время загрузки приложения, отражающее качество пользовательского опыта.
- Частота ошибок: Количество ошибок, с которыми сталкиваются пользователи на единицу времени.

#### 2.3. Создание модели

##### 2.3.1. Формулы расчета

1. Доход:
   [
   \text{Общий доход} = (\text{Количество платящих пользователей} \times \text{Средняя цена подписки}) + \text{Доход от рекламы} + \text{Доход от дополнительных услуг}
   \]

2. Расходы:
   [
   \text{Общие затраты} = \text{Затраты на разработку} + \text{Затраты на маркетинг} + \text{Технические затраты} + \text{Затраты на обслуживание}
   \]

3. Прибыль:
   [
   \text{Прибыль} = \text{Общий доход} - \text{Общие затраты}
   \]

4. ARPU:
   [
   \text{ARPU} = \frac{\text{Общий доход от подписок}}{\text{Количество активных пользователей}}
   \]

5. Оценка жизненного цикла клиента (LTV):
   [
   \text{LTV} = \text{ARPU} \times \text{Срок жизни клиента (CAC)}
   \]

6. Затраты на привлечение клиента (CAC):
   [
   \text{CAC} = \frac{\text{Общие затраты на маркетинг}}{\text{Количество новых пользователей}}
   \]

#### 2.4. Применение и анализ

- Мониторинг: Регулярно отслеживать метрики и сравнивать их с установленными целями.
- Анализ ROI: Рассчитывать возврат на инвестиции для маркетинга и привлечения пользователей.
- Оптимизация: Использовать полученные данные для улучшения продукта и методов привлечения пользователей.


## 3. 
