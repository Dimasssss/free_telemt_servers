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

# Server Metrics 2026-03-05 23:05:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 3008.8 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49557
telemt_connections_bad_total 46718
telemt_handshake_timeouts_total 934
telemt_upstream_connect_attempt_total 1880
telemt_upstream_connect_success_total 1880
telemt_upstream_connect_attempts_per_request{bucket="1"} 1880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 99
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1878
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 24923374 (23.77 MB)
telemt_user_octets_to_client{user="hello"} 3058292191 (2.85 GB)
telemt_user_msgs_from_client{user="hello"} 59527
telemt_user_msgs_to_client{user="hello"} 427898
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 3006.8 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276
telemt_connections_bad_total 9
telemt_upstream_connect_attempt_total 268
telemt_upstream_connect_success_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 266
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 1477884 (1.41 MB)
telemt_user_octets_to_client{user="hello"} 80078374 (76.37 MB)
telemt_user_msgs_from_client{user="hello"} 3922
telemt_user_msgs_to_client{user="hello"} 26833
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 3007.1 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180
telemt_connections_bad_total 23
telemt_upstream_connect_attempt_total 159
telemt_upstream_connect_success_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 157
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 390211 (381.07 KB)
telemt_user_octets_to_client{user="hello"} 5071133 (4.84 MB)
telemt_user_msgs_from_client{user="hello"} 977
telemt_user_msgs_to_client{user="hello"} 2249
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 3009.9 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365
telemt_connections_bad_total 7
telemt_upstream_connect_attempt_total 350
telemt_upstream_connect_success_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 348
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 10069394 (9.60 MB)
telemt_user_octets_to_client{user="hello"} 1564869503 (1.46 GB)
telemt_user_msgs_from_client{user="hello"} 28594
telemt_user_msgs_to_client{user="hello"} 273782
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 3009.7 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 975
telemt_connections_bad_total 546
telemt_upstream_connect_attempt_total 419
telemt_upstream_connect_success_total 419
telemt_upstream_connect_attempts_per_request{bucket="1"} 419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 417
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 9040568 (8.62 MB)
telemt_user_octets_to_client{user="hello"} 1803105428 (1.68 GB)
telemt_user_msgs_from_client{user="hello"} 24639
telemt_user_msgs_to_client{user="hello"} 331416
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```