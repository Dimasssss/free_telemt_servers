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

# Server Metrics 2026-03-05 17:26:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.0

telemt_uptime_seconds 659.3 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2734
telemt_connections_bad_total 1679
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1034
telemt_upstream_connect_success_total 1033
telemt_upstream_connect_attempts_per_request{bucket="1"} 1032
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1031
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 7830426 (7.47 MB)
telemt_user_octets_to_client{user="hello"} 430833527 (410.87 MB)
telemt_user_msgs_from_client{user="hello"} 18939
telemt_user_msgs_to_client{user="hello"} 72951
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.0

telemt_uptime_seconds 661.7 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128
telemt_upstream_connect_attempt_total 130
telemt_upstream_connect_success_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 128
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 745786 (728.31 KB)
telemt_user_octets_to_client{user="hello"} 40871294 (38.98 MB)
telemt_user_msgs_from_client{user="hello"} 1739
telemt_user_msgs_to_client{user="hello"} 10760
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.0

telemt_uptime_seconds 659.7 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 267
telemt_upstream_connect_success_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 265
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 1244923 (1.19 MB)
telemt_user_octets_to_client{user="hello"} 85301146 (81.35 MB)
telemt_user_msgs_from_client{user="hello"} 3361
telemt_user_msgs_to_client{user="hello"} 20261
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.0

telemt_uptime_seconds 657.2 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 193
telemt_upstream_connect_success_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 191
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 866809 (846.49 KB)
telemt_user_octets_to_client{user="hello"} 33723682 (32.16 MB)
telemt_user_msgs_from_client{user="hello"} 2138
telemt_user_msgs_to_client{user="hello"} 9813
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.0

telemt_uptime_seconds 659.1 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 304
telemt_upstream_connect_success_total 304
telemt_upstream_connect_attempts_per_request{bucket="1"} 304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 302
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 17246472 (16.45 MB)
telemt_user_octets_to_client{user="hello"} 133101655 (126.94 MB)
telemt_user_msgs_from_client{user="hello"} 12528
telemt_user_msgs_to_client{user="hello"} 30455
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```