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

# Server Metrics 2026-03-11 02:41:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 44133.0 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116262
telemt_connections_bad_total 3356
telemt_handshake_timeouts_total 2560
telemt_upstream_connect_attempt_total 105069
telemt_upstream_connect_success_total 105032
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 105069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105026
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 2895992095 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 81289109228 (75.71 GB)
telemt_user_msgs_from_client{user="hello"} 2937554
telemt_user_msgs_to_client{user="hello"} 5628263
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 44132.4 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48217
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 2694
telemt_upstream_connect_attempt_total 42508
telemt_upstream_connect_success_total 42499
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 42508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42495
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 2270085463 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 41546532617 (38.69 GB)
telemt_user_msgs_from_client{user="hello"} 1749223
telemt_user_msgs_to_client{user="hello"} 10084098
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 44132.1 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69104
telemt_connections_bad_total 656
telemt_handshake_timeouts_total 4203
telemt_upstream_connect_attempt_total 60363
telemt_upstream_connect_success_total 60361
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 60363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60355
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 11741268258 (10.93 GB)
telemt_user_octets_to_client{user="hello"} 70006939182 (65.20 GB)
telemt_user_msgs_from_client{user="hello"} 5125780
telemt_user_msgs_to_client{user="hello"} 13128252
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 44131.0 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67779
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 543
telemt_upstream_connect_attempt_total 64839
telemt_upstream_connect_success_total 64682
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 64839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8065
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64676
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 1760037342 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 42647070921 (39.72 GB)
telemt_user_msgs_from_client{user="hello"} 1588116
telemt_user_msgs_to_client{user="hello"} 8359448
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 44132.4 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102088
telemt_connections_bad_total 10187
telemt_handshake_timeouts_total 1525
telemt_upstream_connect_attempt_total 86572
telemt_upstream_connect_success_total 86324
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 86572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86320
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 2189215366 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 74551961788 (69.43 GB)
telemt_user_msgs_from_client{user="hello"} 2226284
telemt_user_msgs_to_client{user="hello"} 10345889
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 23101.8 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```