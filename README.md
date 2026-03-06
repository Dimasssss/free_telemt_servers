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

# Server Metrics 2026-03-06 00:12:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 7008.9 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57225
telemt_connections_bad_total 51894
telemt_handshake_timeouts_total 946
telemt_upstream_connect_attempt_total 4341
telemt_upstream_connect_success_total 4341
telemt_upstream_connect_attempts_per_request{bucket="1"} 4341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4339
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 67937905 (64.79 MB)
telemt_user_octets_to_client{user="hello"} 7292252971 (6.79 GB)
telemt_user_msgs_from_client{user="hello"} 146639
telemt_user_msgs_to_client{user="hello"} 1037737
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 7006.7 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 457
telemt_upstream_connect_success_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 455
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 2333095 (2.23 MB)
telemt_user_octets_to_client{user="hello"} 114810534 (109.49 MB)
telemt_user_msgs_from_client{user="hello"} 6651
telemt_user_msgs_to_client{user="hello"} 42500
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 7007.2 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467
telemt_connections_bad_total 94
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 373
telemt_upstream_connect_success_total 373
telemt_upstream_connect_attempts_per_request{bucket="1"} 373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 371
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1448659 (1.38 MB)
telemt_user_octets_to_client{user="hello"} 67302986 (64.19 MB)
telemt_user_msgs_from_client{user="hello"} 3777
telemt_user_msgs_to_client{user="hello"} 20150
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 7010.0 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 829
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 721
telemt_upstream_connect_success_total 721
telemt_upstream_connect_attempts_per_request{bucket="1"} 721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 719
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 23739244 (22.64 MB)
telemt_user_octets_to_client{user="hello"} 3794354677 (3.53 GB)
telemt_user_msgs_from_client{user="hello"} 68425
telemt_user_msgs_to_client{user="hello"} 660076
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 7009.7 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2383
telemt_connections_bad_total 1315
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 925
telemt_upstream_connect_success_total 925
telemt_upstream_connect_attempts_per_request{bucket="1"} 925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 923
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 30407069 (29.00 MB)
telemt_user_octets_to_client{user="hello"} 7915101044 (7.37 GB)
telemt_user_msgs_from_client{user="hello"} 83315
telemt_user_msgs_to_client{user="hello"} 1386531
telemt_user_unique_ips_current{user="hello"} 4
```