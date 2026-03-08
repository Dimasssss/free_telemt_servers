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

# Server Metrics 2026-03-08 07:12:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 236.5 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 487
telemt_upstream_connect_success_total 487
telemt_upstream_connect_attempts_per_request{bucket="1"} 487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 485
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 9790069 (9.34 MB)
telemt_user_octets_to_client{user="hello"} 146303434 (139.53 MB)
telemt_user_msgs_from_client{user="hello"} 11500
telemt_user_msgs_to_client{user="hello"} 12848
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 235.7 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 59
telemt_upstream_connect_success_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 541912 (529.21 KB)
telemt_user_octets_to_client{user="hello"} 22613038 (21.57 MB)
telemt_user_msgs_from_client{user="hello"} 979
telemt_user_msgs_to_client{user="hello"} 9188
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 235.7 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70
telemt_upstream_connect_attempt_total 71
telemt_upstream_connect_success_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 71
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 104636 (102.18 KB)
telemt_user_octets_to_client{user="hello"} 1648252 (1.57 MB)
telemt_user_msgs_from_client{user="hello"} 282
telemt_user_msgs_to_client{user="hello"} 981
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 235.3 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 100
telemt_upstream_connect_success_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 421086 (411.22 KB)
telemt_user_octets_to_client{user="hello"} 22149841 (21.12 MB)
telemt_user_msgs_from_client{user="hello"} 967
telemt_user_msgs_to_client{user="hello"} 4640
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 235.6 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247
telemt_connections_bad_total 43
telemt_upstream_connect_attempt_total 205
telemt_upstream_connect_success_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 203
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 1131273 (1.08 MB)
telemt_user_octets_to_client{user="hello"} 45756906 (43.64 MB)
telemt_user_msgs_from_client{user="hello"} 2506
telemt_user_msgs_to_client{user="hello"} 7940
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```