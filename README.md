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

# Server Metrics 2026-03-11 09:39:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 69218.1 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202743
telemt_connections_bad_total 3592
telemt_handshake_timeouts_total 4275
telemt_upstream_connect_attempt_total 185537
telemt_upstream_connect_success_total 185478
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 185537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 169431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 185470
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 4061420809 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 110521717097 (102.93 GB)
telemt_user_msgs_from_client{user="hello"} 4403833
telemt_user_msgs_to_client{user="hello"} 8213644
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 69217.6 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78841
telemt_connections_bad_total 779
telemt_handshake_timeouts_total 3143
telemt_upstream_connect_attempt_total 71230
telemt_upstream_connect_success_total 71214
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 71230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 250
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71206
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 4946863217 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 55294887885 (51.50 GB)
telemt_user_msgs_from_client{user="hello"} 3142313
telemt_user_msgs_to_client{user="hello"} 14187710
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 69218.0 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109030
telemt_connections_bad_total 991
telemt_handshake_timeouts_total 5223
telemt_upstream_connect_attempt_total 96639
telemt_upstream_connect_success_total 96635
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 96639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10947
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 96627
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 11995011911 (11.17 GB)
telemt_user_octets_to_client{user="hello"} 80731583766 (75.19 GB)
telemt_user_msgs_from_client{user="hello"} 5645177
telemt_user_msgs_to_client{user="hello"} 15683865
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 69217.5 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120526
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 1113
telemt_upstream_connect_attempt_total 114463
telemt_upstream_connect_success_total 114202
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 114462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15299
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 58
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 312
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114194
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 5501297654 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 81809643135 (76.19 GB)
telemt_user_msgs_from_client{user="hello"} 3600448
telemt_user_msgs_to_client{user="hello"} 21090425
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 69217.6 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190312
telemt_connections_bad_total 15095
telemt_handshake_timeouts_total 3328
telemt_upstream_connect_attempt_total 152234
telemt_upstream_connect_success_total 151832
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 152234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 151826
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 2970288495 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 135184786666 (125.90 GB)
telemt_user_msgs_from_client{user="hello"} 3388635
telemt_user_msgs_to_client{user="hello"} 17652899
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 48188.1 (13h 23m)
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