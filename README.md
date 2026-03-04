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

# Server Metrics 2026-03-04 21:25:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 35887.2 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60824
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 1544
telemt_upstream_connect_attempt_total 54459
telemt_upstream_connect_success_total 54447
telemt_upstream_connect_attempts_per_request{bucket="1"} 54435
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54443
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 2188120241 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 42066378495 (39.18 GB)
telemt_user_msgs_from_client{user="hello"} 1800947
telemt_user_msgs_to_client{user="hello"} 6715099
telemt_user_unique_ips_current{user="hello"} 10
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 35890.3 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11653
telemt_connections_bad_total 133
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 11013
telemt_upstream_connect_success_total 11011
telemt_upstream_connect_attempts_per_request{bucket="1"} 11009
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11007
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 1052350539 (1003.60 MB)
telemt_user_octets_to_client{user="hello"} 10992219020 (10.24 GB)
telemt_user_msgs_from_client{user="hello"} 639468
telemt_user_msgs_to_client{user="hello"} 3704956
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 35888.3 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7189
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 6863
telemt_upstream_connect_success_total 6863
telemt_upstream_connect_attempts_per_request{bucket="1"} 6863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6859
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 305534233 (291.38 MB)
telemt_user_octets_to_client{user="hello"} 5085683809 (4.74 GB)
telemt_user_msgs_from_client{user="hello"} 261451
telemt_user_msgs_to_client{user="hello"} 1089310
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 35886.3 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11816
telemt_connections_bad_total 619
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 10568
telemt_upstream_connect_success_total 10564
telemt_upstream_connect_attempts_per_request{bucket="1"} 10560
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 887
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10560
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 342441895 (326.58 MB)
telemt_user_octets_to_client{user="hello"} 4822452787 (4.49 GB)
telemt_user_msgs_from_client{user="hello"} 266799
telemt_user_msgs_to_client{user="hello"} 1209281
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 35888.0 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14826
telemt_connections_bad_total 6421
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 8115
telemt_upstream_connect_success_total 8111
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8109
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8107
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 489709562 (467.02 MB)
telemt_user_octets_to_client{user="hello"} 17277555936 (16.09 GB)
telemt_user_msgs_from_client{user="hello"} 483270
telemt_user_msgs_to_client{user="hello"} 3287668
telemt_user_unique_ips_current{user="hello"} 3
```