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

# Server Metrics 2026-03-11 18:48:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6507.2 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26832
telemt_connections_bad_total 1445
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 24176
telemt_upstream_connect_success_total 24171
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24169
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 657678374 (627.21 MB)
telemt_user_octets_to_client{user="hello"} 15430745537 (14.37 GB)
telemt_user_msgs_from_client{user="hello"} 608894
telemt_user_msgs_to_client{user="hello"} 1154843
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 6495.6 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12771
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 234
telemt_upstream_connect_attempt_total 11491
telemt_upstream_connect_success_total 11490
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 257
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11488
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 175790716 (167.65 MB)
telemt_user_octets_to_client{user="hello"} 7166332994 (6.67 GB)
telemt_user_msgs_from_client{user="hello"} 266587
telemt_user_msgs_to_client{user="hello"} 2691263
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 6515.2 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14748
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 109
telemt_upstream_connect_attempt_total 13794
telemt_upstream_connect_success_total 13792
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 13794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13790
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 144697835 (137.99 MB)
telemt_user_octets_to_client{user="hello"} 5613397205 (5.23 GB)
telemt_user_msgs_from_client{user="hello"} 282882
telemt_user_msgs_to_client{user="hello"} 1610797
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 6511.0 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14550
telemt_connections_bad_total 776
telemt_handshake_timeouts_total 198
telemt_upstream_connect_attempt_total 13042
telemt_upstream_connect_success_total 13008
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 13042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13006
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 493643433 (470.78 MB)
telemt_user_octets_to_client{user="hello"} 8478305766 (7.90 GB)
telemt_user_msgs_from_client{user="hello"} 355080
telemt_user_msgs_to_client{user="hello"} 1937526
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 6518.9 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16070
telemt_connections_bad_total 1296
telemt_handshake_timeouts_total 81
telemt_upstream_connect_attempt_total 14238
telemt_upstream_connect_success_total 14237
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14235
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 260316304 (248.26 MB)
telemt_user_octets_to_client{user="hello"} 3780015006 (3.52 GB)
telemt_user_msgs_from_client{user="hello"} 288912
telemt_user_msgs_to_client{user="hello"} 1102770
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 81125.3 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 514
telemt_connections_bad_total 488
telemt_handshake_timeouts_total 16
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