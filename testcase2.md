### Bалидные ключи среди невалидных в программе KeyValidator
Предусловия:
* Скачать и установить OpenJDK11 по инструкции:  [Инструкция по установке OpenJDK 11](openjdk11-manual.md)
* Скачать программу KeyValidator по ссылке из руководства: [Руководство использования](user-manual.md)

Шаги:
* Открыть командную строку.
* Проверить установку OpenJDK11 командой "Java -version".
* Проверить установку компилятора командой "Javac -version".
* Ввести в командной строке: java KeyValidator 18252235-78e0-44a5-8720-556f0c7da17a e66075b6-ddad-445e-baf6-161b3289522b b6d53250-f07e-4352-a293-6102ddf7f1ca c2bc778a-1cb9-46c6-b435-0489649d2a42 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Ожидаемый результат: 
* Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL