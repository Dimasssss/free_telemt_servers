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

# Server Metrics 2026-03-08 11:50:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 16904.9 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36234
telemt_connections_bad_total 2571
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 31920
telemt_upstream_connect_success_total 31901
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 31920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31899
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 1025551645 (978.04 MB)
telemt_user_octets_to_client{user="hello"} 17270289336 (16.08 GB)
telemt_user_msgs_from_client{user="hello"} 833520
telemt_user_msgs_to_client{user="hello"} 1017415
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 16904.1 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8863
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 8485
telemt_upstream_connect_success_total 8485
telemt_upstream_connect_attempts_per_request{bucket="1"} 8485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8483
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 130177941 (124.15 MB)
telemt_user_octets_to_client{user="hello"} 5611033260 (5.23 GB)
telemt_user_msgs_from_client{user="hello"} 224942
telemt_user_msgs_to_client{user="hello"} 1448668
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 16903.9 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5590
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 5399
telemt_upstream_connect_success_total 5324
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 5399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5322
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 121310805 (115.69 MB)
telemt_user_octets_to_client{user="hello"} 1581370725 (1.47 GB)
telemt_user_msgs_from_client{user="hello"} 86345
telemt_user_msgs_to_client{user="hello"} 265687
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 16903.7 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7761
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 7417
telemt_upstream_connect_success_total 7403
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 7417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 461
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7401
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 884708100 (843.72 MB)
telemt_user_octets_to_client{user="hello"} 2940373525 (2.74 GB)
telemt_user_msgs_from_client{user="hello"} 380568
telemt_user_msgs_to_client{user="hello"} 648113
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 16904.0 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10330
telemt_connections_bad_total 3151
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 7024
telemt_upstream_connect_success_total 7023
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7021
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 118154130 (112.68 MB)
telemt_user_octets_to_client{user="hello"} 6388920372 (5.95 GB)
telemt_user_msgs_from_client{user="hello"} 185577
telemt_user_msgs_to_client{user="hello"} 878344
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```