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

# Server Metrics 2026-03-06 17:59:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 27458.1 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64595
telemt_connections_bad_total 3310
telemt_handshake_timeouts_total 311
telemt_upstream_connect_attempt_total 56740
telemt_upstream_connect_success_total 56726
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 56740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56722
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 2810804141 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 37182248518 (34.63 GB)
telemt_user_msgs_from_client{user="hello"} 1947475
telemt_user_msgs_to_client{user="hello"} 5880878
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 27457.6 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12720
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 12136
telemt_upstream_connect_success_total 12117
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 12136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12113
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 152469486 (145.41 MB)
telemt_user_octets_to_client{user="hello"} 6451319302 (6.01 GB)
telemt_user_msgs_from_client{user="hello"} 250916
telemt_user_msgs_to_client{user="hello"} 1983764
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 27456.9 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9717
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 9373
telemt_upstream_connect_success_total 9371
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9367
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 134473172 (128.24 MB)
telemt_user_octets_to_client{user="hello"} 5552089676 (5.17 GB)
telemt_user_msgs_from_client{user="hello"} 214016
telemt_user_msgs_to_client{user="hello"} 1310757
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 27456.2 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13897
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 12943
telemt_upstream_connect_success_total 12899
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 12943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12895
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 190550347 (181.72 MB)
telemt_user_octets_to_client{user="hello"} 5744389736 (5.35 GB)
telemt_user_msgs_from_client{user="hello"} 239165
telemt_user_msgs_to_client{user="hello"} 1359966
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 27457.5 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19332
telemt_connections_bad_total 6497
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 11933
telemt_upstream_connect_success_total 11933
telemt_upstream_connect_attempts_per_request{bucket="1"} 11933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11929
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 265056794 (252.78 MB)
telemt_user_octets_to_client{user="hello"} 24513242503 (22.83 GB)
telemt_user_msgs_from_client{user="hello"} 457751
telemt_user_msgs_to_client{user="hello"} 4460401
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```