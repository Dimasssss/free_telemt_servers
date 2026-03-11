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

# Server Metrics 2026-03-11 15:22:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 89805.5 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303708
telemt_connections_bad_total 4684
telemt_handshake_timeouts_total 5156
telemt_upstream_connect_attempt_total 280327
telemt_upstream_connect_success_total 280247
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 280327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 256275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 280237
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 5145883711 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 138298153053 (128.80 GB)
telemt_user_msgs_from_client{user="hello"} 6048443
telemt_user_msgs_to_client{user="hello"} 11104775
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 89804.9 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120031
telemt_connections_bad_total 969
telemt_handshake_timeouts_total 3409
telemt_upstream_connect_attempt_total 110502
telemt_upstream_connect_success_total 110481
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 110502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 518
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110471
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 6014539516 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 69527288829 (64.75 GB)
telemt_user_msgs_from_client{user="hello"} 4021334
telemt_user_msgs_to_client{user="hello"} 20165929
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 89804.6 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165039
telemt_connections_bad_total 1252
telemt_handshake_timeouts_total 7200
telemt_upstream_connect_attempt_total 147394
telemt_upstream_connect_success_total 147380
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 147394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16400
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 147370
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 12727304661 (11.85 GB)
telemt_user_octets_to_client{user="hello"} 130396496062 (121.44 GB)
telemt_user_msgs_from_client{user="hello"} 6829462
telemt_user_msgs_to_client{user="hello"} 29193608
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 89803.6 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184014
telemt_connections_bad_total 8151
telemt_handshake_timeouts_total 2137
telemt_upstream_connect_attempt_total 166353
telemt_upstream_connect_success_total 165947
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 166353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 144567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20838
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 451
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 165937
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 9880823562 (9.20 GB)
telemt_user_octets_to_client{user="hello"} 114956542777 (107.06 GB)
telemt_user_msgs_from_client{user="hello"} 5883312
telemt_user_msgs_to_client{user="hello"} 34401262
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 89804.9 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260791
telemt_connections_bad_total 19761
telemt_handshake_timeouts_total 6333
telemt_upstream_connect_attempt_total 212611
telemt_upstream_connect_success_total 212107
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 212611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 183748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 212099
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 5105852335 (4.76 GB)
telemt_user_octets_to_client{user="hello"} 173585086588 (161.66 GB)
telemt_user_msgs_from_client{user="hello"} 5017789
telemt_user_msgs_to_client{user="hello"} 24173833
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 68774.2 (19h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468
telemt_connections_bad_total 445
telemt_handshake_timeouts_total 11
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