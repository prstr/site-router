# Базовый маршрутизатор запросов ProStore

Содержит базовую логику обработки запросов, абстрагированную от способа
получения данных.

Данные, необходимые для построения ответа, передаются через `res.locals`.
Каждый маршрут содержит краткую документацию относительно используемых им данных.
