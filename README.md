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

# Server Metrics 2026-03-11 07:06:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 60028.4 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163003
telemt_connections_bad_total 3504
telemt_handshake_timeouts_total 3973
telemt_upstream_connect_attempt_total 147381
telemt_upstream_connect_success_total 147336
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 147381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 147328
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 3494080522 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 96578029420 (89.95 GB)
telemt_user_msgs_from_client{user="hello"} 3702018
telemt_user_msgs_to_client{user="hello"} 6922533
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 60028.0 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64142
telemt_connections_bad_total 456
telemt_handshake_timeouts_total 3065
telemt_upstream_connect_attempt_total 57453
telemt_upstream_connect_success_total 57439
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 57452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57433
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 4656139924 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 49633589482 (46.22 GB)
telemt_user_msgs_from_client{user="hello"} 2865269
telemt_user_msgs_to_client{user="hello"} 11993622
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 60027.6 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86725
telemt_connections_bad_total 743
telemt_handshake_timeouts_total 4418
telemt_upstream_connect_attempt_total 76382
telemt_upstream_connect_success_total 76379
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 76382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76373
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 11850355007 (11.04 GB)
telemt_user_octets_to_client{user="hello"} 73970864649 (68.89 GB)
telemt_user_msgs_from_client{user="hello"} 5317037
telemt_user_msgs_to_client{user="hello"} 14150193
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 60026.6 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93926
telemt_connections_bad_total 213
telemt_handshake_timeouts_total 655
telemt_upstream_connect_attempt_total 89984
telemt_upstream_connect_success_total 89783
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 89983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89777
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 2010498920 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 60057467685 (55.93 GB)
telemt_user_msgs_from_client{user="hello"} 2023182
telemt_user_msgs_to_client{user="hello"} 14764705
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 60027.8 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159013
telemt_connections_bad_total 13273
telemt_handshake_timeouts_total 1825
telemt_upstream_connect_attempt_total 126136
telemt_upstream_connect_success_total 125887
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 126136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 125881
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 2547918225 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 121702285665 (113.34 GB)
telemt_user_msgs_from_client{user="hello"} 2922194
telemt_user_msgs_to_client{user="hello"} 15595095
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 38997.2 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```