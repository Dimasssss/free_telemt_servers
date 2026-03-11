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

# Server Metrics 2026-03-11 22:28:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2630.8 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4238
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 4086
telemt_upstream_connect_success_total 4085
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 481
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4083
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 41667651 (39.74 MB)
telemt_user_octets_to_client{user="hello"} 2144849022 (2.00 GB)
telemt_user_msgs_from_client{user="hello"} 94661
telemt_user_msgs_to_client{user="hello"} 337288
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2619.0 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1739
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1664
telemt_upstream_connect_success_total 1664
telemt_upstream_connect_attempts_per_request{bucket="1"} 1664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1662
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 9525543 (9.08 MB)
telemt_user_octets_to_client{user="hello"} 233246004 (222.44 MB)
telemt_user_msgs_from_client{user="hello"} 23103
telemt_user_msgs_to_client{user="hello"} 102304
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 2592.6 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4072
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 3140
telemt_upstream_connect_success_total 3140
telemt_upstream_connect_attempts_per_request{bucket="1"} 3140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 372
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3138
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 19008428 (18.13 MB)
telemt_user_octets_to_client{user="hello"} 1928549159 (1.80 GB)
telemt_user_msgs_from_client{user="hello"} 59736
telemt_user_msgs_to_client{user="hello"} 534919
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2617.9 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2705
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 2554
telemt_upstream_connect_success_total 2551
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2549
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 25289288 (24.12 MB)
telemt_user_octets_to_client{user="hello"} 774564712 (738.68 MB)
telemt_user_msgs_from_client{user="hello"} 38642
telemt_user_msgs_to_client{user="hello"} 297859
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2619.4 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2651
telemt_connections_bad_total 504
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2110
telemt_upstream_connect_success_total 2110
telemt_upstream_connect_attempts_per_request{bucket="1"} 2110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2108
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 19766160 (18.85 MB)
telemt_user_octets_to_client{user="hello"} 1077724443 (1.00 GB)
telemt_user_msgs_from_client{user="hello"} 29069
telemt_user_msgs_to_client{user="hello"} 194500
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 2618.7 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2971
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 2487
telemt_upstream_connect_success_total 2487
telemt_upstream_connect_attempts_per_request{bucket="1"} 2487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 416
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2485
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 55187024 (52.63 MB)
telemt_user_octets_to_client{user="hello"} 8390444660 (7.81 GB)
telemt_user_msgs_from_client{user="hello"} 85199
telemt_user_msgs_to_client{user="hello"} 465630
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```