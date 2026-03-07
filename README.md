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

# Server Metrics 2026-03-07 18:12:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 5229.1 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9899
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 9481
telemt_upstream_connect_success_total 9480
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9478
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 224476936 (214.08 MB)
telemt_user_octets_to_client{user="hello"} 3746788620 (3.49 GB)
telemt_user_msgs_from_client{user="hello"} 225527
telemt_user_msgs_to_client{user="hello"} 628288
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 5228.1 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2702
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 2574
telemt_upstream_connect_success_total 2573
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2571
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 38490481 (36.71 MB)
telemt_user_octets_to_client{user="hello"} 1753631614 (1.63 GB)
telemt_user_msgs_from_client{user="hello"} 64802
telemt_user_msgs_to_client{user="hello"} 501496
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 5227.8 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1005
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 972
telemt_upstream_connect_success_total 972
telemt_upstream_connect_attempts_per_request{bucket="1"} 972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 970
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 5368714 (5.12 MB)
telemt_user_octets_to_client{user="hello"} 305143214 (291.01 MB)
telemt_user_msgs_from_client{user="hello"} 14768
telemt_user_msgs_to_client{user="hello"} 74173
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 5056.3 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1542
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 1465
telemt_upstream_connect_success_total 1461
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1459
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 18504144 (17.65 MB)
telemt_user_octets_to_client{user="hello"} 913912642 (871.58 MB)
telemt_user_msgs_from_client{user="hello"} 26199
telemt_user_msgs_to_client{user="hello"} 247113
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 5228.1 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3215
telemt_connections_bad_total 991
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 2168
telemt_upstream_connect_success_total 2166
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2164
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 55361390 (52.80 MB)
telemt_user_octets_to_client{user="hello"} 1162415806 (1.08 GB)
telemt_user_msgs_from_client{user="hello"} 66321
telemt_user_msgs_to_client{user="hello"} 267152
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```