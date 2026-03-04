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

# Server Metrics 2026-03-04 08:43:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 1239.1 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2114
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 2006
telemt_upstream_connect_success_total 2006
telemt_upstream_connect_attempts_per_request{bucket="1"} 2006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2004
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 31207150 (29.76 MB)
telemt_user_octets_to_client{user="hello"} 1489233079 (1.39 GB)
telemt_user_msgs_from_client{user="hello"} 48859
telemt_user_msgs_to_client{user="hello"} 252921
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 1250.2 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 142
telemt_upstream_connect_success_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 140
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 854440 (834.41 KB)
telemt_user_octets_to_client{user="hello"} 6357061 (6.06 MB)
telemt_user_msgs_from_client{user="hello"} 2439
telemt_user_msgs_to_client{user="hello"} 6671
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 1235.0 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196
telemt_connections_bad_total 55
telemt_upstream_connect_attempt_total 141
telemt_upstream_connect_success_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 139
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 644118 (629.02 KB)
telemt_user_octets_to_client{user="hello"} 49651929 (47.35 MB)
telemt_user_msgs_from_client{user="hello"} 1664
telemt_user_msgs_to_client{user="hello"} 10338
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 1225.5 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 301
telemt_upstream_connect_success_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 299
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 1204945 (1.15 MB)
telemt_user_octets_to_client{user="hello"} 36183398 (34.51 MB)
telemt_user_msgs_from_client{user="hello"} 2643
telemt_user_msgs_to_client{user="hello"} 12849
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 1236.9 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 705
telemt_connections_bad_total 223
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 435
telemt_upstream_connect_success_total 435
telemt_upstream_connect_attempts_per_request{bucket="1"} 435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 433
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 4848409 (4.62 MB)
telemt_user_octets_to_client{user="hello"} 186748960 (178.10 MB)
telemt_user_msgs_from_client{user="hello"} 11384
telemt_user_msgs_to_client{user="hello"} 50510
telemt_user_unique_ips_current{user="hello"} 1
```