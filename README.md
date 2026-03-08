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

# Server Metrics 2026-03-08 12:57:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 20908.8 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46153
telemt_connections_bad_total 2649
telemt_handshake_timeouts_total 283
telemt_upstream_connect_attempt_total 41301
telemt_upstream_connect_success_total 41280
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41276
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 1269656671 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 20298126796 (18.90 GB)
telemt_user_msgs_from_client{user="hello"} 1018926
telemt_user_msgs_to_client{user="hello"} 1245757
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 20908.1 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10840
telemt_connections_bad_total 86
telemt_handshake_timeouts_total 106
telemt_upstream_connect_attempt_total 10436
telemt_upstream_connect_success_total 10435
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10433
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 425071298 (405.38 MB)
telemt_user_octets_to_client{user="hello"} 7060865334 (6.58 GB)
telemt_user_msgs_from_client{user="hello"} 369413
telemt_user_msgs_to_client{user="hello"} 1810338
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 20907.8 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7356
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 6940
telemt_upstream_connect_success_total 6865
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 6940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6861
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 162871509 (155.33 MB)
telemt_user_octets_to_client{user="hello"} 1915141409 (1.78 GB)
telemt_user_msgs_from_client{user="hello"} 107845
telemt_user_msgs_to_client{user="hello"} 338417
telemt_user_unique_ips_current{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 20907.6 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9373
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 8968
telemt_upstream_connect_success_total 8950
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 8968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 557
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8948
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 897179408 (855.62 MB)
telemt_user_octets_to_client{user="hello"} 3539145454 (3.30 GB)
telemt_user_msgs_from_client{user="hello"} 402575
telemt_user_msgs_to_client{user="hello"} 763442
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 20908.0 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12633
telemt_connections_bad_total 3887
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 8522
telemt_upstream_connect_success_total 8519
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 8522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8515
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 211815192 (202.00 MB)
telemt_user_octets_to_client{user="hello"} 7537756855 (7.02 GB)
telemt_user_msgs_from_client{user="hello"} 234885
telemt_user_msgs_to_client{user="hello"} 1026875
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```