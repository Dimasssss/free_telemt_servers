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

# Server Metrics 2026-03-09 03:43:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 15814.0 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13081
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 203
telemt_upstream_connect_attempt_total 11788
telemt_upstream_connect_success_total 11785
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 11788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11783
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 124760912 (118.98 MB)
telemt_user_octets_to_client{user="hello"} 8862854752 (8.25 GB)
telemt_user_msgs_from_client{user="hello"} 248979
telemt_user_msgs_to_client{user="hello"} 384915
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 15812.7 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1269
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 1177
telemt_upstream_connect_success_total 1177
telemt_upstream_connect_attempts_per_request{bucket="1"} 1177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1175
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 23612476 (22.52 MB)
telemt_user_octets_to_client{user="hello"} 1163564255 (1.08 GB)
telemt_user_msgs_from_client{user="hello"} 46633
telemt_user_msgs_to_client{user="hello"} 220229
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 15813.1 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1066
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 970
telemt_upstream_connect_success_total 970
telemt_upstream_connect_attempts_per_request{bucket="1"} 970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 968
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 384249478 (366.45 MB)
telemt_user_octets_to_client{user="hello"} 925614262 (882.73 MB)
telemt_user_msgs_from_client{user="hello"} 156416
telemt_user_msgs_to_client{user="hello"} 176662
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 15807.9 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2009
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 201
telemt_upstream_connect_attempt_total 1666
telemt_upstream_connect_success_total 1666
telemt_upstream_connect_attempts_per_request{bucket="1"} 1666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1664
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 14230035 (13.57 MB)
telemt_user_octets_to_client{user="hello"} 1147664365 (1.07 GB)
telemt_user_msgs_from_client{user="hello"} 36928
telemt_user_msgs_to_client{user="hello"} 284747
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 15813.4 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4265
telemt_connections_bad_total 2884
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1349
telemt_upstream_connect_success_total 1349
telemt_upstream_connect_attempts_per_request{bucket="1"} 1349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 170
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1347
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 9930577 (9.47 MB)
telemt_user_octets_to_client{user="hello"} 1592830009 (1.48 GB)
telemt_user_msgs_from_client{user="hello"} 26005
telemt_user_msgs_to_client{user="hello"} 193277
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```