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

# Server Metrics 2026-03-09 03:17:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 14285.2 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11364
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 187
telemt_upstream_connect_attempt_total 10472
telemt_upstream_connect_success_total 10469
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 10472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10467
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 117559853 (112.11 MB)
telemt_user_octets_to_client{user="hello"} 8712449830 (8.11 GB)
telemt_user_msgs_from_client{user="hello"} 236396
telemt_user_msgs_to_client{user="hello"} 369304
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 14283.5 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 915
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 877
telemt_upstream_connect_success_total 877
telemt_upstream_connect_attempts_per_request{bucket="1"} 877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 875
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 10159481 (9.69 MB)
telemt_user_octets_to_client{user="hello"} 529667729 (505.13 MB)
telemt_user_msgs_from_client{user="hello"} 27634
telemt_user_msgs_to_client{user="hello"} 111421
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 14284.0 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 990
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 894
telemt_upstream_connect_success_total 894
telemt_upstream_connect_attempts_per_request{bucket="1"} 894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 892
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 319256218 (304.47 MB)
telemt_user_octets_to_client{user="hello"} 834209575 (795.56 MB)
telemt_user_msgs_from_client{user="hello"} 132439
telemt_user_msgs_to_client{user="hello"} 144177
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 14278.8 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1923
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 201
telemt_upstream_connect_attempt_total 1581
telemt_upstream_connect_success_total 1581
telemt_upstream_connect_attempts_per_request{bucket="1"} 1581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 400
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1579
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 13873809 (13.23 MB)
telemt_user_octets_to_client{user="hello"} 1073786028 (1.00 GB)
telemt_user_msgs_from_client{user="hello"} 35943
telemt_user_msgs_to_client{user="hello"} 267718
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 14284.4 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3861
telemt_connections_bad_total 2596
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1236
telemt_upstream_connect_success_total 1236
telemt_upstream_connect_attempts_per_request{bucket="1"} 1236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 158
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1234
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 9626544 (9.18 MB)
telemt_user_octets_to_client{user="hello"} 1587765981 (1.48 GB)
telemt_user_msgs_from_client{user="hello"} 25334
telemt_user_msgs_to_client{user="hello"} 191832
telemt_user_unique_ips_current{user="hello"} 5
```