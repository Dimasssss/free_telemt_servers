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

# Server Metrics 2026-03-07 07:51:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 2597.9 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3195
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 3085
telemt_upstream_connect_success_total 3085
telemt_upstream_connect_attempts_per_request{bucket="1"} 3085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3083
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 58913671 (56.18 MB)
telemt_user_octets_to_client{user="hello"} 3474550359 (3.24 GB)
telemt_user_msgs_from_client{user="hello"} 81309
telemt_user_msgs_to_client{user="hello"} 664306
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 2597.3 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 805
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 742
telemt_upstream_connect_success_total 741
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 739
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 4844051 (4.62 MB)
telemt_user_octets_to_client{user="hello"} 315165918 (300.57 MB)
telemt_user_msgs_from_client{user="hello"} 11205
telemt_user_msgs_to_client{user="hello"} 82337
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 2596.9 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 695
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 687
telemt_upstream_connect_success_total 687
telemt_upstream_connect_attempts_per_request{bucket="1"} 687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 685
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 26918527 (25.67 MB)
telemt_user_octets_to_client{user="hello"} 198096039 (188.92 MB)
telemt_user_msgs_from_client{user="hello"} 17253
telemt_user_msgs_to_client{user="hello"} 53662
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 2596.8 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 945
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 916
telemt_upstream_connect_success_total 915
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 913
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 7099181 (6.77 MB)
telemt_user_octets_to_client{user="hello"} 260136364 (248.09 MB)
telemt_user_msgs_from_client{user="hello"} 14029
telemt_user_msgs_to_client{user="hello"} 70430
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 2597.4 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1883
telemt_connections_bad_total 466
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 1326
telemt_upstream_connect_success_total 1325
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1323
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 20798562 (19.84 MB)
telemt_user_octets_to_client{user="hello"} 2873377804 (2.68 GB)
telemt_user_msgs_from_client{user="hello"} 30735
telemt_user_msgs_to_client{user="hello"} 503984
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 6
```