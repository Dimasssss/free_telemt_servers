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

# Server Metrics 2026-03-11 18:02:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3735.2 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15294
telemt_connections_bad_total 835
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 13632
telemt_upstream_connect_success_total 13629
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 13632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13627
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 417436861 (398.10 MB)
telemt_user_octets_to_client{user="hello"} 8347898491 (7.77 GB)
telemt_user_msgs_from_client{user="hello"} 350478
telemt_user_msgs_to_client{user="hello"} 634123
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3723.4 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8173
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 7415
telemt_upstream_connect_success_total 7414
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7412
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 117096287 (111.67 MB)
telemt_user_octets_to_client{user="hello"} 4846706621 (4.51 GB)
telemt_user_msgs_from_client{user="hello"} 176083
telemt_user_msgs_to_client{user="hello"} 1874081
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3742.9 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8888
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 94
telemt_upstream_connect_attempt_total 8275
telemt_upstream_connect_success_total 8274
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 807
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8272
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 70271801 (67.02 MB)
telemt_user_octets_to_client{user="hello"} 3845921581 (3.58 GB)
telemt_user_msgs_from_client{user="hello"} 175179
telemt_user_msgs_to_client{user="hello"} 1089825
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3738.8 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8238
telemt_connections_bad_total 234
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 7538
telemt_upstream_connect_success_total 7521
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 7538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 786
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7519
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 429857508 (409.94 MB)
telemt_user_octets_to_client{user="hello"} 3433448513 (3.20 GB)
telemt_user_msgs_from_client{user="hello"} 247826
telemt_user_msgs_to_client{user="hello"} 832724
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3746.8 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9587
telemt_connections_bad_total 781
telemt_handshake_timeouts_total 67
telemt_upstream_connect_attempt_total 8481
telemt_upstream_connect_success_total 8481
telemt_upstream_connect_attempts_per_request{bucket="1"} 8481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8479
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 52140885 (49.73 MB)
telemt_user_octets_to_client{user="hello"} 1223485939 (1.14 GB)
telemt_user_msgs_from_client{user="hello"} 117461
telemt_user_msgs_to_client{user="hello"} 390366
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 78353.2 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495
telemt_connections_bad_total 471
telemt_handshake_timeouts_total 14
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