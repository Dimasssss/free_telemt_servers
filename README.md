# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-11 22:03:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1097.2 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2186
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 2112
telemt_upstream_connect_success_total 2111
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 262
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2109
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 20697802 (19.74 MB)
telemt_user_octets_to_client{user="hello"} 1129165507 (1.05 GB)
telemt_user_msgs_from_client{user="hello"} 46716
telemt_user_msgs_to_client{user="hello"} 179000
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 1085.6 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 907
telemt_upstream_connect_attempt_total 877
telemt_upstream_connect_success_total 877
telemt_upstream_connect_attempts_per_request{bucket="1"} 877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 875
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 6526145 (6.22 MB)
telemt_user_octets_to_client{user="hello"} 163799480 (156.21 MB)
telemt_user_msgs_from_client{user="hello"} 15517
telemt_user_msgs_to_client{user="hello"} 68185
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 1059.2 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2200
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 1521
telemt_upstream_connect_success_total 1521
telemt_upstream_connect_attempts_per_request{bucket="1"} 1521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 206
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1519
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 10312410 (9.83 MB)
telemt_user_octets_to_client{user="hello"} 1036283988 (988.28 MB)
telemt_user_msgs_from_client{user="hello"} 30331
telemt_user_msgs_to_client{user="hello"} 300441
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 1084.6 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1201
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 1118
telemt_upstream_connect_success_total 1116
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1114
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 7630469 (7.28 MB)
telemt_user_octets_to_client{user="hello"} 517330741 (493.37 MB)
telemt_user_msgs_from_client{user="hello"} 19097
telemt_user_msgs_to_client{user="hello"} 198971
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1085.9 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1329
telemt_connections_bad_total 205
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1106
telemt_upstream_connect_success_total 1106
telemt_upstream_connect_attempts_per_request{bucket="1"} 1106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1104
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 16366165 (15.61 MB)
telemt_user_octets_to_client{user="hello"} 1032827699 (984.98 MB)
telemt_user_msgs_from_client{user="hello"} 21873
telemt_user_msgs_to_client{user="hello"} 175743
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 1085.4 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1255
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 1089
telemt_upstream_connect_success_total 1089
telemt_upstream_connect_attempts_per_request{bucket="1"} 1089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 233
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1087
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 31225897 (29.78 MB)
telemt_user_octets_to_client{user="hello"} 1169159359 (1.09 GB)
telemt_user_msgs_from_client{user="hello"} 32339
telemt_user_msgs_to_client{user="hello"} 114446
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```