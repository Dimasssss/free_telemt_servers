# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-10 09:17:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 122236.7 (33h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250706
telemt_connections_bad_total 3428
telemt_handshake_timeouts_total 2144
telemt_upstream_connect_attempt_total 235251
telemt_upstream_connect_success_total 235178
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 235251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 217023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 235166
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 5851387103 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 141019113362 (131.33 GB)
telemt_user_msgs_from_client{user="hello"} 5698177
telemt_user_msgs_to_client{user="hello"} 8860208
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 122235.5 (33h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75539
telemt_connections_bad_total 3229
telemt_handshake_timeouts_total 1022
telemt_upstream_connect_attempt_total 67396
telemt_upstream_connect_success_total 67354
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 67396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 397
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67342
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 2311493863 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 31907674033 (29.72 GB)
telemt_user_msgs_from_client{user="hello"} 1880114
telemt_user_msgs_to_client{user="hello"} 9089220
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 122236.0 (33h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108896
telemt_connections_bad_total 1142
telemt_handshake_timeouts_total 5142
telemt_upstream_connect_attempt_total 76965
telemt_upstream_connect_success_total 76963
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 76965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76951
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 6341589207 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 60845068208 (56.67 GB)
telemt_user_msgs_from_client{user="hello"} 4014392
telemt_user_msgs_to_client{user="hello"} 9736176
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 122230.8 (33h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109991
telemt_connections_bad_total 952
telemt_handshake_timeouts_total 1303
telemt_upstream_connect_attempt_total 102241
telemt_upstream_connect_success_total 102015
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 102241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 102003
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 2921251331 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 76348706695 (71.11 GB)
telemt_user_msgs_from_client{user="hello"} 2658094
telemt_user_msgs_to_client{user="hello"} 17355090
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 122236.1 (33h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168319
telemt_connections_bad_total 26869
telemt_handshake_timeouts_total 4213
telemt_upstream_connect_attempt_total 130145
telemt_upstream_connect_success_total 129343
telemt_upstream_connect_fail_total 802
telemt_upstream_connect_attempts_per_request{bucket="1"} 130145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 802
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 129331
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 2001298929 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 104801737006 (97.60 GB)
telemt_user_msgs_from_client{user="hello"} 2753697
telemt_user_msgs_to_client{user="hello"} 14177293
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 17
```