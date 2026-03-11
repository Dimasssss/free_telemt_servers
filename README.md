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

# Server Metrics 2026-03-11 14:47:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 87656.2 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291509
telemt_connections_bad_total 3682
telemt_handshake_timeouts_total 4835
telemt_upstream_connect_attempt_total 269917
telemt_upstream_connect_success_total 269839
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 269917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 246871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 269829
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 5076834693 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 135743973508 (126.42 GB)
telemt_user_msgs_from_client{user="hello"} 5902167
telemt_user_msgs_to_client{user="hello"} 10800945
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 87655.4 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115507
telemt_connections_bad_total 965
telemt_handshake_timeouts_total 3372
telemt_upstream_connect_attempt_total 106154
telemt_upstream_connect_success_total 106133
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 106154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13592
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 468
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106123
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 5975415795 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 68640684377 (63.93 GB)
telemt_user_msgs_from_client{user="hello"} 3952970
telemt_user_msgs_to_client{user="hello"} 19736606
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 87655.1 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160426
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 7002
telemt_upstream_connect_attempt_total 143199
telemt_upstream_connect_success_total 143185
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 143199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 143175
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 12698180395 (11.83 GB)
telemt_user_octets_to_client{user="hello"} 128397612462 (119.58 GB)
telemt_user_msgs_from_client{user="hello"} 6750522
telemt_user_msgs_to_client{user="hello"} 28699360
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 87654.2 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177745
telemt_connections_bad_total 7453
telemt_handshake_timeouts_total 1997
telemt_upstream_connect_attempt_total 161197
telemt_upstream_connect_success_total 160804
telemt_upstream_connect_fail_total 393
telemt_upstream_connect_attempts_per_request{bucket="1"} 161197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 139829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20447
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 393
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 160794
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 9617015482 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 112061685864 (104.37 GB)
telemt_user_msgs_from_client{user="hello"} 5719792
telemt_user_msgs_to_client{user="hello"} 33302586
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 87655.3 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254084
telemt_connections_bad_total 19341
telemt_handshake_timeouts_total 6317
telemt_upstream_connect_attempt_total 206544
telemt_upstream_connect_success_total 206039
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 206543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 178406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 206031
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 5035171478 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 167639388447 (156.13 GB)
telemt_user_msgs_from_client{user="hello"} 4874645
telemt_user_msgs_to_client{user="hello"} 23068067
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 66624.6 (18h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462
telemt_connections_bad_total 440
telemt_handshake_timeouts_total 10
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