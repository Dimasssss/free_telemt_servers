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

# Server Metrics 2026-03-10 18:30:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14632.9 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58280
telemt_connections_bad_total 1664
telemt_handshake_timeouts_total 1456
telemt_upstream_connect_attempt_total 52299
telemt_upstream_connect_success_total 52287
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 52299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52285
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 1484055128 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 40143125150 (37.39 GB)
telemt_user_msgs_from_client{user="hello"} 1463496
telemt_user_msgs_to_client{user="hello"} 2991153
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 14632.3 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21354
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 363
telemt_upstream_connect_attempt_total 19583
telemt_upstream_connect_success_total 19575
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19573
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 559979791 (534.04 MB)
telemt_user_octets_to_client{user="hello"} 9862188950 (9.18 GB)
telemt_user_msgs_from_client{user="hello"} 565705
telemt_user_msgs_to_client{user="hello"} 3133394
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 14631.9 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32587
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 2780
telemt_upstream_connect_attempt_total 27632
telemt_upstream_connect_success_total 27632
telemt_upstream_connect_attempts_per_request{bucket="1"} 27632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27630
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 354851092 (338.41 MB)
telemt_user_octets_to_client{user="hello"} 29236377004 (27.23 GB)
telemt_user_msgs_from_client{user="hello"} 588061
telemt_user_msgs_to_client{user="hello"} 4362372
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 14630.9 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31606
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 30232
telemt_upstream_connect_success_total 30143
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 30232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3479
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30141
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 404418602 (385.68 MB)
telemt_user_octets_to_client{user="hello"} 26716098021 (24.88 GB)
telemt_user_msgs_from_client{user="hello"} 601263
telemt_user_msgs_to_client{user="hello"} 4704892
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14632.2 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45565
telemt_connections_bad_total 4231
telemt_handshake_timeouts_total 1029
telemt_upstream_connect_attempt_total 38599
telemt_upstream_connect_success_total 38361
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 38599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38359
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1385002261 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 23712977700 (22.08 GB)
telemt_user_msgs_from_client{user="hello"} 1106795
telemt_user_msgs_to_client{user="hello"} 3581996
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 23
```