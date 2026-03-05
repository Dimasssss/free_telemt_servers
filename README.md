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

# Server Metrics 2026-03-05 20:46:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.0

telemt_uptime_seconds 12695.8 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42561
telemt_connections_bad_total 26252
telemt_handshake_timeouts_total 2959
telemt_upstream_connect_attempt_total 12852
telemt_upstream_connect_success_total 12850
telemt_upstream_connect_attempts_per_request{bucket="1"} 12848
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12848
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 243855955 (232.56 MB)
telemt_user_octets_to_client{user="hello"} 6909475895 (6.43 GB)
telemt_user_msgs_from_client{user="hello"} 376045
telemt_user_msgs_to_client{user="hello"} 1193789
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.0

telemt_uptime_seconds 12698.5 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3864
telemt_connections_bad_total 512
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3191
telemt_upstream_connect_success_total 3191
telemt_upstream_connect_attempts_per_request{bucket="1"} 3191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3189
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 178055353 (169.81 MB)
telemt_user_octets_to_client{user="hello"} 2060478175 (1.92 GB)
telemt_user_msgs_from_client{user="hello"} 133195
telemt_user_msgs_to_client{user="hello"} 559052
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.0

telemt_uptime_seconds 12696.5 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4087
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 74
telemt_upstream_connect_attempt_total 3776
telemt_upstream_connect_success_total 3776
telemt_upstream_connect_attempts_per_request{bucket="1"} 3776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3774
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 43575284 (41.56 MB)
telemt_user_octets_to_client{user="hello"} 3446036120 (3.21 GB)
telemt_user_msgs_from_client{user="hello"} 86145
telemt_user_msgs_to_client{user="hello"} 687413
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.0

telemt_uptime_seconds 12694.0 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6758
telemt_connections_bad_total 88
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 6523
telemt_upstream_connect_success_total 6517
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6513
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 425
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6515
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 106775990 (101.83 MB)
telemt_user_octets_to_client{user="hello"} 2867856551 (2.67 GB)
telemt_user_msgs_from_client{user="hello"} 128856
telemt_user_msgs_to_client{user="hello"} 670793
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.0

telemt_uptime_seconds 12695.9 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6293
telemt_connections_bad_total 2445
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 3727
telemt_upstream_connect_success_total 3726
telemt_upstream_connect_attempts_per_request{bucket="1"} 3725
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3724
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 71464619 (68.15 MB)
telemt_user_octets_to_client{user="hello"} 2189132046 (2.04 GB)
telemt_user_msgs_from_client{user="hello"} 117906
telemt_user_msgs_to_client{user="hello"} 483437
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```