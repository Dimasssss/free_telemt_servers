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

# Server Metrics 2026-03-08 19:37:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 44944.8 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103278
telemt_connections_bad_total 5057
telemt_handshake_timeouts_total 1267
telemt_upstream_connect_attempt_total 93627
telemt_upstream_connect_success_total 93595
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 93627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93589
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 2248691493 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 58347013820 (54.34 GB)
telemt_user_msgs_from_client{user="hello"} 2264316
telemt_user_msgs_to_client{user="hello"} 3177426
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 44944.0 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23893
telemt_connections_bad_total 231
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 23121
telemt_upstream_connect_success_total 23116
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23112
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 752718176 (717.85 MB)
telemt_user_octets_to_client{user="hello"} 21170716503 (19.72 GB)
telemt_user_msgs_from_client{user="hello"} 894496
telemt_user_msgs_to_client{user="hello"} 5758263
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 44943.8 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14147
telemt_connections_bad_total 177
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12810
telemt_upstream_connect_success_total 12734
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12730
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 267233320 (254.85 MB)
telemt_user_octets_to_client{user="hello"} 5131310658 (4.78 GB)
telemt_user_msgs_from_client{user="hello"} 230683
telemt_user_msgs_to_client{user="hello"} 871733
telemt_user_unique_ips_current{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 44943.7 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18350
telemt_connections_bad_total 185
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 17569
telemt_upstream_connect_success_total 17532
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 17569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1297
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17528
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 1041802424 (993.54 MB)
telemt_user_octets_to_client{user="hello"} 6254589146 (5.83 GB)
telemt_user_msgs_from_client{user="hello"} 549343
telemt_user_msgs_to_client{user="hello"} 1403845
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 44943.9 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26561
telemt_connections_bad_total 8486
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 17426
telemt_upstream_connect_success_total 17419
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 17426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17413
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 323983661 (308.97 MB)
telemt_user_octets_to_client{user="hello"} 13732567332 (12.79 GB)
telemt_user_msgs_from_client{user="hello"} 433818
telemt_user_msgs_to_client{user="hello"} 1800497
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```