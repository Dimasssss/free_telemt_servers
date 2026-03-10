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

# Server Metrics 2026-03-10 23:53:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 34052.0 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100751
telemt_connections_bad_total 3323
telemt_handshake_timeouts_total 2475
telemt_upstream_connect_attempt_total 90477
telemt_upstream_connect_success_total 90445
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 90477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90441
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 2644010598 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 73870486153 (68.80 GB)
telemt_user_msgs_from_client{user="hello"} 2631590
telemt_user_msgs_to_client{user="hello"} 5057418
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 34051.3 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39318
telemt_connections_bad_total 338
telemt_handshake_timeouts_total 934
telemt_upstream_connect_attempt_total 35728
telemt_upstream_connect_success_total 35719
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 35728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35715
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 2000993333 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 38173813811 (35.55 GB)
telemt_user_msgs_from_client{user="hello"} 1563574
telemt_user_msgs_to_client{user="hello"} 9397273
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 34051.1 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62185
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 4083
telemt_upstream_connect_attempt_total 54084
telemt_upstream_connect_success_total 54082
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 54084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54078
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 1101208515 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 56396338468 (52.52 GB)
telemt_user_msgs_from_client{user="hello"} 1271334
telemt_user_msgs_to_client{user="hello"} 8301188
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 34050.0 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58717
telemt_connections_bad_total 91
telemt_handshake_timeouts_total 515
telemt_upstream_connect_attempt_total 56209
telemt_upstream_connect_success_total 56057
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 56209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6728
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56053
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 838849730 (799.99 MB)
telemt_user_octets_to_client{user="hello"} 37733265524 (35.14 GB)
telemt_user_msgs_from_client{user="hello"} 1156667
telemt_user_msgs_to_client{user="hello"} 7266257
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 34051.2 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85091
telemt_connections_bad_total 8157
telemt_handshake_timeouts_total 1470
telemt_upstream_connect_attempt_total 72242
telemt_upstream_connect_success_total 71994
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 72242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71990
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 2088270949 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 57524251107 (53.57 GB)
telemt_user_msgs_from_client{user="hello"} 1993034
telemt_user_msgs_to_client{user="hello"} 8360660
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 13020.7 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```