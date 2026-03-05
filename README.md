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

# Server Metrics 2026-03-05 23:25:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 4239.7 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55438
telemt_connections_bad_total 51892
telemt_handshake_timeouts_total 935
telemt_upstream_connect_attempt_total 2576
telemt_upstream_connect_success_total 2576
telemt_upstream_connect_attempts_per_request{bucket="1"} 2576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2574
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 37749314 (36.00 MB)
telemt_user_octets_to_client{user="hello"} 5017455181 (4.67 GB)
telemt_user_msgs_from_client{user="hello"} 92318
telemt_user_msgs_to_client{user="hello"} 705422
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 4237.6 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359
telemt_connections_bad_total 16
telemt_upstream_connect_attempt_total 344
telemt_upstream_connect_success_total 344
telemt_upstream_connect_attempts_per_request{bucket="1"} 344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 342
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1842000 (1.76 MB)
telemt_user_octets_to_client{user="hello"} 95275443 (90.86 MB)
telemt_user_msgs_from_client{user="hello"} 5068
telemt_user_msgs_to_client{user="hello"} 35296
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 4238.0 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263
telemt_connections_bad_total 26
telemt_upstream_connect_attempt_total 239
telemt_upstream_connect_success_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 237
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 888800 (867.97 KB)
telemt_user_octets_to_client{user="hello"} 45169435 (43.08 MB)
telemt_user_msgs_from_client{user="hello"} 2312
telemt_user_msgs_to_client{user="hello"} 12831
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 4240.7 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523
telemt_connections_bad_total 53
telemt_upstream_connect_attempt_total 461
telemt_upstream_connect_success_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 79
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 459
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 14494617 (13.82 MB)
telemt_user_octets_to_client{user="hello"} 2389749652 (2.23 GB)
telemt_user_msgs_from_client{user="hello"} 41651
telemt_user_msgs_to_client{user="hello"} 412203
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 4240.7 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1426
telemt_connections_bad_total 766
telemt_upstream_connect_attempt_total 646
telemt_upstream_connect_success_total 646
telemt_upstream_connect_attempts_per_request{bucket="1"} 646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 644
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 25535308 (24.35 MB)
telemt_user_octets_to_client{user="hello"} 6862598699 (6.39 GB)
telemt_user_msgs_from_client{user="hello"} 69704
telemt_user_msgs_to_client{user="hello"} 1199356
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```