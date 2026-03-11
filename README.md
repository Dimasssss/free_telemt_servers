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

# Server Metrics 2026-03-11 19:14:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8040.2 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31726
telemt_connections_bad_total 1799
telemt_handshake_timeouts_total 132
telemt_upstream_connect_attempt_total 28588
telemt_upstream_connect_success_total 28578
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 28587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28576
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 707678340 (674.89 MB)
telemt_user_octets_to_client{user="hello"} 17592316367 (16.38 GB)
telemt_user_msgs_from_client{user="hello"} 713543
telemt_user_msgs_to_client{user="hello"} 1417683
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 8028.6 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15058
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 244
telemt_upstream_connect_attempt_total 13679
telemt_upstream_connect_success_total 13678
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13676
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 194842908 (185.82 MB)
telemt_user_octets_to_client{user="hello"} 8356103699 (7.78 GB)
telemt_user_msgs_from_client{user="hello"} 313244
telemt_user_msgs_to_client{user="hello"} 3196812
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 8048.4 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17604
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 134
telemt_upstream_connect_attempt_total 16508
telemt_upstream_connect_success_total 16505
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16503
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 179265580 (170.96 MB)
telemt_user_octets_to_client{user="hello"} 6851506789 (6.38 GB)
telemt_user_msgs_from_client{user="hello"} 337175
telemt_user_msgs_to_client{user="hello"} 1861842
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 8043.9 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18378
telemt_connections_bad_total 1129
telemt_handshake_timeouts_total 362
telemt_upstream_connect_attempt_total 16076
telemt_upstream_connect_success_total 16029
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 16076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16027
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 534685602 (509.92 MB)
telemt_user_octets_to_client{user="hello"} 9867003091 (9.19 GB)
telemt_user_msgs_from_client{user="hello"} 410693
telemt_user_msgs_to_client{user="hello"} 2472701
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 8052.0 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20027
telemt_connections_bad_total 1570
telemt_handshake_timeouts_total 153
telemt_upstream_connect_attempt_total 17575
telemt_upstream_connect_success_total 17574
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17572
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 307662681 (293.41 MB)
telemt_user_octets_to_client{user="hello"} 6274721099 (5.84 GB)
telemt_user_msgs_from_client{user="hello"} 374544
telemt_user_msgs_to_client{user="hello"} 1923991
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 82658.5 (22h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 17
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