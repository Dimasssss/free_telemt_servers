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

# Server Metrics 2026-03-12 00:35:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10202.9 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19622
telemt_connections_bad_total 1804
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 17085
telemt_upstream_connect_success_total 17080
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17078
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 197167989 (188.03 MB)
telemt_user_octets_to_client{user="hello"} 6695805973 (6.24 GB)
telemt_user_msgs_from_client{user="hello"} 342492
telemt_user_msgs_to_client{user="hello"} 890068
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 10191.4 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7951
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 7628
telemt_upstream_connect_success_total 7628
telemt_upstream_connect_attempts_per_request{bucket="1"} 7628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 998
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7626
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 50716720 (48.37 MB)
telemt_user_octets_to_client{user="hello"} 2533914465 (2.36 GB)
telemt_user_msgs_from_client{user="hello"} 126593
telemt_user_msgs_to_client{user="hello"} 848274
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 10165.0 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13310
telemt_connections_bad_total 279
telemt_handshake_timeouts_total 781
telemt_upstream_connect_attempt_total 10775
telemt_upstream_connect_success_total 10775
telemt_upstream_connect_attempts_per_request{bucket="1"} 10775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10773
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 66759826 (63.67 MB)
telemt_user_octets_to_client{user="hello"} 6074954649 (5.66 GB)
telemt_user_msgs_from_client{user="hello"} 210348
telemt_user_msgs_to_client{user="hello"} 1415724
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 10190.3 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12176
telemt_connections_bad_total 2212
telemt_handshake_timeouts_total 251
telemt_upstream_connect_attempt_total 9340
telemt_upstream_connect_success_total 9329
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 9340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1099
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9327
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 68280861 (65.12 MB)
telemt_user_octets_to_client{user="hello"} 4065417686 (3.79 GB)
telemt_user_msgs_from_client{user="hello"} 144869
telemt_user_msgs_to_client{user="hello"} 1475188
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 10191.1 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10081
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 8933
telemt_upstream_connect_success_total 8933
telemt_upstream_connect_attempts_per_request{bucket="1"} 8933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1447
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8931
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 123944746 (118.20 MB)
telemt_user_octets_to_client{user="hello"} 16899540587 (15.74 GB)
telemt_user_msgs_from_client{user="hello"} 259235
telemt_user_msgs_to_client{user="hello"} 1518556
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 11
```