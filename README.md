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

# Server Metrics 2026-03-04 10:46:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 8628.3 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14763
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 195
telemt_upstream_connect_attempt_total 13457
telemt_upstream_connect_success_total 13456
telemt_upstream_connect_attempts_per_request{bucket="1"} 13455
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13454
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 172151269 (164.18 MB)
telemt_user_octets_to_client{user="hello"} 6435620979 (5.99 GB)
telemt_user_msgs_from_client{user="hello"} 287594
telemt_user_msgs_to_client{user="hello"} 1081064
telemt_user_unique_ips_current{user="hello"} 8
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 8639.1 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1975
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 1812
telemt_upstream_connect_success_total 1810
telemt_upstream_connect_attempts_per_request{bucket="1"} 1808
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1808
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 71720304 (68.40 MB)
telemt_user_octets_to_client{user="hello"} 823849620 (785.68 MB)
telemt_user_msgs_from_client{user="hello"} 63357
telemt_user_msgs_to_client{user="hello"} 258388
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 8623.7 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1750
telemt_connections_bad_total 78
telemt_upstream_connect_attempt_total 1644
telemt_upstream_connect_success_total 1644
telemt_upstream_connect_attempts_per_request{bucket="1"} 1644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 201
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1642
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 42841152 (40.86 MB)
telemt_user_octets_to_client{user="hello"} 3291408594 (3.07 GB)
telemt_user_msgs_from_client{user="hello"} 92231
telemt_user_msgs_to_client{user="hello"} 620453
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 8614.6 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3210
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 2893
telemt_upstream_connect_success_total 2892
telemt_upstream_connect_attempts_per_request{bucket="1"} 2891
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 77
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2890
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 21582761 (20.58 MB)
telemt_user_octets_to_client{user="hello"} 1187549616 (1.11 GB)
telemt_user_msgs_from_client{user="hello"} 36396
telemt_user_msgs_to_client{user="hello"} 323255
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 8625.7 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2967
telemt_connections_bad_total 1542
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1358
telemt_upstream_connect_success_total 1358
telemt_upstream_connect_attempts_per_request{bucket="1"} 1358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1356
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 20793973 (19.83 MB)
telemt_user_octets_to_client{user="hello"} 758628923 (723.48 MB)
telemt_user_msgs_from_client{user="hello"} 41818
telemt_user_msgs_to_client{user="hello"} 189513
telemt_user_unique_ips_current{user="hello"} 1
```