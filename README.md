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

# Server Metrics 2026-03-06 10:32:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 661.3 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1102
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1056
telemt_upstream_connect_success_total 1056
telemt_upstream_connect_attempts_per_request{bucket="1"} 1056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1054
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 38515018 (36.73 MB)
telemt_user_octets_to_client{user="hello"} 689647902 (657.70 MB)
telemt_user_msgs_from_client{user="hello"} 34951
telemt_user_msgs_to_client{user="hello"} 116694
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 660.5 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 167
telemt_upstream_connect_success_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 165
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 1509923 (1.44 MB)
telemt_user_octets_to_client{user="hello"} 19310600 (18.42 MB)
telemt_user_msgs_from_client{user="hello"} 3424
telemt_user_msgs_to_client{user="hello"} 9375
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 660.2 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 222
telemt_upstream_connect_success_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 220
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 9908451 (9.45 MB)
telemt_user_octets_to_client{user="hello"} 57215501 (54.56 MB)
telemt_user_msgs_from_client{user="hello"} 7199
telemt_user_msgs_to_client{user="hello"} 14021
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 659.0 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 313
telemt_upstream_connect_success_total 308
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 306
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 1261131 (1.20 MB)
telemt_user_octets_to_client{user="hello"} 41789130 (39.85 MB)
telemt_user_msgs_from_client{user="hello"} 2871
telemt_user_msgs_to_client{user="hello"} 13130
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 660.4 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 309
telemt_upstream_connect_success_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 307
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 4497913 (4.29 MB)
telemt_user_octets_to_client{user="hello"} 114613849 (109.30 MB)
telemt_user_msgs_from_client{user="hello"} 4911
telemt_user_msgs_to_client{user="hello"} 23315
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```