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

# Server Metrics 2026-03-05 22:50:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 2084.6 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34713
telemt_connections_bad_total 32392
telemt_handshake_timeouts_total 931
telemt_upstream_connect_attempt_total 1376
telemt_upstream_connect_success_total 1376
telemt_upstream_connect_attempts_per_request{bucket="1"} 1376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1374
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 17234384 (16.44 MB)
telemt_user_octets_to_client{user="hello"} 2546967488 (2.37 GB)
telemt_user_msgs_from_client{user="hello"} 41349
telemt_user_msgs_to_client{user="hello"} 348583
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 2082.5 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213
telemt_connections_bad_total 8
telemt_upstream_connect_attempt_total 206
telemt_upstream_connect_success_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 204
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 1200080 (1.14 MB)
telemt_user_octets_to_client{user="hello"} 69178877 (65.97 MB)
telemt_user_msgs_from_client{user="hello"} 3015
telemt_user_msgs_to_client{user="hello"} 19877
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 2083.3 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 124
telemt_upstream_connect_success_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 122
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 295509 (288.58 KB)
telemt_user_octets_to_client{user="hello"} 4462614 (4.26 MB)
telemt_user_msgs_from_client{user="hello"} 702
telemt_user_msgs_to_client{user="hello"} 1811
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 2085.6 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271
telemt_upstream_connect_attempt_total 267
telemt_upstream_connect_success_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 265
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 8778482 (8.37 MB)
telemt_user_octets_to_client{user="hello"} 1382541034 (1.29 GB)
telemt_user_msgs_from_client{user="hello"} 24967
telemt_user_msgs_to_client{user="hello"} 241989
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 2085.4 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 684
telemt_connections_bad_total 380
telemt_upstream_connect_attempt_total 303
telemt_upstream_connect_success_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 301
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 6050011 (5.77 MB)
telemt_user_octets_to_client{user="hello"} 1044425747 (996.04 MB)
telemt_user_msgs_from_client{user="hello"} 16316
telemt_user_msgs_to_client{user="hello"} 201052
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```