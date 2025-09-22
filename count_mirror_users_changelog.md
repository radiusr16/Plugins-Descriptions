## Версия 1.2.0 (23 фев 2025г):
### Добавлено:
- добавлен квар cup_informer_access, отвечающий за флаги доступа игроков, которым  
  будет доступен информер

### Изменено:
- лог с общим числом игроков за сутки и логи с данными посетивших сервер игроков  
  теперь в разных файлах
- все логи пишутся в папку count_unique_players

### Обновившиеся файлы:
- addons/amxmodx/plugins/count_unique_players.amxx
- addons/amxmodx/configs/count_unique_players.cfg

## Версия 1.1.0 (17 июн 2024г):
### Добавлено:
- добавлен квар cup_informer_default_state, который определяет будет (1) или  
нет (0) показываться информер по умолчанию
- добавлен квар cup_informer_toggle_cmd, отвечающий за список команд  
(разделенных ';'), с помощью которых включается/отключается отображение информера
- добавлен квар cup_log_unique_players, определяющий будут (1) или нет (0)  
записываться в лог все уникальные игроки в формате:  
Player: "Nickname<STEAM_X:X:XXXXXXXX><255.255.255.255>"

### Обновившиеся файлы:
- addons/amxmodx/plugins/count_unique_players.amxx
- addons/amxmodx/configs/count_unique_players.cfg
- addons/amxmodx/data/lang/count_unique_players.txt

## Версия 1.0.0 (05 мая 2024г):
- релиз

## Бета версия 0.0.3 (11 апр 2024г):
- создан плагин