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

# Server Metrics 2026-03-05 19:03:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.0

telemt_uptime_seconds 6523.8 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24782
telemt_connections_bad_total 16886
telemt_handshake_timeouts_total 80
telemt_upstream_connect_attempt_total 7453
telemt_upstream_connect_success_total 7452
telemt_upstream_connect_attempts_per_request{bucket="1"} 7451
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7450
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 161656372 (154.17 MB)
telemt_user_octets_to_client{user="hello"} 4028015908 (3.75 GB)
telemt_user_msgs_from_client{user="hello"} 232355
telemt_user_msgs_to_client{user="hello"} 704248
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.0

telemt_uptime_seconds 6526.3 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2455
telemt_connections_bad_total 458
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1862
telemt_upstream_connect_success_total 1862
telemt_upstream_connect_attempts_per_request{bucket="1"} 1862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1860
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 35146937 (33.52 MB)
telemt_user_octets_to_client{user="hello"} 1253789828 (1.17 GB)
telemt_user_msgs_from_client{user="hello"} 55447
telemt_user_msgs_to_client{user="hello"} 324438
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.0

telemt_uptime_seconds 6524.3 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2278
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 2037
telemt_upstream_connect_success_total 2037
telemt_upstream_connect_attempts_per_request{bucket="1"} 2037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2035
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 34308329 (32.72 MB)
telemt_user_octets_to_client{user="hello"} 2910374883 (2.71 GB)
telemt_user_msgs_from_client{user="hello"} 59131
telemt_user_msgs_to_client{user="hello"} 556338
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.0

telemt_uptime_seconds 6521.7 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2572
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2511
telemt_upstream_connect_success_total 2509
telemt_upstream_connect_attempts_per_request{bucket="1"} 2507
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2507
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 29871754 (28.49 MB)
telemt_user_octets_to_client{user="hello"} 1250845967 (1.16 GB)
telemt_user_msgs_from_client{user="hello"} 52753
telemt_user_msgs_to_client{user="hello"} 282026
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.0

telemt_uptime_seconds 6523.7 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3352
telemt_connections_bad_total 1236
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2048
telemt_upstream_connect_success_total 2048
telemt_upstream_connect_attempts_per_request{bucket="1"} 2048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2046
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 40038682 (38.18 MB)
telemt_user_octets_to_client{user="hello"} 1347924654 (1.26 GB)
telemt_user_msgs_from_client{user="hello"} 63764
telemt_user_msgs_to_client{user="hello"} 296260
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```