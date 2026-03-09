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

# Server Metrics 2026-03-09 17:04:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 63908.0 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118514
telemt_connections_bad_total 1661
telemt_handshake_timeouts_total 988
telemt_upstream_connect_attempt_total 111042
telemt_upstream_connect_success_total 111002
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 111042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110996
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 2971211532 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 61055628795 (56.86 GB)
telemt_user_msgs_from_client{user="hello"} 2774629
telemt_user_msgs_to_client{user="hello"} 3918323
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 63906.9 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32164
telemt_connections_bad_total 223
telemt_handshake_timeouts_total 360
telemt_upstream_connect_attempt_total 30303
telemt_upstream_connect_success_total 30282
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 30300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30276
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 1010581135 (963.77 MB)
telemt_user_octets_to_client{user="hello"} 16161306427 (15.05 GB)
telemt_user_msgs_from_client{user="hello"} 865704
telemt_user_msgs_to_client{user="hello"} 4507032
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 63907.5 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41060
telemt_connections_bad_total 658
telemt_handshake_timeouts_total 1795
telemt_upstream_connect_attempt_total 31483
telemt_upstream_connect_success_total 31483
telemt_upstream_connect_attempts_per_request{bucket="1"} 31483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31477
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 4484382360 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 18748652951 (17.46 GB)
telemt_user_msgs_from_client{user="hello"} 2011403
telemt_user_msgs_to_client{user="hello"} 2526908
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 63902.2 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46628
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 888
telemt_upstream_connect_attempt_total 42650
telemt_upstream_connect_success_total 42547
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 42650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5965
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42539
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 1964706664 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 31779346956 (29.60 GB)
telemt_user_msgs_from_client{user="hello"} 1311304
telemt_user_msgs_to_client{user="hello"} 8033238
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 63907.7 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75581
telemt_connections_bad_total 15419
telemt_handshake_timeouts_total 1700
telemt_upstream_connect_attempt_total 55006
telemt_upstream_connect_success_total 55004
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 55006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54996
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 928080591 (885.09 MB)
telemt_user_octets_to_client{user="hello"} 56116338623 (52.26 GB)
telemt_user_msgs_from_client{user="hello"} 1268449
telemt_user_msgs_to_client{user="hello"} 6930868
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 18
```