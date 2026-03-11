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

# Server Metrics 2026-03-11 21:42:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16937.8 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55098
telemt_connections_bad_total 2723
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 49986
telemt_upstream_connect_success_total 49973
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 49986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49971
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 1508900545 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 29094315684 (27.10 GB)
telemt_user_msgs_from_client{user="hello"} 1347018
telemt_user_msgs_to_client{user="hello"} 2855784
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16926.2 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25364
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 263
telemt_upstream_connect_attempt_total 23531
telemt_upstream_connect_success_total 23491
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 23531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23489
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 277768513 (264.90 MB)
telemt_user_octets_to_client{user="hello"} 12318567897 (11.47 GB)
telemt_user_msgs_from_client{user="hello"} 496963
telemt_user_msgs_to_client{user="hello"} 4952275
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 16946.1 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31353
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 256
telemt_upstream_connect_attempt_total 29425
telemt_upstream_connect_success_total 29423
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 29425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29421
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 341107886 (325.31 MB)
telemt_user_octets_to_client{user="hello"} 13614982823 (12.68 GB)
telemt_user_msgs_from_client{user="hello"} 594256
telemt_user_msgs_to_client{user="hello"} 3211575
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16941.5 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33105
telemt_connections_bad_total 1824
telemt_handshake_timeouts_total 482
telemt_upstream_connect_attempt_total 29369
telemt_upstream_connect_success_total 29286
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 29369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2871
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29284
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 732662667 (698.72 MB)
telemt_user_octets_to_client{user="hello"} 18392787310 (17.13 GB)
telemt_user_msgs_from_client{user="hello"} 688293
telemt_user_msgs_to_client{user="hello"} 5957650
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16949.7 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36747
telemt_connections_bad_total 3240
telemt_handshake_timeouts_total 186
telemt_upstream_connect_attempt_total 32266
telemt_upstream_connect_success_total 32108
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 32266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32106
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 552972626 (527.36 MB)
telemt_user_octets_to_client{user="hello"} 11686682488 (10.88 GB)
telemt_user_msgs_from_client{user="hello"} 702457
telemt_user_msgs_to_client{user="hello"} 4263003
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 91556.0 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4363
telemt_connections_bad_total 658
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 3592
telemt_upstream_connect_success_total 3592
telemt_upstream_connect_attempts_per_request{bucket="1"} 3592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 548
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3582
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 33986587 (32.41 MB)
telemt_user_octets_to_client{user="hello"} 2819761061 (2.63 GB)
telemt_user_msgs_from_client{user="hello"} 90307
telemt_user_msgs_to_client{user="hello"} 359900
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 7
```