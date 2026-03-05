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

# Server Metrics 2026-03-05 22:39:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 1468.8 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24793
telemt_connections_bad_total 22967
telemt_handshake_timeouts_total 806
telemt_upstream_connect_attempt_total 985
telemt_upstream_connect_success_total 985
telemt_upstream_connect_attempts_per_request{bucket="1"} 985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 983
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 13611546 (12.98 MB)
telemt_user_octets_to_client{user="hello"} 2024656742 (1.89 GB)
telemt_user_msgs_from_client{user="hello"} 31040
telemt_user_msgs_to_client{user="hello"} 275712
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 1466.7 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139
telemt_connections_bad_total 6
telemt_upstream_connect_attempt_total 134
telemt_upstream_connect_success_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 132
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 943404 (921.29 KB)
telemt_user_octets_to_client{user="hello"} 62648282 (59.75 MB)
telemt_user_msgs_from_client{user="hello"} 2380
telemt_user_msgs_to_client{user="hello"} 16763
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 1467.1 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97
telemt_upstream_connect_attempt_total 99
telemt_upstream_connect_success_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 99
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 225908 (220.61 KB)
telemt_user_octets_to_client{user="hello"} 3918861 (3.74 MB)
telemt_user_msgs_from_client{user="hello"} 548
telemt_user_msgs_to_client{user="hello"} 1453
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 1469.8 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211
telemt_upstream_connect_attempt_total 207
telemt_upstream_connect_success_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 205
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 6171413 (5.89 MB)
telemt_user_octets_to_client{user="hello"} 915266719 (872.87 MB)
telemt_user_msgs_from_client{user="hello"} 17561
telemt_user_msgs_to_client{user="hello"} 159788
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 1469.6 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512
telemt_connections_bad_total 271
telemt_upstream_connect_attempt_total 242
telemt_upstream_connect_success_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 240
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 5940733 (5.67 MB)
telemt_user_octets_to_client{user="hello"} 1042914733 (994.60 MB)
telemt_user_msgs_from_client{user="hello"} 15978
telemt_user_msgs_to_client{user="hello"} 200435
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```