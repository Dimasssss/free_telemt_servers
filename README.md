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

# Server Metrics 2026-03-09 05:20:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 21624.9 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20232
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 18337
telemt_upstream_connect_success_total 18332
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18330
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 172320481 (164.34 MB)
telemt_user_octets_to_client{user="hello"} 10082143944 (9.39 GB)
telemt_user_msgs_from_client{user="hello"} 333115
telemt_user_msgs_to_client{user="hello"} 492368
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 21623.0 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2637
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 2461
telemt_upstream_connect_success_total 2461
telemt_upstream_connect_attempts_per_request{bucket="1"} 2461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2459
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 39533234 (37.70 MB)
telemt_user_octets_to_client{user="hello"} 2170566803 (2.02 GB)
telemt_user_msgs_from_client{user="hello"} 83734
telemt_user_msgs_to_client{user="hello"} 421891
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 21623.6 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1505
telemt_connections_bad_total 88
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1401
telemt_upstream_connect_success_total 1401
telemt_upstream_connect_attempts_per_request{bucket="1"} 1401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1397
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 906402032 (864.41 MB)
telemt_user_octets_to_client{user="hello"} 1096832363 (1.02 GB)
telemt_user_msgs_from_client{user="hello"} 345541
telemt_user_msgs_to_client{user="hello"} 214208
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 21618.4 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2927
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 2403
telemt_upstream_connect_success_total 2403
telemt_upstream_connect_attempts_per_request{bucket="1"} 2403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2399
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 19812333 (18.89 MB)
telemt_user_octets_to_client{user="hello"} 1738364209 (1.62 GB)
telemt_user_msgs_from_client{user="hello"} 50477
telemt_user_msgs_to_client{user="hello"} 395918
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 21623.9 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7052
telemt_connections_bad_total 4375
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2492
telemt_upstream_connect_success_total 2492
telemt_upstream_connect_attempts_per_request{bucket="1"} 2492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2490
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 20264413 (19.33 MB)
telemt_user_octets_to_client{user="hello"} 2327656058 (2.17 GB)
telemt_user_msgs_from_client{user="hello"} 49706
telemt_user_msgs_to_client{user="hello"} 283059
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```