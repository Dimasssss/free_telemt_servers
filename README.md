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

# Server Metrics 2026-03-06 16:42:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 22835.8 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53884
telemt_connections_bad_total 3111
telemt_handshake_timeouts_total 218
telemt_upstream_connect_attempt_total 46879
telemt_upstream_connect_success_total 46867
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 46879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46863
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 2437017020 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 30599058613 (28.50 GB)
telemt_user_msgs_from_client{user="hello"} 1659119
telemt_user_msgs_to_client{user="hello"} 4834728
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 22834.9 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10137
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 9614
telemt_upstream_connect_success_total 9596
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 9614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9594
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 125667734 (119.85 MB)
telemt_user_octets_to_client{user="hello"} 5532762676 (5.15 GB)
telemt_user_msgs_from_client{user="hello"} 202284
telemt_user_msgs_to_client{user="hello"} 1710405
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 22834.2 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8341
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 8027
telemt_upstream_connect_success_total 8025
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8023
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 120398885 (114.82 MB)
telemt_user_octets_to_client{user="hello"} 4873249887 (4.54 GB)
telemt_user_msgs_from_client{user="hello"} 180595
telemt_user_msgs_to_client{user="hello"} 1146367
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 22833.4 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12034
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 11126
telemt_upstream_connect_success_total 11089
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 11126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11087
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 154883567 (147.71 MB)
telemt_user_octets_to_client{user="hello"} 3784879151 (3.52 GB)
telemt_user_msgs_from_client{user="hello"} 192823
telemt_user_msgs_to_client{user="hello"} 959615
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 22834.8 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16461
telemt_connections_bad_total 5667
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 9948
telemt_upstream_connect_success_total 9948
telemt_upstream_connect_attempts_per_request{bucket="1"} 9948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9946
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 237317095 (226.32 MB)
telemt_user_octets_to_client{user="hello"} 21649499874 (20.16 GB)
telemt_user_msgs_from_client{user="hello"} 394691
telemt_user_msgs_to_client{user="hello"} 3903828
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```