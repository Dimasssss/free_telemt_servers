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

# Server Metrics 2026-03-08 11:08:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 14412.0 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30043
telemt_connections_bad_total 2561
telemt_handshake_timeouts_total 187
telemt_upstream_connect_attempt_total 26099
telemt_upstream_connect_success_total 26084
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 26099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26082
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 899545770 (857.87 MB)
telemt_user_octets_to_client{user="hello"} 14926063086 (13.90 GB)
telemt_user_msgs_from_client{user="hello"} 731935
telemt_user_msgs_to_client{user="hello"} 849065
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 14411.3 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7601
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 7245
telemt_upstream_connect_success_total 7245
telemt_upstream_connect_attempts_per_request{bucket="1"} 7245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7243
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 105580209 (100.69 MB)
telemt_user_octets_to_client{user="hello"} 4810150806 (4.48 GB)
telemt_user_msgs_from_client{user="hello"} 188749
telemt_user_msgs_to_client{user="hello"} 1250150
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 14410.9 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4895
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 4771
telemt_upstream_connect_success_total 4771
telemt_upstream_connect_attempts_per_request{bucket="1"} 4771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4769
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 109418858 (104.35 MB)
telemt_user_octets_to_client{user="hello"} 1352512816 (1.26 GB)
telemt_user_msgs_from_client{user="hello"} 76614
telemt_user_msgs_to_client{user="hello"} 232952
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 14410.7 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6763
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 6452
telemt_upstream_connect_success_total 6442
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 6452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6440
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 877822890 (837.16 MB)
telemt_user_octets_to_client{user="hello"} 2693126106 (2.51 GB)
telemt_user_msgs_from_client{user="hello"} 365767
telemt_user_msgs_to_client{user="hello"} 586668
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 14411.0 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9031
telemt_connections_bad_total 2684
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 6202
telemt_upstream_connect_success_total 6201
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6199
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 101480098 (96.78 MB)
telemt_user_octets_to_client{user="hello"} 4327468151 (4.03 GB)
telemt_user_msgs_from_client{user="hello"} 143103
telemt_user_msgs_to_client{user="hello"} 610638
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 2
```