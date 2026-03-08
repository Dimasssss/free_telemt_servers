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

# Server Metrics 2026-03-08 10:17:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 11331.5 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23486
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 152
telemt_upstream_connect_attempt_total 19867
telemt_upstream_connect_success_total 19852
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 19867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1097
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19850
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 687979498 (656.11 MB)
telemt_user_octets_to_client{user="hello"} 12009206232 (11.18 GB)
telemt_user_msgs_from_client{user="hello"} 568447
telemt_user_msgs_to_client{user="hello"} 653075
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 11326.5 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5586
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 5261
telemt_upstream_connect_success_total 5261
telemt_upstream_connect_attempts_per_request{bucket="1"} 5261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5259
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 77092367 (73.52 MB)
telemt_user_octets_to_client{user="hello"} 3725896404 (3.47 GB)
telemt_user_msgs_from_client{user="hello"} 136700
telemt_user_msgs_to_client{user="hello"} 970376
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 11326.3 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4085
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 4002
telemt_upstream_connect_success_total 4002
telemt_upstream_connect_attempts_per_request{bucket="1"} 4002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4000
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 36203078 (34.53 MB)
telemt_user_octets_to_client{user="hello"} 1251333747 (1.17 GB)
telemt_user_msgs_from_client{user="hello"} 43023
telemt_user_msgs_to_client{user="hello"} 205606
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 11326.0 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5195
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 4985
telemt_upstream_connect_success_total 4977
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 4985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4975
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 165276779 (157.62 MB)
telemt_user_octets_to_client{user="hello"} 2307280421 (2.15 GB)
telemt_user_msgs_from_client{user="hello"} 101423
telemt_user_msgs_to_client{user="hello"} 492723
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 11326.5 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6854
telemt_connections_bad_total 2127
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 4650
telemt_upstream_connect_success_total 4650
telemt_upstream_connect_attempts_per_request{bucket="1"} 4650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4648
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 57118353 (54.47 MB)
telemt_user_octets_to_client{user="hello"} 3812343079 (3.55 GB)
telemt_user_msgs_from_client{user="hello"} 110086
telemt_user_msgs_to_client{user="hello"} 499133
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 9
```