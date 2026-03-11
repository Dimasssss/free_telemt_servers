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

# Server Metrics 2026-03-11 22:08:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1404.0 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2606
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 24
telemt_upstream_connect_attempt_total 2526
telemt_upstream_connect_success_total 2525
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 310
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2523
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 26998268 (25.75 MB)
telemt_user_octets_to_client{user="hello"} 1495045823 (1.39 GB)
telemt_user_msgs_from_client{user="hello"} 62544
telemt_user_msgs_to_client{user="hello"} 238316
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 1392.4 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1101
telemt_upstream_connect_attempt_total 1063
telemt_upstream_connect_success_total 1063
telemt_upstream_connect_attempts_per_request{bucket="1"} 1063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1061
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 7347557 (7.01 MB)
telemt_user_octets_to_client{user="hello"} 185893895 (177.28 MB)
telemt_user_msgs_from_client{user="hello"} 17776
telemt_user_msgs_to_client{user="hello"} 81068
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 1366.1 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2781
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 1945
telemt_upstream_connect_success_total 1945
telemt_upstream_connect_attempts_per_request{bucket="1"} 1945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 280
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1943
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 12979755 (12.38 MB)
telemt_user_octets_to_client{user="hello"} 1348716362 (1.26 GB)
telemt_user_msgs_from_client{user="hello"} 38752
telemt_user_msgs_to_client{user="hello"} 418487
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 1391.2 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1511
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 1420
telemt_upstream_connect_success_total 1418
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1416
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 10080758 (9.61 MB)
telemt_user_octets_to_client{user="hello"} 612751181 (584.37 MB)
telemt_user_msgs_from_client{user="hello"} 24728
telemt_user_msgs_to_client{user="hello"} 233350
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1392.6 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1624
telemt_connections_bad_total 284
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1312
telemt_upstream_connect_success_total 1312
telemt_upstream_connect_attempts_per_request{bucket="1"} 1312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1310
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 17421443 (16.61 MB)
telemt_user_octets_to_client{user="hello"} 1047239751 (998.73 MB)
telemt_user_msgs_from_client{user="hello"} 23701
telemt_user_msgs_to_client{user="hello"} 183382
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 1392.2 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1499
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1316
telemt_upstream_connect_success_total 1316
telemt_upstream_connect_attempts_per_request{bucket="1"} 1316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 271
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1314
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 34019319 (32.44 MB)
telemt_user_octets_to_client{user="hello"} 1307402663 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 39236
telemt_user_msgs_to_client{user="hello"} 147013
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 4
```