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

# Server Metrics 2026-03-06 08:50:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 2390.2 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4763
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 4627
telemt_upstream_connect_success_total 4626
telemt_upstream_connect_attempts_per_request{bucket="1"} 4626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4624
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 48443433 (46.20 MB)
telemt_user_octets_to_client{user="hello"} 3223820515 (3.00 GB)
telemt_user_msgs_from_client{user="hello"} 91633
telemt_user_msgs_to_client{user="hello"} 548024
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 2390.4 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 645
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 629
telemt_upstream_connect_success_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 627
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 5491046 (5.24 MB)
telemt_user_octets_to_client{user="hello"} 257959735 (246.01 MB)
telemt_user_msgs_from_client{user="hello"} 13482
telemt_user_msgs_to_client{user="hello"} 76229
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 2388.2 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 951
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 920
telemt_upstream_connect_success_total 920
telemt_upstream_connect_attempts_per_request{bucket="1"} 920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 918
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 10528405 (10.04 MB)
telemt_user_octets_to_client{user="hello"} 253823151 (242.06 MB)
telemt_user_msgs_from_client{user="hello"} 14074
telemt_user_msgs_to_client{user="hello"} 58455
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 2391.0 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1430
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1264
telemt_upstream_connect_success_total 1259
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1257
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 21562426 (20.56 MB)
telemt_user_octets_to_client{user="hello"} 455835520 (434.72 MB)
telemt_user_msgs_from_client{user="hello"} 22195
telemt_user_msgs_to_client{user="hello"} 115436
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 2392.7 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1884
telemt_connections_bad_total 981
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 874
telemt_upstream_connect_success_total 873
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 871
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 30037341 (28.65 MB)
telemt_user_octets_to_client{user="hello"} 547436514 (522.08 MB)
telemt_user_msgs_from_client{user="hello"} 26150
telemt_user_msgs_to_client{user="hello"} 111809
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```