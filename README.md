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

# Server Metrics 2026-03-11 19:24:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8653.7 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33811
telemt_connections_bad_total 1925
telemt_handshake_timeouts_total 136
telemt_upstream_connect_attempt_total 30470
telemt_upstream_connect_success_total 30461
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 30470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30459
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 803562410 (766.34 MB)
telemt_user_octets_to_client{user="hello"} 18647303531 (17.37 GB)
telemt_user_msgs_from_client{user="hello"} 786098
telemt_user_msgs_to_client{user="hello"} 1518041
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 8641.9 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15903
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 244
telemt_upstream_connect_attempt_total 14507
telemt_upstream_connect_success_total 14506
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 298
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14504
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 198544662 (189.35 MB)
telemt_user_octets_to_client{user="hello"} 8437678441 (7.86 GB)
telemt_user_msgs_from_client{user="hello"} 322385
telemt_user_msgs_to_client{user="hello"} 3239391
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 8661.9 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18696
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 144
telemt_upstream_connect_attempt_total 17450
telemt_upstream_connect_success_total 17448
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 17450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17446
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 187981362 (179.27 MB)
telemt_user_octets_to_client{user="hello"} 8374383767 (7.80 GB)
telemt_user_msgs_from_client{user="hello"} 362683
telemt_user_msgs_to_client{user="hello"} 2055054
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 8657.3 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19813
telemt_connections_bad_total 1249
telemt_handshake_timeouts_total 370
telemt_upstream_connect_attempt_total 17321
telemt_upstream_connect_success_total 17268
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 17321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1584
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17266
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 554214066 (528.54 MB)
telemt_user_octets_to_client{user="hello"} 10388350421 (9.67 GB)
telemt_user_msgs_from_client{user="hello"} 436940
telemt_user_msgs_to_client{user="hello"} 2706486
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 8665.5 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21326
telemt_connections_bad_total 1679
telemt_handshake_timeouts_total 157
telemt_upstream_connect_attempt_total 18735
telemt_upstream_connect_success_total 18734
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18732
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 325773847 (310.68 MB)
telemt_user_octets_to_client{user="hello"} 7080609614 (6.59 GB)
telemt_user_msgs_from_client{user="hello"} 407067
telemt_user_msgs_to_client{user="hello"} 2344542
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 83271.8 (23h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 22
telemt_upstream_connect_success_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 22
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 8621 (8.42 KB)
telemt_user_octets_to_client{user="hello"} 3281 (3.20 KB)
telemt_user_msgs_from_client{user="hello"} 26
telemt_user_msgs_to_client{user="hello"} 18
```