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

# Server Metrics 2026-03-06 05:09:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 24860.3 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76504
telemt_connections_bad_total 51936
telemt_handshake_timeouts_total 2443
telemt_upstream_connect_attempt_total 20608
telemt_upstream_connect_success_total 20605
telemt_upstream_connect_attempts_per_request{bucket="1"} 20602
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20601
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 267569898 (255.17 MB)
telemt_user_octets_to_client{user="hello"} 18011060953 (16.77 GB)
telemt_user_msgs_from_client{user="hello"} 498880
telemt_user_msgs_to_client{user="hello"} 2696984
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 24858.2 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2710
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 2520
telemt_upstream_connect_success_total 2519
telemt_upstream_connect_attempts_per_request{bucket="1"} 2518
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 97
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2517
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 57069215 (54.43 MB)
telemt_user_octets_to_client{user="hello"} 1184921346 (1.10 GB)
telemt_user_msgs_from_client{user="hello"} 79272
telemt_user_msgs_to_client{user="hello"} 376334
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 24858.5 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1609
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1380
telemt_upstream_connect_success_total 1380
telemt_upstream_connect_attempts_per_request{bucket="1"} 1380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1376
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 37929966 (36.17 MB)
telemt_user_octets_to_client{user="hello"} 1811004456 (1.69 GB)
telemt_user_msgs_from_client{user="hello"} 49538
telemt_user_msgs_to_client{user="hello"} 365943
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 24861.4 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3323
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 305
telemt_upstream_connect_attempt_total 2789
telemt_upstream_connect_success_total 2789
telemt_upstream_connect_attempts_per_request{bucket="1"} 2789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2785
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 96574228 (92.10 MB)
telemt_user_octets_to_client{user="hello"} 5705790890 (5.31 GB)
telemt_user_msgs_from_client{user="hello"} 137311
telemt_user_msgs_to_client{user="hello"} 1203456
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 24861.1 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8428
telemt_connections_bad_total 4518
telemt_handshake_timeouts_total 154
telemt_upstream_connect_attempt_total 3653
telemt_upstream_connect_success_total 3653
telemt_upstream_connect_attempts_per_request{bucket="1"} 3653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3649
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 77359833 (73.78 MB)
telemt_user_octets_to_client{user="hello"} 15890804179 (14.80 GB)
telemt_user_msgs_from_client{user="hello"} 197923
telemt_user_msgs_to_client{user="hello"} 3027602
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```