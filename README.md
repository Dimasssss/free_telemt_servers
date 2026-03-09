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

# Server Metrics 2026-03-09 07:27:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 29271.0 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31137
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 580
telemt_upstream_connect_attempt_total 28838
telemt_upstream_connect_success_total 28830
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 28838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28826
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 273660466 (260.98 MB)
telemt_user_octets_to_client{user="hello"} 15570587430 (14.50 GB)
telemt_user_msgs_from_client{user="hello"} 554461
telemt_user_msgs_to_client{user="hello"} 829095
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 29269.3 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5291
telemt_connections_bad_total 135
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 4929
telemt_upstream_connect_success_total 4928
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 311
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4924
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 65326464 (62.30 MB)
telemt_user_octets_to_client{user="hello"} 4078143285 (3.80 GB)
telemt_user_msgs_from_client{user="hello"} 140240
telemt_user_msgs_to_client{user="hello"} 800383
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 29269.8 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2554
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2403
telemt_upstream_connect_success_total 2403
telemt_upstream_connect_attempts_per_request{bucket="1"} 2403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2399
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 914906887 (872.52 MB)
telemt_user_octets_to_client{user="hello"} 1509341973 (1.41 GB)
telemt_user_msgs_from_client{user="hello"} 361182
telemt_user_msgs_to_client{user="hello"} 288916
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 29264.6 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5303
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 353
telemt_upstream_connect_attempt_total 4365
telemt_upstream_connect_success_total 4362
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4358
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 139871459 (133.39 MB)
telemt_user_octets_to_client{user="hello"} 5521018852 (5.14 GB)
telemt_user_msgs_from_client{user="hello"} 108357
telemt_user_msgs_to_client{user="hello"} 1384585
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 29270.1 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11808
telemt_connections_bad_total 6309
telemt_handshake_timeouts_total 29
telemt_upstream_connect_attempt_total 5131
telemt_upstream_connect_success_total 5131
telemt_upstream_connect_attempts_per_request{bucket="1"} 5131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5127
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 65091437 (62.08 MB)
telemt_user_octets_to_client{user="hello"} 3263108106 (3.04 GB)
telemt_user_msgs_from_client{user="hello"} 102363
telemt_user_msgs_to_client{user="hello"} 464103
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 1
```