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

# Server Metrics 2026-03-08 11:40:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 16276.4 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34458
telemt_connections_bad_total 2571
telemt_handshake_timeouts_total 210
telemt_upstream_connect_attempt_total 30318
telemt_upstream_connect_success_total 30299
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 30318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30297
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 1010862074 (964.03 MB)
telemt_user_octets_to_client{user="hello"} 16759400728 (15.61 GB)
telemt_user_msgs_from_client{user="hello"} 810585
telemt_user_msgs_to_client{user="hello"} 979587
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 16275.9 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8515
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 8153
telemt_upstream_connect_success_total 8153
telemt_upstream_connect_attempts_per_request{bucket="1"} 8153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8151
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 122706163 (117.02 MB)
telemt_user_octets_to_client{user="hello"} 5482891007 (5.11 GB)
telemt_user_msgs_from_client{user="hello"} 216542
telemt_user_msgs_to_client{user="hello"} 1412987
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 16289.7 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5244
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 5103
telemt_upstream_connect_success_total 5074
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 5103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5072
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 119526595 (113.99 MB)
telemt_user_octets_to_client{user="hello"} 1429300939 (1.33 GB)
telemt_user_msgs_from_client{user="hello"} 84359
telemt_user_msgs_to_client{user="hello"} 249310
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 16275.4 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7577
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 7235
telemt_upstream_connect_success_total 7222
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 7235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7220
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 883286232 (842.37 MB)
telemt_user_octets_to_client{user="hello"} 2886398733 (2.69 GB)
telemt_user_msgs_from_client{user="hello"} 377134
telemt_user_msgs_to_client{user="hello"} 632791
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 16275.7 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10015
telemt_connections_bad_total 3027
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 6834
telemt_upstream_connect_success_total 6833
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6831
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 116157367 (110.78 MB)
telemt_user_octets_to_client{user="hello"} 6216406243 (5.79 GB)
telemt_user_msgs_from_client{user="hello"} 180591
telemt_user_msgs_to_client{user="hello"} 858798
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```