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

# Server Metrics 2026-03-11 04:49:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 51773.3 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131615
telemt_connections_bad_total 3386
telemt_handshake_timeouts_total 2803
telemt_upstream_connect_attempt_total 119415
telemt_upstream_connect_success_total 119372
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 119415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 119366
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 3041657426 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 85841834315 (79.95 GB)
telemt_user_msgs_from_client{user="hello"} 3146374
telemt_user_msgs_to_client{user="hello"} 5963373
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 51772.7 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54078
telemt_connections_bad_total 412
telemt_handshake_timeouts_total 2951
telemt_upstream_connect_attempt_total 47889
telemt_upstream_connect_success_total 47879
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 47889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47873
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 4443046208 (4.14 GB)
telemt_user_octets_to_client{user="hello"} 44575061652 (41.51 GB)
telemt_user_msgs_from_client{user="hello"} 2597461
telemt_user_msgs_to_client{user="hello"} 10656196
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 51772.4 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74999
telemt_connections_bad_total 675
telemt_handshake_timeouts_total 4306
telemt_upstream_connect_attempt_total 65742
telemt_upstream_connect_success_total 65739
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 65742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65733
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 11776268476 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 71134152823 (66.25 GB)
telemt_user_msgs_from_client{user="hello"} 5182610
telemt_user_msgs_to_client{user="hello"} 13359394
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 51771.4 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77342
telemt_connections_bad_total 156
telemt_handshake_timeouts_total 571
telemt_upstream_connect_attempt_total 74073
telemt_upstream_connect_success_total 73909
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 74073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9597
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73903
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 1813251914 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 48409300008 (45.08 GB)
telemt_user_msgs_from_client{user="hello"} 1712799
telemt_user_msgs_to_client{user="hello"} 10655190
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 51772.6 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123003
telemt_connections_bad_total 11694
telemt_handshake_timeouts_total 1679
telemt_upstream_connect_attempt_total 104630
telemt_upstream_connect_success_total 104381
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 104630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104375
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 2370102106 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 98600164911 (91.83 GB)
telemt_user_msgs_from_client{user="hello"} 2555196
telemt_user_msgs_to_client{user="hello"} 12754465
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 30742.1 (8h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```