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

# Server Metrics 2026-03-09 04:03:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 17036.5 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14134
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 205
telemt_upstream_connect_attempt_total 12804
telemt_upstream_connect_success_total 12801
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 12804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12799
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 129599528 (123.60 MB)
telemt_user_octets_to_client{user="hello"} 9006745606 (8.39 GB)
telemt_user_msgs_from_client{user="hello"} 259971
telemt_user_msgs_to_client{user="hello"} 398865
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 17034.8 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1511
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 1392
telemt_upstream_connect_success_total 1392
telemt_upstream_connect_attempts_per_request{bucket="1"} 1392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1390
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 27517876 (26.24 MB)
telemt_user_octets_to_client{user="hello"} 1294720446 (1.21 GB)
telemt_user_msgs_from_client{user="hello"} 54917
telemt_user_msgs_to_client{user="hello"} 246494
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 17035.3 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1124
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1026
telemt_upstream_connect_success_total 1026
telemt_upstream_connect_attempts_per_request{bucket="1"} 1026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1024
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 409108773 (390.16 MB)
telemt_user_octets_to_client{user="hello"} 942137430 (898.49 MB)
telemt_user_msgs_from_client{user="hello"} 165754
telemt_user_msgs_to_client{user="hello"} 179795
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 17030.2 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2251
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 245
telemt_upstream_connect_attempt_total 1813
telemt_upstream_connect_success_total 1813
telemt_upstream_connect_attempts_per_request{bucket="1"} 1813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 445
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1811
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 14726378 (14.04 MB)
telemt_user_octets_to_client{user="hello"} 1207417068 (1.12 GB)
telemt_user_msgs_from_client{user="hello"} 38062
telemt_user_msgs_to_client{user="hello"} 297229
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 17035.8 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4626
telemt_connections_bad_total 3103
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1491
telemt_upstream_connect_success_total 1491
telemt_upstream_connect_attempts_per_request{bucket="1"} 1491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 178
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1489
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 10667529 (10.17 MB)
telemt_user_octets_to_client{user="hello"} 1629739868 (1.52 GB)
telemt_user_msgs_from_client{user="hello"} 27580
telemt_user_msgs_to_client{user="hello"} 200141
telemt_user_unique_ips_current{user="hello"} 8
```