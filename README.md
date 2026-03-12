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

# Server Metrics 2026-03-12 01:23:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13119.8 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25116
telemt_connections_bad_total 1841
telemt_handshake_timeouts_total 151
telemt_upstream_connect_attempt_total 22288
telemt_upstream_connect_success_total 22282
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 22288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22280
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 243306643 (232.04 MB)
telemt_user_octets_to_client{user="hello"} 7713633793 (7.18 GB)
telemt_user_msgs_from_client{user="hello"} 410803
telemt_user_msgs_to_client{user="hello"} 1019602
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 13107.9 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10562
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 10140
telemt_upstream_connect_success_total 10140
telemt_upstream_connect_attempts_per_request{bucket="1"} 10140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10138
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 68185512 (65.03 MB)
telemt_user_octets_to_client{user="hello"} 3570415369 (3.33 GB)
telemt_user_msgs_from_client{user="hello"} 169662
telemt_user_msgs_to_client{user="hello"} 1142621
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 13081.6 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17352
telemt_connections_bad_total 282
telemt_handshake_timeouts_total 865
telemt_upstream_connect_attempt_total 14408
telemt_upstream_connect_success_total 14408
telemt_upstream_connect_attempts_per_request{bucket="1"} 14408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14406
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 1340318671 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 7355643747 (6.85 GB)
telemt_user_msgs_from_client{user="hello"} 713790
telemt_user_msgs_to_client{user="hello"} 1670876
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 13106.8 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18209
telemt_connections_bad_total 4676
telemt_handshake_timeouts_total 690
telemt_upstream_connect_attempt_total 12251
telemt_upstream_connect_success_total 12240
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 12251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12238
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 96898021 (92.41 MB)
telemt_user_octets_to_client{user="hello"} 5579537053 (5.20 GB)
telemt_user_msgs_from_client{user="hello"} 191212
telemt_user_msgs_to_client{user="hello"} 2111480
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 13107.7 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14080
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 12760
telemt_upstream_connect_success_total 12760
telemt_upstream_connect_attempts_per_request{bucket="1"} 12760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12758
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 194377858 (185.37 MB)
telemt_user_octets_to_client{user="hello"} 19135292296 (17.82 GB)
telemt_user_msgs_from_client{user="hello"} 352531
telemt_user_msgs_to_client{user="hello"} 1767100
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 13
```