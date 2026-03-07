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

# Server Metrics 2026-03-07 17:26:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 2457.3 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5513
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 5239
telemt_upstream_connect_success_total 5238
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5236
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 61695016 (58.84 MB)
telemt_user_octets_to_client{user="hello"} 2091494601 (1.95 GB)
telemt_user_msgs_from_client{user="hello"} 98396
telemt_user_msgs_to_client{user="hello"} 348641
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 2456.8 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1171
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1144
telemt_upstream_connect_success_total 1143
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1141
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 20772851 (19.81 MB)
telemt_user_octets_to_client{user="hello"} 939303215 (895.79 MB)
telemt_user_msgs_from_client{user="hello"} 34477
telemt_user_msgs_to_client{user="hello"} 278795
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 2456.3 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402
telemt_connections_bad_total 8
telemt_upstream_connect_attempt_total 392
telemt_upstream_connect_success_total 392
telemt_upstream_connect_attempts_per_request{bucket="1"} 392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 390
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 2342913 (2.23 MB)
telemt_user_octets_to_client{user="hello"} 168839620 (161.02 MB)
telemt_user_msgs_from_client{user="hello"} 6232
telemt_user_msgs_to_client{user="hello"} 36795
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 2284.6 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 756
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 732
telemt_upstream_connect_success_total 730
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 76
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 728
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 10190280 (9.72 MB)
telemt_user_octets_to_client{user="hello"} 245484392 (234.11 MB)
telemt_user_msgs_from_client{user="hello"} 10507
telemt_user_msgs_to_client{user="hello"} 65998
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 2456.5 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1569
telemt_connections_bad_total 480
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1048
telemt_upstream_connect_success_total 1048
telemt_upstream_connect_attempts_per_request{bucket="1"} 1048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1046
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 25525821 (24.34 MB)
telemt_user_octets_to_client{user="hello"} 538192985 (513.26 MB)
telemt_user_msgs_from_client{user="hello"} 31644
telemt_user_msgs_to_client{user="hello"} 122524
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```