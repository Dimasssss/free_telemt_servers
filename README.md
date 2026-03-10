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

# Server Metrics 2026-03-10 17:59:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12794.6 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51968
telemt_connections_bad_total 1397
telemt_handshake_timeouts_total 1426
telemt_upstream_connect_attempt_total 46470
telemt_upstream_connect_success_total 46460
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 46470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46458
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 1403724743 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 34991333920 (32.59 GB)
telemt_user_msgs_from_client{user="hello"} 1316809
telemt_user_msgs_to_client{user="hello"} 2618213
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12794.0 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18602
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 336
telemt_upstream_connect_attempt_total 16983
telemt_upstream_connect_success_total 16980
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 16983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16978
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 529179676 (504.67 MB)
telemt_user_octets_to_client{user="hello"} 8952229980 (8.34 GB)
telemt_user_msgs_from_client{user="hello"} 504996
telemt_user_msgs_to_client{user="hello"} 2800160
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12793.7 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28563
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 2591
telemt_upstream_connect_attempt_total 24208
telemt_upstream_connect_success_total 24208
telemt_upstream_connect_attempts_per_request{bucket="1"} 24208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24206
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 292751689 (279.19 MB)
telemt_user_octets_to_client{user="hello"} 19394643286 (18.06 GB)
telemt_user_msgs_from_client{user="hello"} 497264
telemt_user_msgs_to_client{user="hello"} 3250058
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12792.5 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28557
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 261
telemt_upstream_connect_attempt_total 27280
telemt_upstream_connect_success_total 27200
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 27280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27198
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 381281410 (363.62 MB)
telemt_user_octets_to_client{user="hello"} 26066336575 (24.28 GB)
telemt_user_msgs_from_client{user="hello"} 558402
telemt_user_msgs_to_client{user="hello"} 4512316
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12793.8 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39149
telemt_connections_bad_total 2968
telemt_handshake_timeouts_total 674
telemt_upstream_connect_attempt_total 33980
telemt_upstream_connect_success_total 33743
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 33980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33741
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1334242407 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 21487154498 (20.01 GB)
telemt_user_msgs_from_client{user="hello"} 1007143
telemt_user_msgs_to_client{user="hello"} 3139398
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 34
```