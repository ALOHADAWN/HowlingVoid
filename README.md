## Nova Sector (/tg/station Downstream)

[![CI Suite](https://github.com/NovaSector/NovaSector/workflows/CI%20Suite/badge.svg)](https://github.com/NovaSector/NovaSector/actions?query=workflow%3A%22CI+Suite%22)
[![Percentage of issues still open](https://isitmaintained.com/badge/open/NovaSector/NovaSector.svg)](https://isitmaintained.com/project/NovaSector/NovaSector "Percentage of issues still open")
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/NovaSector/NovaSector.svg)](https://isitmaintained.com/project/NovaSector/NovaSector "Average time to resolve an issue")
![Coverage](https://img.shields.io/codecov/c/github/NovaSector/NovaSector)

[![resentment](.github/images/badges/built-with-resentment.svg)](.github/images/comics/131-bug-free.png) [![technical debt](.github/images/badges/contains-technical-debt.svg)](.github/images/comics/106-tech-debt-modified.png) [![forinfinityandbyond](.github/images/badges/made-in-byond.gif)](https://www.reddit.com/r/SS13/comments/5oplxp/what_is_the_main_problem_with_byond_as_an_engine/dclbu1a)

| Website                 | Link                                                                                                                                   |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Шпаргалка по Git / GitHub | [https://www.notion.so/Git-GitHub-61bc81766b2e4c7d9a346db3078ce833](https://www.notion.so/Git-GitHub-61bc81766b2e4c7d9a346db3078ce833) |
| Руководство по модуляризации | [./modular_nova/readme.md](./modular_nova/readme.md)                                                                                   |
| Гайд по зеркалированию      | [./modular_nova/mirroring_guide.md](./modular_nova/mirroring_guide.md)                                                                 |
| Код                    | [https://github.com/NovaSector/NovaSector](https://github.com/NovaSector/NovaSector)                                                   |
| Вики                    | [https://wiki.novasector13.com](https://wiki.novasector13.com)                                                                         |
| Codedocs                | [https://NovaSector.github.io/NovaSector/](https://NovaSector.github.io/NovaSector/)                                                   |
| Дискорд Нова Сектора   | [https://discord.gg/novasector](https://discord.gg/novasector)                                                                         |
| Coderbus Discord        | [https://discord.gg/Vh8TJp9](https://discord.gg/Vh8TJp9)                                                                               |

Это ответвление Howling Void от Nova Sector /tg/station, созданное в byond.
**Обратите внимание, что этот репозиторий содержит материалы сексуального характера и не подходит для лиц младше 18 лет.**

Space Station 13 — это пропитанная паранойей раундовая ролевая игра, действие которой разворачивается на фоне абсурдной металлической смертельной ловушки, маскирующейся под космическую станцию. В ней очаровательные спрайты воссоздают научно-фантастический мир и его опасный подтекст. Развлекайтесь и выживайте!

## УБЕДИТЕЛЬНАЯ ПРОСЬБА - ТЕСТИРУЙТЕ ВАШИ PULL REQUESTS

Вы несёте ответственность за тестирование своего контента и предоставление доказательств этого в вашем запросе на включение изменений. Не следует отмечать запрос на включение изменений как готовый к проверке, пока вы его не протестируете. Если вам требуется отдельный клиент для тестирования, вы можете использовать гостевую учётную запись, выйдя из BYOND и подключившись к своему тестовому серверу. Тестовые слияния предназначены не для поиска ошибок, а для стресс-тестов, когда локальное тестирование просто не позволяет это сделать.

## СХЕМА РАЗВИТИЯ

![image](https://i.imgur.com/aJnE4WT.png)

[Гайд по мудулярязации](./modular_nova/readme.md)

## Качать

[Качать](.github/guides/DOWNLOADING.md)

[Запуск сервера](.github/guides/RUNNING_A_SERVER.md)

[Карты и прочее](.github/guides/MAPS_AND_AWAY_MISSIONS.md)

## Компиляция

Найдите файл `BUILD.bat` в корневой папке tgstation и дважды щёлкните по нему, чтобы начать сборку. Сборка состоит из нескольких этапов и может занять от 1 до 5 минут.

**Долгий путь**. Найдите `bin/build.cmd` в этой папке и дважды щёлкните по нему, чтобы начать сборку. Сборка состоит из нескольких этапов и может занять от 1 до 5 минут. Если она закроется, это означает, что работа завершена. Затем вы можете [настроить сервер](.github/guides/RUNNING_A_SERVER.md) обычным способом, открыв `tgstation.dmb` в DreamDaemon.

**Сборка таким образом устарела и может вызывать такие ошибки `'tgui.bundle.js': cannot find file`.

**[Как скомпилировать в VSCode и другие параметры сборки](tools/build/README.md).**

## Начало работы

Руководства по контрибуции см. в [Руководствах для контрибуторов](.github/CONTRIBUTING.md).

Информацию о начале работы (среда разработки, компиляция) см. в документе HackMD [здесь](https://hackmd.io/@tgstation/HJ8OdjNBc#tgstation-Development-Guide).

Общую проектную документацию см. в [HackMD](https://hackmd.io/@tgstation).

Информацию о [истории проекта] см. в [Common Core](https://github.com/tgstation/common_core).

## ЛИЦЕНЗИЯ

Весь код после [коммита 333c566b88108de218d882840e61928a9b759d8f от 31.01.2014 в 16:38 PST](https://github.com/tgstation/tgstation/commit/333c566b88108de218d882840e61928a9b759d8f) распространяется по лицензии [GNU AGPL v3](https://www.gnu.org/licenses/agpl-3.0.html).

Весь код до [коммита 333c566b88108de218d882840e61928a9b759d8f от 31.02.12 в 16:38 PST](https://github.com/tgstation/tgstation/commit/333c566b88108de218d882840e61928a9b759d8f) распространяется по лицензии [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html).

Включая инструменты, если в их readme-файле не указано иное.)

Подробнее см. LICENSE и GPLv3.txt.

TGS DMAPI распространяется как подпроект по лицензии MIT.

Информацию о лицензии MIT см. в нижнем колонтитуле [code/\_\_DEFINES/tgs.dm](./code/__DEFINES/tgs.dm) и [code/modules/tgs/LICENSE](./code/modules/tgs/LICENSE).

Все ресурсы, включая иконки и звук, находятся под лицензией [Creative Commons 3.0 BY-SA](https://creativecommons.org/licenses/by-sa/3.0/), если не указано иное.
