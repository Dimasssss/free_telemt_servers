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

# Server Metrics 2026-03-10 19:16:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17397.5 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67638
telemt_connections_bad_total 2169
telemt_handshake_timeouts_total 1927
telemt_upstream_connect_attempt_total 60280
telemt_upstream_connect_success_total 60268
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 60280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60266
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1938025115 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 44149522348 (41.12 GB)
telemt_user_msgs_from_client{user="hello"} 1764981
telemt_user_msgs_to_client{user="hello"} 3317818
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 17396.9 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25730
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 430
telemt_upstream_connect_attempt_total 23518
telemt_upstream_connect_success_total 23511
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 23518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23509
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 789216345 (752.66 MB)
telemt_user_octets_to_client{user="hello"} 15090072255 (14.05 GB)
telemt_user_msgs_from_client{user="hello"} 751631
telemt_user_msgs_to_client{user="hello"} 4689457
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 17396.7 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39592
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 3540
telemt_upstream_connect_attempt_total 33525
telemt_upstream_connect_success_total 33525
telemt_upstream_connect_attempts_per_request{bucket="1"} 33525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33523
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 530776944 (506.19 MB)
telemt_user_octets_to_client{user="hello"} 33393359247 (31.10 GB)
telemt_user_msgs_from_client{user="hello"} 735818
telemt_user_msgs_to_client{user="hello"} 4913791
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 17395.5 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37022
telemt_connections_bad_total 62
telemt_handshake_timeouts_total 271
telemt_upstream_connect_attempt_total 35446
telemt_upstream_connect_success_total 35344
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 35446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35342
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 597604423 (569.92 MB)
telemt_user_octets_to_client{user="hello"} 28939464565 (26.95 GB)
telemt_user_msgs_from_client{user="hello"} 752939
telemt_user_msgs_to_client{user="hello"} 5313322
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 17396.7 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54595
telemt_connections_bad_total 4870
telemt_handshake_timeouts_total 1204
telemt_upstream_connect_attempt_total 46256
telemt_upstream_connect_success_total 46014
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 46256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46012
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 1470097994 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 32907885912 (30.65 GB)
telemt_user_msgs_from_client{user="hello"} 1282444
telemt_user_msgs_to_client{user="hello"} 4898886
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 18
```