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

# Server Metrics 2026-03-09 06:06:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 24377.2 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23969
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 562
telemt_upstream_connect_attempt_total 21993
telemt_upstream_connect_success_total 21986
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 21993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21984
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 204822694 (195.33 MB)
telemt_user_octets_to_client{user="hello"} 12617290907 (11.75 GB)
telemt_user_msgs_from_client{user="hello"} 411236
telemt_user_msgs_to_client{user="hello"} 620889
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 24375.3 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3057
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 2873
telemt_upstream_connect_success_total 2873
telemt_upstream_connect_attempts_per_request{bucket="1"} 2873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 205
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2869
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 46747906 (44.58 MB)
telemt_user_octets_to_client{user="hello"} 2949137274 (2.75 GB)
telemt_user_msgs_from_client{user="hello"} 101200
telemt_user_msgs_to_client{user="hello"} 558698
telemt_user_unique_ips_current{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 24376.0 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1729
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1608
telemt_upstream_connect_success_total 1608
telemt_upstream_connect_attempts_per_request{bucket="1"} 1608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1604
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 907307794 (865.28 MB)
telemt_user_octets_to_client{user="hello"} 1119285884 (1.04 GB)
telemt_user_msgs_from_client{user="hello"} 348145
telemt_user_msgs_to_client{user="hello"} 221672
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 24370.8 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3694
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 3135
telemt_upstream_connect_success_total 3133
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3129
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 126271843 (120.42 MB)
telemt_user_octets_to_client{user="hello"} 2543182385 (2.37 GB)
telemt_user_msgs_from_client{user="hello"} 73345
telemt_user_msgs_to_client{user="hello"} 553824
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 24376.2 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8448
telemt_connections_bad_total 4866
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 3369
telemt_upstream_connect_success_total 3369
telemt_upstream_connect_attempts_per_request{bucket="1"} 3369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3367
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 43232774 (41.23 MB)
telemt_user_octets_to_client{user="hello"} 2673013438 (2.49 GB)
telemt_user_msgs_from_client{user="hello"} 71182
telemt_user_msgs_to_client{user="hello"} 351842
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```