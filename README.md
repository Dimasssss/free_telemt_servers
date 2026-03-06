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

# Server Metrics 2026-03-06 10:07:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 7010.1 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13553
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 13062
telemt_upstream_connect_success_total 13061
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 805
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13059
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 1053766575 (1004.95 MB)
telemt_user_octets_to_client{user="hello"} 7837190791 (7.30 GB)
telemt_user_msgs_from_client{user="hello"} 598779
telemt_user_msgs_to_client{user="hello"} 1305142
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 7010.7 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2087
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 1976
telemt_upstream_connect_success_total 1976
telemt_upstream_connect_attempts_per_request{bucket="1"} 1976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1974
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 20862783 (19.90 MB)
telemt_user_octets_to_client{user="hello"} 640654072 (610.98 MB)
telemt_user_msgs_from_client{user="hello"} 42768
telemt_user_msgs_to_client{user="hello"} 215206
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 7008.4 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2291
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2155
telemt_upstream_connect_success_total 2155
telemt_upstream_connect_attempts_per_request{bucket="1"} 2155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2153
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 131597130 (125.50 MB)
telemt_user_octets_to_client{user="hello"} 1838670484 (1.71 GB)
telemt_user_msgs_from_client{user="hello"} 86012
telemt_user_msgs_to_client{user="hello"} 351029
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 7011.3 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3977
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 3492
telemt_upstream_connect_success_total 3481
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 3492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3479
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 35857453 (34.20 MB)
telemt_user_octets_to_client{user="hello"} 972695402 (927.63 MB)
telemt_user_msgs_from_client{user="hello"} 54391
telemt_user_msgs_to_client{user="hello"} 263080
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 7012.9 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4343
telemt_connections_bad_total 1808
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 2339
telemt_upstream_connect_success_total 2338
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2336
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 120362073 (114.79 MB)
telemt_user_octets_to_client{user="hello"} 3351192352 (3.12 GB)
telemt_user_msgs_from_client{user="hello"} 98445
telemt_user_msgs_to_client{user="hello"} 605260
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```