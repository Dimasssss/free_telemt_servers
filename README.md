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

# Server Metrics 2026-03-11 13:04:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 81506.8 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261668
telemt_connections_bad_total 3637
telemt_handshake_timeouts_total 4668
telemt_upstream_connect_attempt_total 241768
telemt_upstream_connect_success_total 241694
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 241768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 221262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 241686
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 4813227272 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 127210708159 (118.47 GB)
telemt_user_msgs_from_client{user="hello"} 5435836
telemt_user_msgs_to_client{user="hello"} 9984038
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 81506.2 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101919
telemt_connections_bad_total 906
telemt_handshake_timeouts_total 3328
telemt_upstream_connect_attempt_total 93213
telemt_upstream_connect_success_total 93195
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 93213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 307
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93187
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 5212927283 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 62352964382 (58.07 GB)
telemt_user_msgs_from_client{user="hello"} 3511062
telemt_user_msgs_to_client{user="hello"} 17492569
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 81506.0 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141503
telemt_connections_bad_total 1104
telemt_handshake_timeouts_total 6782
telemt_upstream_connect_attempt_total 125853
telemt_upstream_connect_success_total 125839
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 125853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 125831
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 12511593903 (11.65 GB)
telemt_user_octets_to_client{user="hello"} 101797953584 (94.81 GB)
telemt_user_msgs_from_client{user="hello"} 6329597
telemt_user_msgs_to_client{user="hello"} 21288364
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 81504.8 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155372
telemt_connections_bad_total 1713
telemt_handshake_timeouts_total 1896
telemt_upstream_connect_attempt_total 145405
telemt_upstream_connect_success_total 145064
telemt_upstream_connect_fail_total 341
telemt_upstream_connect_attempts_per_request{bucket="1"} 145405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 125950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 78
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 386
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 341
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 145056
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 8437238402 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 108135762312 (100.71 GB)
telemt_user_msgs_from_client{user="hello"} 5108062
telemt_user_msgs_to_client{user="hello"} 31854756
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 81506.1 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231259
telemt_connections_bad_total 18165
telemt_handshake_timeouts_total 4653
telemt_upstream_connect_attempt_total 187162
telemt_upstream_connect_success_total 186662
telemt_upstream_connect_fail_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 187162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 161327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 500
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 186654
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 4741650320 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 153300664723 (142.77 GB)
telemt_user_msgs_from_client{user="hello"} 4471468
telemt_user_msgs_to_client{user="hello"} 21164256
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 60475.6 (16h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429
telemt_connections_bad_total 407
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```