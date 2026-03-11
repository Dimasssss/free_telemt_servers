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

# Server Metrics 2026-03-11 11:52:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 77205.0 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238062
telemt_connections_bad_total 3631
telemt_handshake_timeouts_total 4518
telemt_upstream_connect_attempt_total 219292
telemt_upstream_connect_success_total 219223
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 219292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 200663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 219215
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 4544324259 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 122139964970 (113.75 GB)
telemt_user_msgs_from_client{user="hello"} 5084586
telemt_user_msgs_to_client{user="hello"} 9379225
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 77204.2 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93161
telemt_connections_bad_total 893
telemt_handshake_timeouts_total 3290
telemt_upstream_connect_attempt_total 84770
telemt_upstream_connect_success_total 84754
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 84770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 267
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84746
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 5138346127 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 58032295165 (54.05 GB)
telemt_user_msgs_from_client{user="hello"} 3367331
telemt_user_msgs_to_client{user="hello"} 15506291
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 77203.9 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130075
telemt_connections_bad_total 1094
telemt_handshake_timeouts_total 6656
telemt_upstream_connect_attempt_total 115018
telemt_upstream_connect_success_total 115004
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 115018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114996
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 12364551481 (11.52 GB)
telemt_user_octets_to_client{user="hello"} 88277472736 (82.21 GB)
telemt_user_msgs_from_client{user="hello"} 6059495
telemt_user_msgs_to_client{user="hello"} 17603833
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 77202.8 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141000
telemt_connections_bad_total 335
telemt_handshake_timeouts_total 1521
telemt_upstream_connect_attempt_total 133576
telemt_upstream_connect_success_total 133264
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 133575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 133256
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 5747067897 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 100593470644 (93.68 GB)
telemt_user_msgs_from_client{user="hello"} 3991725
telemt_user_msgs_to_client{user="hello"} 28854905
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 77204.1 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215757
telemt_connections_bad_total 16852
telemt_handshake_timeouts_total 3815
telemt_upstream_connect_attempt_total 174219
telemt_upstream_connect_success_total 173814
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 174218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 149884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 318
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 173806
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 4349997585 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 146477391605 (136.42 GB)
telemt_user_msgs_from_client{user="hello"} 4156151
telemt_user_msgs_to_client{user="hello"} 19976035
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 56173.5 (15h 36m)
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