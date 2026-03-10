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

# Server Metrics 2026-03-10 13:12:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 136359.4 (37h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307667
telemt_connections_bad_total 3471
telemt_handshake_timeouts_total 3135
telemt_upstream_connect_attempt_total 288240
telemt_upstream_connect_success_total 288086
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 288240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 266448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 288072
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 6725491884 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 190903244813 (177.79 GB)
telemt_user_msgs_from_client{user="hello"} 6942857
telemt_user_msgs_to_client{user="hello"} 11291859
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 136358.2 (37h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94831
telemt_connections_bad_total 3271
telemt_handshake_timeouts_total 1279
telemt_upstream_connect_attempt_total 85400
telemt_upstream_connect_success_total 85356
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 85400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 427
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85342
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 2802301041 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 35824191307 (33.36 GB)
telemt_user_msgs_from_client{user="hello"} 2258455
telemt_user_msgs_to_client{user="hello"} 10403186
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 136358.7 (37h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134711
telemt_connections_bad_total 1227
telemt_handshake_timeouts_total 6398
telemt_upstream_connect_attempt_total 100205
telemt_upstream_connect_success_total 100202
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 100205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100188
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 6644634845 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 67974597219 (63.31 GB)
telemt_user_msgs_from_client{user="hello"} 4461708
telemt_user_msgs_to_client{user="hello"} 11393605
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 136353.3 (37h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139734
telemt_connections_bad_total 1056
telemt_handshake_timeouts_total 2929
telemt_upstream_connect_attempt_total 128989
telemt_upstream_connect_success_total 128702
telemt_upstream_connect_fail_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 128989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 287
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 128688
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 4714597811 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 88790991865 (82.69 GB)
telemt_user_msgs_from_client{user="hello"} 3674947
telemt_user_msgs_to_client{user="hello"} 20236831
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 136358.7 (37h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205999
telemt_connections_bad_total 30461
telemt_handshake_timeouts_total 5578
telemt_upstream_connect_attempt_total 161309
telemt_upstream_connect_success_total 160347
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 161309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 138822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 160333
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 3478663998 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 117175654392 (109.13 GB)
telemt_user_msgs_from_client{user="hello"} 3693788
telemt_user_msgs_to_client{user="hello"} 15979482
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```