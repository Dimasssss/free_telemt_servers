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

# Server Metrics 2026-03-08 06:11:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 48354.3 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70165
telemt_connections_bad_total 6040
telemt_handshake_timeouts_total 490
telemt_upstream_connect_attempt_total 60209
telemt_upstream_connect_success_total 60090
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 60209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60084
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 2551561681 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 39118419730 (36.43 GB)
telemt_user_msgs_from_client{user="hello"} 1782055
telemt_user_msgs_to_client{user="hello"} 6130513
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 48353.1 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10443
telemt_connections_bad_total 371
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 9886
telemt_upstream_connect_success_total 9877
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9871
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 277364179 (264.52 MB)
telemt_user_octets_to_client{user="hello"} 15222727065 (14.18 GB)
telemt_user_msgs_from_client{user="hello"} 495867
telemt_user_msgs_to_client{user="hello"} 3526558
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 48352.7 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6526
telemt_connections_bad_total 305
telemt_handshake_timeouts_total 260
telemt_upstream_connect_attempt_total 5841
telemt_upstream_connect_success_total 5841
telemt_upstream_connect_attempts_per_request{bucket="1"} 5841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5835
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 134412396 (128.19 MB)
telemt_user_octets_to_client{user="hello"} 14732414025 (13.72 GB)
telemt_user_msgs_from_client{user="hello"} 243917
telemt_user_msgs_to_client{user="hello"} 3149841
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 48181.1 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15340
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 62
telemt_upstream_connect_attempt_total 14708
telemt_upstream_connect_success_total 14682
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 14708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14676
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 477649812 (455.52 MB)
telemt_user_octets_to_client{user="hello"} 13418398311 (12.50 GB)
telemt_user_msgs_from_client{user="hello"} 457668
telemt_user_msgs_to_client{user="hello"} 3752801
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 48353.0 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19764
telemt_connections_bad_total 8951
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 10534
telemt_upstream_connect_success_total 10526
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 10534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10522
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 1651727474 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 10575872687 (9.85 GB)
telemt_user_msgs_from_client{user="hello"} 877279
telemt_user_msgs_to_client{user="hello"} 2293060
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```