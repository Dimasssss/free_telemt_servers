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

# Server Metrics 2026-03-08 19:06:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 43096.4 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99372
telemt_connections_bad_total 5056
telemt_handshake_timeouts_total 1253
telemt_upstream_connect_attempt_total 89815
telemt_upstream_connect_success_total 89784
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 89815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89778
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 2189751720 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 55596203455 (51.78 GB)
telemt_user_msgs_from_client{user="hello"} 2177901
telemt_user_msgs_to_client{user="hello"} 3057209
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 43095.6 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22656
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 21933
telemt_upstream_connect_success_total 21928
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 21933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21924
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 739037208 (704.80 MB)
telemt_user_octets_to_client{user="hello"} 20264395025 (18.87 GB)
telemt_user_msgs_from_client{user="hello"} 863614
telemt_user_msgs_to_client{user="hello"} 5543222
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 43095.2 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13795
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12468
telemt_upstream_connect_success_total 12392
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12388
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 241916061 (230.71 MB)
telemt_user_octets_to_client{user="hello"} 4238980037 (3.95 GB)
telemt_user_msgs_from_client{user="hello"} 208488
telemt_user_msgs_to_client{user="hello"} 761161
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 43095.1 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17760
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 17000
telemt_upstream_connect_success_total 16964
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 17000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16960
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 1039538712 (991.38 MB)
telemt_user_octets_to_client{user="hello"} 6015401136 (5.60 GB)
telemt_user_msgs_from_client{user="hello"} 543263
telemt_user_msgs_to_client{user="hello"} 1363489
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 43095.4 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25379
telemt_connections_bad_total 8157
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 16594
telemt_upstream_connect_success_total 16587
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16581
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 313103141 (298.60 MB)
telemt_user_octets_to_client{user="hello"} 12666896893 (11.80 GB)
telemt_user_msgs_from_client{user="hello"} 407579
telemt_user_msgs_to_client{user="hello"} 1674507
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```