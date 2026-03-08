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

# Server Metrics 2026-03-08 10:22:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 11639.6 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24169
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 162
telemt_upstream_connect_attempt_total 20495
telemt_upstream_connect_success_total 20480
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 20495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20478
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 709916995 (677.03 MB)
telemt_user_octets_to_client{user="hello"} 12303770953 (11.46 GB)
telemt_user_msgs_from_client{user="hello"} 587753
telemt_user_msgs_to_client{user="hello"} 673366
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 11638.7 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5829
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 5499
telemt_upstream_connect_success_total 5499
telemt_upstream_connect_attempts_per_request{bucket="1"} 5499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5497
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 79506055 (75.82 MB)
telemt_user_octets_to_client{user="hello"} 3875048916 (3.61 GB)
telemt_user_msgs_from_client{user="hello"} 142739
telemt_user_msgs_to_client{user="hello"} 1007757
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 11638.6 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4160
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 4077
telemt_upstream_connect_success_total 4077
telemt_upstream_connect_attempts_per_request{bucket="1"} 4077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4075
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 37154509 (35.43 MB)
telemt_user_octets_to_client{user="hello"} 1288735813 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 45524
telemt_user_msgs_to_client{user="hello"} 214461
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 11638.2 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5358
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 5138
telemt_upstream_connect_success_total 5130
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 5138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 322
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5128
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 254795767 (242.99 MB)
telemt_user_octets_to_client{user="hello"} 2342759280 (2.18 GB)
telemt_user_msgs_from_client{user="hello"} 134052
telemt_user_msgs_to_client{user="hello"} 501869
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 11638.6 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7066
telemt_connections_bad_total 2184
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 4802
telemt_upstream_connect_success_total 4802
telemt_upstream_connect_attempts_per_request{bucket="1"} 4802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4800
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 59553162 (56.79 MB)
telemt_user_octets_to_client{user="hello"} 3901388292 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 114277
telemt_user_msgs_to_client{user="hello"} 512312
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```