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

# Server Metrics 2026-03-08 15:36:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 30462.7 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74714
telemt_connections_bad_total 5026
telemt_handshake_timeouts_total 1054
telemt_upstream_connect_attempt_total 65995
telemt_upstream_connect_success_total 65972
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 65995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65968
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1723248691 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 35313746413 (32.89 GB)
telemt_user_msgs_from_client{user="hello"} 1564734
telemt_user_msgs_to_client{user="hello"} 2096423
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 30461.8 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15755
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 15217
telemt_upstream_connect_success_total 15216
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15212
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 568555430 (542.22 MB)
telemt_user_octets_to_client{user="hello"} 13054976033 (12.16 GB)
telemt_user_msgs_from_client{user="hello"} 579091
telemt_user_msgs_to_client{user="hello"} 3426841
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 30461.4 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10071
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9443
telemt_upstream_connect_success_total 9367
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9363
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 216767697 (206.73 MB)
telemt_user_octets_to_client{user="hello"} 3188724993 (2.97 GB)
telemt_user_msgs_from_client{user="hello"} 159997
telemt_user_msgs_to_client{user="hello"} 548095
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 30461.3 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12986
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 12376
telemt_upstream_connect_success_total 12348
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 12376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12344
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 948519280 (904.58 MB)
telemt_user_octets_to_client{user="hello"} 4652944673 (4.33 GB)
telemt_user_msgs_from_client{user="hello"} 469185
telemt_user_msgs_to_client{user="hello"} 1048429
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 30461.7 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17383
telemt_connections_bad_total 5606
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 11392
telemt_upstream_connect_success_total 11388
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11384
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 233543305 (222.72 MB)
telemt_user_octets_to_client{user="hello"} 8423759361 (7.85 GB)
telemt_user_msgs_from_client{user="hello"} 283417
telemt_user_msgs_to_client{user="hello"} 1183113
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```