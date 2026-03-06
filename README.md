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

# Server Metrics 2026-03-06 23:53:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 20744.0 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29277
telemt_connections_bad_total 135
telemt_handshake_timeouts_total 477
telemt_upstream_connect_attempt_total 27355
telemt_upstream_connect_success_total 27347
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 27354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27343
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 2053417756 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 30880712389 (28.76 GB)
telemt_user_msgs_from_client{user="hello"} 1313666
telemt_user_msgs_to_client{user="hello"} 4853960
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 20742.4 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6628
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 6214
telemt_upstream_connect_success_total 6211
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6209
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 214995408 (205.04 MB)
telemt_user_octets_to_client{user="hello"} 3893593702 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 200912
telemt_user_msgs_to_client{user="hello"} 1087866
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 20742.4 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3025
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2773
telemt_upstream_connect_success_total 2773
telemt_upstream_connect_attempts_per_request{bucket="1"} 2773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 218
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2771
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 64726705 (61.73 MB)
telemt_user_octets_to_client{user="hello"} 1853312972 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 63091
telemt_user_msgs_to_client{user="hello"} 389791
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 20742.5 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4068
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 3931
telemt_upstream_connect_success_total 3924
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 3931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3920
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 99413399 (94.81 MB)
telemt_user_octets_to_client{user="hello"} 1320261612 (1.23 GB)
telemt_user_msgs_from_client{user="hello"} 82653
telemt_user_msgs_to_client{user="hello"} 335148
telemt_user_unique_ips_current{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 20742.8 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11133
telemt_connections_bad_total 4664
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6329
telemt_upstream_connect_success_total 6328
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6326
telemt_user_octets_from_client{user="hello"} 226697665 (216.20 MB)
telemt_user_octets_to_client{user="hello"} 7324334294 (6.82 GB)
telemt_user_msgs_from_client{user="hello"} 211675
telemt_user_msgs_to_client{user="hello"} 1507002
telemt_user_unique_ips_recent_window{user="hello"} 1
```