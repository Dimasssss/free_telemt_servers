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

# Server Metrics 2026-03-09 05:35:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 22542.2 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21546
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 19629
telemt_upstream_connect_success_total 19624
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 19629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19622
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 183097675 (174.62 MB)
telemt_user_octets_to_client{user="hello"} 10988839056 (10.23 GB)
telemt_user_msgs_from_client{user="hello"} 358827
telemt_user_msgs_to_client{user="hello"} 531712
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 22540.7 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2830
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 2646
telemt_upstream_connect_success_total 2646
telemt_upstream_connect_attempts_per_request{bucket="1"} 2646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 197
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2642
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 43236346 (41.23 MB)
telemt_user_octets_to_client{user="hello"} 2706126351 (2.52 GB)
telemt_user_msgs_from_client{user="hello"} 93620
telemt_user_msgs_to_client{user="hello"} 513882
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 22541.1 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1559
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1453
telemt_upstream_connect_success_total 1453
telemt_upstream_connect_attempts_per_request{bucket="1"} 1453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1449
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 906801634 (864.79 MB)
telemt_user_octets_to_client{user="hello"} 1105133255 (1.03 GB)
telemt_user_msgs_from_client{user="hello"} 346683
telemt_user_msgs_to_client{user="hello"} 216970
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 22535.9 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3051
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 2519
telemt_upstream_connect_success_total 2519
telemt_upstream_connect_attempts_per_request{bucket="1"} 2519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2515
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 20466028 (19.52 MB)
telemt_user_octets_to_client{user="hello"} 1790739591 (1.67 GB)
telemt_user_msgs_from_client{user="hello"} 52193
telemt_user_msgs_to_client{user="hello"} 409869
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 22541.4 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7457
telemt_connections_bad_total 4540
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2730
telemt_upstream_connect_success_total 2730
telemt_upstream_connect_attempts_per_request{bucket="1"} 2730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2728
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 21592669 (20.59 MB)
telemt_user_octets_to_client{user="hello"} 2394791524 (2.23 GB)
telemt_user_msgs_from_client{user="hello"} 53231
telemt_user_msgs_to_client{user="hello"} 295585
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```