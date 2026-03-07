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

# Server Metrics 2026-03-07 07:05:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 46614.9 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50800
telemt_connections_bad_total 255
telemt_handshake_timeouts_total 683
telemt_upstream_connect_attempt_total 47326
telemt_upstream_connect_success_total 47313
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 47326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47307
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 2460577577 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 53717405413 (50.03 GB)
telemt_user_msgs_from_client{user="hello"} 1846975
telemt_user_msgs_to_client{user="hello"} 8328802
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 46613.6 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10355
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 9525
telemt_upstream_connect_success_total 9521
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 9525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9515
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 307218068 (292.99 MB)
telemt_user_octets_to_client{user="hello"} 8806805246 (8.20 GB)
telemt_user_msgs_from_client{user="hello"} 344172
telemt_user_msgs_to_client{user="hello"} 2347974
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 46613.5 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5761
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 5352
telemt_upstream_connect_success_total 5352
telemt_upstream_connect_attempts_per_request{bucket="1"} 5352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 470
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5346
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 91157224 (86.93 MB)
telemt_user_octets_to_client{user="hello"} 2959334932 (2.76 GB)
telemt_user_msgs_from_client{user="hello"} 116822
telemt_user_msgs_to_client{user="hello"} 661481
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 46613.6 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6912
telemt_connections_bad_total 215
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 6607
telemt_upstream_connect_success_total 6600
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 6607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6594
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 138120000 (131.72 MB)
telemt_user_octets_to_client{user="hello"} 2210081042 (2.06 GB)
telemt_user_msgs_from_client{user="hello"} 131142
telemt_user_msgs_to_client{user="hello"} 603968
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 46613.9 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20500
telemt_connections_bad_total 9374
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 10785
telemt_upstream_connect_success_total 10783
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 10785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10777
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 378914413 (361.36 MB)
telemt_user_octets_to_client{user="hello"} 16146920224 (15.04 GB)
telemt_user_msgs_from_client{user="hello"} 391601
telemt_user_msgs_to_client{user="hello"} 3151700
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 5
```