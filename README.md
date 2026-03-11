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

# Server Metrics 2026-03-11 15:58:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 91956.6 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314480
telemt_connections_bad_total 5640
telemt_handshake_timeouts_total 5552
telemt_upstream_connect_attempt_total 289314
telemt_upstream_connect_success_total 289234
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 289314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 264354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 289224
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 5374976623 (5.01 GB)
telemt_user_octets_to_client{user="hello"} 140663386653 (131.00 GB)
telemt_user_msgs_from_client{user="hello"} 6227243
telemt_user_msgs_to_client{user="hello"} 11375663
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 91955.9 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124390
telemt_connections_bad_total 973
telemt_handshake_timeouts_total 3420
telemt_upstream_connect_attempt_total 114713
telemt_upstream_connect_success_total 114690
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 114713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 539
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114680
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 6082468605 (5.66 GB)
telemt_user_octets_to_client{user="hello"} 70689817015 (65.84 GB)
telemt_user_msgs_from_client{user="hello"} 4106303
telemt_user_msgs_to_client{user="hello"} 20643840
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 91955.5 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169983
telemt_connections_bad_total 1438
telemt_handshake_timeouts_total 7271
telemt_upstream_connect_attempt_total 151934
telemt_upstream_connect_success_total 151920
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 151934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 151910
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 12759555427 (11.88 GB)
telemt_user_octets_to_client{user="hello"} 132387779388 (123.30 GB)
telemt_user_msgs_from_client{user="hello"} 6913509
telemt_user_msgs_to_client{user="hello"} 29849475
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 91954.6 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191493
telemt_connections_bad_total 9405
telemt_handshake_timeouts_total 2768
telemt_upstream_connect_attempt_total 171682
telemt_upstream_connect_success_total 171268
telemt_upstream_connect_fail_total 414
telemt_upstream_connect_attempts_per_request{bucket="1"} 171682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 149364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 461
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 414
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 171258
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 9992499252 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 117190902877 (109.14 GB)
telemt_user_msgs_from_client{user="hello"} 5995499
telemt_user_msgs_to_client{user="hello"} 35106024
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 91955.8 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268141
telemt_connections_bad_total 20148
telemt_handshake_timeouts_total 6367
telemt_upstream_connect_attempt_total 219273
telemt_upstream_connect_success_total 218768
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 219273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 189595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 218760
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 5151266069 (4.80 GB)
telemt_user_octets_to_client{user="hello"} 175241604735 (163.21 GB)
telemt_user_msgs_from_client{user="hello"} 5126204
telemt_user_msgs_to_client{user="hello"} 24562930
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 70928.3 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472
telemt_connections_bad_total 449
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