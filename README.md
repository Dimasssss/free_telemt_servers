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

# Server Metrics 2026-03-08 14:50:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 27690.3 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67085
telemt_connections_bad_total 5023
telemt_handshake_timeouts_total 1027
telemt_upstream_connect_attempt_total 58591
telemt_upstream_connect_success_total 58569
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 58591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58565
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 1620987375 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 30709642085 (28.60 GB)
telemt_user_msgs_from_client{user="hello"} 1409217
telemt_user_msgs_to_client{user="hello"} 1856699
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 27689.6 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14404
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 13900
telemt_upstream_connect_success_total 13899
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13895
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 520670457 (496.55 MB)
telemt_user_octets_to_client{user="hello"} 10037005499 (9.35 GB)
telemt_user_msgs_from_client{user="hello"} 492465
telemt_user_msgs_to_client{user="hello"} 2548221
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 27689.2 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9335
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 8713
telemt_upstream_connect_success_total 8637
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 8713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8633
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 203814521 (194.37 MB)
telemt_user_octets_to_client{user="hello"} 2873601482 (2.68 GB)
telemt_user_msgs_from_client{user="hello"} 147083
telemt_user_msgs_to_client{user="hello"} 490172
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 27689.1 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11920
telemt_connections_bad_total 151
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 11380
telemt_upstream_connect_success_total 11354
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11350
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 939993880 (896.45 MB)
telemt_user_octets_to_client{user="hello"} 4369117702 (4.07 GB)
telemt_user_msgs_from_client{user="hello"} 450523
telemt_user_msgs_to_client{user="hello"} 979014
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 27689.4 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15746
telemt_connections_bad_total 5104
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 10296
telemt_upstream_connect_success_total 10292
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10288
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 227800296 (217.25 MB)
telemt_user_octets_to_client{user="hello"} 8183661199 (7.62 GB)
telemt_user_msgs_from_client{user="hello"} 269143
telemt_user_msgs_to_client{user="hello"} 1135612
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```