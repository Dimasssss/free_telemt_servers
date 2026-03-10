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

# Server Metrics 2026-03-10 03:08:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 100102.6 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181192
telemt_connections_bad_total 2365
telemt_handshake_timeouts_total 1770
telemt_upstream_connect_attempt_total 169924
telemt_upstream_connect_success_total 169869
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 169924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 169859
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 4967236263 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 103278465167 (96.19 GB)
telemt_user_msgs_from_client{user="hello"} 4489369
telemt_user_msgs_to_client{user="hello"} 6540234
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 100101.8 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56742
telemt_connections_bad_total 3069
telemt_handshake_timeouts_total 862
telemt_upstream_connect_attempt_total 49911
telemt_upstream_connect_success_total 49870
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 49911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49860
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 2144753941 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 24067610117 (22.41 GB)
telemt_user_msgs_from_client{user="hello"} 1565511
telemt_user_msgs_to_client{user="hello"} 6924340
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 100102.2 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70199
telemt_connections_bad_total 931
telemt_handshake_timeouts_total 3882
telemt_upstream_connect_attempt_total 53684
telemt_upstream_connect_success_total 53682
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 53684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53672
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 6047184022 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 54923445475 (51.15 GB)
telemt_user_msgs_from_client{user="hello"} 3439920
telemt_user_msgs_to_client{user="hello"} 8122235
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 100097.0 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76092
telemt_connections_bad_total 531
telemt_handshake_timeouts_total 1055
telemt_upstream_connect_attempt_total 70395
telemt_upstream_connect_success_total 70229
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 70395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70219
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 2306454901 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 48721245394 (45.38 GB)
telemt_user_msgs_from_client{user="hello"} 1900846
telemt_user_msgs_to_client{user="hello"} 11671416
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 100102.5 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125711
telemt_connections_bad_total 22235
telemt_handshake_timeouts_total 3018
telemt_upstream_connect_attempt_total 95277
telemt_upstream_connect_success_total 95265
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 95277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95255
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 1592687980 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 87092069468 (81.11 GB)
telemt_user_msgs_from_client{user="hello"} 2153096
telemt_user_msgs_to_client{user="hello"} 11420059
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 14
```