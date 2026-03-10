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

# Server Metrics 2026-03-10 23:23:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 32217.6 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98268
telemt_connections_bad_total 3305
telemt_handshake_timeouts_total 2212
telemt_upstream_connect_attempt_total 88430
telemt_upstream_connect_success_total 88398
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 88430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88394
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2609484175 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 72446020837 (67.47 GB)
telemt_user_msgs_from_client{user="hello"} 2577890
telemt_user_msgs_to_client{user="hello"} 4942858
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 32216.7 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38183
telemt_connections_bad_total 333
telemt_handshake_timeouts_total 875
telemt_upstream_connect_attempt_total 34704
telemt_upstream_connect_success_total 34695
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 34704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34691
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 1716064615 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 36760071097 (34.24 GB)
telemt_user_msgs_from_client{user="hello"} 1434511
telemt_user_msgs_to_client{user="hello"} 9148272
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 32216.5 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60740
telemt_connections_bad_total 448
telemt_handshake_timeouts_total 4082
telemt_upstream_connect_attempt_total 52703
telemt_upstream_connect_success_total 52701
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 52703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5224
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52697
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 850794469 (811.38 MB)
telemt_user_octets_to_client{user="hello"} 52364061297 (48.77 GB)
telemt_user_msgs_from_client{user="hello"} 1153253
telemt_user_msgs_to_client{user="hello"} 7742413
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 32215.3 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56623
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 334
telemt_upstream_connect_attempt_total 54367
telemt_upstream_connect_success_total 54215
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 54367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54211
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 831596678 (793.07 MB)
telemt_user_octets_to_client{user="hello"} 37469070406 (34.90 GB)
telemt_user_msgs_from_client{user="hello"} 1139016
telemt_user_msgs_to_client{user="hello"} 7191300
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 32216.7 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83024
telemt_connections_bad_total 7819
telemt_handshake_timeouts_total 1468
telemt_upstream_connect_attempt_total 70557
telemt_upstream_connect_success_total 70309
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 70557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70305
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 2081317730 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 57283090148 (53.35 GB)
telemt_user_msgs_from_client{user="hello"} 1976660
telemt_user_msgs_to_client{user="hello"} 8308374
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 11186.0 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```