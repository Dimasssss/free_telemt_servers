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

# Server Metrics 2026-03-09 05:45:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 23153.7 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22281
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 559
telemt_upstream_connect_attempt_total 20343
telemt_upstream_connect_success_total 20337
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20335
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 189831547 (181.04 MB)
telemt_user_octets_to_client{user="hello"} 11355830348 (10.58 GB)
telemt_user_msgs_from_client{user="hello"} 375854
telemt_user_msgs_to_client{user="hello"} 555989
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 23151.9 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2916
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 2732
telemt_upstream_connect_success_total 2732
telemt_upstream_connect_attempts_per_request{bucket="1"} 2732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2728
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 44803617 (42.73 MB)
telemt_user_octets_to_client{user="hello"} 2835267491 (2.64 GB)
telemt_user_msgs_from_client{user="hello"} 96906
telemt_user_msgs_to_client{user="hello"} 535735
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 23152.5 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1606
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1500
telemt_upstream_connect_success_total 1500
telemt_upstream_connect_attempts_per_request{bucket="1"} 1500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1496
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 907037118 (865.02 MB)
telemt_user_octets_to_client{user="hello"} 1109742581 (1.03 GB)
telemt_user_msgs_from_client{user="hello"} 347393
telemt_user_msgs_to_client{user="hello"} 218802
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 23147.3 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3224
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 2680
telemt_upstream_connect_success_total 2680
telemt_upstream_connect_attempts_per_request{bucket="1"} 2680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2676
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 62101761 (59.22 MB)
telemt_user_octets_to_client{user="hello"} 1881338017 (1.75 GB)
telemt_user_msgs_from_client{user="hello"} 57409
telemt_user_msgs_to_client{user="hello"} 422862
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 23152.8 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7798
telemt_connections_bad_total 4649
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 2959
telemt_upstream_connect_success_total 2959
telemt_upstream_connect_attempts_per_request{bucket="1"} 2959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2957
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 30796471 (29.37 MB)
telemt_user_octets_to_client{user="hello"} 2536426973 (2.36 GB)
telemt_user_msgs_from_client{user="hello"} 60422
telemt_user_msgs_to_client{user="hello"} 315254
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```