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

# Server Metrics 2026-03-11 09:09:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 67378.5 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194327
telemt_connections_bad_total 3558
telemt_handshake_timeouts_total 4205
telemt_upstream_connect_attempt_total 177446
telemt_upstream_connect_success_total 177391
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 177446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 161894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 177383
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 3914066575 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 107900758465 (100.49 GB)
telemt_user_msgs_from_client{user="hello"} 4238698
telemt_user_msgs_to_client{user="hello"} 7942351
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 67377.7 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75273
telemt_connections_bad_total 596
telemt_handshake_timeouts_total 3136
telemt_upstream_connect_attempt_total 68023
telemt_upstream_connect_success_total 68008
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 68023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9239
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68002
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 4924663920 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 53864425401 (50.17 GB)
telemt_user_msgs_from_client{user="hello"} 3098736
telemt_user_msgs_to_client{user="hello"} 13837944
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 67378.2 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104395
telemt_connections_bad_total 929
telemt_handshake_timeouts_total 5208
telemt_upstream_connect_attempt_total 92246
telemt_upstream_connect_success_total 92242
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 92246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 92234
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 11963144081 (11.14 GB)
telemt_user_octets_to_client{user="hello"} 78219182835 (72.85 GB)
telemt_user_msgs_from_client{user="hello"} 5554565
telemt_user_msgs_to_client{user="hello"} 15248902
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 67376.5 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115614
telemt_connections_bad_total 227
telemt_handshake_timeouts_total 1045
telemt_upstream_connect_attempt_total 109811
telemt_upstream_connect_success_total 109562
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 109811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 298
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 109554
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 4701708134 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 78340733644 (72.96 GB)
telemt_user_msgs_from_client{user="hello"} 3253660
telemt_user_msgs_to_client{user="hello"} 20097637
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 67377.6 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184424
telemt_connections_bad_total 14766
telemt_handshake_timeouts_total 3099
telemt_upstream_connect_attempt_total 147193
telemt_upstream_connect_success_total 146791
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 147193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 125826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 278
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 146785
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 2889322305 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 133646214690 (124.47 GB)
telemt_user_msgs_from_client{user="hello"} 3294222
telemt_user_msgs_to_client{user="hello"} 17369640
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 46347.0 (12h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```