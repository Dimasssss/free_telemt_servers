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

# Server Metrics 2026-03-11 19:09:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 7733.4 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30458
telemt_connections_bad_total 1764
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 27409
telemt_upstream_connect_success_total 27403
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 27409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27401
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 692056102 (660.00 MB)
telemt_user_octets_to_client{user="hello"} 16954586584 (15.79 GB)
telemt_user_msgs_from_client{user="hello"} 686344
telemt_user_msgs_to_client{user="hello"} 1349878
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 7721.5 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14537
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 242
telemt_upstream_connect_attempt_total 13172
telemt_upstream_connect_success_total 13171
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 276
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13169
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 192315372 (183.41 MB)
telemt_user_octets_to_client{user="hello"} 8236937999 (7.67 GB)
telemt_user_msgs_from_client{user="hello"} 306482
telemt_user_msgs_to_client{user="hello"} 3136497
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 7741.3 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17048
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 133
telemt_upstream_connect_attempt_total 15982
telemt_upstream_connect_success_total 15980
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 15982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15978
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 175642016 (167.51 MB)
telemt_user_octets_to_client{user="hello"} 6547440812 (6.10 GB)
telemt_user_msgs_from_client{user="hello"} 326587
telemt_user_msgs_to_client{user="hello"} 1821667
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 7737.0 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17680
telemt_connections_bad_total 1129
telemt_handshake_timeouts_total 360
telemt_upstream_connect_attempt_total 15417
telemt_upstream_connect_success_total 15374
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 15417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15372
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 519714958 (495.64 MB)
telemt_user_octets_to_client{user="hello"} 9677396359 (9.01 GB)
telemt_user_msgs_from_client{user="hello"} 397375
telemt_user_msgs_to_client{user="hello"} 2386693
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 7745.0 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19304
telemt_connections_bad_total 1515
telemt_handshake_timeouts_total 147
telemt_upstream_connect_attempt_total 16932
telemt_upstream_connect_success_total 16931
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16929
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 296895031 (283.14 MB)
telemt_user_octets_to_client{user="hello"} 5439798489 (5.07 GB)
telemt_user_msgs_from_client{user="hello"} 355967
telemt_user_msgs_to_client{user="hello"} 1650148
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 82351.4 (22h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518
telemt_connections_bad_total 490
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```