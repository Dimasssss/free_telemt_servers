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

# Server Metrics 2026-03-11 16:03:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 92264.9 (25h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316224
telemt_connections_bad_total 5777
telemt_handshake_timeouts_total 5675
telemt_upstream_connect_attempt_total 290767
telemt_upstream_connect_success_total 290687
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 290767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 265643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 290677
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 5395511691 (5.02 GB)
telemt_user_octets_to_client{user="hello"} 140987827919 (131.31 GB)
telemt_user_msgs_from_client{user="hello"} 6251299
telemt_user_msgs_to_client{user="hello"} 11413627
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 92264.5 (25h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125219
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 3420
telemt_upstream_connect_attempt_total 115498
telemt_upstream_connect_success_total 115475
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 115498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 115465
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 6090948164 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 71417028601 (66.51 GB)
telemt_user_msgs_from_client{user="hello"} 4125945
telemt_user_msgs_to_client{user="hello"} 20925364
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 92264.1 (25h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170678
telemt_connections_bad_total 1446
telemt_handshake_timeouts_total 7361
telemt_upstream_connect_attempt_total 152486
telemt_upstream_connect_success_total 152472
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 152486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17023
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 152462
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 12762938418 (11.89 GB)
telemt_user_octets_to_client{user="hello"} 132558834518 (123.46 GB)
telemt_user_msgs_from_client{user="hello"} 6923789
telemt_user_msgs_to_client{user="hello"} 29923942
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 92263.2 (25h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192463
telemt_connections_bad_total 9407
telemt_handshake_timeouts_total 2853
telemt_upstream_connect_attempt_total 172525
telemt_upstream_connect_success_total 172108
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 172525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 150083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21462
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 467
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 172098
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 10001956729 (9.32 GB)
telemt_user_octets_to_client{user="hello"} 118906010365 (110.74 GB)
telemt_user_msgs_from_client{user="hello"} 6016608
telemt_user_msgs_to_client{user="hello"} 35561852
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 92264.3 (25h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269383
telemt_connections_bad_total 20211
telemt_handshake_timeouts_total 6373
telemt_upstream_connect_attempt_total 220352
telemt_upstream_connect_success_total 219846
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 220351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 190470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29006
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 370
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 219838
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 5160253725 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 175644739155 (163.58 GB)
telemt_user_msgs_from_client{user="hello"} 5147183
telemt_user_msgs_to_client{user="hello"} 24658652
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 71233.7 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473
telemt_connections_bad_total 450
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