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

# Server Metrics 2026-03-06 18:50:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 2573.0 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4331
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 64
telemt_upstream_connect_attempt_total 3994
telemt_upstream_connect_success_total 3991
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3989
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 620393201 (591.65 MB)
telemt_user_octets_to_client{user="hello"} 7952804391 (7.41 GB)
telemt_user_msgs_from_client{user="hello"} 342849
telemt_user_msgs_to_client{user="hello"} 1262250
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 2571.8 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1258
telemt_connections_bad_total 57
telemt_upstream_connect_attempt_total 1189
telemt_upstream_connect_success_total 1189
telemt_upstream_connect_attempts_per_request{bucket="1"} 1189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1187
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 14105086 (13.45 MB)
telemt_user_octets_to_client{user="hello"} 1181277105 (1.10 GB)
telemt_user_msgs_from_client{user="hello"} 30409
telemt_user_msgs_to_client{user="hello"} 326744
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 2571.6 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 722
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 720
telemt_upstream_connect_success_total 720
telemt_upstream_connect_attempts_per_request{bucket="1"} 720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 718
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 10760862 (10.26 MB)
telemt_user_octets_to_client{user="hello"} 484864140 (462.40 MB)
telemt_user_msgs_from_client{user="hello"} 15830
telemt_user_msgs_to_client{user="hello"} 110615
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 2571.7 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 687
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 661
telemt_upstream_connect_success_total 659
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 657
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 23050390 (21.98 MB)
telemt_user_octets_to_client{user="hello"} 386606458 (368.70 MB)
telemt_user_msgs_from_client{user="hello"} 20095
telemt_user_msgs_to_client{user="hello"} 93394
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 2572.1 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2238
telemt_connections_bad_total 470
telemt_upstream_connect_attempt_total 1752
telemt_upstream_connect_success_total 1752
telemt_upstream_connect_attempts_per_request{bucket="1"} 1752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1750
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 19574665 (18.67 MB)
telemt_user_octets_to_client{user="hello"} 1297509177 (1.21 GB)
telemt_user_msgs_from_client{user="hello"} 41095
telemt_user_msgs_to_client{user="hello"} 269940
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 2
```