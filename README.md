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

# Server Metrics 2026-03-11 10:41:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 72903.6 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218159
telemt_connections_bad_total 3617
telemt_handshake_timeouts_total 4421
telemt_upstream_connect_attempt_total 200215
telemt_upstream_connect_success_total 200152
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 200215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 183062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 200144
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 4309517665 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 115676550132 (107.73 GB)
telemt_user_msgs_from_client{user="hello"} 4723829
telemt_user_msgs_to_client{user="hello"} 8738454
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 72903.1 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85511
telemt_connections_bad_total 793
telemt_handshake_timeouts_total 3171
telemt_upstream_connect_attempt_total 77586
telemt_upstream_connect_success_total 77570
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 77586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 260
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77562
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 5030858429 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 56551582501 (52.67 GB)
telemt_user_msgs_from_client{user="hello"} 3247330
telemt_user_msgs_to_client{user="hello"} 14764648
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 72902.7 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118239
telemt_connections_bad_total 1078
telemt_handshake_timeouts_total 5312
telemt_upstream_connect_attempt_total 105089
telemt_upstream_connect_success_total 105085
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 105089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105077
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 12304474744 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 86680026030 (80.73 GB)
telemt_user_msgs_from_client{user="hello"} 5903757
telemt_user_msgs_to_client{user="hello"} 17028279
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 72901.7 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129714
telemt_connections_bad_total 324
telemt_handshake_timeouts_total 1231
telemt_upstream_connect_attempt_total 122960
telemt_upstream_connect_success_total 122676
telemt_upstream_connect_fail_total 284
telemt_upstream_connect_attempts_per_request{bucket="1"} 122960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16152
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 66
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 284
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 122668
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 5621417737 (5.24 GB)
telemt_user_octets_to_client{user="hello"} 86797195977 (80.84 GB)
telemt_user_msgs_from_client{user="hello"} 3755478
telemt_user_msgs_to_client{user="hello"} 22981833
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 72903.1 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202472
telemt_connections_bad_total 15836
telemt_handshake_timeouts_total 3415
telemt_upstream_connect_attempt_total 162741
telemt_upstream_connect_success_total 162339
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 162741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 139490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 302
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 162331
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 3620284764 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 142730411186 (132.93 GB)
telemt_user_msgs_from_client{user="hello"} 3765369
telemt_user_msgs_to_client{user="hello"} 19020180
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 51872.4 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 9
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