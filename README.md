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

# Server Metrics 2026-03-08 03:52:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 40039.1 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56736
telemt_connections_bad_total 5991
telemt_handshake_timeouts_total 406
telemt_upstream_connect_attempt_total 47958
telemt_upstream_connect_success_total 47951
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 47958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47947
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 2368723109 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 32658837178 (30.42 GB)
telemt_user_msgs_from_client{user="hello"} 1514688
telemt_user_msgs_to_client{user="hello"} 5100855
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 40038.3 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7919
telemt_connections_bad_total 363
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 7422
telemt_upstream_connect_success_total 7414
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7408
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 180139706 (171.79 MB)
telemt_user_octets_to_client{user="hello"} 10720932134 (9.98 GB)
telemt_user_msgs_from_client{user="hello"} 339611
telemt_user_msgs_to_client{user="hello"} 2503795
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 40038.1 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4859
telemt_connections_bad_total 250
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 4523
telemt_upstream_connect_success_total 4523
telemt_upstream_connect_attempts_per_request{bucket="1"} 4523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4519
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 122944200 (117.25 MB)
telemt_user_octets_to_client{user="hello"} 14236798743 (13.26 GB)
telemt_user_msgs_from_client{user="hello"} 222658
telemt_user_msgs_to_client{user="hello"} 3009033
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 39866.4 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13434
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 12884
telemt_upstream_connect_success_total 12858
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 12884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2037
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12854
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 347809541 (331.70 MB)
telemt_user_octets_to_client{user="hello"} 11365251052 (10.58 GB)
telemt_user_msgs_from_client{user="hello"} 371024
telemt_user_msgs_to_client{user="hello"} 3297268
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 40038.3 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15843
telemt_connections_bad_total 7358
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 8239
telemt_upstream_connect_success_total 8231
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 8239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8227
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1621473755 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 7769059713 (7.24 GB)
telemt_user_msgs_from_client{user="hello"} 806989
telemt_user_msgs_to_client{user="hello"} 1744878
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```