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

# Server Metrics 2026-03-06 18:25:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 1032.3 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1764
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 1616
telemt_upstream_connect_success_total 1614
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 78
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1612
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 154711158 (147.54 MB)
telemt_user_octets_to_client{user="hello"} 3297837540 (3.07 GB)
telemt_user_msgs_from_client{user="hello"} 102031
telemt_user_msgs_to_client{user="hello"} 541753
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 1030.9 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 506
telemt_upstream_connect_success_total 506
telemt_upstream_connect_attempts_per_request{bucket="1"} 506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 504
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 4523859 (4.31 MB)
telemt_user_octets_to_client{user="hello"} 295601320 (281.91 MB)
telemt_user_msgs_from_client{user="hello"} 10440
telemt_user_msgs_to_client{user="hello"} 85812
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 1030.9 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 402
telemt_upstream_connect_success_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 400
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 5932311 (5.66 MB)
telemt_user_octets_to_client{user="hello"} 90961768 (86.75 MB)
telemt_user_msgs_from_client{user="hello"} 6531
telemt_user_msgs_to_client{user="hello"} 24915
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 1030.9 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 320
telemt_upstream_connect_success_total 320
telemt_upstream_connect_attempts_per_request{bucket="1"} 320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 318
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 19958951 (19.03 MB)
telemt_user_octets_to_client{user="hello"} 192902764 (183.97 MB)
telemt_user_msgs_from_client{user="hello"} 13146
telemt_user_msgs_to_client{user="hello"} 48078
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 1031.2 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 906
telemt_connections_bad_total 194
telemt_upstream_connect_attempt_total 701
telemt_upstream_connect_success_total 701
telemt_upstream_connect_attempts_per_request{bucket="1"} 701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 699
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 5515679 (5.26 MB)
telemt_user_octets_to_client{user="hello"} 271360798 (258.79 MB)
telemt_user_msgs_from_client{user="hello"} 12802
telemt_user_msgs_to_client{user="hello"} 67461
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 7
```