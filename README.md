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

# Server Metrics 2026-03-08 20:29:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 48026.5 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108256
telemt_connections_bad_total 5085
telemt_handshake_timeouts_total 1275
telemt_upstream_connect_attempt_total 98479
telemt_upstream_connect_success_total 98445
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 98479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98439
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 2314027985 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 61674039117 (57.44 GB)
telemt_user_msgs_from_client{user="hello"} 2377241
telemt_user_msgs_to_client{user="hello"} 3335432
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 48025.9 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25140
telemt_connections_bad_total 274
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 24302
telemt_upstream_connect_success_total 24295
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 24302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24289
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 807027468 (769.64 MB)
telemt_user_octets_to_client{user="hello"} 21796918305 (20.30 GB)
telemt_user_msgs_from_client{user="hello"} 933415
telemt_user_msgs_to_client{user="hello"} 5916176
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 48025.6 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14748
telemt_connections_bad_total 184
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13393
telemt_upstream_connect_success_total 13317
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13311
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 1413447998 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 5567722221 (5.19 GB)
telemt_user_msgs_from_client{user="hello"} 641906
telemt_user_msgs_to_client{user="hello"} 939834
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 48025.4 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19243
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 18414
telemt_upstream_connect_success_total 18376
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 18414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18372
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 1059488962 (1010.41 MB)
telemt_user_octets_to_client{user="hello"} 6379355349 (5.94 GB)
telemt_user_msgs_from_client{user="hello"} 562022
telemt_user_msgs_to_client{user="hello"} 1437344
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 48025.6 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28247
telemt_connections_bad_total 9157
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 18411
telemt_upstream_connect_success_total 18404
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18398
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 342736335 (326.86 MB)
telemt_user_octets_to_client{user="hello"} 15532980165 (14.47 GB)
telemt_user_msgs_from_client{user="hello"} 476335
telemt_user_msgs_to_client{user="hello"} 2037887
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```