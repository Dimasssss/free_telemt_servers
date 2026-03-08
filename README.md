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

# Server Metrics 2026-03-08 22:01:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 53584.0 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115060
telemt_connections_bad_total 5496
telemt_handshake_timeouts_total 1282
telemt_upstream_connect_attempt_total 104481
telemt_upstream_connect_success_total 104443
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 104481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104437
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 2561244288 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 68965894548 (64.23 GB)
telemt_user_msgs_from_client{user="hello"} 2605706
telemt_user_msgs_to_client{user="hello"} 3591950
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 53583.2 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27158
telemt_connections_bad_total 292
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 26263
telemt_upstream_connect_success_total 26256
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26250
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 839112877 (800.24 MB)
telemt_user_octets_to_client{user="hello"} 22731036250 (21.17 GB)
telemt_user_msgs_from_client{user="hello"} 979069
telemt_user_msgs_to_client{user="hello"} 6162035
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 53582.9 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15443
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 14033
telemt_upstream_connect_success_total 13957
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13951
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 1554542816 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 5690559186 (5.30 GB)
telemt_user_msgs_from_client{user="hello"} 697514
telemt_user_msgs_to_client{user="hello"} 976389
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 53582.9 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21092
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 20235
telemt_upstream_connect_success_total 20195
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 20235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1515
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20189
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 1067582953 (1018.13 MB)
telemt_user_octets_to_client{user="hello"} 6575621070 (6.12 GB)
telemt_user_msgs_from_client{user="hello"} 575216
telemt_user_msgs_to_client{user="hello"} 1494127
telemt_user_unique_ips_current{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 53583.1 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31109
telemt_connections_bad_total 10173
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 20197
telemt_upstream_connect_success_total 20190
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 20197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20184
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 374218440 (356.88 MB)
telemt_user_octets_to_client{user="hello"} 17477046246 (16.28 GB)
telemt_user_msgs_from_client{user="hello"} 535810
telemt_user_msgs_to_client{user="hello"} 2268615
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```