# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-09 07:37:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 29882.6 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32044
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 580
telemt_upstream_connect_attempt_total 29722
telemt_upstream_connect_success_total 29714
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 29722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29710
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 282047146 (268.98 MB)
telemt_user_octets_to_client{user="hello"} 15703851677 (14.63 GB)
telemt_user_msgs_from_client{user="hello"} 566398
telemt_user_msgs_to_client{user="hello"} 843341
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 29880.9 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5567
telemt_connections_bad_total 135
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 5203
telemt_upstream_connect_success_total 5202
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5198
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 84300764 (80.40 MB)
telemt_user_octets_to_client{user="hello"} 4518491930 (4.21 GB)
telemt_user_msgs_from_client{user="hello"} 159348
telemt_user_msgs_to_client{user="hello"} 887893
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 29881.5 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2680
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2527
telemt_upstream_connect_success_total 2527
telemt_upstream_connect_attempts_per_request{bucket="1"} 2527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2523
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 1002125056 (955.70 MB)
telemt_user_octets_to_client{user="hello"} 1535673741 (1.43 GB)
telemt_user_msgs_from_client{user="hello"} 393089
telemt_user_msgs_to_client{user="hello"} 293608
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 29876.3 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5447
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 353
telemt_upstream_connect_attempt_total 4505
telemt_upstream_connect_success_total 4501
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 765
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4497
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 143274379 (136.64 MB)
telemt_user_octets_to_client{user="hello"} 5592599392 (5.21 GB)
telemt_user_msgs_from_client{user="hello"} 112949
telemt_user_msgs_to_client{user="hello"} 1401416
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 29881.6 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12301
telemt_connections_bad_total 6558
telemt_handshake_timeouts_total 29
telemt_upstream_connect_attempt_total 5373
telemt_upstream_connect_success_total 5373
telemt_upstream_connect_attempts_per_request{bucket="1"} 5373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5369
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 65764178 (62.72 MB)
telemt_user_octets_to_client{user="hello"} 3281296287 (3.06 GB)
telemt_user_msgs_from_client{user="hello"} 104173
telemt_user_msgs_to_client{user="hello"} 467939
telemt_user_unique_ips_current{user="hello"} 9
```