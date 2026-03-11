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

# Server Metrics 2026-03-11 22:33:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2937.6 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4636
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 4473
telemt_upstream_connect_success_total 4472
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4470
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 43333995 (41.33 MB)
telemt_user_octets_to_client{user="hello"} 2284567489 (2.13 GB)
telemt_user_msgs_from_client{user="hello"} 98824
telemt_user_msgs_to_client{user="hello"} 343900
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2926.0 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1932
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1845
telemt_upstream_connect_success_total 1845
telemt_upstream_connect_attempts_per_request{bucket="1"} 1845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1843
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 10453717 (9.97 MB)
telemt_user_octets_to_client{user="hello"} 244164086 (232.85 MB)
telemt_user_msgs_from_client{user="hello"} 25230
telemt_user_msgs_to_client{user="hello"} 106945
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 2899.6 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4475
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 3508
telemt_upstream_connect_success_total 3508
telemt_upstream_connect_attempts_per_request{bucket="1"} 3508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 458
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3506
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 21501870 (20.51 MB)
telemt_user_octets_to_client{user="hello"} 2195824504 (2.05 GB)
telemt_user_msgs_from_client{user="hello"} 67742
telemt_user_msgs_to_client{user="hello"} 588539
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2924.9 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2963
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 2806
telemt_upstream_connect_success_total 2803
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2801
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 26642995 (25.41 MB)
telemt_user_octets_to_client{user="hello"} 856233855 (816.57 MB)
telemt_user_msgs_from_client{user="hello"} 42089
telemt_user_msgs_to_client{user="hello"} 334032
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2926.2 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2983
telemt_connections_bad_total 560
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 2382
telemt_upstream_connect_success_total 2382
telemt_upstream_connect_attempts_per_request{bucket="1"} 2382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2380
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 23958687 (22.85 MB)
telemt_user_octets_to_client{user="hello"} 1109479736 (1.03 GB)
telemt_user_msgs_from_client{user="hello"} 32019
telemt_user_msgs_to_client{user="hello"} 201187
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 2925.7 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3249
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 2697
telemt_upstream_connect_success_total 2697
telemt_upstream_connect_attempts_per_request{bucket="1"} 2697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 459
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2695
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 58924694 (56.19 MB)
telemt_user_octets_to_client{user="hello"} 9229655246 (8.60 GB)
telemt_user_msgs_from_client{user="hello"} 95661
telemt_user_msgs_to_client{user="hello"} 534746
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 6
```