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

# Server Metrics 2026-03-11 15:48:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 91342.1 (25h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311262
telemt_connections_bad_total 5366
telemt_handshake_timeouts_total 5314
telemt_upstream_connect_attempt_total 286708
telemt_upstream_connect_success_total 286628
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 286708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 262003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 286618
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 5347796349 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 139629888432 (130.04 GB)
telemt_user_msgs_from_client{user="hello"} 6186307
telemt_user_msgs_to_client{user="hello"} 11274525
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 91341.1 (25h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123206
telemt_connections_bad_total 972
telemt_handshake_timeouts_total 3419
telemt_upstream_connect_attempt_total 113580
telemt_upstream_connect_success_total 113557
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 113580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 533
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 113547
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 6071159165 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 70178034154 (65.36 GB)
telemt_user_msgs_from_client{user="hello"} 4085281
telemt_user_msgs_to_client{user="hello"} 20447106
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 91340.9 (25h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168721
telemt_connections_bad_total 1438
telemt_handshake_timeouts_total 7263
telemt_upstream_connect_attempt_total 150723
telemt_upstream_connect_success_total 150709
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 150723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 150699
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 12752647895 (11.88 GB)
telemt_user_octets_to_client{user="hello"} 132141354936 (123.07 GB)
telemt_user_msgs_from_client{user="hello"} 6895043
telemt_user_msgs_to_client{user="hello"} 29750522
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 91340.1 (25h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189726
telemt_connections_bad_total 9405
telemt_handshake_timeouts_total 2579
telemt_upstream_connect_attempt_total 170173
telemt_upstream_connect_success_total 169760
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 170173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 148051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21156
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 459
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 169750
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 9942495149 (9.26 GB)
telemt_user_octets_to_client{user="hello"} 116232535364 (108.25 GB)
telemt_user_msgs_from_client{user="hello"} 5951854
telemt_user_msgs_to_client{user="hello"} 34771042
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 91341.2 (25h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266161
telemt_connections_bad_total 20038
telemt_handshake_timeouts_total 6359
telemt_upstream_connect_attempt_total 217496
telemt_upstream_connect_success_total 216991
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 217496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 188034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 216983
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 5136231104 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 174578582281 (162.59 GB)
telemt_user_msgs_from_client{user="hello"} 5091603
telemt_user_msgs_to_client{user="hello"} 24408679
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 70310.5 (19h 31m)
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