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

# Server Metrics 2026-03-11 11:37:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 76283.5 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233496
telemt_connections_bad_total 3629
telemt_handshake_timeouts_total 4497
telemt_upstream_connect_attempt_total 214931
telemt_upstream_connect_success_total 214863
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 214930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 196546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 214855
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 4499304787 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 120870671029 (112.57 GB)
telemt_user_msgs_from_client{user="hello"} 5022041
telemt_user_msgs_to_client{user="hello"} 9262860
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 76282.6 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91305
telemt_connections_bad_total 848
telemt_handshake_timeouts_total 3261
telemt_upstream_connect_attempt_total 83065
telemt_upstream_connect_success_total 83049
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 83065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83041
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 5127900730 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 57753196623 (53.79 GB)
telemt_user_msgs_from_client{user="hello"} 3346430
telemt_user_msgs_to_client{user="hello"} 15372824
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 76282.4 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127899
telemt_connections_bad_total 1093
telemt_handshake_timeouts_total 6643
telemt_upstream_connect_attempt_total 112926
telemt_upstream_connect_success_total 112912
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 112926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 112904
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 12354609935 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 88120856617 (82.07 GB)
telemt_user_msgs_from_client{user="hello"} 6030579
telemt_user_msgs_to_client{user="hello"} 17530235
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 76281.3 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138180
telemt_connections_bad_total 335
telemt_handshake_timeouts_total 1262
telemt_upstream_connect_attempt_total 131111
telemt_upstream_connect_success_total 130806
telemt_upstream_connect_fail_total 305
telemt_upstream_connect_attempts_per_request{bucket="1"} 131111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 305
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 130798
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 5729968140 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 100187141503 (93.31 GB)
telemt_user_msgs_from_client{user="hello"} 3958095
telemt_user_msgs_to_client{user="hello"} 28682736
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 76282.6 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212327
telemt_connections_bad_total 16501
telemt_handshake_timeouts_total 3747
telemt_upstream_connect_attempt_total 171327
telemt_upstream_connect_success_total 170923
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 171326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 147282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 170915
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 3854416519 (3.59 GB)
telemt_user_octets_to_client{user="hello"} 145202471957 (135.23 GB)
telemt_user_msgs_from_client{user="hello"} 3946266
telemt_user_msgs_to_client{user="hello"} 19631534
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 55252.0 (15h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426
telemt_connections_bad_total 404
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```