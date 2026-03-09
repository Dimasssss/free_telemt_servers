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

# Server Metrics 2026-03-09 03:33:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 15202.6 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12088
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 188
telemt_upstream_connect_attempt_total 11160
telemt_upstream_connect_success_total 11157
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 11160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11155
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 120104008 (114.54 MB)
telemt_user_octets_to_client{user="hello"} 8816789683 (8.21 GB)
telemt_user_msgs_from_client{user="hello"} 242941
telemt_user_msgs_to_client{user="hello"} 378489
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 15201.0 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1131
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 1066
telemt_upstream_connect_success_total 1066
telemt_upstream_connect_attempts_per_request{bucket="1"} 1066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1064
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 13363088 (12.74 MB)
telemt_user_octets_to_client{user="hello"} 833325898 (794.72 MB)
telemt_user_msgs_from_client{user="hello"} 34811
telemt_user_msgs_to_client{user="hello"} 154739
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 15201.4 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1040
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 944
telemt_upstream_connect_success_total 944
telemt_upstream_connect_attempts_per_request{bucket="1"} 944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 942
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 384172834 (366.38 MB)
telemt_user_octets_to_client{user="hello"} 923752993 (880.96 MB)
telemt_user_msgs_from_client{user="hello"} 156205
telemt_user_msgs_to_client{user="hello"} 175899
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 15196.1 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1977
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 201
telemt_upstream_connect_attempt_total 1634
telemt_upstream_connect_success_total 1634
telemt_upstream_connect_attempts_per_request{bucket="1"} 1634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 418
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1632
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 14026511 (13.38 MB)
telemt_user_octets_to_client{user="hello"} 1096023502 (1.02 GB)
telemt_user_msgs_from_client{user="hello"} 36361
telemt_user_msgs_to_client{user="hello"} 273287
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 15201.6 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4090
telemt_connections_bad_total 2764
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1296
telemt_upstream_connect_success_total 1296
telemt_upstream_connect_attempts_per_request{bucket="1"} 1296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1294
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 9825016 (9.37 MB)
telemt_user_octets_to_client{user="hello"} 1591138404 (1.48 GB)
telemt_user_msgs_from_client{user="hello"} 25744
telemt_user_msgs_to_client{user="hello"} 192727
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```