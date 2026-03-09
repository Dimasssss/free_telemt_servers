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

# Server Metrics 2026-03-09 04:54:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 20095.9 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18234
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 553
telemt_upstream_connect_attempt_total 16403
telemt_upstream_connect_success_total 16398
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16396
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 155972884 (148.75 MB)
telemt_user_octets_to_client{user="hello"} 9581729634 (8.92 GB)
telemt_user_msgs_from_client{user="hello"} 300378
telemt_user_msgs_to_client{user="hello"} 450875
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 20094.4 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1991
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 1832
telemt_upstream_connect_success_total 1832
telemt_upstream_connect_attempts_per_request{bucket="1"} 1832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1830
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 33121990 (31.59 MB)
telemt_user_octets_to_client{user="hello"} 1525260033 (1.42 GB)
telemt_user_msgs_from_client{user="hello"} 68143
telemt_user_msgs_to_client{user="hello"} 300749
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 20094.9 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1352
telemt_connections_bad_total 86
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1250
telemt_upstream_connect_success_total 1250
telemt_upstream_connect_attempts_per_request{bucket="1"} 1250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1248
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 463785205 (442.30 MB)
telemt_user_octets_to_client{user="hello"} 1014008464 (967.03 MB)
telemt_user_msgs_from_client{user="hello"} 187935
telemt_user_msgs_to_client{user="hello"} 195455
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 20089.7 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2641
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 2126
telemt_upstream_connect_success_total 2126
telemt_upstream_connect_attempts_per_request{bucket="1"} 2126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2124
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 17293065 (16.49 MB)
telemt_user_octets_to_client{user="hello"} 1375970432 (1.28 GB)
telemt_user_msgs_from_client{user="hello"} 44438
telemt_user_msgs_to_client{user="hello"} 337509
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 20095.3 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5582
telemt_connections_bad_total 3651
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1889
telemt_upstream_connect_success_total 1889
telemt_upstream_connect_attempts_per_request{bucket="1"} 1889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1887
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 13734763 (13.10 MB)
telemt_user_octets_to_client{user="hello"} 1684931417 (1.57 GB)
telemt_user_msgs_from_client{user="hello"} 35216
telemt_user_msgs_to_client{user="hello"} 213327
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```