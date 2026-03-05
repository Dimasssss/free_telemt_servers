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

# Server Metrics 2026-03-05 18:28:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.0

telemt_uptime_seconds 4366.1 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16577
telemt_connections_bad_total 11258
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 5026
telemt_upstream_connect_success_total 5025
telemt_upstream_connect_attempts_per_request{bucket="1"} 5024
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5023
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 141033963 (134.50 MB)
telemt_user_octets_to_client{user="hello"} 3146031546 (2.93 GB)
telemt_user_msgs_from_client{user="hello"} 181997
telemt_user_msgs_to_client{user="hello"} 542995
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.0

telemt_uptime_seconds 4368.7 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1664
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1082
telemt_upstream_connect_success_total 1082
telemt_upstream_connect_attempts_per_request{bucket="1"} 1082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1080
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 11516278 (10.98 MB)
telemt_user_octets_to_client{user="hello"} 792001562 (755.31 MB)
telemt_user_msgs_from_client{user="hello"} 28513
telemt_user_msgs_to_client{user="hello"} 203033
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.0

telemt_uptime_seconds 4366.5 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1350
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 1179
telemt_upstream_connect_success_total 1179
telemt_upstream_connect_attempts_per_request{bucket="1"} 1179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1177
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 22928790 (21.87 MB)
telemt_user_octets_to_client{user="hello"} 608622035 (580.43 MB)
telemt_user_msgs_from_client{user="hello"} 27281
telemt_user_msgs_to_client{user="hello"} 143737
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.0

telemt_uptime_seconds 4364.0 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1463
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1426
telemt_upstream_connect_success_total 1425
telemt_upstream_connect_attempts_per_request{bucket="1"} 1424
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 97
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1423
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 16430946 (15.67 MB)
telemt_user_octets_to_client{user="hello"} 402335039 (383.70 MB)
telemt_user_msgs_from_client{user="hello"} 21746
telemt_user_msgs_to_client{user="hello"} 105789
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.0

telemt_uptime_seconds 4366.3 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2367
telemt_connections_bad_total 784
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1524
telemt_upstream_connect_success_total 1524
telemt_upstream_connect_attempts_per_request{bucket="1"} 1524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1522
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 35985809 (34.32 MB)
telemt_user_octets_to_client{user="hello"} 1204291195 (1.12 GB)
telemt_user_msgs_from_client{user="hello"} 53161
telemt_user_msgs_to_client{user="hello"} 260268
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```