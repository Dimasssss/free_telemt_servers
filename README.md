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

# Server Metrics 2026-03-04 23:12:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 42352.5 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65806
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 1552
telemt_upstream_connect_attempt_total 59286
telemt_upstream_connect_success_total 59271
telemt_upstream_connect_attempts_per_request{bucket="1"} 59256
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59267
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 2318927434 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 46553933710 (43.36 GB)
telemt_user_msgs_from_client{user="hello"} 1962680
telemt_user_msgs_to_client{user="hello"} 7406317
telemt_user_unique_ips_current{user="hello"} 13
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 42355.4 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12038
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 11328
telemt_upstream_connect_success_total 11326
telemt_upstream_connect_attempts_per_request{bucket="1"} 11324
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11322
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 1054887173 (1006.02 MB)
telemt_user_octets_to_client{user="hello"} 11039487715 (10.28 GB)
telemt_user_msgs_from_client{user="hello"} 646177
telemt_user_msgs_to_client{user="hello"} 3722577
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 42353.4 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11145
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 7258
telemt_upstream_connect_success_total 7258
telemt_upstream_connect_attempts_per_request{bucket="1"} 7258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7254
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 307831438 (293.57 MB)
telemt_user_octets_to_client{user="hello"} 5243785913 (4.88 GB)
telemt_user_msgs_from_client{user="hello"} 267857
telemt_user_msgs_to_client{user="hello"} 1128621
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 42351.4 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14528
telemt_connections_bad_total 637
telemt_handshake_timeouts_total 67
telemt_upstream_connect_attempt_total 12717
telemt_upstream_connect_success_total 12712
telemt_upstream_connect_attempts_per_request{bucket="1"} 12707
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12708
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 387361112 (369.42 MB)
telemt_user_octets_to_client{user="hello"} 5488744822 (5.11 GB)
telemt_user_msgs_from_client{user="hello"} 298666
telemt_user_msgs_to_client{user="hello"} 1369453
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 42353.1 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16959
telemt_connections_bad_total 7613
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9007
telemt_upstream_connect_success_total 9003
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9001
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8997
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 508831227 (485.26 MB)
telemt_user_octets_to_client{user="hello"} 20547856776 (19.14 GB)
telemt_user_msgs_from_client{user="hello"} 535954
telemt_user_msgs_to_client{user="hello"} 3896393
telemt_user_unique_ips_current{user="hello"} 2
```