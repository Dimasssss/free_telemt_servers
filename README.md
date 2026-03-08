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

# Server Metrics 2026-03-08 21:41:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 52352.7 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113858
telemt_connections_bad_total 5495
telemt_handshake_timeouts_total 1281
telemt_upstream_connect_attempt_total 103291
telemt_upstream_connect_success_total 103253
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 103291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103247
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 2488735605 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 65710245754 (61.20 GB)
telemt_user_msgs_from_client{user="hello"} 2553019
telemt_user_msgs_to_client{user="hello"} 3519245
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 52351.7 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27005
telemt_connections_bad_total 291
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 26111
telemt_upstream_connect_success_total 26104
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26098
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 838208943 (799.38 MB)
telemt_user_octets_to_client{user="hello"} 22654645688 (21.10 GB)
telemt_user_msgs_from_client{user="hello"} 976480
telemt_user_msgs_to_client{user="hello"} 6149179
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 52351.3 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15227
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13822
telemt_upstream_connect_success_total 13746
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13740
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1554126617 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 5662889114 (5.27 GB)
telemt_user_msgs_from_client{user="hello"} 696364
telemt_user_msgs_to_client{user="hello"} 970302
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 52351.2 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20760
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 19907
telemt_upstream_connect_success_total 19867
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 19907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19861
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 1066842692 (1017.42 MB)
telemt_user_octets_to_client{user="hello"} 6542408379 (6.09 GB)
telemt_user_msgs_from_client{user="hello"} 573132
telemt_user_msgs_to_client{user="hello"} 1483502
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 52339.7 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30598
telemt_connections_bad_total 9944
telemt_handshake_timeouts_total 239
telemt_upstream_connect_attempt_total 19923
telemt_upstream_connect_success_total 19916
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19910
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 369416514 (352.30 MB)
telemt_user_octets_to_client{user="hello"} 17335326172 (16.14 GB)
telemt_user_msgs_from_client{user="hello"} 527443
telemt_user_msgs_to_client{user="hello"} 2247256
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```