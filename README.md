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

# Server Metrics 2026-03-09 06:21:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 25294.9 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25250
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 565
telemt_upstream_connect_attempt_total 23211
telemt_upstream_connect_success_total 23203
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 23211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23199
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 216131121 (206.12 MB)
telemt_user_octets_to_client{user="hello"} 13209191895 (12.30 GB)
telemt_user_msgs_from_client{user="hello"} 437423
telemt_user_msgs_to_client{user="hello"} 661573
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 25293.3 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3376
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 3179
telemt_upstream_connect_success_total 3179
telemt_upstream_connect_attempts_per_request{bucket="1"} 3179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 225
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3175
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 48700578 (46.44 MB)
telemt_user_octets_to_client{user="hello"} 3027761108 (2.82 GB)
telemt_user_msgs_from_client{user="hello"} 105995
telemt_user_msgs_to_client{user="hello"} 580561
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 25293.6 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1777
telemt_connections_bad_total 106
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1649
telemt_upstream_connect_success_total 1649
telemt_upstream_connect_attempts_per_request{bucket="1"} 1649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1645
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 907503119 (865.46 MB)
telemt_user_octets_to_client{user="hello"} 1121668531 (1.04 GB)
telemt_user_msgs_from_client{user="hello"} 348640
telemt_user_msgs_to_client{user="hello"} 223172
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 25288.4 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4072
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 3335
telemt_upstream_connect_success_total 3333
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3329
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 128169549 (122.23 MB)
telemt_user_octets_to_client{user="hello"} 2724860022 (2.54 GB)
telemt_user_msgs_from_client{user="hello"} 77872
telemt_user_msgs_to_client{user="hello"} 589218
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 25294.0 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8965
telemt_connections_bad_total 5029
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 3721
telemt_upstream_connect_success_total 3721
telemt_upstream_connect_attempts_per_request{bucket="1"} 3721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3717
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 55370094 (52.81 MB)
telemt_user_octets_to_client{user="hello"} 2770768798 (2.58 GB)
telemt_user_msgs_from_client{user="hello"} 80242
telemt_user_msgs_to_client{user="hello"} 374772
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```