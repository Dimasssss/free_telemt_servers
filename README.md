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

# Server Metrics 2026-03-09 05:55:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 23765.6 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23103
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 560
telemt_upstream_connect_attempt_total 21139
telemt_upstream_connect_success_total 21132
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 21139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21130
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 195611420 (186.55 MB)
telemt_user_octets_to_client{user="hello"} 11814438325 (11.00 GB)
telemt_user_msgs_from_client{user="hello"} 389991
telemt_user_msgs_to_client{user="hello"} 578689
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 23763.8 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2973
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 2789
telemt_upstream_connect_success_total 2789
telemt_upstream_connect_attempts_per_request{bucket="1"} 2789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2785
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 45533280 (43.42 MB)
telemt_user_octets_to_client{user="hello"} 2900161000 (2.70 GB)
telemt_user_msgs_from_client{user="hello"} 98684
telemt_user_msgs_to_client{user="hello"} 547567
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 23764.2 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1676
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1563
telemt_upstream_connect_success_total 1563
telemt_upstream_connect_attempts_per_request{bucket="1"} 1563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1559
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 907148704 (865.12 MB)
telemt_user_octets_to_client{user="hello"} 1112802151 (1.04 GB)
telemt_user_msgs_from_client{user="hello"} 347699
telemt_user_msgs_to_client{user="hello"} 220003
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 23759.0 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3404
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 2852
telemt_upstream_connect_success_total 2851
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2847
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 123206797 (117.50 MB)
telemt_user_octets_to_client{user="hello"} 2046323013 (1.91 GB)
telemt_user_msgs_from_client{user="hello"} 65853
telemt_user_msgs_to_client{user="hello"} 449529
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 23764.5 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8118
telemt_connections_bad_total 4756
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 3154
telemt_upstream_connect_success_total 3154
telemt_upstream_connect_attempts_per_request{bucket="1"} 3154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3152
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 38045955 (36.28 MB)
telemt_user_octets_to_client{user="hello"} 2576700552 (2.40 GB)
telemt_user_msgs_from_client{user="hello"} 65342
telemt_user_msgs_to_client{user="hello"} 327266
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```