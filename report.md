# Отчёт о тестировании программы KeyValidator

## Краткое описание

Дата начала 29.04.2020 - Дата окончания 29.04.2020. Было проведено ручное и исследовательское тестирование приложения KeyValidator

На тестирование затрачено: 1,5 часа

В результате тестирования выявлены следующие дефекты:
* [Сообщение FAIL при вводе валидного ключа в KeyValidator](https://github.com/Toanio/java-homework1.1/issues/1)
* [Сообщение OK при вводе невалидного ключа в KeyValidator](https://github.com/Toanio/java-homework1.1/issues/2)

## Описание процесса тестирования


В качестве тестовых данных использовались данные из [Руководства пользователя KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 - ожидаемый результат Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 ожидаемый результат Result for  80b427f8-92cd-3aae-ba04-3927fbe17c6: ОК
* b295bc63-9f03-3b4b-af80-969b39f8c262 ожидаемый результат Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* 387eedc6-12e9-3b32-9881-63b6b5e85317 ожидаемый результат Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: OK
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 ожидаемый результат Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK

* 18252235-78e0-44a5-8720-556f0c7da17a ожидаемый результат Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* e66075b6-ddad-445e-baf6-161b3289522b ожидаемый результат Result for e66075b6-ddad-445e-baf6-161b3289522b : FAIL
* b6d53250-f07e-4352-a293-6102ddf7f1ca ожидаемый результат Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* c2bc778a-1cb9-46c6-b435-0489649d2a42 ожидаемый результат Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 ожидаемый результат Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL


Тестирование производилось в следующем окружении:
* Windows 10 x64
* openjdk version "11.0.7" 2020-04-14

