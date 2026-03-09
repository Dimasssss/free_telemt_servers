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

# Server Metrics 2026-03-09 01:51:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 9087.0 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7693
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 7029
telemt_upstream_connect_success_total 7027
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7025
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 76630442 (73.08 MB)
telemt_user_octets_to_client{user="hello"} 7452219622 (6.94 GB)
telemt_user_msgs_from_client{user="hello"} 172426
telemt_user_msgs_to_client{user="hello"} 283796
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 9085.4 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 530
telemt_upstream_connect_success_total 530
telemt_upstream_connect_attempts_per_request{bucket="1"} 530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 528
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 7680626 (7.32 MB)
telemt_user_octets_to_client{user="hello"} 457756286 (436.55 MB)
telemt_user_msgs_from_client{user="hello"} 21421
telemt_user_msgs_to_client{user="hello"} 90354
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 9086.0 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 536
telemt_upstream_connect_success_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 534
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 29877194 (28.49 MB)
telemt_user_octets_to_client{user="hello"} 81509773 (77.73 MB)
telemt_user_msgs_from_client{user="hello"} 16708
telemt_user_msgs_to_client{user="hello"} 26124
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 9080.7 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1197
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 1022
telemt_upstream_connect_success_total 1022
telemt_upstream_connect_attempts_per_request{bucket="1"} 1022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1020
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 8090502 (7.72 MB)
telemt_user_octets_to_client{user="hello"} 563268558 (537.17 MB)
telemt_user_msgs_from_client{user="hello"} 20724
telemt_user_msgs_to_client{user="hello"} 157135
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 9086.2 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2554
telemt_connections_bad_total 1631
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 903
telemt_upstream_connect_success_total 903
telemt_upstream_connect_attempts_per_request{bucket="1"} 903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 901
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 7042924 (6.72 MB)
telemt_user_octets_to_client{user="hello"} 1290345351 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 19569
telemt_user_msgs_to_client{user="hello"} 159987
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```