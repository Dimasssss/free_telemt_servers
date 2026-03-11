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

# Server Metrics 2026-03-11 05:55:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 55748.4 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146021
telemt_connections_bad_total 3480
telemt_handshake_timeouts_total 3799
telemt_upstream_connect_attempt_total 131518
telemt_upstream_connect_success_total 131474
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 131518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 131468
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 3183085959 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 90445117511 (84.23 GB)
telemt_user_msgs_from_client{user="hello"} 3368800
telemt_user_msgs_to_client{user="hello"} 6368060
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 55747.8 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58346
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 2982
telemt_upstream_connect_attempt_total 51941
telemt_upstream_connect_success_total 51929
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 51941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51923
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 4545117405 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 47604903723 (44.34 GB)
telemt_user_msgs_from_client{user="hello"} 2744192
telemt_user_msgs_to_client{user="hello"} 11262879
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 55747.3 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79507
telemt_connections_bad_total 726
telemt_handshake_timeouts_total 4347
telemt_upstream_connect_attempt_total 69976
telemt_upstream_connect_success_total 69973
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 69976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7869
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69967
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 11800132283 (10.99 GB)
telemt_user_octets_to_client{user="hello"} 71578275100 (66.66 GB)
telemt_user_msgs_from_client{user="hello"} 5223358
telemt_user_msgs_to_client{user="hello"} 13504897
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 55746.5 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84252
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 623
telemt_upstream_connect_attempt_total 80648
telemt_upstream_connect_success_total 80471
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 80648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10607
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80465
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 1874212916 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 53518501560 (49.84 GB)
telemt_user_msgs_from_client{user="hello"} 1827766
telemt_user_msgs_to_client{user="hello"} 12450538
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 55747.7 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141604
telemt_connections_bad_total 12446
telemt_handshake_timeouts_total 1745
telemt_upstream_connect_attempt_total 114469
telemt_upstream_connect_success_total 114220
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 114469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114214
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 2451364651 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 109411331613 (101.90 GB)
telemt_user_msgs_from_client{user="hello"} 2730208
telemt_user_msgs_to_client{user="hello"} 14513886
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 34717.1 (9h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 7
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