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

# Server Metrics 2026-03-08 07:02:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 51433.5 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76311
telemt_connections_bad_total 6900
telemt_handshake_timeouts_total 755
telemt_upstream_connect_attempt_total 65107
telemt_upstream_connect_success_total 64987
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 65107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64981
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 2687165988 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 40694001807 (37.90 GB)
telemt_user_msgs_from_client{user="hello"} 1899823
telemt_user_msgs_to_client{user="hello"} 6412005
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 51432.6 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11254
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 10677
telemt_upstream_connect_success_total 10668
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10662
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 287925121 (274.59 MB)
telemt_user_octets_to_client{user="hello"} 15816765812 (14.73 GB)
telemt_user_msgs_from_client{user="hello"} 520182
telemt_user_msgs_to_client{user="hello"} 3675696
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 51432.4 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7613
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 297
telemt_upstream_connect_attempt_total 6830
telemt_upstream_connect_success_total 6830
telemt_upstream_connect_attempts_per_request{bucket="1"} 6830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6824
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 147363201 (140.54 MB)
telemt_user_octets_to_client{user="hello"} 14809345062 (13.79 GB)
telemt_user_msgs_from_client{user="hello"} 252895
telemt_user_msgs_to_client{user="hello"} 3176573
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 51260.5 (14h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16290
telemt_connections_bad_total 246
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 15601
telemt_upstream_connect_success_total 15572
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 15601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2297
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15566
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 486855644 (464.30 MB)
telemt_user_octets_to_client{user="hello"} 13919797836 (12.96 GB)
telemt_user_msgs_from_client{user="hello"} 474354
telemt_user_msgs_to_client{user="hello"} 3883079
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 51432.5 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21518
telemt_connections_bad_total 9503
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 11717
telemt_upstream_connect_success_total 11709
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 11717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11703
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 1661860355 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 10958564509 (10.21 GB)
telemt_user_msgs_from_client{user="hello"} 896009
telemt_user_msgs_to_client{user="hello"} 2384407
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 6
```