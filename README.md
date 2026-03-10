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

# Server Metrics 2026-03-10 14:29:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 191.6 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1375
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1282
telemt_upstream_connect_success_total 1282
telemt_upstream_connect_attempts_per_request{bucket="1"} 1282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1280
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 9228383 (8.80 MB)
telemt_user_octets_to_client{user="hello"} 416575983 (397.28 MB)
telemt_user_msgs_from_client{user="hello"} 15680
telemt_user_msgs_to_client{user="hello"} 35351
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 190.9 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 301
telemt_upstream_connect_success_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 299
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 2385109 (2.27 MB)
telemt_user_octets_to_client{user="hello"} 97914546 (93.38 MB)
telemt_user_msgs_from_client{user="hello"} 6081
telemt_user_msgs_to_client{user="hello"} 31346
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 190.7 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 447
telemt_upstream_connect_success_total 447
telemt_upstream_connect_attempts_per_request{bucket="1"} 447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 445
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 10210215 (9.74 MB)
telemt_user_octets_to_client{user="hello"} 6707284 (6.40 MB)
telemt_user_msgs_from_client{user="hello"} 4869
telemt_user_msgs_to_client{user="hello"} 6466
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 189.7 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 503
telemt_upstream_connect_success_total 502
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 500
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 1723455 (1.64 MB)
telemt_user_octets_to_client{user="hello"} 171599586 (163.65 MB)
telemt_user_msgs_from_client{user="hello"} 4807
telemt_user_msgs_to_client{user="hello"} 34568
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 190.8 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 757
telemt_upstream_connect_success_total 757
telemt_upstream_connect_attempts_per_request{bucket="1"} 757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 81
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 755
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 6006993 (5.73 MB)
telemt_user_octets_to_client{user="hello"} 528651308 (504.16 MB)
telemt_user_msgs_from_client{user="hello"} 13314
telemt_user_msgs_to_client{user="hello"} 61148
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```