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

# Server Metrics 2026-03-12 06:04:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 29965.9 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77434
telemt_connections_bad_total 2109
telemt_handshake_timeouts_total 2252
telemt_upstream_connect_attempt_total 69537
telemt_upstream_connect_success_total 69507
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 69537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69503
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 705405796 (672.73 MB)
telemt_user_octets_to_client{user="hello"} 21244417934 (19.79 GB)
telemt_user_msgs_from_client{user="hello"} 1034224
telemt_user_msgs_to_client{user="hello"} 2442747
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 29954.1 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31083
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 152
telemt_upstream_connect_attempt_total 29627
telemt_upstream_connect_success_total 29617
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29613
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 278116670 (265.23 MB)
telemt_user_octets_to_client{user="hello"} 15178686631 (14.14 GB)
telemt_user_msgs_from_client{user="hello"} 554153
telemt_user_msgs_to_client{user="hello"} 4720984
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 29927.8 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47942
telemt_connections_bad_total 674
telemt_handshake_timeouts_total 1060
telemt_upstream_connect_attempt_total 43201
telemt_upstream_connect_success_total 43194
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 43201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43190
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 5373085754 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 27323934726 (25.45 GB)
telemt_user_msgs_from_client{user="hello"} 2618241
telemt_user_msgs_to_client{user="hello"} 4892445
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 29953.0 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52919
telemt_connections_bad_total 12927
telemt_handshake_timeouts_total 844
telemt_upstream_connect_attempt_total 37180
telemt_upstream_connect_success_total 35470
telemt_upstream_connect_fail_total 1710
telemt_upstream_connect_attempts_per_request{bucket="1"} 37180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1710
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35466
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 1217575670 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 23394386501 (21.79 GB)
telemt_user_msgs_from_client{user="hello"} 941381
telemt_user_msgs_to_client{user="hello"} 9684150
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 145.7 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 448
telemt_upstream_connect_success_total 447
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 445
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 5801144 (5.53 MB)
telemt_user_octets_to_client{user="hello"} 96796674 (92.31 MB)
telemt_user_msgs_from_client{user="hello"} 5951
telemt_user_msgs_to_client{user="hello"} 22715
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 29953.9 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47227
telemt_connections_bad_total 766
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 43968
telemt_upstream_connect_success_total 43956
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 43967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43952
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 815194556 (777.43 MB)
telemt_user_octets_to_client{user="hello"} 41462753040 (38.62 GB)
telemt_user_msgs_from_client{user="hello"} 1172691
telemt_user_msgs_to_client{user="hello"} 5516525
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 27
```