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

# Server Metrics 2026-03-08 14:45:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 27382.4 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66221
telemt_connections_bad_total 5023
telemt_handshake_timeouts_total 1026
telemt_upstream_connect_attempt_total 57738
telemt_upstream_connect_success_total 57716
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 57738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57712
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 1615071993 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 30425465785 (28.34 GB)
telemt_user_msgs_from_client{user="hello"} 1397935
telemt_user_msgs_to_client{user="hello"} 1839779
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 27381.5 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14146
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 13648
telemt_upstream_connect_success_total 13647
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13643
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 515572032 (491.69 MB)
telemt_user_octets_to_client{user="hello"} 9603924140 (8.94 GB)
telemt_user_msgs_from_client{user="hello"} 481622
telemt_user_msgs_to_client{user="hello"} 2457876
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 27381.3 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9257
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 8641
telemt_upstream_connect_success_total 8565
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 8641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8561
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 203617508 (194.18 MB)
telemt_user_octets_to_client{user="hello"} 2873320692 (2.68 GB)
telemt_user_msgs_from_client{user="hello"} 146683
telemt_user_msgs_to_client{user="hello"} 489624
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 27381.4 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11828
telemt_connections_bad_total 151
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 11305
telemt_upstream_connect_success_total 11281
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 11305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11277
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 939391219 (895.87 MB)
telemt_user_octets_to_client{user="hello"} 4350058903 (4.05 GB)
telemt_user_msgs_from_client{user="hello"} 449052
telemt_user_msgs_to_client{user="hello"} 975639
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 27381.4 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15560
telemt_connections_bad_total 5048
telemt_handshake_timeouts_total 113
telemt_upstream_connect_attempt_total 10168
telemt_upstream_connect_success_total 10164
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10160
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 224238388 (213.85 MB)
telemt_user_octets_to_client{user="hello"} 8048053066 (7.50 GB)
telemt_user_msgs_from_client{user="hello"} 263751
telemt_user_msgs_to_client{user="hello"} 1117359
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```