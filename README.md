# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-11 21:27:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16017.1 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52826
telemt_connections_bad_total 2581
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 47890
telemt_upstream_connect_success_total 47878
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 47890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47876
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 1494436795 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 28077464282 (26.15 GB)
telemt_user_msgs_from_client{user="hello"} 1310502
telemt_user_msgs_to_client{user="hello"} 2734169
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16005.4 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24448
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 262
telemt_upstream_connect_attempt_total 22646
telemt_upstream_connect_success_total 22607
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 22646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22605
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 266947010 (254.58 MB)
telemt_user_octets_to_client{user="hello"} 11480171255 (10.69 GB)
telemt_user_msgs_from_client{user="hello"} 468367
telemt_user_msgs_to_client{user="hello"} 4720816
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 16025.4 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30195
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 28325
telemt_upstream_connect_success_total 28323
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 28325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28321
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 327853208 (312.67 MB)
telemt_user_octets_to_client{user="hello"} 10972696112 (10.22 GB)
telemt_user_msgs_from_client{user="hello"} 552580
telemt_user_msgs_to_client{user="hello"} 2728515
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16020.7 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32106
telemt_connections_bad_total 1812
telemt_handshake_timeouts_total 481
telemt_upstream_connect_attempt_total 28409
telemt_upstream_connect_success_total 28327
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28325
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 726838485 (693.17 MB)
telemt_user_octets_to_client{user="hello"} 18190149487 (16.94 GB)
telemt_user_msgs_from_client{user="hello"} 674229
telemt_user_msgs_to_client{user="hello"} 5863589
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16028.8 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35324
telemt_connections_bad_total 3075
telemt_handshake_timeouts_total 186
telemt_upstream_connect_attempt_total 31039
telemt_upstream_connect_success_total 31036
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 31039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31034
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 540575039 (515.53 MB)
telemt_user_octets_to_client{user="hello"} 11456479128 (10.67 GB)
telemt_user_msgs_from_client{user="hello"} 688626
telemt_user_msgs_to_client{user="hello"} 4167425
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 90635.2 (25h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3486
telemt_connections_bad_total 643
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 2747
telemt_upstream_connect_success_total 2747
telemt_upstream_connect_attempts_per_request{bucket="1"} 2747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 421
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2737
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 29694494 (28.32 MB)
telemt_user_octets_to_client{user="hello"} 2628919778 (2.45 GB)
telemt_user_msgs_from_client{user="hello"} 79427
telemt_user_msgs_to_client{user="hello"} 317527
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 6
```