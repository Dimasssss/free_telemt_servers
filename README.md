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

# Server Metrics 2026-03-11 00:54:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 37716.6 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105286
telemt_connections_bad_total 3344
telemt_handshake_timeouts_total 2495
telemt_upstream_connect_attempt_total 94799
telemt_upstream_connect_success_total 94765
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 94799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94761
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 2709952787 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 77132768826 (71.84 GB)
telemt_user_msgs_from_client{user="hello"} 2740553
telemt_user_msgs_to_client{user="hello"} 5241333
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 37716.0 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41985
telemt_connections_bad_total 342
telemt_handshake_timeouts_total 980
telemt_upstream_connect_attempt_total 38230
telemt_upstream_connect_success_total 38221
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 38230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38217
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 2015318957 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 38545839322 (35.90 GB)
telemt_user_msgs_from_client{user="hello"} 1599723
telemt_user_msgs_to_client{user="hello"} 9548938
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 37715.7 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64846
telemt_connections_bad_total 561
telemt_handshake_timeouts_total 4112
telemt_upstream_connect_attempt_total 56526
telemt_upstream_connect_success_total 56524
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 56526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56520
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 8181326341 (7.62 GB)
telemt_user_octets_to_client{user="hello"} 60711630659 (56.54 GB)
telemt_user_msgs_from_client{user="hello"} 3791387
telemt_user_msgs_to_client{user="hello"} 9485636
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 37714.6 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62097
telemt_connections_bad_total 113
telemt_handshake_timeouts_total 527
telemt_upstream_connect_attempt_total 59423
telemt_upstream_connect_success_total 59269
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 59423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59265
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 853687203 (814.14 MB)
telemt_user_octets_to_client{user="hello"} 38425153116 (35.79 GB)
telemt_user_msgs_from_client{user="hello"} 1193528
telemt_user_msgs_to_client{user="hello"} 7497751
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 37716.0 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90134
telemt_connections_bad_total 8889
telemt_handshake_timeouts_total 1486
telemt_upstream_connect_attempt_total 76425
telemt_upstream_connect_success_total 76177
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 76425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76173
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 2120748186 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 61974295898 (57.72 GB)
telemt_user_msgs_from_client{user="hello"} 2070540
telemt_user_msgs_to_client{user="hello"} 9004589
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 16685.3 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```