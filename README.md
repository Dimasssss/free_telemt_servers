# Информация

Покупаю сервера у разных хостингов для тестов и запуска прокси для Telegram

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
```tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

# Server Metrics 2026-03-03 21:40:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.6

telemt_uptime_seconds 1782.0 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2398
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 836
telemt_upstream_connect_success_total 835
telemt_upstream_connect_attempts_per_request{bucket="1"} 834
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 833
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 10439426 (9.96 MB)
telemt_user_octets_to_client{user="hello"} 503164693 (479.86 MB)
telemt_user_msgs_from_client{user="hello"} 17993
telemt_user_msgs_to_client{user="hello"} 79486
telemt_user_unique_ips_current{user="hello"} 7
```

## psb.hosting

```
telemt 3.1.6

telemt_uptime_seconds 1785.0 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62
telemt_upstream_connect_attempt_total 61
telemt_upstream_connect_success_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 476288 (465.12 KB)
telemt_user_octets_to_client{user="hello"} 13801880 (13.16 MB)
telemt_user_msgs_from_client{user="hello"} 1271
telemt_user_msgs_to_client{user="hello"} 7695
```

## koara.io

```
telemt 3.1.6

telemt_uptime_seconds 1781.4 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 151
telemt_upstream_connect_success_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 149
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1556194 (1.48 MB)
telemt_user_octets_to_client{user="hello"} 33187150 (31.65 MB)
telemt_user_msgs_from_client{user="hello"} 4605
telemt_user_msgs_to_client{user="hello"} 12278
```

## landvps.ru

```
telemt 3.1.6

telemt_uptime_seconds 1783.3 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1353
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 1162
telemt_upstream_connect_attempt_total 161
telemt_upstream_connect_success_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 392384 (383.19 KB)
telemt_user_octets_to_client{user="hello"} 16459533 (15.70 MB)
telemt_user_msgs_from_client{user="hello"} 1013
telemt_user_msgs_to_client{user="hello"} 5230
```

## rdp-onedash.ru

```
telemt 3.1.6

telemt_uptime_seconds 1783.0 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515
telemt_connections_bad_total 328
telemt_upstream_connect_attempt_total 184
telemt_upstream_connect_success_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 182
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 7963038 (7.59 MB)
telemt_user_octets_to_client{user="hello"} 2426744813 (2.26 GB)
telemt_user_msgs_from_client{user="hello"} 21767
telemt_user_msgs_to_client{user="hello"} 417706
telemt_user_unique_ips_current{user="hello"} 1
```