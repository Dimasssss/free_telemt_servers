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

# Server Metrics 2026-03-11 00:34:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 36495.2 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103776
telemt_connections_bad_total 3342
telemt_handshake_timeouts_total 2492
telemt_upstream_connect_attempt_total 93352
telemt_upstream_connect_success_total 93318
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 93352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93314
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 2695149463 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 76033369931 (70.81 GB)
telemt_user_msgs_from_client{user="hello"} 2713006
telemt_user_msgs_to_client{user="hello"} 5197929
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 36494.7 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41165
telemt_connections_bad_total 342
telemt_handshake_timeouts_total 975
telemt_upstream_connect_attempt_total 37458
telemt_upstream_connect_success_total 37448
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 37457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37444
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 2011428435 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 38512091319 (35.87 GB)
telemt_user_msgs_from_client{user="hello"} 1589084
telemt_user_msgs_to_client{user="hello"} 9528219
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 36494.7 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63889
telemt_connections_bad_total 458
telemt_handshake_timeouts_total 4091
telemt_upstream_connect_attempt_total 55720
telemt_upstream_connect_success_total 55718
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 55720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5720
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55714
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 8170574656 (7.61 GB)
telemt_user_octets_to_client{user="hello"} 58195844278 (54.20 GB)
telemt_user_msgs_from_client{user="hello"} 3762245
telemt_user_msgs_to_client{user="hello"} 8700432
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 36493.4 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61081
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 526
telemt_upstream_connect_attempt_total 58446
telemt_upstream_connect_success_total 58292
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 58446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7076
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58288
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 849924285 (810.55 MB)
telemt_user_octets_to_client{user="hello"} 38355868677 (35.72 GB)
telemt_user_msgs_from_client{user="hello"} 1184286
telemt_user_msgs_to_client{user="hello"} 7467435
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 36494.7 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88518
telemt_connections_bad_total 8663
telemt_handshake_timeouts_total 1473
telemt_upstream_connect_attempt_total 75079
telemt_upstream_connect_success_total 74831
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 75079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74827
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2108952196 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 60540636243 (56.38 GB)
telemt_user_msgs_from_client{user="hello"} 2043583
telemt_user_msgs_to_client{user="hello"} 8688563
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 15464.1 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```