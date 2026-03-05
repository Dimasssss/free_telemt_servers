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

# Server Metrics 2026-03-05 17:41:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.0

telemt_uptime_seconds 1583.4 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5958
telemt_connections_bad_total 4048
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 1873
telemt_upstream_connect_success_total 1872
telemt_upstream_connect_attempts_per_request{bucket="1"} 1871
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1870
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 27134120 (25.88 MB)
telemt_user_octets_to_client{user="hello"} 710509961 (677.60 MB)
telemt_user_msgs_from_client{user="hello"} 56391
telemt_user_msgs_to_client{user="hello"} 143376
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.0

telemt_uptime_seconds 1586.0 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411
telemt_upstream_connect_attempt_total 413
telemt_upstream_connect_success_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 411
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 3441112 (3.28 MB)
telemt_user_octets_to_client{user="hello"} 152804175 (145.73 MB)
telemt_user_msgs_from_client{user="hello"} 8570
telemt_user_msgs_to_client{user="hello"} 45623
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.0

telemt_uptime_seconds 1584.0 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 609
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 458
telemt_upstream_connect_success_total 458
telemt_upstream_connect_attempts_per_request{bucket="1"} 458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 456
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 2389969 (2.28 MB)
telemt_user_octets_to_client{user="hello"} 143637653 (136.98 MB)
telemt_user_msgs_from_client{user="hello"} 6364
telemt_user_msgs_to_client{user="hello"} 34495
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.0

telemt_uptime_seconds 1581.4 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 423
telemt_upstream_connect_success_total 423
telemt_upstream_connect_attempts_per_request{bucket="1"} 423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 421
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 2430345 (2.32 MB)
telemt_user_octets_to_client{user="hello"} 108110582 (103.10 MB)
telemt_user_msgs_from_client{user="hello"} 5735
telemt_user_msgs_to_client{user="hello"} 29418
telemt_user_unique_ips_current{user="hello"} 1
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.0

telemt_uptime_seconds 1583.3 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 836
telemt_connections_bad_total 279
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 541
telemt_upstream_connect_success_total 541
telemt_upstream_connect_attempts_per_request{bucket="1"} 541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 539
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 23258131 (22.18 MB)
telemt_user_octets_to_client{user="hello"} 679517130 (648.04 MB)
telemt_user_msgs_from_client{user="hello"} 25430
telemt_user_msgs_to_client{user="hello"} 131958
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```