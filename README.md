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

# Server Metrics 2026-03-07 19:55:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 11391.9 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20165
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 19369
telemt_upstream_connect_success_total 19366
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19364
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 1764018607 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 13949757476 (12.99 GB)
telemt_user_msgs_from_client{user="hello"} 765013
telemt_user_msgs_to_client{user="hello"} 2111989
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 11391.0 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4553
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4373
telemt_upstream_connect_success_total 4371
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4369
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 62551466 (59.65 MB)
telemt_user_octets_to_client{user="hello"} 2832066946 (2.64 GB)
telemt_user_msgs_from_client{user="hello"} 110846
telemt_user_msgs_to_client{user="hello"} 811301
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 11391.0 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2218
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2146
telemt_upstream_connect_success_total 2146
telemt_upstream_connect_attempts_per_request{bucket="1"} 2146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 210
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2144
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 69913550 (66.67 MB)
telemt_user_octets_to_client{user="hello"} 2408847033 (2.24 GB)
telemt_user_msgs_from_client{user="hello"} 74583
telemt_user_msgs_to_client{user="hello"} 491025
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 11219.2 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4779
telemt_connections_bad_total 88
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4592
telemt_upstream_connect_success_total 4581
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 4592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 682
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4579
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 69951903 (66.71 MB)
telemt_user_octets_to_client{user="hello"} 4293929823 (4.00 GB)
telemt_user_msgs_from_client{user="hello"} 114782
telemt_user_msgs_to_client{user="hello"} 1318730
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 11391.2 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6606
telemt_connections_bad_total 2102
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 4391
telemt_upstream_connect_success_total 4384
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4382
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 1561129194 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 2521475455 (2.35 GB)
telemt_user_msgs_from_client{user="hello"} 650135
telemt_user_msgs_to_client{user="hello"} 612609
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```