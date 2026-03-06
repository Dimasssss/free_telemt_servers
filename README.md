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

# Server Metrics 2026-03-06 10:27:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 353.4 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 548
telemt_upstream_connect_success_total 548
telemt_upstream_connect_attempts_per_request{bucket="1"} 548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 546
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 5363373 (5.11 MB)
telemt_user_octets_to_client{user="hello"} 457630023 (436.43 MB)
telemt_user_msgs_from_client{user="hello"} 14026
telemt_user_msgs_to_client{user="hello"} 75322
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 352.5 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119
telemt_connections_bad_total 13
telemt_upstream_connect_attempt_total 106
telemt_upstream_connect_success_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 989543 (966.35 KB)
telemt_user_octets_to_client{user="hello"} 8328428 (7.94 MB)
telemt_user_msgs_from_client{user="hello"} 2188
telemt_user_msgs_to_client{user="hello"} 4897
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 352.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 116
telemt_upstream_connect_success_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 8910103 (8.50 MB)
telemt_user_octets_to_client{user="hello"} 17666021 (16.85 MB)
telemt_user_msgs_from_client{user="hello"} 4416
telemt_user_msgs_to_client{user="hello"} 4973
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 351.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 120
telemt_upstream_connect_success_total 119
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 117
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 460602 (449.81 KB)
telemt_user_octets_to_client{user="hello"} 21210073 (20.23 MB)
telemt_user_msgs_from_client{user="hello"} 1166
telemt_user_msgs_to_client{user="hello"} 6228
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 352.5 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250
telemt_connections_bad_total 62
telemt_upstream_connect_attempt_total 181
telemt_upstream_connect_success_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 179
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 2966285 (2.83 MB)
telemt_user_octets_to_client{user="hello"} 11679422 (11.14 MB)
telemt_user_msgs_from_client{user="hello"} 1499
telemt_user_msgs_to_client{user="hello"} 3604
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 2
```