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

# Server Metrics 2026-03-08 10:32:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 12255.8 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25253
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 21516
telemt_upstream_connect_success_total 21501
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 21516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21499
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 798739096 (761.74 MB)
telemt_user_octets_to_client{user="hello"} 13179970528 (12.27 GB)
telemt_user_msgs_from_client{user="hello"} 632142
telemt_user_msgs_to_client{user="hello"} 727566
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 12255.0 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6157
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 5824
telemt_upstream_connect_success_total 5824
telemt_upstream_connect_attempts_per_request{bucket="1"} 5824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5822
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 84534389 (80.62 MB)
telemt_user_octets_to_client{user="hello"} 4006849577 (3.73 GB)
telemt_user_msgs_from_client{user="hello"} 154042
telemt_user_msgs_to_client{user="hello"} 1056743
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 12254.6 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4440
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 4335
telemt_upstream_connect_success_total 4335
telemt_upstream_connect_attempts_per_request{bucket="1"} 4335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4333
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 37953006 (36.19 MB)
telemt_user_octets_to_client{user="hello"} 1312293280 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 48050
telemt_user_msgs_to_client{user="hello"} 221033
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 12254.5 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5787
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 5523
telemt_upstream_connect_success_total 5514
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5512
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 492397515 (469.59 MB)
telemt_user_octets_to_client{user="hello"} 2475452620 (2.31 GB)
telemt_user_msgs_from_client{user="hello"} 221949
telemt_user_msgs_to_client{user="hello"} 532490
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 12254.8 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7446
telemt_connections_bad_total 2294
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 5063
telemt_upstream_connect_success_total 5063
telemt_upstream_connect_attempts_per_request{bucket="1"} 5063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5061
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 61822516 (58.96 MB)
telemt_user_octets_to_client{user="hello"} 4018529311 (3.74 GB)
telemt_user_msgs_from_client{user="hello"} 120379
telemt_user_msgs_to_client{user="hello"} 550446
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```