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

# Server Metrics 2026-03-05 23:20:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 3932.1 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55291
telemt_connections_bad_total 51890
telemt_handshake_timeouts_total 935
telemt_upstream_connect_attempt_total 2434
telemt_upstream_connect_success_total 2434
telemt_upstream_connect_attempts_per_request{bucket="1"} 2434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2432
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 35695680 (34.04 MB)
telemt_user_octets_to_client{user="hello"} 4630632671 (4.31 GB)
telemt_user_msgs_from_client{user="hello"} 86676
telemt_user_msgs_to_client{user="hello"} 652736
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 3929.9 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353
telemt_connections_bad_total 16
telemt_upstream_connect_attempt_total 338
telemt_upstream_connect_success_total 338
telemt_upstream_connect_attempts_per_request{bucket="1"} 338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 336
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1800782 (1.72 MB)
telemt_user_octets_to_client{user="hello"} 94942241 (90.54 MB)
telemt_user_msgs_from_client{user="hello"} 4917
telemt_user_msgs_to_client{user="hello"} 35011
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 3930.3 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224
telemt_connections_bad_total 26
telemt_upstream_connect_attempt_total 200
telemt_upstream_connect_success_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 198
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 678454 (662.55 KB)
telemt_user_octets_to_client{user="hello"} 19804320 (18.89 MB)
telemt_user_msgs_from_client{user="hello"} 1716
telemt_user_msgs_to_client{user="hello"} 6720
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 3933.0 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 506
telemt_connections_bad_total 53
telemt_upstream_connect_attempt_total 444
telemt_upstream_connect_success_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 76
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 442
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 13431039 (12.81 MB)
telemt_user_octets_to_client{user="hello"} 2251144685 (2.10 GB)
telemt_user_msgs_from_client{user="hello"} 38337
telemt_user_msgs_to_client{user="hello"} 388789
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 3932.9 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1284
telemt_connections_bad_total 711
telemt_upstream_connect_attempt_total 561
telemt_upstream_connect_success_total 561
telemt_upstream_connect_attempts_per_request{bucket="1"} 561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 559
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 20920476 (19.95 MB)
telemt_user_octets_to_client{user="hello"} 5483186539 (5.11 GB)
telemt_user_msgs_from_client{user="hello"} 56930
telemt_user_msgs_to_client{user="hello"} 962972
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```