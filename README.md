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

# Server Metrics 2026-03-11 21:06:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14789.0 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50341
telemt_connections_bad_total 2544
telemt_handshake_timeouts_total 235
telemt_upstream_connect_attempt_total 45499
telemt_upstream_connect_success_total 45488
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 45499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45486
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 1459526104 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 25980349236 (24.20 GB)
telemt_user_msgs_from_client{user="hello"} 1248355
telemt_user_msgs_to_client{user="hello"} 2298460
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 14777.4 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23218
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 257
telemt_upstream_connect_attempt_total 21472
telemt_upstream_connect_success_total 21433
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 21472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21431
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 246062897 (234.66 MB)
telemt_user_octets_to_client{user="hello"} 11015223016 (10.26 GB)
telemt_user_msgs_from_client{user="hello"} 439058
telemt_user_msgs_to_client{user="hello"} 4507104
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 14797.3 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28520
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 253
telemt_upstream_connect_attempt_total 26704
telemt_upstream_connect_success_total 26702
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 26704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26700
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 311973285 (297.52 MB)
telemt_user_octets_to_client{user="hello"} 10155276435 (9.46 GB)
telemt_user_msgs_from_client{user="hello"} 514419
telemt_user_msgs_to_client{user="hello"} 2567890
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 14792.6 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30502
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 439
telemt_upstream_connect_attempt_total 26910
telemt_upstream_connect_success_total 26829
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 26910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26827
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 710544520 (677.63 MB)
telemt_user_octets_to_client{user="hello"} 16183992951 (15.07 GB)
telemt_user_msgs_from_client{user="hello"} 635027
telemt_user_msgs_to_client{user="hello"} 5046181
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14800.8 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33807
telemt_connections_bad_total 2853
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 29786
telemt_upstream_connect_success_total 29783
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 29786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29781
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 512931182 (489.17 MB)
telemt_user_octets_to_client{user="hello"} 11206538397 (10.44 GB)
telemt_user_msgs_from_client{user="hello"} 667135
telemt_user_msgs_to_client{user="hello"} 4091710
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 89407.3 (24h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2457
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 1891
telemt_upstream_connect_success_total 1891
telemt_upstream_connect_attempts_per_request{bucket="1"} 1891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 289
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1881
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 23146898 (22.07 MB)
telemt_user_octets_to_client{user="hello"} 2239210074 (2.09 GB)
telemt_user_msgs_from_client{user="hello"} 61721
telemt_user_msgs_to_client{user="hello"} 258089
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 8
```