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

# Server Metrics 2026-03-11 02:56:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 45049.1 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118021
telemt_connections_bad_total 3363
telemt_handshake_timeouts_total 2572
telemt_upstream_connect_attempt_total 106726
telemt_upstream_connect_success_total 106688
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 106726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106682
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 2911650065 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 81938056044 (76.31 GB)
telemt_user_msgs_from_client{user="hello"} 2957973
telemt_user_msgs_to_client{user="hello"} 5661611
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 45048.5 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49123
telemt_connections_bad_total 388
telemt_handshake_timeouts_total 2917
telemt_upstream_connect_attempt_total 43178
telemt_upstream_connect_success_total 43169
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43165
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 2272211355 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 41626859305 (38.77 GB)
telemt_user_msgs_from_client{user="hello"} 1754485
telemt_user_msgs_to_client{user="hello"} 10117401
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 45048.2 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69643
telemt_connections_bad_total 660
telemt_handshake_timeouts_total 4207
telemt_upstream_connect_attempt_total 60880
telemt_upstream_connect_success_total 60878
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 60880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60872
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 11743012985 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70037521822 (65.23 GB)
telemt_user_msgs_from_client{user="hello"} 5130223
telemt_user_msgs_to_client{user="hello"} 13141419
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 45047.2 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68780
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 546
telemt_upstream_connect_attempt_total 65795
telemt_upstream_connect_success_total 65638
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 65795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65632
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 1763259570 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 42678264179 (39.75 GB)
telemt_user_msgs_from_client{user="hello"} 1595674
telemt_user_msgs_to_client{user="hello"} 8375341
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 45048.8 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104997
telemt_connections_bad_total 10360
telemt_handshake_timeouts_total 1527
telemt_upstream_connect_attempt_total 89211
telemt_upstream_connect_success_total 88963
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 89211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88959
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 2203845954 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 77829618787 (72.48 GB)
telemt_user_msgs_from_client{user="hello"} 2262714
telemt_user_msgs_to_client{user="hello"} 10616294
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 24017.9 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```