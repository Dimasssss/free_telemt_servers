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

# Server Metrics 2026-03-04 09:45:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 4934.3 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8905
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 141
telemt_upstream_connect_attempt_total 7859
telemt_upstream_connect_success_total 7859
telemt_upstream_connect_attempts_per_request{bucket="1"} 7859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7857
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 108594861 (103.56 MB)
telemt_user_octets_to_client{user="hello"} 3707924709 (3.45 GB)
telemt_user_msgs_from_client{user="hello"} 169287
telemt_user_msgs_to_client{user="hello"} 639994
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 4945.7 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 920
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 831
telemt_upstream_connect_success_total 831
telemt_upstream_connect_attempts_per_request{bucket="1"} 831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 829
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 29555356 (28.19 MB)
telemt_user_octets_to_client{user="hello"} 340327052 (324.56 MB)
telemt_user_msgs_from_client{user="hello"} 29245
telemt_user_msgs_to_client{user="hello"} 105439
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 4930.4 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 869
telemt_connections_bad_total 59
telemt_upstream_connect_attempt_total 788
telemt_upstream_connect_success_total 788
telemt_upstream_connect_attempts_per_request{bucket="1"} 788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 786
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 13473405 (12.85 MB)
telemt_user_octets_to_client{user="hello"} 1505690666 (1.40 GB)
telemt_user_msgs_from_client{user="hello"} 37880
telemt_user_msgs_to_client{user="hello"} 263026
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 4921.0 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1744
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 1586
telemt_upstream_connect_success_total 1585
telemt_upstream_connect_attempts_per_request{bucket="1"} 1584
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1583
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 6640011 (6.33 MB)
telemt_user_octets_to_client{user="hello"} 241413001 (230.23 MB)
telemt_user_msgs_from_client{user="hello"} 14375
telemt_user_msgs_to_client{user="hello"} 76871
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 4932.3 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1799
telemt_connections_bad_total 866
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 880
telemt_upstream_connect_success_total 880
telemt_upstream_connect_attempts_per_request{bucket="1"} 880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 878
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 12046036 (11.49 MB)
telemt_user_octets_to_client{user="hello"} 437111268 (416.86 MB)
telemt_user_msgs_from_client{user="hello"} 26890
telemt_user_msgs_to_client{user="hello"} 114450
telemt_user_unique_ips_current{user="hello"} 1
```