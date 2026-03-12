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

# Server Metrics 2026-03-12 07:10:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 33961.1 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98314
telemt_connections_bad_total 2120
telemt_handshake_timeouts_total 2522
telemt_upstream_connect_attempt_total 89098
telemt_upstream_connect_success_total 88769
telemt_upstream_connect_fail_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 89097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 328
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88765
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 894027599 (852.61 MB)
telemt_user_octets_to_client{user="hello"} 26073012731 (24.28 GB)
telemt_user_msgs_from_client{user="hello"} 1323149
telemt_user_msgs_to_client{user="hello"} 2983540
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 33949.2 (9h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39950
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 558
telemt_upstream_connect_attempt_total 37813
telemt_upstream_connect_success_total 37702
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 37811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37698
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 324640841 (309.60 MB)
telemt_user_octets_to_client{user="hello"} 16600362296 (15.46 GB)
telemt_user_msgs_from_client{user="hello"} 645783
telemt_user_msgs_to_client{user="hello"} 5315115
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 33922.7 (9h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59242
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 1144
telemt_upstream_connect_attempt_total 53578
telemt_upstream_connect_success_total 53473
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 53577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53469
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 5495892883 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 31470277095 (29.31 GB)
telemt_user_msgs_from_client{user="hello"} 2787266
telemt_user_msgs_to_client{user="hello"} 5619141
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 33948.1 (9h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64194
telemt_connections_bad_total 13098
telemt_handshake_timeouts_total 931
telemt_upstream_connect_attempt_total 47488
telemt_upstream_connect_success_total 45675
telemt_upstream_connect_fail_total 1813
telemt_upstream_connect_attempts_per_request{bucket="1"} 47488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1813
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45671
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1436875202 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 37094020946 (34.55 GB)
telemt_user_msgs_from_client{user="hello"} 1222552
telemt_user_msgs_to_client{user="hello"} 14790764
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4140.5 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6698
telemt_connections_bad_total 764
telemt_handshake_timeouts_total 146
telemt_upstream_connect_attempt_total 5593
telemt_upstream_connect_success_total 5520
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 5592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5518
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 141886328 (135.31 MB)
telemt_user_octets_to_client{user="hello"} 5050449675 (4.70 GB)
telemt_user_msgs_from_client{user="hello"} 156401
telemt_user_msgs_to_client{user="hello"} 761052
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 33948.8 (9h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62632
telemt_connections_bad_total 1075
telemt_handshake_timeouts_total 343
telemt_upstream_connect_attempt_total 58549
telemt_upstream_connect_success_total 58377
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 58548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58373
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 1011026410 (964.19 MB)
telemt_user_octets_to_client{user="hello"} 51107648133 (47.60 GB)
telemt_user_msgs_from_client{user="hello"} 1451537
telemt_user_msgs_to_client{user="hello"} 6600717
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 31
```