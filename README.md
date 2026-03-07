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

# Server Metrics 2026-03-07 22:23:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 20325.0 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31741
telemt_connections_bad_total 222
telemt_handshake_timeouts_total 183
telemt_upstream_connect_attempt_total 30521
telemt_upstream_connect_success_total 30517
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30515
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 2114350881 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 22195793165 (20.67 GB)
telemt_user_msgs_from_client{user="hello"} 1119671
telemt_user_msgs_to_client{user="hello"} 3437581
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 20324.3 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5973
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 5691
telemt_upstream_connect_success_total 5684
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5680
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 96963103 (92.47 MB)
telemt_user_octets_to_client{user="hello"} 3841399782 (3.58 GB)
telemt_user_msgs_from_client{user="hello"} 153141
telemt_user_msgs_to_client{user="hello"} 1080872
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 20324.0 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3589
telemt_connections_bad_total 115
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3413
telemt_upstream_connect_success_total 3413
telemt_upstream_connect_attempts_per_request{bucket="1"} 3413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3411
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 96300848 (91.84 MB)
telemt_user_octets_to_client{user="hello"} 8314168972 (7.74 GB)
telemt_user_msgs_from_client{user="hello"} 149176
telemt_user_msgs_to_client{user="hello"} 1667918
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 20152.3 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9453
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9098
telemt_upstream_connect_success_total 9075
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 9098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9073
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 169905717 (162.03 MB)
telemt_user_octets_to_client{user="hello"} 9350190351 (8.71 GB)
telemt_user_msgs_from_client{user="hello"} 243617
telemt_user_msgs_to_client{user="hello"} 2755091
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 20324.7 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10256
telemt_connections_bad_total 3778
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 6286
telemt_upstream_connect_success_total 6278
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 6286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6276
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 1583853352 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 4025188791 (3.75 GB)
telemt_user_msgs_from_client{user="hello"} 708101
telemt_user_msgs_to_client{user="hello"} 939643
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```