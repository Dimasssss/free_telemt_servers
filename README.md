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

# Server Metrics 2026-03-04 18:59:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 27175.3 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43588
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 1261
telemt_upstream_connect_attempt_total 41311
telemt_upstream_connect_success_total 41302
telemt_upstream_connect_attempts_per_request{bucket="1"} 41293
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41298
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 1408791966 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 31970579189 (29.77 GB)
telemt_user_msgs_from_client{user="hello"} 1292874
telemt_user_msgs_to_client{user="hello"} 5036335
telemt_user_unique_ips_current{user="hello"} 8
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 27178.1 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9924
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 9321
telemt_upstream_connect_success_total 9319
telemt_upstream_connect_attempts_per_request{bucket="1"} 9317
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9315
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 845739047 (806.56 MB)
telemt_user_octets_to_client{user="hello"} 10517982470 (9.80 GB)
telemt_user_msgs_from_client{user="hello"} 538939
telemt_user_msgs_to_client{user="hello"} 3551480
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 27176.2 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5587
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 5410
telemt_upstream_connect_success_total 5410
telemt_upstream_connect_attempts_per_request{bucket="1"} 5410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5406
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 232731849 (221.95 MB)
telemt_user_octets_to_client{user="hello"} 4148802930 (3.86 GB)
telemt_user_msgs_from_client{user="hello"} 207031
telemt_user_msgs_to_client{user="hello"} 890529
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 27174.1 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9217
telemt_connections_bad_total 431
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 8242
telemt_upstream_connect_success_total 8238
telemt_upstream_connect_attempts_per_request{bucket="1"} 8234
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8234
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 130053247 (124.03 MB)
telemt_user_octets_to_client{user="hello"} 4311855185 (4.02 GB)
telemt_user_msgs_from_client{user="hello"} 154657
telemt_user_msgs_to_client{user="hello"} 1040903
telemt_user_unique_ips_current{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 27175.9 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11083
telemt_connections_bad_total 4825
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 6039
telemt_upstream_connect_success_total 6036
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6035
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6032
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 175334557 (167.21 MB)
telemt_user_octets_to_client{user="hello"} 11562061465 (10.77 GB)
telemt_user_msgs_from_client{user="hello"} 273604
telemt_user_msgs_to_client{user="hello"} 2206472
telemt_user_unique_ips_current{user="hello"} 3
```