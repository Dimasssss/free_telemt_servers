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

# Server Metrics 2026-03-04 09:19:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 3395.3 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5938
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 100
telemt_upstream_connect_attempt_total 5126
telemt_upstream_connect_success_total 5126
telemt_upstream_connect_attempts_per_request{bucket="1"} 5126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5124
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 66358276 (63.28 MB)
telemt_user_octets_to_client{user="hello"} 2496671842 (2.33 GB)
telemt_user_msgs_from_client{user="hello"} 102942
telemt_user_msgs_to_client{user="hello"} 429983
telemt_user_unique_ips_current{user="hello"} 5
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 3406.7 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 487
telemt_upstream_connect_success_total 487
telemt_upstream_connect_attempts_per_request{bucket="1"} 487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 485
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 11885328 (11.33 MB)
telemt_user_octets_to_client{user="hello"} 186971129 (178.31 MB)
telemt_user_msgs_from_client{user="hello"} 15155
telemt_user_msgs_to_client{user="hello"} 60289
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 3391.3 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517
telemt_connections_bad_total 56
telemt_upstream_connect_attempt_total 446
telemt_upstream_connect_success_total 446
telemt_upstream_connect_attempts_per_request{bucket="1"} 446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 444
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 5478168 (5.22 MB)
telemt_user_octets_to_client{user="hello"} 781967267 (745.74 MB)
telemt_user_msgs_from_client{user="hello"} 15186
telemt_user_msgs_to_client{user="hello"} 132830
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 3381.8 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1009
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 911
telemt_upstream_connect_success_total 911
telemt_upstream_connect_attempts_per_request{bucket="1"} 911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 909
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 4454830 (4.25 MB)
telemt_user_octets_to_client{user="hello"} 173244021 (165.22 MB)
telemt_user_msgs_from_client{user="hello"} 8498
telemt_user_msgs_to_client{user="hello"} 52351
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 3393.2 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1328
telemt_connections_bad_total 597
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 682
telemt_upstream_connect_success_total 682
telemt_upstream_connect_attempts_per_request{bucket="1"} 682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 680
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 9219281 (8.79 MB)
telemt_user_octets_to_client{user="hello"} 355249621 (338.79 MB)
telemt_user_msgs_from_client{user="hello"} 20778
telemt_user_msgs_to_client{user="hello"} 92459
telemt_user_unique_ips_current{user="hello"} 2
```