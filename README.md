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

# Server Metrics 2026-03-09 04:49:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 19790.6 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17851
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 468
telemt_upstream_connect_attempt_total 16106
telemt_upstream_connect_success_total 16101
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16099
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 154327537 (147.18 MB)
telemt_user_octets_to_client{user="hello"} 9525910607 (8.87 GB)
telemt_user_msgs_from_client{user="hello"} 296331
telemt_user_msgs_to_client{user="hello"} 445786
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 19788.9 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1961
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 1803
telemt_upstream_connect_success_total 1803
telemt_upstream_connect_attempts_per_request{bucket="1"} 1803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1801
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 32952683 (31.43 MB)
telemt_user_octets_to_client{user="hello"} 1523949708 (1.42 GB)
telemt_user_msgs_from_client{user="hello"} 67666
telemt_user_msgs_to_client{user="hello"} 300072
telemt_user_unique_ips_current{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 19789.5 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1334
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1233
telemt_upstream_connect_success_total 1233
telemt_upstream_connect_attempts_per_request{bucket="1"} 1233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1231
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 463613904 (442.14 MB)
telemt_user_octets_to_client{user="hello"} 1003629485 (957.14 MB)
telemt_user_msgs_from_client{user="hello"} 187520
telemt_user_msgs_to_client{user="hello"} 193665
telemt_user_unique_ips_current{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 19784.3 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2603
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 2098
telemt_upstream_connect_success_total 2098
telemt_upstream_connect_attempts_per_request{bucket="1"} 2098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2096
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 17196323 (16.40 MB)
telemt_user_octets_to_client{user="hello"} 1375621392 (1.28 GB)
telemt_user_msgs_from_client{user="hello"} 44258
telemt_user_msgs_to_client{user="hello"} 337250
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 19789.8 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5482
telemt_connections_bad_total 3596
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 1845
telemt_upstream_connect_success_total 1845
telemt_upstream_connect_attempts_per_request{bucket="1"} 1845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1843
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 13385343 (12.77 MB)
telemt_user_octets_to_client{user="hello"} 1673872352 (1.56 GB)
telemt_user_msgs_from_client{user="hello"} 34580
telemt_user_msgs_to_client{user="hello"} 211490
telemt_user_unique_ips_current{user="hello"} 3
```