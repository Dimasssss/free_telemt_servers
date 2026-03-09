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

# Server Metrics 2026-03-09 02:06:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 10004.2 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8435
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 7718
telemt_upstream_connect_success_total 7716
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7714
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 85306490 (81.35 MB)
telemt_user_octets_to_client{user="hello"} 8143310546 (7.58 GB)
telemt_user_msgs_from_client{user="hello"} 188351
telemt_user_msgs_to_client{user="hello"} 311955
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 10002.6 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 625
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 596
telemt_upstream_connect_success_total 596
telemt_upstream_connect_attempts_per_request{bucket="1"} 596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 594
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 8053028 (7.68 MB)
telemt_user_octets_to_client{user="hello"} 464328430 (442.82 MB)
telemt_user_msgs_from_client{user="hello"} 22343
telemt_user_msgs_to_client{user="hello"} 92176
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 10003.0 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 668
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 583
telemt_upstream_connect_success_total 583
telemt_upstream_connect_attempts_per_request{bucket="1"} 583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 581
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 29987733 (28.60 MB)
telemt_user_octets_to_client{user="hello"} 84495371 (80.58 MB)
telemt_user_msgs_from_client{user="hello"} 17011
telemt_user_msgs_to_client{user="hello"} 27227
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 9997.9 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1295
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 1108
telemt_upstream_connect_success_total 1108
telemt_upstream_connect_attempts_per_request{bucket="1"} 1108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1106
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 8927362 (8.51 MB)
telemt_user_octets_to_client{user="hello"} 581234462 (554.31 MB)
telemt_user_msgs_from_client{user="hello"} 23041
telemt_user_msgs_to_client{user="hello"} 165483
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 10003.4 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2778
telemt_connections_bad_total 1799
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 954
telemt_upstream_connect_success_total 954
telemt_upstream_connect_attempts_per_request{bucket="1"} 954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 952
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 7115254 (6.79 MB)
telemt_user_octets_to_client{user="hello"} 1292167706 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 19763
telemt_user_msgs_to_client{user="hello"} 160496
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```