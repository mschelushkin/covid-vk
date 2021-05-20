# covid-vk

Данный репозиторий относится к Выпускной Курсовой Работе Чёлушкина Максима.

# "Исследование пользовательских текстов,опубликованных во время пандемии коронавируса"

Для более удобного просмотра рекомендуется использовать расширение foldable headings для jupyter notebook или google collab.

[Конфиг](https://github.com/mschelushkin/covid-vk/blob/main/config.json) - конфигурация, необходимая для работы с данными.
Здесь находится информация о рассматриваемых сообществ: названия, id, флаг - необходимость фильрации публикаций.
Также здесь находятся основные фильтры для публикаций сообществ.

[Парсер ВК](https://github.com/mschelushkin/covid-vk/blob/main/vk_parser.ipynb) - здесь находятся основные скрипты для сбора данных из ВКонтакте с помощью vkAPI.
Собранные данные можно посмотреть [здесь](https://drive.google.com/drive/folders/13P6Z_aNf87Bwdf5R1DW-zPh8YMmREqr2)

[LDA](https://github.com/mschelushkin/covid-vk/blob/main/LDA_model.ipynb) - Основные эксперименты связанные с обучением LDA модели.

[LDA с биграммами](https://github.com/mschelushkin/covid-vk/blob/main/LDA_model-bigrams.ipynb) - Эксперимент с обучением LDA с применением биграмм.

[BTM](https://github.com/mschelushkin/covid-vk/blob/main/BTM.ipynb) - эксперименты с обучением [Biterm Topic Modeling](https://github.com/bnosac/BTM)

[Тематическое моделирование](https://github.com/mschelushkin/covid-vk/blob/main/tone%20detection.ipynb) - применение тематического моделирования с помощью [dostoevsky](https://pypi.org/project/dostoevsky/)

[Визуализации](https://github.com/mschelushkin/covid-vk/blob/main/diploma%20vis.ipynb) - основные визуализации, показанные в тексте

[Тексты](https://github.com/mschelushkin/covid-vk/tree/main/topic_texts) всех тем, полученных с помощью LDA

[Примеры](https://github.com/mschelushkin/covid-vk/tree/main/visualization) визуализаций из текста
