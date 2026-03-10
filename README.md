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

# Server Metrics 2026-03-10 21:25:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 25180.5 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89663
telemt_connections_bad_total 3272
telemt_handshake_timeouts_total 2166
telemt_upstream_connect_attempt_total 80233
telemt_upstream_connect_success_total 80201
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 80233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80197
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 2489577931 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 61971940662 (57.72 GB)
telemt_user_msgs_from_client{user="hello"} 2343857
telemt_user_msgs_to_client{user="hello"} 4202123
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 25179.8 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34093
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 632
telemt_upstream_connect_attempt_total 31092
telemt_upstream_connect_success_total 31083
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 31092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31079
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 1621260816 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 28098277089 (26.17 GB)
telemt_user_msgs_from_client{user="hello"} 1262150
telemt_user_msgs_to_client{user="hello"} 7852971
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 25179.6 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55038
telemt_connections_bad_total 407
telemt_handshake_timeouts_total 3733
telemt_upstream_connect_attempt_total 47786
telemt_upstream_connect_success_total 47784
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 47786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47780
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 741849364 (707.48 MB)
telemt_user_octets_to_client{user="hello"} 42895187359 (39.95 GB)
telemt_user_msgs_from_client{user="hello"} 1009669
telemt_user_msgs_to_client{user="hello"} 6484942
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 25178.4 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49513
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 316
telemt_upstream_connect_attempt_total 47510
telemt_upstream_connect_success_total 47374
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47370
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 790219044 (753.61 MB)
telemt_user_octets_to_client{user="hello"} 36067605214 (33.59 GB)
telemt_user_msgs_from_client{user="hello"} 1053398
telemt_user_msgs_to_client{user="hello"} 6833347
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 25179.7 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72146
telemt_connections_bad_total 6426
telemt_handshake_timeouts_total 1397
telemt_upstream_connect_attempt_total 61398
telemt_upstream_connect_success_total 61154
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 61398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61150
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 1851878781 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 46019952208 (42.86 GB)
telemt_user_msgs_from_client{user="hello"} 1693604
telemt_user_msgs_to_client{user="hello"} 6446794
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 4149.1 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19
telemt_connections_bad_total 19
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```