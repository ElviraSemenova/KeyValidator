### Невалидные ключи среди валидных в программе KeyValidator

Предусловия:
* Скачать и установить OpenJDK11 по инструкции: [Инструкция по установке OpenJDK 11](openjdk11-manual.md)
* Скачать программу KeyValidator по ссылке из руководства: [Руководство использования](user-manual.md)

Шаги:
* Открыть командную строку.
* Проверить установку OpenJDK11 командой "Java -version".
* Проверить установку компилятора командой "Javac -version".
* Ввести в командной строке: java KeyValidator 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 80b427f8-92cd-3aae-ba04-3927fbe17c6 b295bc63-9f03-3b4b-af80-969b39f8c262 387eedc6-12e9-3b32-9881-63b6b5e85317 c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Ожидаемый результат: 
* Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* Result for 80b427f8-92cd-3aae-ba04-03927fbe17c6: OK
* Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: OK
* Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK