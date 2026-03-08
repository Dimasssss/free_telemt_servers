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

# Server Metrics 2026-03-08 21:56:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 53276.1 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114817
telemt_connections_bad_total 5496
telemt_handshake_timeouts_total 1281
telemt_upstream_connect_attempt_total 104239
telemt_upstream_connect_success_total 104201
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 104239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104195
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 2558418184 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 68718902517 (64.00 GB)
telemt_user_msgs_from_client{user="hello"} 2599297
telemt_user_msgs_to_client{user="hello"} 3582622
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 53275.4 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27108
telemt_connections_bad_total 291
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 26214
telemt_upstream_connect_success_total 26207
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26201
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 838833401 (799.97 MB)
telemt_user_octets_to_client{user="hello"} 22719330579 (21.16 GB)
telemt_user_msgs_from_client{user="hello"} 978372
telemt_user_msgs_to_client{user="hello"} 6159055
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 53275.1 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15378
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13968
telemt_upstream_connect_success_total 13892
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13886
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 1554418716 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 5681449825 (5.29 GB)
telemt_user_msgs_from_client{user="hello"} 697154
telemt_user_msgs_to_client{user="hello"} 974215
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 53275.0 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21015
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 20161
telemt_upstream_connect_success_total 20121
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 20161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1506
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20115
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 1067464019 (1018.01 MB)
telemt_user_octets_to_client{user="hello"} 6574465991 (6.12 GB)
telemt_user_msgs_from_client{user="hello"} 574908
telemt_user_msgs_to_client{user="hello"} 1493440
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 53275.4 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30988
telemt_connections_bad_total 10118
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 20132
telemt_upstream_connect_success_total 20125
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 20132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20119
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 373734262 (356.42 MB)
telemt_user_octets_to_client{user="hello"} 17469734582 (16.27 GB)
telemt_user_msgs_from_client{user="hello"} 535027
telemt_user_msgs_to_client{user="hello"} 2267016
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```