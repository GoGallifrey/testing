# testing
Безопасность:
API-ключ теперь берется из переменных окружения
Ограниченный набор доступных функций при выполнении кода

Обработка ошибок:
Реализовано логирование ошибок
Реализована обработка исключений

Интерфейс:
Реализован интерактивный режим
Понятные сообщения об ошибках

Документация:
Добавлены docstrings
Типизация аргументов и возвращаемых значений

Предобработка данных:
Базовая очистка данных в методе preprocess_data()

Гибкость:
Можно использовать как скрипт с аргументами, так и в интерактивном режиме

Производительность:
Кэшированы запросы к LLM, если вопросы повторяются.
