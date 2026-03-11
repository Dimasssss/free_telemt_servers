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

# Server Metrics 2026-03-11 20:56:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14175.3 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49144
telemt_connections_bad_total 2492
telemt_handshake_timeouts_total 233
telemt_upstream_connect_attempt_total 44397
telemt_upstream_connect_success_total 44386
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 44397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44384
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 1447716828 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 25486682427 (23.74 GB)
telemt_user_msgs_from_client{user="hello"} 1221326
telemt_user_msgs_to_client{user="hello"} 2205217
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 14163.3 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22704
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 257
telemt_upstream_connect_attempt_total 20989
telemt_upstream_connect_success_total 20950
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 20989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20948
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 241266114 (230.09 MB)
telemt_user_octets_to_client{user="hello"} 10886996471 (10.14 GB)
telemt_user_msgs_from_client{user="hello"} 428940
telemt_user_msgs_to_client{user="hello"} 4435529
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 14183.3 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27691
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 253
telemt_upstream_connect_attempt_total 25911
telemt_upstream_connect_success_total 25909
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 25911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25907
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 306272473 (292.08 MB)
telemt_user_octets_to_client{user="hello"} 9750786131 (9.08 GB)
telemt_user_msgs_from_client{user="hello"} 496832
telemt_user_msgs_to_client{user="hello"} 2446809
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 14178.7 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29784
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 436
telemt_upstream_connect_attempt_total 26207
telemt_upstream_connect_success_total 26128
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 26207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26126
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 702245239 (669.71 MB)
telemt_user_octets_to_client{user="hello"} 14813347530 (13.80 GB)
telemt_user_msgs_from_client{user="hello"} 613845
telemt_user_msgs_to_client{user="hello"} 4452962
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14186.9 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33001
telemt_connections_bad_total 2709
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 29136
telemt_upstream_connect_success_total 29133
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 29136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29131
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 509868890 (486.25 MB)
telemt_user_octets_to_client{user="hello"} 10981678840 (10.23 GB)
telemt_user_msgs_from_client{user="hello"} 658911
telemt_user_msgs_to_client{user="hello"} 4011648
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 88793.4 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2042
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 1496
telemt_upstream_connect_success_total 1496
telemt_upstream_connect_attempts_per_request{bucket="1"} 1496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 240
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1486
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 17940981 (17.11 MB)
telemt_user_octets_to_client{user="hello"} 1855079576 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 47446
telemt_user_msgs_to_client{user="hello"} 210377
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 8
```