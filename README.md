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

# Server Metrics 2026-03-10 18:24:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14326.7 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57251
telemt_connections_bad_total 1595
telemt_handshake_timeouts_total 1449
telemt_upstream_connect_attempt_total 51368
telemt_upstream_connect_success_total 51357
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 51368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51355
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 1470456820 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 39264912162 (36.57 GB)
telemt_user_msgs_from_client{user="hello"} 1438165
telemt_user_msgs_to_client{user="hello"} 2902725
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 14325.7 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20897
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 360
telemt_upstream_connect_attempt_total 19148
telemt_upstream_connect_success_total 19142
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2731
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19140
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 556333714 (530.56 MB)
telemt_user_octets_to_client{user="hello"} 9757540772 (9.09 GB)
telemt_user_msgs_from_client{user="hello"} 556653
telemt_user_msgs_to_client{user="hello"} 3091823
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 14325.3 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31990
telemt_connections_bad_total 91
telemt_handshake_timeouts_total 2746
telemt_upstream_connect_attempt_total 27121
telemt_upstream_connect_success_total 27121
telemt_upstream_connect_attempts_per_request{bucket="1"} 27121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27119
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 349847351 (333.64 MB)
telemt_user_octets_to_client{user="hello"} 27802881937 (25.89 GB)
telemt_user_msgs_from_client{user="hello"} 573791
telemt_user_msgs_to_client{user="hello"} 4182401
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 14324.2 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31071
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 29714
telemt_upstream_connect_success_total 29626
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 29714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3414
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29624
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 393672303 (375.44 MB)
telemt_user_octets_to_client{user="hello"} 26585727388 (24.76 GB)
telemt_user_msgs_from_client{user="hello"} 590343
telemt_user_msgs_to_client{user="hello"} 4662209
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14325.5 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44656
telemt_connections_bad_total 4176
telemt_handshake_timeouts_total 1009
telemt_upstream_connect_attempt_total 37783
telemt_upstream_connect_success_total 37543
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 37781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37541
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 1379869823 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 23469506535 (21.86 GB)
telemt_user_msgs_from_client{user="hello"} 1093331
telemt_user_msgs_to_client{user="hello"} 3537017
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```