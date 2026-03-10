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

# Server Metrics 2026-03-10 14:34:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 499.0 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2877
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 2725
telemt_upstream_connect_success_total 2725
telemt_upstream_connect_attempts_per_request{bucket="1"} 2725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2723
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 29208714 (27.86 MB)
telemt_user_octets_to_client{user="hello"} 1296017937 (1.21 GB)
telemt_user_msgs_from_client{user="hello"} 41175
telemt_user_msgs_to_client{user="hello"} 73388
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 498.0 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 790
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 692
telemt_upstream_connect_success_total 692
telemt_upstream_connect_attempts_per_request{bucket="1"} 692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 690
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 16662372 (15.89 MB)
telemt_user_octets_to_client{user="hello"} 641888282 (612.15 MB)
telemt_user_msgs_from_client{user="hello"} 21450
telemt_user_msgs_to_client{user="hello"} 181523
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 497.9 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1210
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 1121
telemt_upstream_connect_success_total 1121
telemt_upstream_connect_attempts_per_request{bucket="1"} 1121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1119
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 13168894 (12.56 MB)
telemt_user_octets_to_client{user="hello"} 63607845 (60.66 MB)
telemt_user_msgs_from_client{user="hello"} 13725
telemt_user_msgs_to_client{user="hello"} 28304
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 496.6 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1288
telemt_handshake_timeouts_total 29
telemt_upstream_connect_attempt_total 1183
telemt_upstream_connect_success_total 1179
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1177
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 7371487 (7.03 MB)
telemt_user_octets_to_client{user="hello"} 546317214 (521.01 MB)
telemt_user_msgs_from_client{user="hello"} 15966
telemt_user_msgs_to_client{user="hello"} 104483
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 497.9 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2060
telemt_connections_bad_total 332
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 1627
telemt_upstream_connect_success_total 1627
telemt_upstream_connect_attempts_per_request{bucket="1"} 1627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1625
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 13397641 (12.78 MB)
telemt_user_octets_to_client{user="hello"} 996876340 (950.70 MB)
telemt_user_msgs_from_client{user="hello"} 29311
telemt_user_msgs_to_client{user="hello"} 116592
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 25
```