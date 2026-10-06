<p align="center">
  <img src="https://e24x5-fox.github.io/claude-rus-hub/assets/mascot-wave.png" width="140" alt="">
</p>

<h1 align="center">e24x5</h1>

<p align="center">
  <b>Русификаторы игр, собранные вместе с нейросетью Claude.</b><br>
  Бесплатно, без рекламы и файлообменников. Установщик сам находит игру в Steam,<br>
  ставит перевод и одной кнопкой возвращает всё как было.
</p>

<p align="center">
  <a href="https://e24x5-fox.github.io/claude-rus-hub/"><b>📦 Каталог русификаторов</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/e24x5-Fox/claude-rus-hub">Репозиторий</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/e24x5-Fox/claude-rus-hub/issues">Сообщить об ошибке</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/e24x5-Fox">Основной аккаунт e24x5-Fox</a>
</p>

<p align="center">
  <a href="https://github.com/e24x5-Fox/claude-rus-hub/releases"><img src="https://img.shields.io/github/downloads/e24x5-Fox/claude-rus-hub/total?label=%D1%81%D0%BA%D0%B0%D1%87%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D0%B9&color=8b5cf6" alt="Скачиваний"></a>
</p>

---

## Переводы

| Игра | Движок | Что переведено | Руководство Steam |
|---|---|---|---|
| **Amorous** <sub>18+</sub> | FNA / MonoGame | 12 884 реплики, ~270 тыс. слов; интерфейс, титры, картинки с надписями. Шрифты перепечены с кириллицей | [открыть](https://steamcommunity.com/sharedfiles/filedetails/?id=3804932857) |
| **My Furry Protogen 2** <sub>18+</sub> | Ren'Py | 3722 реплики и весь интерфейс, ~60 тыс. слов; термины сведены с первой частью | [открыть](https://steamcommunity.com/sharedfiles/filedetails/?id=3809458791) |
| **My Furry Protogen** <sub>18+</sub> | Ren'Py | 2007 реплик и весь интерфейс, ~36 тыс. слов | [открыть](https://steamcommunity.com/sharedfiles/filedetails/?id=3809392303) |
| **ATLYSS** | Unity | диалоги NPC, задания, предметы, навыки, интерфейс, ~20 тыс. слов. Сохранения и игра с англоязычными не ломаются | [открыть](https://steamcommunity.com/sharedfiles/filedetails/?id=3812663935) |
| **Bodycam** | Unreal Engine 5 | весь интерфейс: меню, настройки, снаряжение, режимы, подсказки — 3674 строки | [открыть](https://steamcommunity.com/sharedfiles/filedetails/?id=3809991310) |
| **Drag'n Wash** <sub>18+</sub> | Unity | 1839 реплик, интерфейс, настройки и 87 рисованных табличек в мире игры | [открыть](https://steamcommunity.com/sharedfiles/filedetails/?id=3802642718) |
| **Odd Remedy** | Unity | ранний доступ: меню, управление, обучение, задания, телефон, надписи в уровнях | — |

Скачивать — кнопкой в [каталоге](https://e24x5-fox.github.io/claude-rus-hub/): она всегда ведёт на свежую версию.
Там же у каждой игры отчёт VirusTotal об установщике.

## Как это устроено

- **Один установщик на игру.** Находит игру по библиотекам Steam, делает резервные копии,
  перед каждой правкой сверяет, что в файле лежит ожидаемый английский текст.
  Откат возвращает игру к оригиналу. Python и прочие программы ставить не нужно.
- **Оригиналы по возможности не трогаются.** У Ren'Py перевод — отдельные файлы рядом с игрой,
  у Unreal — отдельный архив в `~mods`. Где без правки файлов не обойтись, есть откат.
- **Перевод живой, а не машинный подстрочник.** Регистр и тон — как в оригинале, включая мат
  во взрослых играх. Имена, термины и обращения («ты» / «вы») сведены по всей игре.
- **После обновления игры** перевод обычно слетает — просто запустите установщик ещё раз.
  За обновлениями игр я слежу и, если перевод сломался, выпускаю исправленную версию.

## Честно об авторстве

Тексты переведены и код установщиков написан нейросетью **Claude** (Anthropic) в Claude Code.
Я — автор и руководитель проекта: выбираю игры, проверяю результат в игре,
решаю, как звучит перевод, и отвечаю за выпуск.

## Нашли ошибку?

Пишите в [Issues](https://github.com/e24x5-Fox/claude-rus-hub/issues) или в комментариях
руководства Steam нужной игры — с названием игры и, если можно, скриншотом.
