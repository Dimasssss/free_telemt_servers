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

# Server Metrics 2026-03-11 17:26:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1584.8 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6598
telemt_connections_bad_total 377
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 5942
telemt_upstream_connect_success_total 5940
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5938
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 145467543 (138.73 MB)
telemt_user_octets_to_client{user="hello"} 3247842084 (3.02 GB)
telemt_user_msgs_from_client{user="hello"} 136318
telemt_user_msgs_to_client{user="hello"} 248247
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 1573.2 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3679
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 82
telemt_upstream_connect_attempt_total 3298
telemt_upstream_connect_success_total 3297
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3295
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 25038712 (23.88 MB)
telemt_user_octets_to_client{user="hello"} 2142221341 (2.00 GB)
telemt_user_msgs_from_client{user="hello"} 62340
telemt_user_msgs_to_client{user="hello"} 848239
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 1592.5 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3702
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 3536
telemt_upstream_connect_success_total 3536
telemt_upstream_connect_attempts_per_request{bucket="1"} 3536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 369
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3534
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 22757335 (21.70 MB)
telemt_user_octets_to_client{user="hello"} 761407936 (726.14 MB)
telemt_user_msgs_from_client{user="hello"} 60374
telemt_user_msgs_to_client{user="hello"} 294616
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 1588.2 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3839
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 3505
telemt_upstream_connect_success_total 3494
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 3505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3492
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 86601741 (82.59 MB)
telemt_user_octets_to_client{user="hello"} 1423738878 (1.33 GB)
telemt_user_msgs_from_client{user="hello"} 75880
telemt_user_msgs_to_client{user="hello"} 358557
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1596.6 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4256
telemt_connections_bad_total 344
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 3764
telemt_upstream_connect_success_total 3764
telemt_upstream_connect_attempts_per_request{bucket="1"} 3764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3762
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 21856917 (20.84 MB)
telemt_user_octets_to_client{user="hello"} 437385098 (417.12 MB)
telemt_user_msgs_from_client{user="hello"} 42938
telemt_user_msgs_to_client{user="hello"} 168497
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 76202.9 (21h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494
telemt_connections_bad_total 470
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```