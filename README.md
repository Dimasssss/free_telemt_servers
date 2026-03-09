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

# Server Metrics 2026-03-09 03:58:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 16730.8 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13821
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 203
telemt_upstream_connect_attempt_total 12502
telemt_upstream_connect_success_total 12499
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 12502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12497
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 128018659 (122.09 MB)
telemt_user_octets_to_client{user="hello"} 8918684481 (8.31 GB)
telemt_user_msgs_from_client{user="hello"} 256315
telemt_user_msgs_to_client{user="hello"} 393610
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 16729.2 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1470
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 1352
telemt_upstream_connect_success_total 1352
telemt_upstream_connect_attempts_per_request{bucket="1"} 1352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1350
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 26954915 (25.71 MB)
telemt_user_octets_to_client{user="hello"} 1283589852 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 53613
telemt_user_msgs_to_client{user="hello"} 243055
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 16729.8 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1097
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 999
telemt_upstream_connect_success_total 999
telemt_upstream_connect_attempts_per_request{bucket="1"} 999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 997
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 384321619 (366.52 MB)
telemt_user_octets_to_client{user="hello"} 927180252 (884.23 MB)
telemt_user_msgs_from_client{user="hello"} 156620
telemt_user_msgs_to_client{user="hello"} 177295
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 16724.5 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2164
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 235
telemt_upstream_connect_attempt_total 1748
telemt_upstream_connect_success_total 1748
telemt_upstream_connect_attempts_per_request{bucket="1"} 1748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1746
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 14535887 (13.86 MB)
telemt_user_octets_to_client{user="hello"} 1192702411 (1.11 GB)
telemt_user_msgs_from_client{user="hello"} 37616
telemt_user_msgs_to_client{user="hello"} 293431
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 16730.2 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4493
telemt_connections_bad_total 3048
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1413
telemt_upstream_connect_success_total 1413
telemt_upstream_connect_attempts_per_request{bucket="1"} 1413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 174
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1411
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 10073234 (9.61 MB)
telemt_user_octets_to_client{user="hello"} 1600121504 (1.49 GB)
telemt_user_msgs_from_client{user="hello"} 26388
telemt_user_msgs_to_client{user="hello"} 194514
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```