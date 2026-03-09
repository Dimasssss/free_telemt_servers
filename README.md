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

# Server Metrics 2026-03-09 14:41:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 55321.9 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98080
telemt_connections_bad_total 1649
telemt_handshake_timeouts_total 942
telemt_upstream_connect_attempt_total 91219
telemt_upstream_connect_success_total 91181
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 91219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91175
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 2419956136 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 45815190358 (42.67 GB)
telemt_user_msgs_from_client{user="hello"} 2223236
telemt_user_msgs_to_client{user="hello"} 3063088
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 55320.8 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23505
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 288
telemt_upstream_connect_attempt_total 22198
telemt_upstream_connect_success_total 22181
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 22198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22175
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 804554431 (767.28 MB)
telemt_user_octets_to_client{user="hello"} 12503723363 (11.64 GB)
telemt_user_msgs_from_client{user="hello"} 678183
telemt_user_msgs_to_client{user="hello"} 3358688
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 55321.4 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29310
telemt_connections_bad_total 190
telemt_handshake_timeouts_total 1495
telemt_upstream_connect_attempt_total 21233
telemt_upstream_connect_success_total 21233
telemt_upstream_connect_attempts_per_request{bucket="1"} 21233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21227
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 4330944963 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 11503677125 (10.71 GB)
telemt_user_msgs_from_client{user="hello"} 1812176
telemt_user_msgs_to_client{user="hello"} 1640306
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 55315.8 (15h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31567
telemt_connections_bad_total 184
telemt_handshake_timeouts_total 809
telemt_upstream_connect_attempt_total 28885
telemt_upstream_connect_success_total 28813
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 28885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28807
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 1780384193 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 20284784211 (18.89 GB)
telemt_user_msgs_from_client{user="hello"} 1023871
telemt_user_msgs_to_client{user="hello"} 4889961
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 55321.2 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57579
telemt_connections_bad_total 13451
telemt_handshake_timeouts_total 1438
telemt_upstream_connect_attempt_total 39909
telemt_upstream_connect_success_total 39907
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 39909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39901
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 701133665 (668.65 MB)
telemt_user_octets_to_client{user="hello"} 39336710975 (36.64 GB)
telemt_user_msgs_from_client{user="hello"} 899095
telemt_user_msgs_to_client{user="hello"} 4857647
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 16
```