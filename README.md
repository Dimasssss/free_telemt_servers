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

# Server Metrics 2026-03-06 08:34:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 1466.5 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3141
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 3048
telemt_upstream_connect_success_total 3048
telemt_upstream_connect_attempts_per_request{bucket="1"} 3048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3046
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 32418812 (30.92 MB)
telemt_user_octets_to_client{user="hello"} 1975008191 (1.84 GB)
telemt_user_msgs_from_client{user="hello"} 56185
telemt_user_msgs_to_client{user="hello"} 339998
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 1467.0 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 429
telemt_upstream_connect_success_total 429
telemt_upstream_connect_attempts_per_request{bucket="1"} 429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 427
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 4072097 (3.88 MB)
telemt_user_octets_to_client{user="hello"} 221129518 (210.89 MB)
telemt_user_msgs_from_client{user="hello"} 9933
telemt_user_msgs_to_client{user="hello"} 59978
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 1465.1 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 363
telemt_upstream_connect_success_total 363
telemt_upstream_connect_attempts_per_request{bucket="1"} 363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 361
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 3897371 (3.72 MB)
telemt_user_octets_to_client{user="hello"} 103897637 (99.08 MB)
telemt_user_msgs_from_client{user="hello"} 6359
telemt_user_msgs_to_client{user="hello"} 25012
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 1467.4 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 914
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 838
telemt_upstream_connect_success_total 835
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 77
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 833
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 11673153 (11.13 MB)
telemt_user_octets_to_client{user="hello"} 325011233 (309.95 MB)
telemt_user_msgs_from_client{user="hello"} 13884
telemt_user_msgs_to_client{user="hello"} 79809
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 1469.0 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1449
telemt_connections_bad_total 817
telemt_upstream_connect_attempt_total 613
telemt_upstream_connect_success_total 613
telemt_upstream_connect_attempts_per_request{bucket="1"} 613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 97
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 611
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 26636566 (25.40 MB)
telemt_user_octets_to_client{user="hello"} 484632502 (462.18 MB)
telemt_user_msgs_from_client{user="hello"} 21668
telemt_user_msgs_to_client{user="hello"} 96632
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```