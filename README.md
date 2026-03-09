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

# Server Metrics 2026-03-09 06:41:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 26518.2 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27164
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 568
telemt_upstream_connect_attempt_total 25009
telemt_upstream_connect_success_total 25001
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 25009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24997
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 231449825 (220.73 MB)
telemt_user_octets_to_client{user="hello"} 14077571490 (13.11 GB)
telemt_user_msgs_from_client{user="hello"} 475386
telemt_user_msgs_to_client{user="hello"} 725102
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 26516.4 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3740
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 75
telemt_upstream_connect_attempt_total 3530
telemt_upstream_connect_success_total 3530
telemt_upstream_connect_attempts_per_request{bucket="1"} 3530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 245
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3526
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 51440770 (49.06 MB)
telemt_user_octets_to_client{user="hello"} 3159409785 (2.94 GB)
telemt_user_msgs_from_client{user="hello"} 112496
telemt_user_msgs_to_client{user="hello"} 611043
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 26516.8 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2026
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1891
telemt_upstream_connect_success_total 1891
telemt_upstream_connect_attempts_per_request{bucket="1"} 1891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1887
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 908152457 (866.08 MB)
telemt_user_octets_to_client{user="hello"} 1148883159 (1.07 GB)
telemt_user_msgs_from_client{user="hello"} 350662
telemt_user_msgs_to_client{user="hello"} 230304
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 26511.7 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4651
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 3733
telemt_upstream_connect_success_total 3731
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3727
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 129348107 (123.36 MB)
telemt_user_octets_to_client{user="hello"} 2791307635 (2.60 GB)
telemt_user_msgs_from_client{user="hello"} 80663
telemt_user_msgs_to_client{user="hello"} 605151
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 26517.2 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9606
telemt_connections_bad_total 5248
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 4129
telemt_upstream_connect_success_total 4129
telemt_upstream_connect_attempts_per_request{bucket="1"} 4129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4125
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 57665413 (54.99 MB)
telemt_user_octets_to_client{user="hello"} 2877016417 (2.68 GB)
telemt_user_msgs_from_client{user="hello"} 85504
telemt_user_msgs_to_client{user="hello"} 393632
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 7
```