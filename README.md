# Отчёт о тестировании KeyValidator.class

## Краткое описание

29/04/2020 - было проведено тестирование установки приложения KeyValidator.class

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Невалидные ключи в списке валидных ключей](https://github.com/agasferon/JQA_task1.1/issues/1#issue-608693640)
* [Валидный ключ в списке невалидных ключей](https://github.com/agasferon/JQA_task1.1/issues/2#issue-608694538)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

В качестве тестовых данных использовались ключи данные в [руководстве использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

Валидные ключи (Result: OK):
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи (Result: FAIL):
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Тестирование производилось в следующем окружении:
* Windows 10 1903 18362.778
* openjdk version "11.0.7" 2020-04-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.7+10, mixed mode)