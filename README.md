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

# Server Metrics 2026-03-09 05:50:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 23459.8 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22653
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 559
telemt_upstream_connect_attempt_total 20706
telemt_upstream_connect_success_total 20699
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 20706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20697
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 192498494 (183.58 MB)
telemt_user_octets_to_client{user="hello"} 11523714102 (10.73 GB)
telemt_user_msgs_from_client{user="hello"} 382714
telemt_user_msgs_to_client{user="hello"} 567239
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 23457.9 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2947
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 2763
telemt_upstream_connect_success_total 2763
telemt_upstream_connect_attempts_per_request{bucket="1"} 2763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2759
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 45124385 (43.03 MB)
telemt_user_octets_to_client{user="hello"} 2861771907 (2.67 GB)
telemt_user_msgs_from_client{user="hello"} 97713
telemt_user_msgs_to_client{user="hello"} 541262
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 23458.4 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1659
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1546
telemt_upstream_connect_success_total 1546
telemt_upstream_connect_attempts_per_request{bucket="1"} 1546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1542
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 907110367 (865.09 MB)
telemt_user_octets_to_client{user="hello"} 1112495951 (1.04 GB)
telemt_user_msgs_from_client{user="hello"} 347610
telemt_user_msgs_to_client{user="hello"} 219820
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 23453.2 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3344
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 2792
telemt_upstream_connect_success_total 2792
telemt_upstream_connect_attempts_per_request{bucket="1"} 2792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2788
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 122747978 (117.06 MB)
telemt_user_octets_to_client{user="hello"} 1997010320 (1.86 GB)
telemt_user_msgs_from_client{user="hello"} 64616
telemt_user_msgs_to_client{user="hello"} 441461
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 23458.7 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7982
telemt_connections_bad_total 4704
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 3078
telemt_upstream_connect_success_total 3078
telemt_upstream_connect_attempts_per_request{bucket="1"} 3078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3076
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 31330810 (29.88 MB)
telemt_user_octets_to_client{user="hello"} 2556067184 (2.38 GB)
telemt_user_msgs_from_client{user="hello"} 61856
telemt_user_msgs_to_client{user="hello"} 321182
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```