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

# Server Metrics 2026-03-07 07:25:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 1058.5 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1354
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1299
telemt_upstream_connect_success_total 1299
telemt_upstream_connect_attempts_per_request{bucket="1"} 1299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1297
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 19242098 (18.35 MB)
telemt_user_octets_to_client{user="hello"} 1873529437 (1.74 GB)
telemt_user_msgs_from_client{user="hello"} 34593
telemt_user_msgs_to_client{user="hello"} 414193
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 1057.9 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 356
telemt_upstream_connect_success_total 355
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 353
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 1631420 (1.56 MB)
telemt_user_octets_to_client{user="hello"} 83340007 (79.48 MB)
telemt_user_msgs_from_client{user="hello"} 4443
telemt_user_msgs_to_client{user="hello"} 28548
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 1057.2 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 324
telemt_upstream_connect_success_total 324
telemt_upstream_connect_attempts_per_request{bucket="1"} 324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 322
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 9364117 (8.93 MB)
telemt_user_octets_to_client{user="hello"} 105899468 (100.99 MB)
telemt_user_msgs_from_client{user="hello"} 5501
telemt_user_msgs_to_client{user="hello"} 25536
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 1057.5 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 464
telemt_upstream_connect_success_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 462
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 4523131 (4.31 MB)
telemt_user_octets_to_client{user="hello"} 110871850 (105.74 MB)
telemt_user_msgs_from_client{user="hello"} 7535
telemt_user_msgs_to_client{user="hello"} 31153
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 1057.9 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 610
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 412
telemt_upstream_connect_success_total 412
telemt_upstream_connect_attempts_per_request{bucket="1"} 412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 410
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 3724491 (3.55 MB)
telemt_user_octets_to_client{user="hello"} 1121209715 (1.04 GB)
telemt_user_msgs_from_client{user="hello"} 9144
telemt_user_msgs_to_client{user="hello"} 204421
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```