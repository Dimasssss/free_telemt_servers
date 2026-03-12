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

# Server Metrics 2026-03-12 07:00:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 33346.7 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94310
telemt_connections_bad_total 2120
telemt_handshake_timeouts_total 2395
telemt_upstream_connect_attempt_total 85603
telemt_upstream_connect_success_total 85420
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 85601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85416
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 863515139 (823.51 MB)
telemt_user_octets_to_client{user="hello"} 25326129681 (23.59 GB)
telemt_user_msgs_from_client{user="hello"} 1274524
telemt_user_msgs_to_client{user="hello"} 2892761
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 33335.0 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38600
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 557
telemt_upstream_connect_attempt_total 36489
telemt_upstream_connect_success_total 36433
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 36488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36429
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 318978945 (304.20 MB)
telemt_user_octets_to_client{user="hello"} 16394685300 (15.27 GB)
telemt_user_msgs_from_client{user="hello"} 631921
telemt_user_msgs_to_client{user="hello"} 5222336
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 33308.4 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57287
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 1141
telemt_upstream_connect_attempt_total 51665
telemt_upstream_connect_success_total 51620
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 51665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51616
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 5470724610 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 31190977931 (29.05 GB)
telemt_user_msgs_from_client{user="hello"} 2766739
telemt_user_msgs_to_client{user="hello"} 5551207
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 33334.2 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62687
telemt_connections_bad_total 13098
telemt_handshake_timeouts_total 924
telemt_upstream_connect_attempt_total 46037
telemt_upstream_connect_success_total 44259
telemt_upstream_connect_fail_total 1777
telemt_upstream_connect_attempts_per_request{bucket="1"} 46036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1777
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44255
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 1427518729 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 35910015766 (33.44 GB)
telemt_user_msgs_from_client{user="hello"} 1198473
telemt_user_msgs_to_client{user="hello"} 14423655
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3526.3 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5369
telemt_connections_bad_total 632
telemt_handshake_timeouts_total 141
telemt_upstream_connect_attempt_total 4431
telemt_upstream_connect_success_total 4386
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 4431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4384
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 138005215 (131.61 MB)
telemt_user_octets_to_client{user="hello"} 4958963554 (4.62 GB)
telemt_user_msgs_from_client{user="hello"} 145910
telemt_user_msgs_to_client{user="hello"} 731048
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 33334.7 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60237
telemt_connections_bad_total 1032
telemt_handshake_timeouts_total 332
telemt_upstream_connect_attempt_total 56257
telemt_upstream_connect_success_total 56158
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 56256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9258
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56154
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 996494371 (950.33 MB)
telemt_user_octets_to_client{user="hello"} 50677984085 (47.20 GB)
telemt_user_msgs_from_client{user="hello"} 1418674
telemt_user_msgs_to_client{user="hello"} 6505263
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 42
```