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

# Server Metrics 2026-03-08 16:48:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 34777.8 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83639
telemt_connections_bad_total 5041
telemt_handshake_timeouts_total 1099
telemt_upstream_connect_attempt_total 74667
telemt_upstream_connect_success_total 74642
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 74667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74636
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 1905580570 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 42191603270 (39.29 GB)
telemt_user_msgs_from_client{user="hello"} 1780710
telemt_user_msgs_to_client{user="hello"} 2470148
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 34776.7 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17993
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 17403
telemt_upstream_connect_success_total 17400
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 17403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17396
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 642507197 (612.74 MB)
telemt_user_octets_to_client{user="hello"} 17764164987 (16.54 GB)
telemt_user_msgs_from_client{user="hello"} 698553
telemt_user_msgs_to_client{user="hello"} 4833224
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 34776.6 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11028
telemt_connections_bad_total 151
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 10392
telemt_upstream_connect_success_total 10316
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 10392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10312
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 224315189 (213.92 MB)
telemt_user_octets_to_client{user="hello"} 3657936705 (3.41 GB)
telemt_user_msgs_from_client{user="hello"} 179347
telemt_user_msgs_to_client{user="hello"} 641333
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 34776.4 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14916
telemt_connections_bad_total 167
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 14216
telemt_upstream_connect_success_total 14185
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 14216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14181
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1004382851 (957.85 MB)
telemt_user_octets_to_client{user="hello"} 5128219718 (4.78 GB)
telemt_user_msgs_from_client{user="hello"} 503634
telemt_user_msgs_to_client{user="hello"} 1156206
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 34776.8 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19796
telemt_connections_bad_total 6421
telemt_handshake_timeouts_total 189
telemt_upstream_connect_attempt_total 12886
telemt_upstream_connect_success_total 12882
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 12886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12878
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 251108899 (239.48 MB)
telemt_user_octets_to_client{user="hello"} 10977661026 (10.22 GB)
telemt_user_msgs_from_client{user="hello"} 325197
telemt_user_msgs_to_client{user="hello"} 1426975
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```