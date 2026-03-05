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

# Server Metrics 2026-03-05 23:00:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 2700.4 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44465
telemt_connections_bad_total 41844
telemt_handshake_timeouts_total 933
telemt_upstream_connect_attempt_total 1671
telemt_upstream_connect_success_total 1671
telemt_upstream_connect_attempts_per_request{bucket="1"} 1671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1669
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 20063860 (19.13 MB)
telemt_user_octets_to_client{user="hello"} 2665523007 (2.48 GB)
telemt_user_msgs_from_client{user="hello"} 49786
telemt_user_msgs_to_client{user="hello"} 370419
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 2698.2 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243
telemt_connections_bad_total 8
telemt_upstream_connect_attempt_total 236
telemt_upstream_connect_success_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 234
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 1334493 (1.27 MB)
telemt_user_octets_to_client{user="hello"} 73573833 (70.17 MB)
telemt_user_msgs_from_client{user="hello"} 3485
telemt_user_msgs_to_client{user="hello"} 22625
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 2698.7 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172
telemt_connections_bad_total 23
telemt_upstream_connect_attempt_total 151
telemt_upstream_connect_success_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 149
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 362784 (354.28 KB)
telemt_user_octets_to_client{user="hello"} 4834964 (4.61 MB)
telemt_user_msgs_from_client{user="hello"} 894
telemt_user_msgs_to_client{user="hello"} 2089
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 2701.3 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321
telemt_upstream_connect_attempt_total 314
telemt_upstream_connect_success_total 314
telemt_upstream_connect_attempts_per_request{bucket="1"} 314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 312
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 9872766 (9.42 MB)
telemt_user_octets_to_client{user="hello"} 1548617036 (1.44 GB)
telemt_user_msgs_from_client{user="hello"} 28066
telemt_user_msgs_to_client{user="hello"} 269260
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 2701.1 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 871
telemt_connections_bad_total 490
telemt_upstream_connect_attempt_total 380
telemt_upstream_connect_success_total 380
telemt_upstream_connect_attempts_per_request{bucket="1"} 380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 378
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 8244382 (7.86 MB)
telemt_user_octets_to_client{user="hello"} 1642028173 (1.53 GB)
telemt_user_msgs_from_client{user="hello"} 22370
telemt_user_msgs_to_client{user="hello"} 302364
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```