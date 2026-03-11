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

# Server Metrics 2026-03-11 17:06:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 356.0 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1795
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1633
telemt_upstream_connect_success_total 1631
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1629
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 80300838 (76.58 MB)
telemt_user_octets_to_client{user="hello"} 693300196 (661.18 MB)
telemt_user_msgs_from_client{user="hello"} 46977
telemt_user_msgs_to_client{user="hello"} 56000
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 344.2 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 827
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 762
telemt_upstream_connect_success_total 761
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 759
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 4414345 (4.21 MB)
telemt_user_octets_to_client{user="hello"} 256430669 (244.55 MB)
telemt_user_msgs_from_client{user="hello"} 10377
telemt_user_msgs_to_client{user="hello"} 89252
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 363.6 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 942
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 915
telemt_upstream_connect_success_total 915
telemt_upstream_connect_attempts_per_request{bucket="1"} 915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 913
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 4433227 (4.23 MB)
telemt_user_octets_to_client{user="hello"} 276402961 (263.60 MB)
telemt_user_msgs_from_client{user="hello"} 12903
telemt_user_msgs_to_client{user="hello"} 107994
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 359.5 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1004
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 919
telemt_upstream_connect_success_total 917
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 915
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 9587278 (9.14 MB)
telemt_user_octets_to_client{user="hello"} 304503276 (290.40 MB)
telemt_user_msgs_from_client{user="hello"} 13724
telemt_user_msgs_to_client{user="hello"} 81731
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 367.6 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1232
telemt_connections_bad_total 86
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1098
telemt_upstream_connect_success_total 1098
telemt_upstream_connect_attempts_per_request{bucket="1"} 1098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1096
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 4931601 (4.70 MB)
telemt_user_octets_to_client{user="hello"} 125369023 (119.56 MB)
telemt_user_msgs_from_client{user="hello"} 9465
telemt_user_msgs_to_client{user="hello"} 41693
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 74974.0 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491
telemt_connections_bad_total 467
telemt_handshake_timeouts_total 13
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