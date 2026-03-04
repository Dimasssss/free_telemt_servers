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

# Server Metrics 2026-03-04 22:00:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 38043.0 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62544
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 1544
telemt_upstream_connect_attempt_total 56152
telemt_upstream_connect_success_total 56138
telemt_upstream_connect_attempts_per_request{bucket="1"} 56124
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56134
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 2271503615 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 43493953967 (40.51 GB)
telemt_user_msgs_from_client{user="hello"} 1872895
telemt_user_msgs_to_client{user="hello"} 6935475
telemt_user_unique_ips_current{user="hello"} 7
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 38045.8 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11817
telemt_connections_bad_total 135
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 11170
telemt_upstream_connect_success_total 11168
telemt_upstream_connect_attempts_per_request{bucket="1"} 11166
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11164
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 1053943883 (1005.12 MB)
telemt_user_octets_to_client{user="hello"} 11029066839 (10.27 GB)
telemt_user_msgs_from_client{user="hello"} 643705
telemt_user_msgs_to_client{user="hello"} 3717689
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 38044.2 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7392
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 7046
telemt_upstream_connect_success_total 7046
telemt_upstream_connect_attempts_per_request{bucket="1"} 7046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7042
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 306094901 (291.91 MB)
telemt_user_octets_to_client{user="hello"} 5119942137 (4.77 GB)
telemt_user_msgs_from_client{user="hello"} 262965
telemt_user_msgs_to_client{user="hello"} 1098999
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 38041.9 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13061
telemt_connections_bad_total 625
telemt_handshake_timeouts_total 62
telemt_upstream_connect_attempt_total 11421
telemt_upstream_connect_success_total 11417
telemt_upstream_connect_attempts_per_request{bucket="1"} 11413
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11413
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 360338853 (343.65 MB)
telemt_user_octets_to_client{user="hello"} 4992822309 (4.65 GB)
telemt_user_msgs_from_client{user="hello"} 276820
telemt_user_msgs_to_client{user="hello"} 1253865
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 38043.7 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15583
telemt_connections_bad_total 6818
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 8470
telemt_upstream_connect_success_total 8466
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8464
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8462
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 499290995 (476.16 MB)
telemt_user_octets_to_client{user="hello"} 18167018507 (16.92 GB)
telemt_user_msgs_from_client{user="hello"} 510189
telemt_user_msgs_to_client{user="hello"} 3480646
telemt_user_unique_ips_current{user="hello"} 1
```