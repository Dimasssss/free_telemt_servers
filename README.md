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

# Server Metrics 2026-03-05 22:09:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.0

telemt_uptime_seconds 17627.1 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123223
telemt_connections_bad_total 100613
telemt_handshake_timeouts_total 5649
telemt_upstream_connect_attempt_total 16383
telemt_upstream_connect_success_total 16380
telemt_upstream_connect_attempts_per_request{bucket="1"} 16377
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16378
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 328661066 (313.44 MB)
telemt_user_octets_to_client{user="hello"} 11993116956 (11.17 GB)
telemt_user_msgs_from_client{user="hello"} 512627
telemt_user_msgs_to_client{user="hello"} 2198702
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.0

telemt_uptime_seconds 17630.0 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4590
telemt_connections_bad_total 519
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3909
telemt_upstream_connect_success_total 3909
telemt_upstream_connect_attempts_per_request{bucket="1"} 3909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3907
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 220837826 (210.61 MB)
telemt_user_octets_to_client{user="hello"} 7357224337 (6.85 GB)
telemt_user_msgs_from_client{user="hello"} 200975
telemt_user_msgs_to_client{user="hello"} 2206525
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.0

telemt_uptime_seconds 17627.9 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4904
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 78
telemt_upstream_connect_attempt_total 4533
telemt_upstream_connect_success_total 4533
telemt_upstream_connect_attempts_per_request{bucket="1"} 4533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4531
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 54034122 (51.53 MB)
telemt_user_octets_to_client{user="hello"} 5457066925 (5.08 GB)
telemt_user_msgs_from_client{user="hello"} 116138
telemt_user_msgs_to_client{user="hello"} 1076632
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.0

telemt_uptime_seconds 17625.4 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8570
telemt_connections_bad_total 95
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 8101
telemt_upstream_connect_success_total 8095
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8091
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8091
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 123877386 (118.14 MB)
telemt_user_octets_to_client{user="hello"} 4531767126 (4.22 GB)
telemt_user_msgs_from_client{user="hello"} 173993
telemt_user_msgs_to_client{user="hello"} 990027
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.0

telemt_uptime_seconds 17627.4 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8538
telemt_connections_bad_total 3331
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 5049
telemt_upstream_connect_success_total 5048
telemt_upstream_connect_attempts_per_request{bucket="1"} 5047
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5046
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 86913331 (82.89 MB)
telemt_user_octets_to_client{user="hello"} 3258983557 (3.04 GB)
telemt_user_msgs_from_client{user="hello"} 158818
telemt_user_msgs_to_client{user="hello"} 702508
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```