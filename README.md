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

# Server Metrics 2026-03-08 14:24:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 26146.3 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60972
telemt_connections_bad_total 3632
telemt_handshake_timeouts_total 339
telemt_upstream_connect_attempt_total 54627
telemt_upstream_connect_success_total 54605
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 54627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54601
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 1522508899 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 27818428630 (25.91 GB)
telemt_user_msgs_from_client{user="hello"} 1306989
telemt_user_msgs_to_client{user="hello"} 1710720
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 26145.5 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13459
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 114
telemt_upstream_connect_attempt_total 12984
telemt_upstream_connect_success_total 12983
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12979
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 496323426 (473.33 MB)
telemt_user_octets_to_client{user="hello"} 8506187375 (7.92 GB)
telemt_user_msgs_from_client{user="hello"} 444740
telemt_user_msgs_to_client{user="hello"} 2179420
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 26145.2 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8865
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 8268
telemt_upstream_connect_success_total 8192
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 8268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8188
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 200763281 (191.46 MB)
telemt_user_octets_to_client{user="hello"} 2554772621 (2.38 GB)
telemt_user_msgs_from_client{user="hello"} 139219
telemt_user_msgs_to_client{user="hello"} 444898
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 26145.1 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11341
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 10862
telemt_upstream_connect_success_total 10841
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 10862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10837
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 933485833 (890.24 MB)
telemt_user_octets_to_client{user="hello"} 4298889985 (4.00 GB)
telemt_user_msgs_from_client{user="hello"} 443351
telemt_user_msgs_to_client{user="hello"} 959008
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 26145.3 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14924
telemt_connections_bad_total 4826
telemt_handshake_timeouts_total 112
telemt_upstream_connect_attempt_total 9761
telemt_upstream_connect_success_total 9757
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 9761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9753
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 221353736 (211.10 MB)
telemt_user_octets_to_client{user="hello"} 7967391792 (7.42 GB)
telemt_user_msgs_from_client{user="hello"} 257601
telemt_user_msgs_to_client{user="hello"} 1101238
telemt_user_unique_ips_current{user="hello"} 6
```