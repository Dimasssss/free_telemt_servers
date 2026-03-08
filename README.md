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

# Server Metrics 2026-03-08 20:13:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 47102.1 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106892
telemt_connections_bad_total 5076
telemt_handshake_timeouts_total 1273
telemt_upstream_connect_attempt_total 97159
telemt_upstream_connect_success_total 97125
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 97159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97119
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 2302361108 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 61252905563 (57.05 GB)
telemt_user_msgs_from_client{user="hello"} 2349818
telemt_user_msgs_to_client{user="hello"} 3300375
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 47101.4 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24756
telemt_connections_bad_total 273
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 23926
telemt_upstream_connect_success_total 23919
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 23926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23913
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 799096842 (762.08 MB)
telemt_user_octets_to_client{user="hello"} 21516865477 (20.04 GB)
telemt_user_msgs_from_client{user="hello"} 924205
telemt_user_msgs_to_client{user="hello"} 5841831
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 47101.0 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14632
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13281
telemt_upstream_connect_success_total 13205
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13199
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 1383656577 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 5512776637 (5.13 GB)
telemt_user_msgs_from_client{user="hello"} 629369
telemt_user_msgs_to_client{user="hello"} 929010
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 47101.0 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19038
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 18216
telemt_upstream_connect_success_total 18179
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 18216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18175
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 1058508531 (1009.47 MB)
telemt_user_octets_to_client{user="hello"} 6314850115 (5.88 GB)
telemt_user_msgs_from_client{user="hello"} 559760
telemt_user_msgs_to_client{user="hello"} 1421747
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 47101.1 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27868
telemt_connections_bad_total 8993
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 18198
telemt_upstream_connect_success_total 18191
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18185
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 340335139 (324.57 MB)
telemt_user_octets_to_client{user="hello"} 15487953139 (14.42 GB)
telemt_user_msgs_from_client{user="hello"} 472031
telemt_user_msgs_to_client{user="hello"} 2029628
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```