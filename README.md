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

# Server Metrics 2026-03-11 08:33:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 65231.1 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184598
telemt_connections_bad_total 3547
telemt_handshake_timeouts_total 4124
telemt_upstream_connect_attempt_total 168160
telemt_upstream_connect_success_total 168109
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 168160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 153519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 168101
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 3776218308 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 105502964165 (98.26 GB)
telemt_user_msgs_from_client{user="hello"} 4069371
telemt_user_msgs_to_client{user="hello"} 7625032
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 65230.7 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71701
telemt_connections_bad_total 587
telemt_handshake_timeouts_total 3108
telemt_upstream_connect_attempt_total 64621
telemt_upstream_connect_success_total 64607
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 64621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 238
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64601
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 4887815687 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 53194789269 (49.54 GB)
telemt_user_msgs_from_client{user="hello"} 3047332
telemt_user_msgs_to_client{user="hello"} 13500623
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 65230.3 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99433
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 5185
telemt_upstream_connect_attempt_total 87518
telemt_upstream_connect_success_total 87515
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 87518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9730
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87507
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 11929859325 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 75563518306 (70.37 GB)
telemt_user_msgs_from_client{user="hello"} 5472079
telemt_user_msgs_to_client{user="hello"} 14749480
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 65229.5 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109217
telemt_connections_bad_total 223
telemt_handshake_timeouts_total 929
telemt_upstream_connect_attempt_total 103983
telemt_upstream_connect_success_total 103747
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 103982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13909
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103739
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 4495400387 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 71870645492 (66.93 GB)
telemt_user_msgs_from_client{user="hello"} 3092315
telemt_user_msgs_to_client{user="hello"} 18244986
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 65230.5 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178031
telemt_connections_bad_total 14370
telemt_handshake_timeouts_total 2971
telemt_upstream_connect_attempt_total 141532
telemt_upstream_connect_success_total 141282
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 141532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 141276
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 2854785109 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 131774627433 (122.72 GB)
telemt_user_msgs_from_client{user="hello"} 3218519
telemt_user_msgs_to_client{user="hello"} 16993158
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 44199.9 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410
telemt_connections_bad_total 388
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