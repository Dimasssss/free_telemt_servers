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

# Server Metrics 2026-03-11 20:36:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12948.0 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46405
telemt_connections_bad_total 2484
telemt_handshake_timeouts_total 213
telemt_upstream_connect_attempt_total 41738
telemt_upstream_connect_success_total 41728
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 41738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41726
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 1419799372 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 24377899185 (22.70 GB)
telemt_user_msgs_from_client{user="hello"} 1158182
telemt_user_msgs_to_client{user="hello"} 2055105
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12936.4 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21388
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 256
telemt_upstream_connect_attempt_total 19723
telemt_upstream_connect_success_total 19684
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 19723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19682
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 231426980 (220.71 MB)
telemt_user_octets_to_client{user="hello"} 10424879565 (9.71 GB)
telemt_user_msgs_from_client{user="hello"} 404689
telemt_user_msgs_to_client{user="hello"} 4208447
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12956.2 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25960
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 247
telemt_upstream_connect_attempt_total 24297
telemt_upstream_connect_success_total 24295
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 24297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24293
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 299704081 (285.82 MB)
telemt_user_octets_to_client{user="hello"} 9644731478 (8.98 GB)
telemt_user_msgs_from_client{user="hello"} 473677
telemt_user_msgs_to_client{user="hello"} 2396248
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12951.7 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28282
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 412
telemt_upstream_connect_attempt_total 24759
telemt_upstream_connect_success_total 24684
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 24759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24682
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 670959502 (639.88 MB)
telemt_user_octets_to_client{user="hello"} 13509867603 (12.58 GB)
telemt_user_msgs_from_client{user="hello"} 578972
telemt_user_msgs_to_client{user="hello"} 3936960
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12959.9 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31027
telemt_connections_bad_total 2466
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 27438
telemt_upstream_connect_success_total 27437
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 27438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27435
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 491514551 (468.74 MB)
telemt_user_octets_to_client{user="hello"} 10523293325 (9.80 GB)
telemt_user_msgs_from_client{user="hello"} 621525
telemt_user_msgs_to_client{user="hello"} 3886876
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 87566.3 (24h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1031
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 502
telemt_upstream_connect_success_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 494
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 4245400 (4.05 MB)
telemt_user_octets_to_client{user="hello"} 189210013 (180.44 MB)
telemt_user_msgs_from_client{user="hello"} 9582
telemt_user_msgs_to_client{user="hello"} 23804
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```