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

# Server Metrics 2026-03-11 10:51:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 73517.7 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220648
telemt_connections_bad_total 3618
telemt_handshake_timeouts_total 4425
telemt_upstream_connect_attempt_total 202625
telemt_upstream_connect_success_total 202561
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 202625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 185298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 202553
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 4341396235 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 116978804354 (108.95 GB)
telemt_user_msgs_from_client{user="hello"} 4778720
telemt_user_msgs_to_client{user="hello"} 8851848
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 73516.7 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86627
telemt_connections_bad_total 800
telemt_handshake_timeouts_total 3198
telemt_upstream_connect_attempt_total 78632
telemt_upstream_connect_success_total 78616
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 78632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 260
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78608
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 5036450299 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 56735648717 (52.84 GB)
telemt_user_msgs_from_client{user="hello"} 3261164
telemt_user_msgs_to_client{user="hello"} 14861063
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 73516.4 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119548
telemt_connections_bad_total 1078
telemt_handshake_timeouts_total 5337
telemt_upstream_connect_attempt_total 106265
telemt_upstream_connect_success_total 106261
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 106265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11925
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106253
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 12311022173 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 87025312810 (81.05 GB)
telemt_user_msgs_from_client{user="hello"} 5923291
telemt_user_msgs_to_client{user="hello"} 17126284
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 73515.5 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131063
telemt_connections_bad_total 324
telemt_handshake_timeouts_total 1233
telemt_upstream_connect_attempt_total 124269
telemt_upstream_connect_success_total 123979
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 124268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 66
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 340
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 123971
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 5660750540 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 90096275559 (83.91 GB)
telemt_user_msgs_from_client{user="hello"} 3806417
telemt_user_msgs_to_client{user="hello"} 24159418
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 73516.8 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204089
telemt_connections_bad_total 15949
telemt_handshake_timeouts_total 3419
telemt_upstream_connect_attempt_total 164188
telemt_upstream_connect_success_total 163786
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 164188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 140770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 305
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 163778
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 3628322951 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 143036564545 (133.21 GB)
telemt_user_msgs_from_client{user="hello"} 3781595
telemt_user_msgs_to_client{user="hello"} 19085603
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 52486.2 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422
telemt_connections_bad_total 400
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