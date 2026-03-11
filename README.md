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

# Server Metrics 2026-03-11 15:43:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 91034.5 (25h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309653
telemt_connections_bad_total 5230
telemt_handshake_timeouts_total 5198
telemt_upstream_connect_attempt_total 285433
telemt_upstream_connect_success_total 285353
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 285433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 260868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 285343
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 5339452301 (4.97 GB)
telemt_user_octets_to_client{user="hello"} 139222888128 (129.66 GB)
telemt_user_msgs_from_client{user="hello"} 6170159
telemt_user_msgs_to_client{user="hello"} 11237186
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 91033.9 (25h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122645
telemt_connections_bad_total 972
telemt_handshake_timeouts_total 3418
telemt_upstream_connect_attempt_total 113038
telemt_upstream_connect_success_total 113015
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 113038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 533
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 113005
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 6063808684 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 70048639009 (65.24 GB)
telemt_user_msgs_from_client{user="hello"} 4074133
telemt_user_msgs_to_client{user="hello"} 20396965
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 91033.7 (25h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168231
telemt_connections_bad_total 1436
telemt_handshake_timeouts_total 7263
telemt_upstream_connect_attempt_total 150248
telemt_upstream_connect_success_total 150234
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 150248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 150224
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 12750170335 (11.87 GB)
telemt_user_octets_to_client{user="hello"} 132049080725 (122.98 GB)
telemt_user_msgs_from_client{user="hello"} 6887338
telemt_user_msgs_to_client{user="hello"} 29709673
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 91032.5 (25h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188785
telemt_connections_bad_total 9405
telemt_handshake_timeouts_total 2481
telemt_upstream_connect_attempt_total 169369
telemt_upstream_connect_success_total 168956
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 169369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 147326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 455
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 168946
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 9933381801 (9.25 GB)
telemt_user_octets_to_client{user="hello"} 115886973176 (107.93 GB)
telemt_user_msgs_from_client{user="hello"} 5937284
telemt_user_msgs_to_client{user="hello"} 34705099
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 91033.9 (25h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265237
telemt_connections_bad_total 19983
telemt_handshake_timeouts_total 6354
telemt_upstream_connect_attempt_total 216667
telemt_upstream_connect_success_total 216162
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 216667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 187323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 216154
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 5131009339 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 174292275743 (162.32 GB)
telemt_user_msgs_from_client{user="hello"} 5078103
telemt_user_msgs_to_client{user="hello"} 24352209
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 70003.2 (19h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 12
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