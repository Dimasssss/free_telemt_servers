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

# Server Metrics 2026-03-08 23:43:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 1444.1 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1328
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 1126
telemt_upstream_connect_success_total 1126
telemt_upstream_connect_attempts_per_request{bucket="1"} 1126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1124
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 14842383 (14.15 MB)
telemt_user_octets_to_client{user="hello"} 1636167647 (1.52 GB)
telemt_user_msgs_from_client{user="hello"} 38607
telemt_user_msgs_to_client{user="hello"} 65999
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 1442.4 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 115
telemt_upstream_connect_success_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 113
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 922150 (900.54 KB)
telemt_user_octets_to_client{user="hello"} 33329372 (31.79 MB)
telemt_user_msgs_from_client{user="hello"} 2179
telemt_user_msgs_to_client{user="hello"} 8153
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 1442.9 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140
telemt_connections_bad_total 26
telemt_upstream_connect_attempt_total 115
telemt_upstream_connect_success_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 113
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 3975783 (3.79 MB)
telemt_user_octets_to_client{user="hello"} 14120793 (13.47 MB)
telemt_user_msgs_from_client{user="hello"} 2662
telemt_user_msgs_to_client{user="hello"} 4732
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 1437.9 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209
telemt_upstream_connect_attempt_total 207
telemt_upstream_connect_success_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 205
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 769956 (751.91 KB)
telemt_user_octets_to_client{user="hello"} 27877057 (26.59 MB)
telemt_user_msgs_from_client{user="hello"} 2342
telemt_user_msgs_to_client{user="hello"} 7874
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 1443.3 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400
telemt_connections_bad_total 259
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 136
telemt_upstream_connect_success_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 134
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 3692469 (3.52 MB)
telemt_user_octets_to_client{user="hello"} 996403438 (950.24 MB)
telemt_user_msgs_from_client{user="hello"} 10461
telemt_user_msgs_to_client{user="hello"} 107756
telemt_user_unique_ips_current{user="hello"} 6
```