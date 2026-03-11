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

# Server Metrics 2026-03-11 14:21:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 86119.8 (23h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283988
telemt_connections_bad_total 3679
telemt_handshake_timeouts_total 4780
telemt_upstream_connect_attempt_total 262802
telemt_upstream_connect_success_total 262724
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 262801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 240415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 262714
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 5019923812 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 133882743642 (124.69 GB)
telemt_user_msgs_from_client{user="hello"} 5802597
telemt_user_msgs_to_client{user="hello"} 10614610
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 86119.3 (23h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112114
telemt_connections_bad_total 922
telemt_handshake_timeouts_total 3356
telemt_upstream_connect_attempt_total 102958
telemt_upstream_connect_success_total 102937
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 102957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 446
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 102927
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 5936522296 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 67896459781 (63.23 GB)
telemt_user_msgs_from_client{user="hello"} 3894315
telemt_user_msgs_to_client{user="hello"} 19382635
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 86118.8 (23h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156148
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 6908
telemt_upstream_connect_attempt_total 139309
telemt_upstream_connect_success_total 139295
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 139309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 123932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 139285
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 12671885706 (11.80 GB)
telemt_user_octets_to_client{user="hello"} 127534819626 (118.78 GB)
telemt_user_msgs_from_client{user="hello"} 6682623
telemt_user_msgs_to_client{user="hello"} 28421401
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 86117.7 (23h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173394
telemt_connections_bad_total 6838
telemt_handshake_timeouts_total 1954
telemt_upstream_connect_attempt_total 157621
telemt_upstream_connect_success_total 157240
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 157621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 136679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20042
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 430
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 157230
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 9500051027 (8.85 GB)
telemt_user_octets_to_client{user="hello"} 110699034879 (103.10 GB)
telemt_user_msgs_from_client{user="hello"} 5634343
telemt_user_msgs_to_client{user="hello"} 32819878
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 86119.0 (23h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248710
telemt_connections_bad_total 19066
telemt_handshake_timeouts_total 6222
telemt_upstream_connect_attempt_total 201707
telemt_upstream_connect_success_total 201204
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 201707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 174147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 201196
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 4967242942 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 161119407189 (150.05 GB)
telemt_user_msgs_from_client{user="hello"} 4747243
telemt_user_msgs_to_client{user="hello"} 22228667
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 65088.4 (18h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454
telemt_connections_bad_total 432
telemt_handshake_timeouts_total 10
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