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

# Server Metrics 2026-03-08 07:38:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 1776.5 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3037
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 2927
telemt_upstream_connect_success_total 2926
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2924
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 50607273 (48.26 MB)
telemt_user_octets_to_client{user="hello"} 924152207 (881.34 MB)
telemt_user_msgs_from_client{user="hello"} 64419
telemt_user_msgs_to_client{user="hello"} 74326
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 1775.4 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 501
telemt_upstream_connect_success_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 499
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 7904968 (7.54 MB)
telemt_user_octets_to_client{user="hello"} 345611157 (329.60 MB)
telemt_user_msgs_from_client{user="hello"} 13864
telemt_user_msgs_to_client{user="hello"} 80815
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 1775.1 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 507
telemt_upstream_connect_success_total 507
telemt_upstream_connect_attempts_per_request{bucket="1"} 507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 505
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 2634726 (2.51 MB)
telemt_user_octets_to_client{user="hello"} 167012138 (159.28 MB)
telemt_user_msgs_from_client{user="hello"} 4710
telemt_user_msgs_to_client{user="hello"} 23589
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 1775.0 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 704
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 679
telemt_upstream_connect_success_total 678
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 676
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 25671808 (24.48 MB)
telemt_user_octets_to_client{user="hello"} 154249378 (147.10 MB)
telemt_user_msgs_from_client{user="hello"} 10332
telemt_user_msgs_to_client{user="hello"} 43415
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 1775.3 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1356
telemt_connections_bad_total 318
telemt_upstream_connect_attempt_total 1027
telemt_upstream_connect_success_total 1027
telemt_upstream_connect_attempts_per_request{bucket="1"} 1027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1025
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 8251469 (7.87 MB)
telemt_user_octets_to_client{user="hello"} 243757304 (232.47 MB)
telemt_user_msgs_from_client{user="hello"} 13264
telemt_user_msgs_to_client{user="hello"} 39864
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```