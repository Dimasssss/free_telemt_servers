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

# Server Metrics 2026-03-06 05:30:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 26091.2 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78077
telemt_connections_bad_total 51938
telemt_handshake_timeouts_total 2444
telemt_upstream_connect_attempt_total 22154
telemt_upstream_connect_success_total 22151
telemt_upstream_connect_attempts_per_request{bucket="1"} 22148
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22147
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 292023988 (278.50 MB)
telemt_user_octets_to_client{user="hello"} 19418918513 (18.09 GB)
telemt_user_msgs_from_client{user="hello"} 543078
telemt_user_msgs_to_client{user="hello"} 2920063
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 26089.0 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2906
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 2711
telemt_upstream_connect_success_total 2710
telemt_upstream_connect_attempts_per_request{bucket="1"} 2709
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2708
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 58407665 (55.70 MB)
telemt_user_octets_to_client{user="hello"} 1236939164 (1.15 GB)
telemt_user_msgs_from_client{user="hello"} 82477
telemt_user_msgs_to_client{user="hello"} 393190
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 26089.4 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1813
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1578
telemt_upstream_connect_success_total 1578
telemt_upstream_connect_attempts_per_request{bucket="1"} 1578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1574
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 39681056 (37.84 MB)
telemt_user_octets_to_client{user="hello"} 1952215059 (1.82 GB)
telemt_user_msgs_from_client{user="hello"} 53988
telemt_user_msgs_to_client{user="hello"} 397171
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 26092.2 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3676
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 3102
telemt_upstream_connect_success_total 3102
telemt_upstream_connect_attempts_per_request{bucket="1"} 3102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 403
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3098
telemt_user_octets_from_client{user="hello"} 97798983 (93.27 MB)
telemt_user_octets_to_client{user="hello"} 5760032098 (5.36 GB)
telemt_user_msgs_from_client{user="hello"} 140158
telemt_user_msgs_to_client{user="hello"} 1219332
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 26092.0 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8795
telemt_connections_bad_total 4739
telemt_handshake_timeouts_total 157
telemt_upstream_connect_attempt_total 3796
telemt_upstream_connect_success_total 3796
telemt_upstream_connect_attempts_per_request{bucket="1"} 3796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3792
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 78121488 (74.50 MB)
telemt_user_octets_to_client{user="hello"} 15937056592 (14.84 GB)
telemt_user_msgs_from_client{user="hello"} 199786
telemt_user_msgs_to_client{user="hello"} 3037075
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```