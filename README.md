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

# Server Metrics 2026-03-11 21:01:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14482.1 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49771
telemt_connections_bad_total 2534
telemt_handshake_timeouts_total 234
telemt_upstream_connect_attempt_total 44948
telemt_upstream_connect_success_total 44937
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 44948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44935
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 1453642249 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 25656220556 (23.89 GB)
telemt_user_msgs_from_client{user="hello"} 1234145
telemt_user_msgs_to_client{user="hello"} 2237419
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 14470.6 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22920
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 257
telemt_upstream_connect_attempt_total 21184
telemt_upstream_connect_success_total 21145
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 21184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21143
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 242964314 (231.71 MB)
telemt_user_octets_to_client{user="hello"} 10920249639 (10.17 GB)
telemt_user_msgs_from_client{user="hello"} 432582
telemt_user_msgs_to_client{user="hello"} 4453739
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 14490.6 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28046
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 253
telemt_upstream_connect_attempt_total 26263
telemt_upstream_connect_success_total 26261
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 26263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26259
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 309420495 (295.09 MB)
telemt_user_octets_to_client{user="hello"} 9955970701 (9.27 GB)
telemt_user_msgs_from_client{user="hello"} 506357
telemt_user_msgs_to_client{user="hello"} 2503534
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 14485.8 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30063
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 436
telemt_upstream_connect_attempt_total 26481
telemt_upstream_connect_success_total 26401
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 26481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26399
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 705418359 (672.74 MB)
telemt_user_octets_to_client{user="hello"} 15321808548 (14.27 GB)
telemt_user_msgs_from_client{user="hello"} 622091
telemt_user_msgs_to_client{user="hello"} 4667324
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14493.9 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33411
telemt_connections_bad_total 2772
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 29476
telemt_upstream_connect_success_total 29473
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 29476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29471
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 511025137 (487.35 MB)
telemt_user_octets_to_client{user="hello"} 11032221892 (10.27 GB)
telemt_user_msgs_from_client{user="hello"} 662125
telemt_user_msgs_to_client{user="hello"} 4036659
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 89100.3 (24h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2270
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 1712
telemt_upstream_connect_success_total 1712
telemt_upstream_connect_attempts_per_request{bucket="1"} 1712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 274
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1702
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 21214443 (20.23 MB)
telemt_user_octets_to_client{user="hello"} 2056798176 (1.92 GB)
telemt_user_msgs_from_client{user="hello"} 56329
telemt_user_msgs_to_client{user="hello"} 233622
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 4
```