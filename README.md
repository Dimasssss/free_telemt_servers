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

# Server Metrics 2026-03-10 17:38:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11568.8 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47172
telemt_connections_bad_total 712
telemt_handshake_timeouts_total 1379
telemt_upstream_connect_attempt_total 42511
telemt_upstream_connect_success_total 42501
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 42511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42499
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 1342190090 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 31435329461 (29.28 GB)
telemt_user_msgs_from_client{user="hello"} 1212131
telemt_user_msgs_to_client{user="hello"} 2403608
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 11568.1 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17041
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 319
telemt_upstream_connect_attempt_total 15495
telemt_upstream_connect_success_total 15492
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 15495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15490
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 464772095 (443.24 MB)
telemt_user_octets_to_client{user="hello"} 8276718832 (7.71 GB)
telemt_user_msgs_from_client{user="hello"} 450988
telemt_user_msgs_to_client{user="hello"} 2593521
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 11567.6 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26414
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 2351
telemt_upstream_connect_attempt_total 22440
telemt_upstream_connect_success_total 22440
telemt_upstream_connect_attempts_per_request{bucket="1"} 22440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22438
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 206627648 (197.06 MB)
telemt_user_octets_to_client{user="hello"} 14018079154 (13.06 GB)
telemt_user_msgs_from_client{user="hello"} 443162
telemt_user_msgs_to_client{user="hello"} 2606804
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 11566.6 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26018
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 249
telemt_upstream_connect_attempt_total 24822
telemt_upstream_connect_success_total 24754
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 24822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24752
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 355611979 (339.14 MB)
telemt_user_octets_to_client{user="hello"} 23994142321 (22.35 GB)
telemt_user_msgs_from_client{user="hello"} 520765
telemt_user_msgs_to_client{user="hello"} 4209469
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11567.9 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35534
telemt_connections_bad_total 2317
telemt_handshake_timeouts_total 622
telemt_upstream_connect_attempt_total 31158
telemt_upstream_connect_success_total 30921
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 31158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30919
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1286838345 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 19682392301 (18.33 GB)
telemt_user_msgs_from_client{user="hello"} 936057
telemt_user_msgs_to_client{user="hello"} 2874778
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 28
```