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

# Server Metrics 2026-03-11 22:13:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1710.7 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3104
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 2990
telemt_upstream_connect_success_total 2989
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2987
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 35121570 (33.49 MB)
telemt_user_octets_to_client{user="hello"} 1840135186 (1.71 GB)
telemt_user_msgs_from_client{user="hello"} 78907
telemt_user_msgs_to_client{user="hello"} 282306
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 1699.0 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1268
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 1224
telemt_upstream_connect_success_total 1224
telemt_upstream_connect_attempts_per_request{bucket="1"} 1224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1222
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 7936572 (7.57 MB)
telemt_user_octets_to_client{user="hello"} 205219162 (195.71 MB)
telemt_user_msgs_from_client{user="hello"} 19315
telemt_user_msgs_to_client{user="hello"} 88167
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 1672.6 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3124
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 29
telemt_upstream_connect_attempt_total 2270
telemt_upstream_connect_success_total 2270
telemt_upstream_connect_attempts_per_request{bucket="1"} 2270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 293
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2268
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 14363769 (13.70 MB)
telemt_user_octets_to_client{user="hello"} 1369702201 (1.28 GB)
telemt_user_msgs_from_client{user="hello"} 43431
telemt_user_msgs_to_client{user="hello"} 425900
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 1698.0 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1774
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 1671
telemt_upstream_connect_success_total 1669
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1667
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 16158991 (15.41 MB)
telemt_user_octets_to_client{user="hello"} 697592882 (665.28 MB)
telemt_user_msgs_from_client{user="hello"} 29641
telemt_user_msgs_to_client{user="hello"} 267140
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1699.2 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1986
telemt_connections_bad_total 340
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1617
telemt_upstream_connect_success_total 1617
telemt_upstream_connect_attempts_per_request{bucket="1"} 1617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1615
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 18451482 (17.60 MB)
telemt_user_octets_to_client{user="hello"} 1063466049 (1014.20 MB)
telemt_user_msgs_from_client{user="hello"} 25876
telemt_user_msgs_to_client{user="hello"} 188571
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 1698.7 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1756
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1560
telemt_upstream_connect_success_total 1560
telemt_upstream_connect_attempts_per_request{bucket="1"} 1560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 289
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1558
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 35760517 (34.10 MB)
telemt_user_octets_to_client{user="hello"} 2183049671 (2.03 GB)
telemt_user_msgs_from_client{user="hello"} 43993
telemt_user_msgs_to_client{user="hello"} 169146
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 9
```