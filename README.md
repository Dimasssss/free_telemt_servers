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

# Server Metrics 2026-03-06 09:57:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 6393.8 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12394
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 82
telemt_upstream_connect_attempt_total 11932
telemt_upstream_connect_success_total 11931
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11929
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 162283007 (154.77 MB)
telemt_user_octets_to_client{user="hello"} 7328946749 (6.83 GB)
telemt_user_msgs_from_client{user="hello"} 264588
telemt_user_msgs_to_client{user="hello"} 1213808
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 6394.2 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1945
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 1838
telemt_upstream_connect_success_total 1838
telemt_upstream_connect_attempts_per_request{bucket="1"} 1838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1836
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 19354877 (18.46 MB)
telemt_user_octets_to_client{user="hello"} 580868671 (553.96 MB)
telemt_user_msgs_from_client{user="hello"} 38917
telemt_user_msgs_to_client{user="hello"} 195439
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 6392.1 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2148
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2017
telemt_upstream_connect_success_total 2017
telemt_upstream_connect_attempts_per_request{bucket="1"} 2017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2015
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 130280326 (124.25 MB)
telemt_user_octets_to_client{user="hello"} 1613665725 (1.50 GB)
telemt_user_msgs_from_client{user="hello"} 82341
telemt_user_msgs_to_client{user="hello"} 308659
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 6394.4 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3571
telemt_connections_bad_total 116
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 3145
telemt_upstream_connect_success_total 3135
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3133
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 32274967 (30.78 MB)
telemt_user_octets_to_client{user="hello"} 908031021 (865.97 MB)
telemt_user_msgs_from_client{user="hello"} 49687
telemt_user_msgs_to_client{user="hello"} 243825
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 6396.0 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3861
telemt_connections_bad_total 1698
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 1997
telemt_upstream_connect_success_total 1996
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1994
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 116488623 (111.09 MB)
telemt_user_octets_to_client{user="hello"} 2598846595 (2.42 GB)
telemt_user_msgs_from_client{user="hello"} 88395
telemt_user_msgs_to_client{user="hello"} 471775
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```