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

# Server Metrics 2026-03-11 01:50:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 41077.3 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110795
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2540
telemt_upstream_connect_attempt_total 99848
telemt_upstream_connect_success_total 99812
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 99848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8939
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99808
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 2766737882 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 79700677442 (74.23 GB)
telemt_user_msgs_from_client{user="hello"} 2835519
telemt_user_msgs_to_client{user="hello"} 5488215
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 41076.4 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45668
telemt_connections_bad_total 356
telemt_handshake_timeouts_total 2070
telemt_upstream_connect_attempt_total 40680
telemt_upstream_connect_success_total 40671
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 40680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40667
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 2133481499 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 38820187422 (36.15 GB)
telemt_user_msgs_from_client{user="hello"} 1663283
telemt_user_msgs_to_client{user="hello"} 9648965
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 41076.2 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67015
telemt_connections_bad_total 635
telemt_handshake_timeouts_total 4136
telemt_upstream_connect_attempt_total 58463
telemt_upstream_connect_success_total 58461
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 58463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58455
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 11001461380 (10.25 GB)
telemt_user_octets_to_client{user="hello"} 68030590063 (63.36 GB)
telemt_user_msgs_from_client{user="hello"} 4842388
telemt_user_msgs_to_client{user="hello"} 12543013
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 41075.2 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65587
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 538
telemt_upstream_connect_attempt_total 62751
telemt_upstream_connect_success_total 62596
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 62751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62592
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 1747489336 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 42523380034 (39.60 GB)
telemt_user_msgs_from_client{user="hello"} 1567871
telemt_user_msgs_to_client{user="hello"} 8312095
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 41076.4 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94753
telemt_connections_bad_total 9555
telemt_handshake_timeouts_total 1503
telemt_upstream_connect_attempt_total 80199
telemt_upstream_connect_success_total 79951
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 80199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79947
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 2144098106 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 64981162459 (60.52 GB)
telemt_user_msgs_from_client{user="hello"} 2131061
telemt_user_msgs_to_client{user="hello"} 9342228
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 20045.8 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```