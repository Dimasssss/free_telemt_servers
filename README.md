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

# Server Metrics 2026-03-08 22:22:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 54815.5 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116112
telemt_connections_bad_total 5589
telemt_handshake_timeouts_total 1282
telemt_upstream_connect_attempt_total 105428
telemt_upstream_connect_success_total 105390
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 105428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105384
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2581058190 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 70216379344 (65.39 GB)
telemt_user_msgs_from_client{user="hello"} 2634372
telemt_user_msgs_to_client{user="hello"} 3633797
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 54814.5 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27299
telemt_connections_bad_total 292
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 26402
telemt_upstream_connect_success_total 26395
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26389
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 840040904 (801.13 MB)
telemt_user_octets_to_client{user="hello"} 22791954491 (21.23 GB)
telemt_user_msgs_from_client{user="hello"} 981794
telemt_user_msgs_to_client{user="hello"} 6178080
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 54814.3 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15543
telemt_connections_bad_total 234
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 14126
telemt_upstream_connect_success_total 14050
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14044
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1564648984 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 5693559901 (5.30 GB)
telemt_user_msgs_from_client{user="hello"} 701517
telemt_user_msgs_to_client{user="hello"} 977798
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 54814.1 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21341
telemt_connections_bad_total 213
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 20471
telemt_upstream_connect_success_total 20431
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 20471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20425
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 1068015138 (1018.54 MB)
telemt_user_octets_to_client{user="hello"} 6594705978 (6.14 GB)
telemt_user_msgs_from_client{user="hello"} 576489
telemt_user_msgs_to_client{user="hello"} 1501592
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 54814.4 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31855
telemt_connections_bad_total 10439
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 20667
telemt_upstream_connect_success_total 20660
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 20667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20654
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 381907517 (364.22 MB)
telemt_user_octets_to_client{user="hello"} 18119666250 (16.88 GB)
telemt_user_msgs_from_client{user="hello"} 554563
telemt_user_msgs_to_client{user="hello"} 2342446
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```