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

# Server Metrics 2026-03-08 08:14:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 3932.0 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6645
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 6428
telemt_upstream_connect_success_total 6424
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 6428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6422
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 96340099 (91.88 MB)
telemt_user_octets_to_client{user="hello"} 2499215993 (2.33 GB)
telemt_user_msgs_from_client{user="hello"} 134283
telemt_user_msgs_to_client{user="hello"} 171587
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 3931.4 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1727
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1669
telemt_upstream_connect_success_total 1669
telemt_upstream_connect_attempts_per_request{bucket="1"} 1669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1667
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 19856876 (18.94 MB)
telemt_user_octets_to_client{user="hello"} 937424431 (894.00 MB)
telemt_user_msgs_from_client{user="hello"} 36075
telemt_user_msgs_to_client{user="hello"} 228685
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 3930.7 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1388
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1351
telemt_upstream_connect_success_total 1351
telemt_upstream_connect_attempts_per_request{bucket="1"} 1351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1349
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 20871214 (19.90 MB)
telemt_user_octets_to_client{user="hello"} 347714070 (331.61 MB)
telemt_user_msgs_from_client{user="hello"} 13113
telemt_user_msgs_to_client{user="hello"} 57657
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 3930.7 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1484
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 1426
telemt_upstream_connect_success_total 1423
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 90
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1421
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 37796709 (36.05 MB)
telemt_user_octets_to_client{user="hello"} 405475189 (386.69 MB)
telemt_user_msgs_from_client{user="hello"} 22993
telemt_user_msgs_to_client{user="hello"} 109884
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 3931.0 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2607
telemt_connections_bad_total 703
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1878
telemt_upstream_connect_success_total 1878
telemt_upstream_connect_attempts_per_request{bucket="1"} 1878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1876
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 18784347 (17.91 MB)
telemt_user_octets_to_client{user="hello"} 515482788 (491.60 MB)
telemt_user_msgs_from_client{user="hello"} 28530
telemt_user_msgs_to_client{user="hello"} 94027
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```