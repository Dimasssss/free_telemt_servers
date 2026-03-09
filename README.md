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

# Server Metrics 2026-03-09 06:11:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 24683.3 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24430
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 563
telemt_upstream_connect_attempt_total 22438
telemt_upstream_connect_success_total 22431
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 22438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22427
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 208573875 (198.91 MB)
telemt_user_octets_to_client{user="hello"} 12857721270 (11.97 GB)
telemt_user_msgs_from_client{user="hello"} 420633
telemt_user_msgs_to_client{user="hello"} 636316
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 24681.4 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3185
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 2992
telemt_upstream_connect_success_total 2992
telemt_upstream_connect_attempts_per_request{bucket="1"} 2992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 219
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2988
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 47431782 (45.23 MB)
telemt_user_octets_to_client{user="hello"} 2977837449 (2.77 GB)
telemt_user_msgs_from_client{user="hello"} 102864
telemt_user_msgs_to_client{user="hello"} 566073
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 24682.0 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1738
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1617
telemt_upstream_connect_success_total 1617
telemt_upstream_connect_attempts_per_request{bucket="1"} 1617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1613
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 907330136 (865.30 MB)
telemt_user_octets_to_client{user="hello"} 1119604300 (1.04 GB)
telemt_user_msgs_from_client{user="hello"} 348214
telemt_user_msgs_to_client{user="hello"} 221907
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 24676.6 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3760
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 3200
telemt_upstream_connect_success_total 3198
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 626
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3194
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 127089183 (121.20 MB)
telemt_user_octets_to_client{user="hello"} 2651622609 (2.47 GB)
telemt_user_msgs_from_client{user="hello"} 75377
telemt_user_msgs_to_client{user="hello"} 575958
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 24682.2 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8605
telemt_connections_bad_total 4920
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 3471
telemt_upstream_connect_success_total 3471
telemt_upstream_connect_attempts_per_request{bucket="1"} 3471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3467
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 43993695 (41.96 MB)
telemt_user_octets_to_client{user="hello"} 2713274725 (2.53 GB)
telemt_user_msgs_from_client{user="hello"} 73272
telemt_user_msgs_to_client{user="hello"} 360886
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```