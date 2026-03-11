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

# Server Metrics 2026-03-11 16:40:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1551.6 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7811
telemt_connections_bad_total 411
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 6775
telemt_upstream_connect_success_total 6771
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 532
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6769
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 63401658 (60.46 MB)
telemt_user_octets_to_client{user="hello"} 2450569495 (2.28 GB)
telemt_user_msgs_from_client{user="hello"} 101544
telemt_user_msgs_to_client{user="hello"} 219825
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 94442.8 (26h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130256
telemt_connections_bad_total 975
telemt_handshake_timeouts_total 3471
telemt_upstream_connect_attempt_total 120322
telemt_upstream_connect_success_total 120299
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 120322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 621
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 120289
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 6121864007 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 73222082093 (68.19 GB)
telemt_user_msgs_from_client{user="hello"} 4195516
telemt_user_msgs_to_client{user="hello"} 21473548
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 94442.4 (26h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176082
telemt_connections_bad_total 1446
telemt_handshake_timeouts_total 7867
telemt_upstream_connect_attempt_total 157233
telemt_upstream_connect_success_total 157219
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 157233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 139449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 157209
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 12800164732 (11.92 GB)
telemt_user_octets_to_client{user="hello"} 135776420515 (126.45 GB)
telemt_user_msgs_from_client{user="hello"} 7028765
telemt_user_msgs_to_client{user="hello"} 30873968
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 94441.4 (26h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199846
telemt_connections_bad_total 10659
telemt_handshake_timeouts_total 3395
telemt_upstream_connect_attempt_total 177870
telemt_upstream_connect_success_total 177439
telemt_upstream_connect_fail_total 431
telemt_upstream_connect_attempts_per_request{bucket="1"} 177870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 489
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 431
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 177429
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 10461486951 (9.74 GB)
telemt_user_octets_to_client{user="hello"} 122956081976 (114.51 GB)
telemt_user_msgs_from_client{user="hello"} 6249306
telemt_user_msgs_to_client{user="hello"} 36677192
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 73411.9 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 12
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