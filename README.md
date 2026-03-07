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

# Server Metrics 2026-03-07 01:00:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 24745.4 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32054
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 487
telemt_upstream_connect_attempt_total 29893
telemt_upstream_connect_success_total 29886
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 29893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29882
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 2074981678 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 32987606584 (30.72 GB)
telemt_user_msgs_from_client{user="hello"} 1369892
telemt_user_msgs_to_client{user="hello"} 5193212
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 24744.1 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6695
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 6265
telemt_upstream_connect_success_total 6262
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6258
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 215258974 (205.29 MB)
telemt_user_octets_to_client{user="hello"} 3894539109 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 201774
telemt_user_msgs_to_client{user="hello"} 1088908
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 24744.1 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3164
telemt_connections_bad_total 166
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2878
telemt_upstream_connect_success_total 2878
telemt_upstream_connect_attempts_per_request{bucket="1"} 2878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 240
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2874
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 65106921 (62.09 MB)
telemt_user_octets_to_client{user="hello"} 1861975135 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 64121
telemt_user_msgs_to_client{user="hello"} 392610
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 24744.0 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4343
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4188
telemt_upstream_connect_success_total 4181
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4177
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 100706945 (96.04 MB)
telemt_user_octets_to_client{user="hello"} 1362766644 (1.27 GB)
telemt_user_msgs_from_client{user="hello"} 85828
telemt_user_msgs_to_client{user="hello"} 350595
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 24744.5 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12162
telemt_connections_bad_total 5383
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6632
telemt_upstream_connect_success_total 6631
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6627
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 227703021 (217.15 MB)
telemt_user_octets_to_client{user="hello"} 7420855755 (6.91 GB)
telemt_user_msgs_from_client{user="hello"} 214367
telemt_user_msgs_to_client{user="hello"} 1526685
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```