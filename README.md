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

# Server Metrics 2026-03-11 06:00:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 56054.4 (15h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147589
telemt_connections_bad_total 3488
telemt_handshake_timeouts_total 3859
telemt_upstream_connect_attempt_total 132973
telemt_upstream_connect_success_total 132929
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 132973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 132923
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 3284378863 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 90838762526 (84.60 GB)
telemt_user_msgs_from_client{user="hello"} 3419666
telemt_user_msgs_to_client{user="hello"} 6402139
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 56053.5 (15h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58708
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 3009
telemt_upstream_connect_attempt_total 52245
telemt_upstream_connect_success_total 52233
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 52245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52227
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 4552957215 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 47629668219 (44.36 GB)
telemt_user_msgs_from_client{user="hello"} 2751122
telemt_user_msgs_to_client{user="hello"} 11275661
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 56053.3 (15h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79989
telemt_connections_bad_total 726
telemt_handshake_timeouts_total 4350
telemt_upstream_connect_attempt_total 70439
telemt_upstream_connect_success_total 70436
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 70439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70430
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 11802082311 (10.99 GB)
telemt_user_octets_to_client{user="hello"} 71625000135 (66.71 GB)
telemt_user_msgs_from_client{user="hello"} 5227866
telemt_user_msgs_to_client{user="hello"} 13516322
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 56052.4 (15h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84864
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 623
telemt_upstream_connect_attempt_total 81235
telemt_upstream_connect_success_total 81057
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 81235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10685
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81051
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 1877042745 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 53570979702 (49.89 GB)
telemt_user_msgs_from_client{user="hello"} 1834430
telemt_user_msgs_to_client{user="hello"} 12471533
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 56053.4 (15h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142535
telemt_connections_bad_total 12501
telemt_handshake_timeouts_total 1770
telemt_upstream_connect_attempt_total 115137
telemt_upstream_connect_success_total 114888
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 115137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114882
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 2456414470 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 109535776267 (102.01 GB)
telemt_user_msgs_from_client{user="hello"} 2740709
telemt_user_msgs_to_client{user="hello"} 14541363
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 35022.9 (9h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```