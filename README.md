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

# Server Metrics 2026-03-11 17:11:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 663.3 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3149
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 2851
telemt_upstream_connect_success_total 2849
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2847
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 102344288 (97.60 MB)
telemt_user_octets_to_client{user="hello"} 915092052 (872.70 MB)
telemt_user_msgs_from_client{user="hello"} 67857
telemt_user_msgs_to_client{user="hello"} 86749
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 651.8 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1561
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 1383
telemt_upstream_connect_success_total 1382
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1380
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 8363758 (7.98 MB)
telemt_user_octets_to_client{user="hello"} 476083032 (454.03 MB)
telemt_user_msgs_from_client{user="hello"} 20155
telemt_user_msgs_to_client{user="hello"} 155325
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 671.1 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1765
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 1703
telemt_upstream_connect_success_total 1703
telemt_upstream_connect_attempts_per_request{bucket="1"} 1703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1701
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 9270715 (8.84 MB)
telemt_user_octets_to_client{user="hello"} 381658601 (363.98 MB)
telemt_user_msgs_from_client{user="hello"} 25024
telemt_user_msgs_to_client{user="hello"} 150795
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 666.9 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1683
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 1541
telemt_upstream_connect_success_total 1537
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1535
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 13833283 (13.19 MB)
telemt_user_octets_to_client{user="hello"} 617985241 (589.36 MB)
telemt_user_msgs_from_client{user="hello"} 25628
telemt_user_msgs_to_client{user="hello"} 148158
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 675.1 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1974
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1770
telemt_upstream_connect_success_total 1770
telemt_upstream_connect_attempts_per_request{bucket="1"} 1770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 252
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1768
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 9681206 (9.23 MB)
telemt_user_octets_to_client{user="hello"} 186425131 (177.79 MB)
telemt_user_msgs_from_client{user="hello"} 17040
telemt_user_msgs_to_client{user="hello"} 66641
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 75281.4 (20h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492
telemt_connections_bad_total 468
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