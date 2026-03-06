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

# Server Metrics 2026-03-06 16:27:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 21912.0 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51904
telemt_connections_bad_total 3106
telemt_handshake_timeouts_total 215
telemt_upstream_connect_attempt_total 44993
telemt_upstream_connect_success_total 44981
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 44993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44979
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 2381649431 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 28857194412 (26.88 GB)
telemt_user_msgs_from_client{user="hello"} 1597636
telemt_user_msgs_to_client{user="hello"} 4567214
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 21911.1 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9683
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 9189
telemt_upstream_connect_success_total 9171
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 9189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9169
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 111354760 (106.20 MB)
telemt_user_octets_to_client{user="hello"} 5263972624 (4.90 GB)
telemt_user_msgs_from_client{user="hello"} 190610
telemt_user_msgs_to_client{user="hello"} 1629736
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 21910.3 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8026
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 7727
telemt_upstream_connect_success_total 7725
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7723
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 117771249 (112.32 MB)
telemt_user_octets_to_client{user="hello"} 4793271306 (4.46 GB)
telemt_user_msgs_from_client{user="hello"} 174896
telemt_user_msgs_to_client{user="hello"} 1124018
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 21909.5 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11450
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 10630
telemt_upstream_connect_success_total 10593
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 10630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10591
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 147536460 (140.70 MB)
telemt_user_octets_to_client{user="hello"} 3467947693 (3.23 GB)
telemt_user_msgs_from_client{user="hello"} 184791
telemt_user_msgs_to_client{user="hello"} 903086
telemt_user_unique_ips_current{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 21910.9 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15974
telemt_connections_bad_total 5501
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 9635
telemt_upstream_connect_success_total 9635
telemt_upstream_connect_attempts_per_request{bucket="1"} 9635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9633
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 233600222 (222.78 MB)
telemt_user_octets_to_client{user="hello"} 21273228967 (19.81 GB)
telemt_user_msgs_from_client{user="hello"} 384666
telemt_user_msgs_to_client{user="hello"} 3832637
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```