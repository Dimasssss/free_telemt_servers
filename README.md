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

# Server Metrics 2026-03-08 15:10:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 28922.4 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70526
telemt_connections_bad_total 5024
telemt_handshake_timeouts_total 1035
telemt_upstream_connect_attempt_total 61918
telemt_upstream_connect_success_total 61896
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 61918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61892
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1661872070 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 32427295148 (30.20 GB)
telemt_user_msgs_from_client{user="hello"} 1471175
telemt_user_msgs_to_client{user="hello"} 1951822
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 28921.7 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15271
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 118
telemt_upstream_connect_attempt_total 14755
telemt_upstream_connect_success_total 14754
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14750
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 564350585 (538.21 MB)
telemt_user_octets_to_client{user="hello"} 12812141452 (11.93 GB)
telemt_user_msgs_from_client{user="hello"} 568684
telemt_user_msgs_to_client{user="hello"} 3363380
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 28921.4 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9685
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9059
telemt_upstream_connect_success_total 8983
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8979
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 206061047 (196.52 MB)
telemt_user_octets_to_client{user="hello"} 3014596447 (2.81 GB)
telemt_user_msgs_from_client{user="hello"} 151581
telemt_user_msgs_to_client{user="hello"} 520349
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 28921.3 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12512
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 11940
telemt_upstream_connect_success_total 11913
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 11940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11909
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 944762482 (901.00 MB)
telemt_user_octets_to_client{user="hello"} 4518783132 (4.21 GB)
telemt_user_msgs_from_client{user="hello"} 462593
telemt_user_msgs_to_client{user="hello"} 1018026
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 28921.6 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16386
telemt_connections_bad_total 5327
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 10704
telemt_upstream_connect_success_total 10700
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10696
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 231227145 (220.52 MB)
telemt_user_octets_to_client{user="hello"} 8339465385 (7.77 GB)
telemt_user_msgs_from_client{user="hello"} 277973
telemt_user_msgs_to_client{user="hello"} 1167035
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 7
```