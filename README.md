# RU AdList для Pi-Hole
Вручную дорабатываемый и обновляемый список (блоклист) рекламных доменов (adservers) из RU AdList для Pi-Hole.

Данный блоклист позиционируется как более полный и проработанный аналог автоматически конвертированным блоклистам.

Список составлен путём ручной правки [оригинального блоклиста](https://raw.githubusercontent.com/easylist/ruadlist/refs/heads/master/advblock/adservers.txt), с поправкой на результат автоматической конвертации скриптом от [anthonytwh](https://github.com/anthonytwh/pihole-blocklist-converter).

## Добавление в Pi-Hole:
Для добавления в Pi-Hole, в панели управления перейдите в _**Adlists**_ и вставьте в строку **Address:** ссылку на данный блоклист:

```bash
https://raw.githubusercontent.com/ElkyBoy/ruadlist-pihole/refs/heads/main/adservers_pihole.txt
```

В строку **Comment:** введите удобное вам примечание, например "RU AdList".

Не забудьте обновить блоклисты в Pi-Hole: _**Tools**_ -> _**Update Gravity**_ -> кнопка Update.

## Ссылки и благодарности:
Оригинальный репозиторий RU AdList: https://github.com/easylist/ruadlist

Особая благодарность anthonytwh за его скрипт: https://github.com/anthonytwh/pihole-blocklist-converter

При создании и доработке блоклиста использовались программы [Notepad++](https://github.com/notepad-plus-plus/notepad-plus-plus) и [WinMerge](https://github.com/WinMerge/winmerge).

### Примечание
Внимание, я не имею опыта в работе с блоклистами! Данный блоклист тестируется мной лично и при обнаружении проблем он поправляется, но гарантий актуальности списка и стабильности легальных сайтов я дать не могу!

Данный блоклист предоставляется "как есть".
