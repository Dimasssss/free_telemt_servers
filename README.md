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

# Server Metrics 2026-03-12 01:18:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12795.9 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24551
telemt_connections_bad_total 1839
telemt_handshake_timeouts_total 149
telemt_upstream_connect_attempt_total 21737
telemt_upstream_connect_success_total 21731
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21729
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 236207050 (225.26 MB)
telemt_user_octets_to_client{user="hello"} 7455945720 (6.94 GB)
telemt_user_msgs_from_client{user="hello"} 397011
telemt_user_msgs_to_client{user="hello"} 996071
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12784.2 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10261
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 9853
telemt_upstream_connect_success_total 9853
telemt_upstream_connect_attempts_per_request{bucket="1"} 9853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9851
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 66433374 (63.36 MB)
telemt_user_octets_to_client{user="hello"} 3482447138 (3.24 GB)
telemt_user_msgs_from_client{user="hello"} 165358
telemt_user_msgs_to_client{user="hello"} 1118272
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12757.9 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17005
telemt_connections_bad_total 282
telemt_handshake_timeouts_total 864
telemt_upstream_connect_attempt_total 14076
telemt_upstream_connect_success_total 14076
telemt_upstream_connect_attempts_per_request{bucket="1"} 14076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14074
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 1152696753 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 7346299136 (6.84 GB)
telemt_user_msgs_from_client{user="hello"} 642747
telemt_user_msgs_to_client{user="hello"} 1662960
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12783.1 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17469
telemt_connections_bad_total 4269
telemt_handshake_timeouts_total 690
telemt_upstream_connect_attempt_total 11925
telemt_upstream_connect_success_total 11913
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 11924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11911
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 93972419 (89.62 MB)
telemt_user_octets_to_client{user="hello"} 5373264705 (5.00 GB)
telemt_user_msgs_from_client{user="hello"} 184226
telemt_user_msgs_to_client{user="hello"} 2024084
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 12783.9 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13570
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 12274
telemt_upstream_connect_success_total 12274
telemt_upstream_connect_attempts_per_request{bucket="1"} 12274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12272
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 190295261 (181.48 MB)
telemt_user_octets_to_client{user="hello"} 18686588652 (17.40 GB)
telemt_user_msgs_from_client{user="hello"} 340303
telemt_user_msgs_to_client{user="hello"} 1718449
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 12
```