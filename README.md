Manual Testing функционала «Доставка» (до этого был только «Самовывоз»). Данный функционал имеет региональную привязку, и список доступных магазинов для доставки зависит от конкретного адреса.

STLC_SberMarket - схема STLC и жизненный цикл тестирования доработки функционала «Доставка»: этапы тестирования, какие активности выполняются на каждом этапе, какие виды тестирования проводятся на каждом этапе, какая тестовая документация, отчетность, с какими специалистами сотрудничаем (разработчик, аналитик, смежные команды и другие).

Sbermarket_Test_Strategy - стратегия тестирования. Для реализации функционала «Доставка» была разработана интеграция с тремя сервисами: Яндекс.Карты, сервисом курьерской доставки и системой платежей SberPay.
Матрица покрытия Sbermarket_Traceability_Matrix. В ней пользовательские сценарии (Use Cases): 10 шт. позитивных сценариев от этапа авторизации до этапа оплаты.

RoadMap_Sbermarket - дорожная карта с этапами тестирования и сроки/даты для каждого этапа тестирования.

Test Model - nестовая модель, состоящая из двух тестовых наборов: для мобильного приложения (22 тест-кейса) и веб-приложения (22 тест-кейса). 
Sbermarket_Web_TestSuite - тестовый набор для веб-приложения.
Sbermarket_Mobile_TestSuite - тестовый набор для мобильного приложения.

Sniffers - информациz j снифферах: что это такое и для чего используются в тестировании.

Fiddler_interface - скрин интерфейса Fiddler.

«01.Error_handling_Request», «01.Error_handling_Response», «02.Error_handling_Request» и т.д. -  файлы с запросами и ответами при обработке ошибок.


POST-PUT - отличия запросов POST и PUT.


«01.DevTools_код-ошибки», «02.DevTools_код-ошибки» и так далее - HTTP ошибки, появляющиеся в инструментах разработчика DevTools при тестировании.

DevTools_ошибки - список всех HTTP ошибок и их описанием.

SberMarket_Test_Report - результаты проведенного тестирования.


