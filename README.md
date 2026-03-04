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

# Server Metrics 2026-03-04 09:04:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 2471.6 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4424
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 84
telemt_upstream_connect_attempt_total 3695
telemt_upstream_connect_success_total 3695
telemt_upstream_connect_attempts_per_request{bucket="1"} 3695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3693
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 52976678 (50.52 MB)
telemt_user_octets_to_client{user="hello"} 2016489809 (1.88 GB)
telemt_user_msgs_from_client{user="hello"} 76660
telemt_user_msgs_to_client{user="hello"} 343508
telemt_user_unique_ips_current{user="hello"} 12
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 2482.8 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312
telemt_connections_bad_total 13
telemt_upstream_connect_attempt_total 296
telemt_upstream_connect_success_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 294
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 3693361 (3.52 MB)
telemt_user_octets_to_client{user="hello"} 67601405 (64.47 MB)
telemt_user_msgs_from_client{user="hello"} 6616
telemt_user_msgs_to_client{user="hello"} 25753
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 2467.5 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375
telemt_connections_bad_total 56
telemt_upstream_connect_attempt_total 308
telemt_upstream_connect_success_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 306
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 1636183 (1.56 MB)
telemt_user_octets_to_client{user="hello"} 100144498 (95.51 MB)
telemt_user_msgs_from_client{user="hello"} 4037
telemt_user_msgs_to_client{user="hello"} 22840
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 2458.0 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 798
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 716
telemt_upstream_connect_success_total 716
telemt_upstream_connect_attempts_per_request{bucket="1"} 716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 714
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 2578368 (2.46 MB)
telemt_user_octets_to_client{user="hello"} 86565450 (82.56 MB)
telemt_user_msgs_from_client{user="hello"} 5443
telemt_user_msgs_to_client{user="hello"} 29098
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 2469.5 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082
telemt_connections_bad_total 437
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 597
telemt_upstream_connect_success_total 597
telemt_upstream_connect_attempts_per_request{bucket="1"} 597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 595
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 7777051 (7.42 MB)
telemt_user_octets_to_client{user="hello"} 316821422 (302.14 MB)
telemt_user_msgs_from_client{user="hello"} 18067
telemt_user_msgs_to_client{user="hello"} 84085
telemt_user_unique_ips_current{user="hello"} 3
```