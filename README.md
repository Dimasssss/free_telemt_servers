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

# Server Metrics 2026-03-08 18:56:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 42479.9 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98212
telemt_connections_bad_total 5049
telemt_handshake_timeouts_total 1252
telemt_upstream_connect_attempt_total 88694
telemt_upstream_connect_success_total 88664
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 88694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88658
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 2160986792 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 54607075418 (50.86 GB)
telemt_user_msgs_from_client{user="hello"} 2145618
telemt_user_msgs_to_client{user="hello"} 3013627
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 42479.4 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22244
telemt_connections_bad_total 201
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 21534
telemt_upstream_connect_success_total 21529
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 21534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21525
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 735601810 (701.52 MB)
telemt_user_octets_to_client{user="hello"} 19989699430 (18.62 GB)
telemt_user_msgs_from_client{user="hello"} 855456
telemt_user_msgs_to_client{user="hello"} 5486137
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 42478.8 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13659
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12332
telemt_upstream_connect_success_total 12256
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12252
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 241475616 (230.29 MB)
telemt_user_octets_to_client{user="hello"} 4223993070 (3.93 GB)
telemt_user_msgs_from_client{user="hello"} 207365
telemt_user_msgs_to_client{user="hello"} 756855
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 42478.8 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17628
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 16868
telemt_upstream_connect_success_total 16832
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 16868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16828
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1039064076 (990.93 MB)
telemt_user_octets_to_client{user="hello"} 5985949795 (5.57 GB)
telemt_user_msgs_from_client{user="hello"} 542037
telemt_user_msgs_to_client{user="hello"} 1353804
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 42479.0 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25039
telemt_connections_bad_total 8048
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 16373
telemt_upstream_connect_success_total 16366
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16360
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 309673480 (295.33 MB)
telemt_user_octets_to_client{user="hello"} 12396733982 (11.55 GB)
telemt_user_msgs_from_client{user="hello"} 399388
telemt_user_msgs_to_client{user="hello"} 1635077
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```