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

# Server Metrics 2026-03-07 20:15:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 12624.3 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21898
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 21071
telemt_upstream_connect_success_total 21068
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 21071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21066
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 1782464218 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 14863132813 (13.84 GB)
telemt_user_msgs_from_client{user="hello"} 805858
telemt_user_msgs_to_client{user="hello"} 2265130
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 12623.4 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4755
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4571
telemt_upstream_connect_success_total 4569
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4567
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 73706761 (70.29 MB)
telemt_user_octets_to_client{user="hello"} 2883851460 (2.69 GB)
telemt_user_msgs_from_client{user="hello"} 118203
telemt_user_msgs_to_client{user="hello"} 830961
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 12623.1 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2414
telemt_connections_bad_total 93
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 2291
telemt_upstream_connect_success_total 2291
telemt_upstream_connect_attempts_per_request{bucket="1"} 2291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 220
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2289
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 74761357 (71.30 MB)
telemt_user_octets_to_client{user="hello"} 3553350359 (3.31 GB)
telemt_user_msgs_from_client{user="hello"} 88508
telemt_user_msgs_to_client{user="hello"} 734534
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 12451.6 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5392
telemt_connections_bad_total 90
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 5175
telemt_upstream_connect_success_total 5162
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 5175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5160
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 76669755 (73.12 MB)
telemt_user_octets_to_client{user="hello"} 5019276037 (4.67 GB)
telemt_user_msgs_from_client{user="hello"} 131127
telemt_user_msgs_to_client{user="hello"} 1564842
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 12623.3 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7372
telemt_connections_bad_total 2322
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 4906
telemt_upstream_connect_success_total 4899
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4897
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 1567875351 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 3189048974 (2.97 GB)
telemt_user_msgs_from_client{user="hello"} 666885
telemt_user_msgs_to_client{user="hello"} 748270
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```