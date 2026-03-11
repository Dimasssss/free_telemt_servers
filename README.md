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

# Server Metrics 2026-03-11 20:51:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13868.3 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48578
telemt_connections_bad_total 2484
telemt_handshake_timeouts_total 220
telemt_upstream_connect_attempt_total 43860
telemt_upstream_connect_success_total 43849
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 43860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43847
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 1442041650 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 25345645267 (23.60 GB)
telemt_user_msgs_from_client{user="hello"} 1211557
telemt_user_msgs_to_client{user="hello"} 2184001
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 13856.9 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22369
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 257
telemt_upstream_connect_attempt_total 20670
telemt_upstream_connect_success_total 20631
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 20670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20629
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 237437958 (226.44 MB)
telemt_user_octets_to_client{user="hello"} 10715587729 (9.98 GB)
telemt_user_msgs_from_client{user="hello"} 420830
telemt_user_msgs_to_client{user="hello"} 4359173
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 13876.6 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27310
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 249
telemt_upstream_connect_attempt_total 25554
telemt_upstream_connect_success_total 25552
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 25554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25550
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 304734238 (290.62 MB)
telemt_user_octets_to_client{user="hello"} 9723480029 (9.06 GB)
telemt_user_msgs_from_client{user="hello"} 491624
telemt_user_msgs_to_client{user="hello"} 2436674
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 13872.0 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29498
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 424
telemt_upstream_connect_attempt_total 25935
telemt_upstream_connect_success_total 25857
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 25934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2466
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25855
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 699284023 (666.89 MB)
telemt_user_octets_to_client{user="hello"} 14465940553 (13.47 GB)
telemt_user_msgs_from_client{user="hello"} 607666
telemt_user_msgs_to_client{user="hello"} 4321337
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13880.3 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32612
telemt_connections_bad_total 2648
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 28813
telemt_upstream_connect_success_total 28812
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 28813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28810
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 507764873 (484.24 MB)
telemt_user_octets_to_client{user="hello"} 10926483051 (10.18 GB)
telemt_user_msgs_from_client{user="hello"} 653409
telemt_user_msgs_to_client{user="hello"} 3994228
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 88486.6 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1805
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 1258
telemt_upstream_connect_success_total 1258
telemt_upstream_connect_attempts_per_request{bucket="1"} 1258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 197
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1248
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 12470955 (11.89 MB)
telemt_user_octets_to_client{user="hello"} 1035426046 (987.46 MB)
telemt_user_msgs_from_client{user="hello"} 32217
telemt_user_msgs_to_client{user="hello"} 137904
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 7
```