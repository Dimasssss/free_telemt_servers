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

# Server Metrics 2026-03-10 22:06:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 27628.7 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93086
telemt_connections_bad_total 3290
telemt_handshake_timeouts_total 2181
telemt_upstream_connect_attempt_total 83476
telemt_upstream_connect_success_total 83444
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 83476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83440
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 2531486377 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 66162140439 (61.62 GB)
telemt_user_msgs_from_client{user="hello"} 2418184
telemt_user_msgs_to_client{user="hello"} 4360826
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 27628.4 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35369
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 707
telemt_upstream_connect_attempt_total 32213
telemt_upstream_connect_success_total 32204
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 32213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4731
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32200
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 1662805690 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 33331422883 (31.04 GB)
telemt_user_msgs_from_client{user="hello"} 1332266
telemt_user_msgs_to_client{user="hello"} 8456270
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 27628.1 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57493
telemt_connections_bad_total 423
telemt_handshake_timeouts_total 3970
telemt_upstream_connect_attempt_total 49851
telemt_upstream_connect_success_total 49849
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 49851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4762
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49845
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 765715242 (730.24 MB)
telemt_user_octets_to_client{user="hello"} 46745983901 (43.54 GB)
telemt_user_msgs_from_client{user="hello"} 1064231
telemt_user_msgs_to_client{user="hello"} 7024747
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 27626.9 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52773
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 322
telemt_upstream_connect_attempt_total 50674
telemt_upstream_connect_success_total 50532
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 50674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50528
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 816062385 (778.26 MB)
telemt_user_octets_to_client{user="hello"} 37032619623 (34.49 GB)
telemt_user_msgs_from_client{user="hello"} 1102619
telemt_user_msgs_to_client{user="hello"} 7061877
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 27628.3 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76278
telemt_connections_bad_total 6915
telemt_handshake_timeouts_total 1408
telemt_upstream_connect_attempt_total 64927
telemt_upstream_connect_success_total 64683
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 64927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64679
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2019245451 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 49669580562 (46.26 GB)
telemt_user_msgs_from_client{user="hello"} 1834431
telemt_user_msgs_to_client{user="hello"} 7175514
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 6597.7 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```