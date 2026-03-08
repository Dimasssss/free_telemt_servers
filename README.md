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

# Server Metrics 2026-03-08 06:57:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 51125.4 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75789
telemt_connections_bad_total 6863
telemt_handshake_timeouts_total 755
telemt_upstream_connect_attempt_total 64625
telemt_upstream_connect_success_total 64506
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 64625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64500
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2638659535 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 40519981565 (37.74 GB)
telemt_user_msgs_from_client{user="hello"} 1874188
telemt_user_msgs_to_client{user="hello"} 6381757
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 51124.7 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11168
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 10595
telemt_upstream_connect_success_total 10585
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10579
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 287540046 (274.22 MB)
telemt_user_octets_to_client{user="hello"} 15791845938 (14.71 GB)
telemt_user_msgs_from_client{user="hello"} 519145
telemt_user_msgs_to_client{user="hello"} 3664242
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 51124.5 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7464
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 297
telemt_upstream_connect_attempt_total 6682
telemt_upstream_connect_success_total 6682
telemt_upstream_connect_attempts_per_request{bucket="1"} 6682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6676
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 138398065 (131.99 MB)
telemt_user_octets_to_client{user="hello"} 14781386234 (13.77 GB)
telemt_user_msgs_from_client{user="hello"} 250244
telemt_user_msgs_to_client{user="hello"} 3170644
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 50952.8 (14h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16153
telemt_connections_bad_total 246
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 15474
telemt_upstream_connect_success_total 15445
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 15474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2293
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15439
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 486281685 (463.75 MB)
telemt_user_octets_to_client{user="hello"} 13893561618 (12.94 GB)
telemt_user_msgs_from_client{user="hello"} 472987
telemt_user_msgs_to_client{user="hello"} 3875353
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 51124.6 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21329
telemt_connections_bad_total 9448
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 11585
telemt_upstream_connect_success_total 11577
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 11585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11571
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 1660716522 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 10892725960 (10.14 GB)
telemt_user_msgs_from_client{user="hello"} 893380
telemt_user_msgs_to_client{user="hello"} 2370905
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```