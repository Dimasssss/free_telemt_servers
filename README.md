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

# Server Metrics 2026-03-10 18:19:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14019.7 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56073
telemt_connections_bad_total 1539
telemt_handshake_timeouts_total 1442
telemt_upstream_connect_attempt_total 50295
telemt_upstream_connect_success_total 50284
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 50295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50282
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 1454802817 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 38079480296 (35.46 GB)
telemt_user_msgs_from_client{user="hello"} 1407336
telemt_user_msgs_to_client{user="hello"} 2838468
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 14019.2 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20401
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 348
telemt_upstream_connect_attempt_total 18678
telemt_upstream_connect_success_total 18670
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 18676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18668
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 552152382 (526.57 MB)
telemt_user_octets_to_client{user="hello"} 9621846064 (8.96 GB)
telemt_user_msgs_from_client{user="hello"} 546593
telemt_user_msgs_to_client{user="hello"} 3038414
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 14018.8 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31303
telemt_connections_bad_total 90
telemt_handshake_timeouts_total 2728
telemt_upstream_connect_attempt_total 26570
telemt_upstream_connect_success_total 26570
telemt_upstream_connect_attempts_per_request{bucket="1"} 26570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26568
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 345783308 (329.76 MB)
telemt_user_octets_to_client{user="hello"} 26273152383 (24.47 GB)
telemt_user_msgs_from_client{user="hello"} 563100
telemt_user_msgs_to_client{user="hello"} 4023747
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 14017.8 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30641
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 29289
telemt_upstream_connect_success_total 29201
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 29289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29199
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 391836202 (373.68 MB)
telemt_user_octets_to_client{user="hello"} 26558977389 (24.73 GB)
telemt_user_msgs_from_client{user="hello"} 586323
telemt_user_msgs_to_client{user="hello"} 4650386
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14019.0 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43577
telemt_connections_bad_total 4049
telemt_handshake_timeouts_total 919
telemt_upstream_connect_attempt_total 36954
telemt_upstream_connect_success_total 36717
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 36954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36715
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 1361785007 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 23141160967 (21.55 GB)
telemt_user_msgs_from_client{user="hello"} 1072782
telemt_user_msgs_to_client{user="hello"} 3484081
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 25
```