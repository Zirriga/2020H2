# Лабораторные работы за осенний семестр 2020

В `master` ветке данного репозитория присутствуют актуальные задания, включая 
распределение протоколов по студентам.

# Прогресс

Легенда:

| Символ   | Значение                                                                                   |
| --       | --                                                                                         |
|          | Работа не сдана или находится на рассмотрении                                              |
| +        | Работа принята                                                                             |
| !        | Работа рассмотрена, требуется демо                                                         |
| ?        | Работа рассмотрена, но требует доработки                                                   |
| -        | Работу сдавать не требуется                                                                |
| -------- | --------                                                                                   |
| SSH ключ | [Отправить SSH ключ преподавателю](https://insysnw.github.io/labs/900-ssh-keygen/)         |
| Л.1a     | [TCP чат](https://insysnw.github.io/labs/01-tcp-chat/)                                     |
| Л.1б     | [TCP чат](https://insysnw.github.io/labs/01-tcp-chat/) (неблокирующие сокеты)              |
| Л.2c     | [UDP сервер существующего протокола](https://insysnw.github.io/labs/02-udp-real-protocol/) |
| Л.2к     | [UDP клиент существующего протокола](https://insysnw.github.io/labs/02-udp-real-protocol/) |
| Л.3с     | Сервер для задания из методички (пункт 1.2.`n`)                                            |
| Л.3к     | Клиент для задания из методички (пункт 1.2.`n`)                                            |

## Группа 201

| ФИО              | SSH ключ | Л.1a               | Л.1б              | Л.2c | Л.2к | Л.3с | Л.3к |
| --               | --       | --                 | --                | --   | --   | --   | --   |
| Антропова А.А.   | +        |                    |                   | tftp | ntp  | 9    | 5    |
| Белов Е.А.       | +        | [?](../../pull/10) |                   | tftp | dhcp [?](../../pull/43) | 3    | 12   |
| Буй К.Д.         | +        |                    |                   | tftp | dns  | 19   | 6    |
| Гладкова Е.Д.    | +        |                    |                   |      |      |      |      |
| Голзицкий Н.С.   | +        |                    |                   |      |      |      |      |
| Гуляев Д.В.      | +        |                    |                   |      |      |      |      |
| Данилов А.И.     | +        | [?](../../pull/8)  |                   | dhcp | ntp  | 12   | 3    |
| Казанджи М.А.    | +        | [?](../../pull/7)  | [?](../../pull/7) | ntp  | snmp |      |      |
| Киселев Н.Д.     | +        |                    |                   | dns  | tftp | 1    | 11   |
| Лялин А.С.       | +        |                    |                   |      |      |      |      |
| Натура А.А.      | +        |                    |                   | ntp  | dns  |      |      |
| Никитин И.Н.     | +        |                    |                   |      |      |      |      |
| Романов А.Л.     | +        |                    |                   | dns  | dhcp | 5    | 9    |
| Свечников Р.А.   | +        | [?](../../pull/6)  |                   | dhcp | dns  |      |      |
| Сибагатулин А.Ф. |          |                    |                   |      |      |      |      |
| Товпеко К.А.     | +        | [?](../../pull/2)  | [?](../../pull/2) | dns  | ntp  |      |      |
| Черноног С.А.    | +        |                    |                   |      |      | 11   | 1    |
| Шаляпин Г.А.     | +        |                    |                   |      |      | 6    | 19   |

## Группа 203

| ФИО             | Ssh ключ | Л.1a               | Л.1б               | Л.2с | Л.2к | Л.3с | Л.3к |
| --              | --       | --                 | --                 | --   | --   | --   | --   |
| Ворошилов А.А.  | +        |                    |                    |      |      | 14   | 12   |
| Гусев Н.С.      |          |                    |                    |      |      | 4    | 18   |
| Зарецкая Е.С.   |          |                    |                    | ntp  | tftp | 17   | 13   |
| Иванов И.Д.     | +        |                    | [+](../../pull/13) | dns  | ntp  | 8    | 5    |
| Калашников Р.А. |          |                    |                    | dns  | snmp |      |      |
| Костарев В.И.   | +        |                    |                    | dhcp | snmp |      |      |
| Любченкова А.А. | +        |                    |                    | tftp | dns  | 13   | 17   |
| Меньшов П.А.    | +        |                    |                    | dns  | tftp |      |      |
| Морозов Е.С.    | +        |                    |                    | dns  | dhcp | 3    | 9    |
| Никитина Д.С.   | +        |                    |                    |      |      |      |      |
| Овсянников Е.А. | +        | [?](../../pull/11) |                    | tftp | ntp  | 12   | 14   |
| Орлова П.А.     | +        |                    |                    | tftp | dns  |      |      |
| Пентегов А.О.   | +        |                    |                    |      |      | 18   | 4    |
| Семёнов Д.С.    | +        |                    |                    | dhcp | dns  | 19   | 7    |
| Середин К.В.    | +        | [?](../../pull/5)  |                    | dhcp | ntp  | 7    | 19   |
| Трушин И.А.     | +        |                    |                    | tftp | dhcp | 9    | 3    |
| Черникова А.С.  | +        |                    |                    | tftp | ntp  | 5    | 8    |
| Шелепов В.А.    | +        |                    |                    | dhcp | tftp |      |      |

# Требования к отчету:

* Инструкция по использованию;
* Инструкция по сборке/установке;
* Описание используемого протокола;
  * Своего для первой и третьей лабораторной;
  * Используемого подмножества для второй;
* ???
* PROFIT

Отчет можно писать как в сообщении к PR-у, так и присылать в иных 
форматах (`.pdf`, `.docx`, `.txt` и т.п.).

# Порядок сдачи

* Fork от данного репозитория
* Push каждой лабораторной в отдельную ветку
* Создание отдельного PR на каждую лабораторную

При создании PR, в качестве напоминалки, сделан шаблон.
