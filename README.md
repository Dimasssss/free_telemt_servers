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

# Server Metrics 2026-03-11 22:18:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2017.2 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3546
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 3420
telemt_upstream_connect_success_total 3419
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 396
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3417
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 37208729 (35.49 MB)
telemt_user_octets_to_client{user="hello"} 1904116100 (1.77 GB)
telemt_user_msgs_from_client{user="hello"} 83634
telemt_user_msgs_to_client{user="hello"} 299484
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2005.7 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1429
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 1373
telemt_upstream_connect_success_total 1373
telemt_upstream_connect_attempts_per_request{bucket="1"} 1373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1371
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 8549087 (8.15 MB)
telemt_user_octets_to_client{user="hello"} 224961232 (214.54 MB)
telemt_user_msgs_from_client{user="hello"} 20760
telemt_user_msgs_to_client{user="hello"} 96328
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 1979.3 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3417
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 2544
telemt_upstream_connect_success_total 2544
telemt_upstream_connect_attempts_per_request{bucket="1"} 2544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 303
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2542
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 15353558 (14.64 MB)
telemt_user_octets_to_client{user="hello"} 1394895727 (1.30 GB)
telemt_user_msgs_from_client{user="hello"} 47330
telemt_user_msgs_to_client{user="hello"} 432206
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2004.5 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2066
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 1934
telemt_upstream_connect_success_total 1932
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1930
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 23024832 (21.96 MB)
telemt_user_octets_to_client{user="hello"} 717988914 (684.73 MB)
telemt_user_msgs_from_client{user="hello"} 33336
telemt_user_msgs_to_client{user="hello"} 276761
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2005.9 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2231
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1802
telemt_upstream_connect_success_total 1802
telemt_upstream_connect_attempts_per_request{bucket="1"} 1802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1800
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 18963941 (18.09 MB)
telemt_user_octets_to_client{user="hello"} 1071288899 (1021.66 MB)
telemt_user_msgs_from_client{user="hello"} 27080
telemt_user_msgs_to_client{user="hello"} 190714
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 2005.4 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2085
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 1875
telemt_upstream_connect_success_total 1875
telemt_upstream_connect_attempts_per_request{bucket="1"} 1875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 341
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1873
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 44155032 (42.11 MB)
telemt_user_octets_to_client{user="hello"} 4050815946 (3.77 GB)
telemt_user_msgs_from_client{user="hello"} 55833
telemt_user_msgs_to_client{user="hello"} 219026
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 11
```