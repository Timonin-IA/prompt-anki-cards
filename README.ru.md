# prompt-anki-cards
LLM промпт для создания карточек в Anki

1. Краткое описание
Данный промпт используется для автоматизированного создания карточек в Anki с
помощью LLM, таких как ChatGPT, DeepSeek и другие. В основном автор тестировал
работу промпта в DeepSeek.

2. Использование
Промпт копируется и вставляется в качестве первого сообщения LLM, с измененными
значениями переменных.
Для данной версии список переменных приведен ниже:
- {тема} - тема для карточек
- {количество} - количество карточек
- {результат} - формат предоставления результата, на данный момент предлагается
оставлять его неизменным.

3. Примеры работы