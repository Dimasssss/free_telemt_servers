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

# Server Metrics 2026-03-09 07:12:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 28353.1 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29894
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 27654
telemt_upstream_connect_success_total 27646
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 27654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27642
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 264681113 (252.42 MB)
telemt_user_octets_to_client{user="hello"} 15145397758 (14.11 GB)
telemt_user_msgs_from_client{user="hello"} 533126
telemt_user_msgs_to_client{user="hello"} 799875
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 28351.7 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4866
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 4559
telemt_upstream_connect_success_total 4558
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4554
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 59802778 (57.03 MB)
telemt_user_octets_to_client{user="hello"} 3891387784 (3.62 GB)
telemt_user_msgs_from_client{user="hello"} 129796
telemt_user_msgs_to_client{user="hello"} 753906
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 28352.1 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2392
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2245
telemt_upstream_connect_success_total 2245
telemt_upstream_connect_attempts_per_request{bucket="1"} 2245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2241
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 913419156 (871.10 MB)
telemt_user_octets_to_client{user="hello"} 1444287332 (1.35 GB)
telemt_user_msgs_from_client{user="hello"} 357694
telemt_user_msgs_to_client{user="hello"} 276773
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 28347.0 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5125
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 353
telemt_upstream_connect_attempt_total 4192
telemt_upstream_connect_success_total 4189
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4185
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 135950287 (129.65 MB)
telemt_user_octets_to_client{user="hello"} 4345108892 (4.05 GB)
telemt_user_msgs_from_client{user="hello"} 97744
telemt_user_msgs_to_client{user="hello"} 1031655
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 28352.4 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11313
telemt_connections_bad_total 6134
telemt_handshake_timeouts_total 29
telemt_upstream_connect_attempt_total 4815
telemt_upstream_connect_success_total 4815
telemt_upstream_connect_attempts_per_request{bucket="1"} 4815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4811
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 61905064 (59.04 MB)
telemt_user_octets_to_client{user="hello"} 3054935104 (2.85 GB)
telemt_user_msgs_from_client{user="hello"} 95308
telemt_user_msgs_to_client{user="hello"} 425453
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```