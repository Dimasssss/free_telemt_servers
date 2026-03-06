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

# Server Metrics 2026-03-06 08:29:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 1158.9 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2510
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 2434
telemt_upstream_connect_success_total 2434
telemt_upstream_connect_attempts_per_request{bucket="1"} 2434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2432
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 26801574 (25.56 MB)
telemt_user_octets_to_client{user="hello"} 1486265276 (1.38 GB)
telemt_user_msgs_from_client{user="hello"} 42359
telemt_user_msgs_to_client{user="hello"} 226089
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 1159.5 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 292
telemt_upstream_connect_success_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 290
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 2852330 (2.72 MB)
telemt_user_octets_to_client{user="hello"} 182849493 (174.38 MB)
telemt_user_msgs_from_client{user="hello"} 7247
telemt_user_msgs_to_client{user="hello"} 47722
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 1157.4 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 242
telemt_upstream_connect_success_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 240
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 2566112 (2.45 MB)
telemt_user_octets_to_client{user="hello"} 94614051 (90.23 MB)
telemt_user_msgs_from_client{user="hello"} 5020
telemt_user_msgs_to_client{user="hello"} 21656
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 1159.8 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 475
telemt_upstream_connect_success_total 474
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 472
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 3104693 (2.96 MB)
telemt_user_octets_to_client{user="hello"} 135422832 (129.15 MB)
telemt_user_msgs_from_client{user="hello"} 7359
telemt_user_msgs_to_client{user="hello"} 37139
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 1161.7 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1032
telemt_connections_bad_total 596
telemt_upstream_connect_attempt_total 424
telemt_upstream_connect_success_total 424
telemt_upstream_connect_attempts_per_request{bucket="1"} 424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 422
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 21990724 (20.97 MB)
telemt_user_octets_to_client{user="hello"} 454903097 (433.83 MB)
telemt_user_msgs_from_client{user="hello"} 18647
telemt_user_msgs_to_client{user="hello"} 89582
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```