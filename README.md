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

# Server Metrics 2026-03-08 18:51:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 42172.1 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97626
telemt_connections_bad_total 5049
telemt_handshake_timeouts_total 1252
telemt_upstream_connect_attempt_total 88123
telemt_upstream_connect_success_total 88093
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 88123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88087
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 2148472285 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 54454982577 (50.72 GB)
telemt_user_msgs_from_client{user="hello"} 2134194
telemt_user_msgs_to_client{user="hello"} 3003923
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 42171.2 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22136
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 21438
telemt_upstream_connect_success_total 21433
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 21438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21429
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 734867024 (700.82 MB)
telemt_user_octets_to_client{user="hello"} 19948127719 (18.58 GB)
telemt_user_msgs_from_client{user="hello"} 853307
telemt_user_msgs_to_client{user="hello"} 5473015
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 42170.9 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13610
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12283
telemt_upstream_connect_success_total 12207
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12203
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 241317103 (230.14 MB)
telemt_user_octets_to_client{user="hello"} 4221373195 (3.93 GB)
telemt_user_msgs_from_client{user="hello"} 206837
telemt_user_msgs_to_client{user="hello"} 755332
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 42170.8 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17543
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 16783
telemt_upstream_connect_success_total 16747
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 16783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16743
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 1038662076 (990.55 MB)
telemt_user_octets_to_client{user="hello"} 5946578495 (5.54 GB)
telemt_user_msgs_from_client{user="hello"} 541086
telemt_user_msgs_to_client{user="hello"} 1347242
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 42171.0 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24908
telemt_connections_bad_total 7994
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 16298
telemt_upstream_connect_success_total 16291
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16285
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 309107344 (294.79 MB)
telemt_user_octets_to_client{user="hello"} 12366696353 (11.52 GB)
telemt_user_msgs_from_client{user="hello"} 398041
telemt_user_msgs_to_client{user="hello"} 1628553
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```