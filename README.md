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

# Server Metrics 2026-03-08 22:12:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 54199.5 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115681
telemt_connections_bad_total 5528
telemt_handshake_timeouts_total 1282
telemt_upstream_connect_attempt_total 105065
telemt_upstream_connect_success_total 105027
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 105065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105021
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 2576524520 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 69855921496 (65.06 GB)
telemt_user_msgs_from_client{user="hello"} 2623585
telemt_user_msgs_to_client{user="hello"} 3618858
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 54198.8 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27210
telemt_connections_bad_total 292
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 26315
telemt_upstream_connect_success_total 26308
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26302
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 839336509 (800.45 MB)
telemt_user_octets_to_client{user="hello"} 22735170402 (21.17 GB)
telemt_user_msgs_from_client{user="hello"} 979822
telemt_user_msgs_to_client{user="hello"} 6164721
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 54198.5 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15502
telemt_connections_bad_total 231
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 14090
telemt_upstream_connect_success_total 14014
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14008
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1564572831 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 5691699272 (5.30 GB)
telemt_user_msgs_from_client{user="hello"} 701289
telemt_user_msgs_to_client{user="hello"} 977090
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 54198.4 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21274
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 20405
telemt_upstream_connect_success_total 20365
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 20405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20359
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 1067793600 (1018.33 MB)
telemt_user_octets_to_client{user="hello"} 6582631789 (6.13 GB)
telemt_user_msgs_from_client{user="hello"} 575874
telemt_user_msgs_to_client{user="hello"} 1496740
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 54198.7 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31564
telemt_connections_bad_total 10283
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 20535
telemt_upstream_connect_success_total 20528
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 20535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20522
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 376825113 (359.37 MB)
telemt_user_octets_to_client{user="hello"} 17636567037 (16.43 GB)
telemt_user_msgs_from_client{user="hello"} 541895
telemt_user_msgs_to_client{user="hello"} 2289926
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```