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

# Server Metrics 2026-03-09 03:53:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 16425.5 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13657
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 203
telemt_upstream_connect_attempt_total 12341
telemt_upstream_connect_success_total 12338
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 12341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12336
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 127305678 (121.41 MB)
telemt_user_octets_to_client{user="hello"} 8905839380 (8.29 GB)
telemt_user_msgs_from_client{user="hello"} 254361
telemt_user_msgs_to_client{user="hello"} 391654
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 16423.8 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1409
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 1290
telemt_upstream_connect_success_total 1290
telemt_upstream_connect_attempts_per_request{bucket="1"} 1290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1288
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 26335366 (25.12 MB)
telemt_user_octets_to_client{user="hello"} 1270073638 (1.18 GB)
telemt_user_msgs_from_client{user="hello"} 52088
telemt_user_msgs_to_client{user="hello"} 239299
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 16424.3 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1087
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 990
telemt_upstream_connect_success_total 990
telemt_upstream_connect_attempts_per_request{bucket="1"} 990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 988
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 384298018 (366.50 MB)
telemt_user_octets_to_client{user="hello"} 926006903 (883.11 MB)
telemt_user_msgs_from_client{user="hello"} 156548
telemt_user_msgs_to_client{user="hello"} 176925
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 16419.1 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2108
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 221
telemt_upstream_connect_attempt_total 1719
telemt_upstream_connect_success_total 1719
telemt_upstream_connect_attempts_per_request{bucket="1"} 1719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1717
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 14423664 (13.76 MB)
telemt_user_octets_to_client{user="hello"} 1180245625 (1.10 GB)
telemt_user_msgs_from_client{user="hello"} 37399
telemt_user_msgs_to_client{user="hello"} 291103
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 16424.7 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4409
telemt_connections_bad_total 2993
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1384
telemt_upstream_connect_success_total 1384
telemt_upstream_connect_attempts_per_request{bucket="1"} 1384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 172
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1382
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 9989063 (9.53 MB)
telemt_user_octets_to_client{user="hello"} 1594529188 (1.49 GB)
telemt_user_msgs_from_client{user="hello"} 26163
telemt_user_msgs_to_client{user="hello"} 193673
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```