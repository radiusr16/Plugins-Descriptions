## Бета версия 0.0.18 (16 апр 2025г):
### Добавлено:
- добавлен квар `rpc_respawns_num_default`, отвечающий за доступное количество  
  авто-возрождений игрока по умолчанию
- добавлены доп. значения квару `rpc_respawns_flags_default`:  
  e - игнорировать максимальное время работы функции возрождения  
  f - возродиться на месте смерти
- добавлен unstuck для возрождения на месте смерти
- добавлены native функции:
```
native rpc_is_respawn_duration_expired(id);
native rpc_get_respawns_count(id);
native rpc_set_respawns_count(id, respawns_count);
native rpc_get_respawns_num(id);
native rpc_set_respawns_num(id, respawns_num);
```

### Изменено:
- `respawn_player_core.cfg` перемещен в `addons/amxmodx/configs/respawn_player/`

### Исправлено:
- фикс радара при возрождении (предоставлен BlackSignature)

### Удалено:
- команда `rpc_settings` перенесена в плагин Respawn Player Settings

## Бета версия 0.0.1 (18 янв 2024г):
- создан плагин