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

# Server Metrics 2026-03-06 19:52:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 6270.0 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11281
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 365
telemt_upstream_connect_attempt_total 10147
telemt_upstream_connect_success_total 10143
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10141
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 951249727 (907.18 MB)
telemt_user_octets_to_client{user="hello"} 13187190577 (12.28 GB)
telemt_user_msgs_from_client{user="hello"} 599968
telemt_user_msgs_to_client{user="hello"} 2091235
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 6268.8 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2919
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 2730
telemt_upstream_connect_success_total 2727
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2725
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 64819725 (61.82 MB)
telemt_user_octets_to_client{user="hello"} 2039474191 (1.90 GB)
telemt_user_msgs_from_client{user="hello"} 71306
telemt_user_msgs_to_client{user="hello"} 574205
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 6269.0 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1673
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 1563
telemt_upstream_connect_success_total 1563
telemt_upstream_connect_attempts_per_request{bucket="1"} 1563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1561
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 17060846 (16.27 MB)
telemt_user_octets_to_client{user="hello"} 663629099 (632.89 MB)
telemt_user_msgs_from_client{user="hello"} 27014
telemt_user_msgs_to_client{user="hello"} 157558
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 6269.1 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1442
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1402
telemt_upstream_connect_success_total 1398
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1396
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 36834046 (35.13 MB)
telemt_user_octets_to_client{user="hello"} 527490628 (503.05 MB)
telemt_user_msgs_from_client{user="hello"} 32942
telemt_user_msgs_to_client{user="hello"} 139566
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 6269.3 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4830
telemt_connections_bad_total 1153
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3645
telemt_upstream_connect_success_total 3645
telemt_upstream_connect_attempts_per_request{bucket="1"} 3645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3643
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 137902431 (131.51 MB)
telemt_user_octets_to_client{user="hello"} 2356731277 (2.19 GB)
telemt_user_msgs_from_client{user="hello"} 111049
telemt_user_msgs_to_client{user="hello"} 535968
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 6
```