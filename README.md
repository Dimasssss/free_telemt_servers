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

# Server Metrics 2026-03-04 12:34:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 4064.2 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6830
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 6578
telemt_upstream_connect_success_total 6578
telemt_upstream_connect_attempts_per_request{bucket="1"} 6578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6576
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 306945365 (292.73 MB)
telemt_user_octets_to_client{user="hello"} 7508070661 (6.99 GB)
telemt_user_msgs_from_client{user="hello"} 261803
telemt_user_msgs_to_client{user="hello"} 1120060
telemt_user_unique_ips_current{user="hello"} 12
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 4067.2 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1679
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1540
telemt_upstream_connect_success_total 1540
telemt_upstream_connect_attempts_per_request{bucket="1"} 1540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 85
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1538
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 28946733 (27.61 MB)
telemt_user_octets_to_client{user="hello"} 2556330272 (2.38 GB)
telemt_user_msgs_from_client{user="hello"} 51887
telemt_user_msgs_to_client{user="hello"} 793412
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 4065.5 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 607
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 583
telemt_upstream_connect_success_total 583
telemt_upstream_connect_attempts_per_request{bucket="1"} 583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 581
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 21097223 (20.12 MB)
telemt_user_octets_to_client{user="hello"} 278505088 (265.60 MB)
telemt_user_msgs_from_client{user="hello"} 22433
telemt_user_msgs_to_client{user="hello"} 63009
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 4063.1 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1431
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 1320
telemt_upstream_connect_success_total 1320
telemt_upstream_connect_attempts_per_request{bucket="1"} 1320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1318
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 8738233 (8.33 MB)
telemt_user_octets_to_client{user="hello"} 330759810 (315.44 MB)
telemt_user_msgs_from_client{user="hello"} 17253
telemt_user_msgs_to_client{user="hello"} 103783
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 4064.9 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1806
telemt_connections_bad_total 727
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1030
telemt_upstream_connect_success_total 1029
telemt_upstream_connect_attempts_per_request{bucket="1"} 1028
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1027
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 19621109 (18.71 MB)
telemt_user_octets_to_client{user="hello"} 2604307545 (2.43 GB)
telemt_user_msgs_from_client{user="hello"} 42876
telemt_user_msgs_to_client{user="hello"} 481388
```