**Отчет о тестировании KeyValidator**


***Краткое описание***

06.11.2020 - 07.11.2020 были проведены следующие виды тестирования приложения KeyValidator:
1. Тестирование установки
2. Тестирование методом черного ящика

На тестирование затрачено - 2 ч.

В результате тестирования были выявлены следующие дефекты:
* https://github.com/OlgaNevezhina/1Java/issues/1;
* https://github.com/OlgaNevezhina/1Java/issues/2.

***Описание процесса тестирования***

В процессе тестирования использовались следующие артефакты:
* [Тест-кейс установочного тестирования](https://docs.google.com/spreadsheets/d/1XTB_JxorHTn7mfPiOBuurxlMeeSzcozjTu7qmwEgzJ0/edit?usp=sharing)
* [Тест-кейс тестирования методом черного ящика](https://docs.google.com/spreadsheets/d/1XTB_JxorHTn7mfPiOBuurxlMeeSzcozjTu7qmwEgzJ0/edit?usp=sharing)

В качестве тестовых данных для тестирования методом черного ящика использовались данные из [Руководства использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

* Ключ 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 - ожидаемый результат: сообщение в терминале Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* Ключ 80b427f8-92cd-3aae-ba04-3927fbe17c6 - ожидаемый результат: сообщение в терминале Result for 80b427f8-92cd-3aae-ba04-3927fbe17c6: OK
* Ключ b295bc63-9f03-3b4b-af80-969b39f8c262 - ожидаемый результат: сообщение в терминале Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* Ключ 387eedc6-12e9-3b32-9881-63b6b5e85317 - ожидаемый результат: сообщение в терминале Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: OK
* Ключ c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 - ожидаемый результат: сообщение в терминале Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK
* Ключ 18252235-78e0-44a5-8720-556f0c7da17a - ожидаемый результат: сообщение в терминале Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* Ключ e66075b6-ddad-445e-baf6-161b3289522b - ожидаемый результат: сообщение в терминале Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* Ключ b6d53250-f07e-4352-a293-6102ddf7f1ca - ожидаемый результат: сообщение в терминале Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* Ключ c2bc778a-1cb9-46c6-b435-0489649d2a42 - ожидаемый результат: сообщение в терминале Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* Ключ 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 - ожидаемый результат: сообщение в терминале Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL

Тестирование производилось в следующем окружении:

MacOS High Sierra версия 10.13.6 (17G66)
openjdk version "11.0.5" 2019-10-15
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.5+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.5+10, mixed mode)
