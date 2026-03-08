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

# Server Metrics 2026-03-08 20:39:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 48642.9 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109134
telemt_connections_bad_total 5128
telemt_handshake_timeouts_total 1276
telemt_upstream_connect_attempt_total 99295
telemt_upstream_connect_success_total 99259
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 99295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99253
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2321270316 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 61910603840 (57.66 GB)
telemt_user_msgs_from_client{user="hello"} 2396036
telemt_user_msgs_to_client{user="hello"} 3360622
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 48642.1 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25456
telemt_connections_bad_total 274
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 24614
telemt_upstream_connect_success_total 24607
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 24614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24601
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 826450995 (788.17 MB)
telemt_user_octets_to_client{user="hello"} 22094882377 (20.58 GB)
telemt_user_msgs_from_client{user="hello"} 951205
telemt_user_msgs_to_client{user="hello"} 6006622
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 48641.9 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14850
telemt_connections_bad_total 228
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13450
telemt_upstream_connect_success_total 13374
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13368
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 1413792215 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 5577993945 (5.19 GB)
telemt_user_msgs_from_client{user="hello"} 642916
telemt_user_msgs_to_client{user="hello"} 943756
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 48641.6 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19433
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 18604
telemt_upstream_connect_success_total 18566
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 18604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18562
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 1059879775 (1010.78 MB)
telemt_user_octets_to_client{user="hello"} 6388210411 (5.95 GB)
telemt_user_msgs_from_client{user="hello"} 563071
telemt_user_msgs_to_client{user="hello"} 1441338
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 48641.9 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28654
telemt_connections_bad_total 9281
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 18677
telemt_upstream_connect_success_total 18670
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18664
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 344703905 (328.74 MB)
telemt_user_octets_to_client{user="hello"} 15569045832 (14.50 GB)
telemt_user_msgs_from_client{user="hello"} 479343
telemt_user_msgs_to_client{user="hello"} 2045116
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```