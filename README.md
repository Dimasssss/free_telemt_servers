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

# Server Metrics 2026-03-06 15:05:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 16984.1 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40992
telemt_connections_bad_total 3086
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 34413
telemt_upstream_connect_success_total 34404
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 34413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34402
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 1974904196 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 22587827789 (21.04 GB)
telemt_user_msgs_from_client{user="hello"} 1288918
telemt_user_msgs_to_client{user="hello"} 3564924
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 16983.1 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7418
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 89
telemt_upstream_connect_attempt_total 6965
telemt_upstream_connect_success_total 6963
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6961
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 74673590 (71.21 MB)
telemt_user_octets_to_client{user="hello"} 3242699919 (3.02 GB)
telemt_user_msgs_from_client{user="hello"} 141452
telemt_user_msgs_to_client{user="hello"} 1019898
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 16982.3 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6525
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 6322
telemt_upstream_connect_success_total 6322
telemt_upstream_connect_attempts_per_request{bucket="1"} 6322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6320
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 94869707 (90.47 MB)
telemt_user_octets_to_client{user="hello"} 4082388173 (3.80 GB)
telemt_user_msgs_from_client{user="hello"} 141609
telemt_user_msgs_to_client{user="hello"} 953475
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 16981.6 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9186
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 8543
telemt_upstream_connect_success_total 8517
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 8543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8515
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 133423397 (127.24 MB)
telemt_user_octets_to_client{user="hello"} 2892180692 (2.69 GB)
telemt_user_msgs_from_client{user="hello"} 154081
telemt_user_msgs_to_client{user="hello"} 745945
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 16983.0 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12778
telemt_connections_bad_total 4576
telemt_handshake_timeouts_total 534
telemt_upstream_connect_attempt_total 7467
telemt_upstream_connect_success_total 7467
telemt_upstream_connect_attempts_per_request{bucket="1"} 7467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7465
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 205029076 (195.53 MB)
telemt_user_octets_to_client{user="hello"} 19141750406 (17.83 GB)
telemt_user_msgs_from_client{user="hello"} 325516
telemt_user_msgs_to_client{user="hello"} 3413876
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```