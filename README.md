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

# Server Metrics 2026-03-10 15:30:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3878.5 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18937
telemt_connections_bad_total 264
telemt_handshake_timeouts_total 358
telemt_upstream_connect_attempt_total 17199
telemt_upstream_connect_success_total 17196
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 17199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17194
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 263378231 (251.18 MB)
telemt_user_octets_to_client{user="hello"} 9627903501 (8.97 GB)
telemt_user_msgs_from_client{user="hello"} 364240
telemt_user_msgs_to_client{user="hello"} 672507
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3877.7 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5643
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 157
telemt_upstream_connect_attempt_total 5139
telemt_upstream_connect_success_total 5139
telemt_upstream_connect_attempts_per_request{bucket="1"} 5139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5137
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 100751630 (96.08 MB)
telemt_user_octets_to_client{user="hello"} 4243623811 (3.95 GB)
telemt_user_msgs_from_client{user="hello"} 142232
telemt_user_msgs_to_client{user="hello"} 1272122
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3877.4 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9053
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 318
telemt_upstream_connect_attempt_total 8338
telemt_upstream_connect_success_total 8338
telemt_upstream_connect_attempts_per_request{bucket="1"} 8338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8336
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 61516412 (58.67 MB)
telemt_user_octets_to_client{user="hello"} 2597987674 (2.42 GB)
telemt_user_msgs_from_client{user="hello"} 132540
telemt_user_msgs_to_client{user="hello"} 681343
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3876.4 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8927
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 125
telemt_upstream_connect_attempt_total 8520
telemt_upstream_connect_success_total 8497
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 8520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8495
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 154911162 (147.73 MB)
telemt_user_octets_to_client{user="hello"} 7953557920 (7.41 GB)
telemt_user_msgs_from_client{user="hello"} 179527
telemt_user_msgs_to_client{user="hello"} 1212602
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3877.8 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12736
telemt_connections_bad_total 940
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 11046
telemt_upstream_connect_success_total 11044
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 11046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11042
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 879342823 (838.61 MB)
telemt_user_octets_to_client{user="hello"} 7727913800 (7.20 GB)
telemt_user_msgs_from_client{user="hello"} 469757
telemt_user_msgs_to_client{user="hello"} 828321
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 23
```