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

# Server Metrics 2026-03-12 06:50:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 32732.3 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91302
telemt_connections_bad_total 2118
telemt_handshake_timeouts_total 2385
telemt_upstream_connect_attempt_total 82898
telemt_upstream_connect_success_total 82750
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 82898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82746
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 840860574 (801.91 MB)
telemt_user_octets_to_client{user="hello"} 24679319121 (22.98 GB)
telemt_user_msgs_from_client{user="hello"} 1236630
telemt_user_msgs_to_client{user="hello"} 2812355
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 32720.5 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37189
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 554
telemt_upstream_connect_attempt_total 35135
telemt_upstream_connect_success_total 35101
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 35135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35097
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 312105877 (297.65 MB)
telemt_user_octets_to_client{user="hello"} 16079575439 (14.98 GB)
telemt_user_msgs_from_client{user="hello"} 617527
telemt_user_msgs_to_client{user="hello"} 5117430
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 32694.3 (9h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55387
telemt_connections_bad_total 676
telemt_handshake_timeouts_total 1138
telemt_upstream_connect_attempt_total 49895
telemt_upstream_connect_success_total 49861
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 49895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49857
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 5458427840 (5.08 GB)
telemt_user_octets_to_client{user="hello"} 30360297217 (28.28 GB)
telemt_user_msgs_from_client{user="hello"} 2740423
telemt_user_msgs_to_client{user="hello"} 5400472
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 32719.6 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60582
telemt_connections_bad_total 13010
telemt_handshake_timeouts_total 898
telemt_upstream_connect_attempt_total 44179
telemt_upstream_connect_success_total 42427
telemt_upstream_connect_fail_total 1752
telemt_upstream_connect_attempts_per_request{bucket="1"} 44179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1752
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42423
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 1411074784 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 32176487217 (29.97 GB)
telemt_user_msgs_from_client{user="hello"} 1152437
telemt_user_msgs_to_client{user="hello"} 12998821
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2911.9 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4283
telemt_connections_bad_total 521
telemt_handshake_timeouts_total 114
telemt_upstream_connect_attempt_total 3527
telemt_upstream_connect_success_total 3500
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 3527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3498
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 127759003 (121.84 MB)
telemt_user_octets_to_client{user="hello"} 4246901331 (3.96 GB)
telemt_user_msgs_from_client{user="hello"} 120283
telemt_user_msgs_to_client{user="hello"} 596356
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 32720.4 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57591
telemt_connections_bad_total 904
telemt_handshake_timeouts_total 327
telemt_upstream_connect_attempt_total 53799
telemt_upstream_connect_success_total 53729
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 53799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8847
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53725
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 978200522 (932.88 MB)
telemt_user_octets_to_client{user="hello"} 50032754618 (46.60 GB)
telemt_user_msgs_from_client{user="hello"} 1380546
telemt_user_msgs_to_client{user="hello"} 6374731
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 39
```