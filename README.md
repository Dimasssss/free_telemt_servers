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

# Server Metrics 2026-03-09 05:04:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 20707.2 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19015
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 555
telemt_upstream_connect_attempt_total 17142
telemt_upstream_connect_success_total 17137
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17135
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 161909956 (154.41 MB)
telemt_user_octets_to_client{user="hello"} 9807890692 (9.13 GB)
telemt_user_msgs_from_client{user="hello"} 312927
telemt_user_msgs_to_client{user="hello"} 467639
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 20705.4 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2217
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 2047
telemt_upstream_connect_success_total 2047
telemt_upstream_connect_attempts_per_request{bucket="1"} 2047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 140
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2045
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 34245359 (32.66 MB)
telemt_user_octets_to_client{user="hello"} 1588423820 (1.48 GB)
telemt_user_msgs_from_client{user="hello"} 70943
telemt_user_msgs_to_client{user="hello"} 315233
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 20706.1 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1433
telemt_connections_bad_total 86
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1333
telemt_upstream_connect_success_total 1333
telemt_upstream_connect_attempts_per_request{bucket="1"} 1333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1329
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 879184117 (838.46 MB)
telemt_user_octets_to_client{user="hello"} 1035096652 (987.15 MB)
telemt_user_msgs_from_client{user="hello"} 334708
telemt_user_msgs_to_client{user="hello"} 205032
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 20701.0 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2728
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 2214
telemt_upstream_connect_success_total 2214
telemt_upstream_connect_attempts_per_request{bucket="1"} 2214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2210
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 18234010 (17.39 MB)
telemt_user_octets_to_client{user="hello"} 1532447181 (1.43 GB)
telemt_user_msgs_from_client{user="hello"} 46919
telemt_user_msgs_to_client{user="hello"} 359924
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 20706.4 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5844
telemt_connections_bad_total 3760
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2035
telemt_upstream_connect_success_total 2035
telemt_upstream_connect_attempts_per_request{bucket="1"} 2035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2033
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 16723727 (15.95 MB)
telemt_user_octets_to_client{user="hello"} 2039002725 (1.90 GB)
telemt_user_msgs_from_client{user="hello"} 41517
telemt_user_msgs_to_client{user="hello"} 245666
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```