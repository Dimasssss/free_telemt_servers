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

# Server Metrics 2026-03-09 03:02:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 13367.4 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10716
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 186
telemt_upstream_connect_attempt_total 9874
telemt_upstream_connect_success_total 9871
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 9874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9869
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 113184454 (107.94 MB)
telemt_user_octets_to_client{user="hello"} 8579931761 (7.99 GB)
telemt_user_msgs_from_client{user="hello"} 225478
telemt_user_msgs_to_client{user="hello"} 356692
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 13365.5 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 782
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 746
telemt_upstream_connect_success_total 746
telemt_upstream_connect_attempts_per_request{bucket="1"} 746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 744
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 9712726 (9.26 MB)
telemt_user_octets_to_client{user="hello"} 516532103 (492.60 MB)
telemt_user_msgs_from_client{user="hello"} 26468
telemt_user_msgs_to_client{user="hello"} 107142
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 13366.0 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 913
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 817
telemt_upstream_connect_success_total 817
telemt_upstream_connect_attempts_per_request{bucket="1"} 817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 815
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 317104827 (302.41 MB)
telemt_user_octets_to_client{user="hello"} 551651052 (526.10 MB)
telemt_user_msgs_from_client{user="hello"} 126627
telemt_user_msgs_to_client{user="hello"} 105663
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 13360.9 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1818
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 201
telemt_upstream_connect_attempt_total 1483
telemt_upstream_connect_success_total 1483
telemt_upstream_connect_attempts_per_request{bucket="1"} 1483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1481
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 12151765 (11.59 MB)
telemt_user_octets_to_client{user="hello"} 804123062 (766.87 MB)
telemt_user_msgs_from_client{user="hello"} 31170
telemt_user_msgs_to_client{user="hello"} 226390
telemt_user_unique_ips_current{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 13366.4 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3632
telemt_connections_bad_total 2432
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1171
telemt_upstream_connect_success_total 1171
telemt_upstream_connect_attempts_per_request{bucket="1"} 1171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1169
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 9403744 (8.97 MB)
telemt_user_octets_to_client{user="hello"} 1573338847 (1.47 GB)
telemt_user_msgs_from_client{user="hello"} 24722
telemt_user_msgs_to_client{user="hello"} 189487
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```