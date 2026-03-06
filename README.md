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

# Server Metrics 2026-03-06 15:56:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 20063.7 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46965
telemt_connections_bad_total 3097
telemt_handshake_timeouts_total 179
telemt_upstream_connect_attempt_total 40202
telemt_upstream_connect_success_total 40190
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 40202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40188
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 2294628921 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 25315808279 (23.58 GB)
telemt_user_msgs_from_client{user="hello"} 1476984
telemt_user_msgs_to_client{user="hello"} 4020530
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 20063.1 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8832
telemt_connections_bad_total 169
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 8345
telemt_upstream_connect_success_total 8327
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 8345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8325
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 92717199 (88.42 MB)
telemt_user_octets_to_client{user="hello"} 4847184434 (4.51 GB)
telemt_user_msgs_from_client{user="hello"} 170253
telemt_user_msgs_to_client{user="hello"} 1519375
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 20062.4 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7473
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 7190
telemt_upstream_connect_success_total 7188
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7186
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 108871118 (103.83 MB)
telemt_user_octets_to_client{user="hello"} 4431121604 (4.13 GB)
telemt_user_msgs_from_client{user="hello"} 162712
telemt_user_msgs_to_client{user="hello"} 1044608
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 20061.5 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10449
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 9684
telemt_upstream_connect_success_total 9649
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 9684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9647
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 142191966 (135.60 MB)
telemt_user_octets_to_client{user="hello"} 3233427674 (3.01 GB)
telemt_user_msgs_from_client{user="hello"} 171939
telemt_user_msgs_to_client{user="hello"} 838190
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 20062.8 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14824
telemt_connections_bad_total 5165
telemt_handshake_timeouts_total 550
telemt_upstream_connect_attempt_total 8848
telemt_upstream_connect_success_total 8848
telemt_upstream_connect_attempts_per_request{bucket="1"} 8848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8846
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 225396578 (214.95 MB)
telemt_user_octets_to_client{user="hello"} 20810195770 (19.38 GB)
telemt_user_msgs_from_client{user="hello"} 368442
telemt_user_msgs_to_client{user="hello"} 3735204
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```