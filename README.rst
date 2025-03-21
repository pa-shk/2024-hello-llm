Hello, LLM! для 4-го курса ФПЛ (2024/2025)
==========================================

В рамках предмета
`“Информационный поиск и извлечение данных” <https://nnov.hse.ru/ba/ling/courses/902203178.html>`__
в НИУ ВШЭ - Нижний Новгород.

Преподаватели:
--------------

-  `Демидовский Александр
   Владимирович <https://www.hse.ru/staff/demidovs>`__ - лектор
-  `Сальников Игорь Геннадьевич <https://github.com/SalnikovIgor>`__ -
   преподаватель практики
-  `Тугарёв Артём Михайлович <https://www.hse.ru/org/persons/224103384>`__ -
   преподаватель практики

Студенческая исследовательская бригада:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  `Жариков Егор Игоревич <https://t.me/godb0i>`__ - ассистент
-  `Блюдова Василиса Михайловна <https://t.me/Vasilisa282>`__ - ассистент

План лабораторных работ:
------------------------

1. `Лабораторная работа №7. Оценка нейросетевой языковой модели <https://github.com/fipl-hse/2024-hello-llm/tree/main/lab_7_llm>`__

   1. Дедлайн: 19 февраля

2. `Лабораторная работа №8. Тонкая настройка нейросетевой языковой модели <https://github.com/fipl-hse/2024-hello-llm/tree/main/lab_8_sft>`__

   1. Дедлайн: 12 марта


История занятий
---------------

+------------+---------------------+---------------------------------------------------------------+
| Дата       | Тема лекции         | Тема практики. Материалы практики.                            |
+============+=====================+===============================================================+
| 15.01.2025 | Современные задачи  | Создание форка.                                               |
|            | в области NLP.      |                                                               |
|            | Анонс               |                                                               |
|            | лабораторной работы.|                                                               |
+------------+---------------------+---------------------------------------------------------------+
| 22.01.2025 | Датасеты в          | Загрузка датасета из HuggingFace.                             |
|            | экосистеме          | `Листинг <./seminars/seminar_01_22_2025/try_datasets.py>`__.  |
|            | HuggingFace.        | Подготовка датасета.                                          |
|            |                     | `Листинг <./seminars/seminar_01_22_2025/try_pandas.py>`__.    |
|            |                     | Перегрузка протоколов датасета.                               |
|            |                     | `Листинг <./seminars/seminar_01_22_2025/try_iter_data.py>`__. |
+------------+---------------------+---------------------------------------------------------------+
| 29.01.2025 | Инференс            | Анализ ``PyTorch`` модели.                                    |
|            | языковых            | `Листинг <./seminars/seminar_01_29_2025/try_info.py>`__.      |
|            | моделей.            | Инференс модели.                                              |
|            |                     | `Листинг <./seminars/seminar_01_29_2025/try_model.py>`__.     |
+------------+---------------------+---------------------------------------------------------------+
| 05.02.2025 | Пакетная обработка  | Упаковка семплов через ``DataLoader``.                        |
|            | и загрузка примеров | `Листинг <./seminars/seminar_02_05_2025/try_dataloader.py>`__.|
|            | при инференсе       | Инференс генерационной модели.                                |
|            | языковых моделей.   | `Листинг <./seminars/seminar_02_05_2025/try_generate.py>`__.  |
|            |                     | Инференс NLI модели.                                          |
|            |                     | `Листинг <./seminars/seminar_02_05_2025/try_nli.py>`__.       |
+------------+---------------------+---------------------------------------------------------------+
| 12.02.2025 | Оценка качества     | Оценка качества модели.                                       |
|            | моделей и улучшение | `Листинг <./seminars/seminar_02_12_2025/try_evaluate.py>`__.  |
|            | качества.           | Модель как сервис.                                            |
|            |                     | `Листинг <./seminars/seminar_02_12_2025/try_fastapi.py>`__.   |
+------------+---------------------+---------------------------------------------------------------+
| 19.02.2024 | N/A                 | Сдача лабораторной работы №7.                                 |
+------------+---------------------+---------------------------------------------------------------+
| 26.02.2025 | Тонкая настройка    | Тонкая настройка модели.                                      |
|            | языковых моделей    | `Листинг <./seminars/seminar_02_26_2025/try_sft.py>`__.       |
|            | с помощью метода    |                                                               |
|            | ``LoRA``            |                                                               |
+------------+---------------------+---------------------------------------------------------------+
| 05.03.2025 | Консультация.       | N/A                                                           |
+------------+---------------------+---------------------------------------------------------------+
| 12.03.2025 | N/A                 | Сдача лабораторной работы №8.                                 |
+------------+---------------------+---------------------------------------------------------------+
| 19.03.2025 | N/A                 | Досдача лабораторных работ.                                   |
+------------+---------------------+---------------------------------------------------------------+

Более полное содержание пройденных занятий Вы найдете в :ref:`lectures-content-label`.

Литература
----------

Базовый уровень
~~~~~~~~~~~~~~~

1. `HuggingFace NLP Course <https://huggingface.co/learn/nlp-course/chapter1/1>`__.

Порядок сдачи и оценивания лабораторной работы
----------------------------------------------

1. Лабораторная работа допускается к очной сдаче.
2. Студент объяснил работу программы и показал её в действии.
3. Студент выполнил задание ментора по некоторой модификации кода.
4. Студент получает оценку:

   1. Соответствующую ожидаемой, если все шаги выше выполнены и ментор
      удовлетворён ответом студента.
   2. На балл выше ожидаемой, если все шаги выше выполнены и ментор
      решает поощрить студента за отличный ответ.
   3. На балл ниже ожидаемой, если лабораторная работа сдана на неделю
      позже срока сдачи и выполнены критерии в 4.1.
   4. На два балла ниже ожидаемой, если лабораторная работа сдана на две
      недели позже от срока сдачи и выполнены критерии в 4.1.

.. note:: Студент может улучшить оценку по лабораторной работе,
          если после основной сдачи выполнит задания следующего уровня
          сложности относительно того уровня, на котором выполнялась реализация.

**Лабораторная работа допускается к очной сдаче, если она:**

1. Представлена в виде пулл реквеста (Pull Request, PR) с правильно
   составленным названием по шаблону:
   ``Laboratory work #<NUMBER>, <SURNAME> <NAME> - <UNIVERSITY GROUP NAME>``.

   1. Пример: ``Laboratory work #1, Kashchikhin Andrey - 21FPL1``.

2. Имеет заполненный файл ``settings.json`` с ожидаемой оценкой.
   Допустимые значения: 4, 6, 8, 10.
3. Имеет “зелёный” статус - автоматические проверки качества и стиля
   кода, соответствующие заданной ожидаемой оценке, удовлетворены.
4. Имеет лейбл ``done``, выставленный ментором. Означает, что ментор
   посмотрел код студента и удовлетворён качеством кода.

Ресурсы
-------

1. `Таблица
   успеваемости <https://docs.google.com/spreadsheets/d/1Y66lNzVtdNGyNdZNBLJgKttQ2ejb8ECjfAeMxCo8F1A/edit?usp=sharing>`__
2. `Таблица
   c моделями и датасетами <https://docs.google.com/spreadsheets/d/1PiNl1Y7jRtrFHjPY7dywOz0eTCp5VbAJVcCKShkGUcU/edit?usp=sharing>`__
3. `Сайт с документацией <https://fipl-hse.github.io/>`__
4. :ref:`starting-guide-label`
5. :ref:`running-tests-label`
6. :ref:`faq-label`
