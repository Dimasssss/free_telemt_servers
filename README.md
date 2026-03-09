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

# Server Metrics 2026-03-09 02:26:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 11227.1 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9279
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 8526
telemt_upstream_connect_success_total 8523
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 8526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8521
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 103846751 (99.04 MB)
telemt_user_octets_to_client{user="hello"} 8372004347 (7.80 GB)
telemt_user_msgs_from_client{user="hello"} 204301
telemt_user_msgs_to_client{user="hello"} 333007
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 11225.4 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 663
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 633
telemt_upstream_connect_success_total 633
telemt_upstream_connect_attempts_per_request{bucket="1"} 633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 631
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 8254728 (7.87 MB)
telemt_user_octets_to_client{user="hello"} 464974134 (443.43 MB)
telemt_user_msgs_from_client{user="hello"} 23103
telemt_user_msgs_to_client{user="hello"} 93005
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 11226.0 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 679
telemt_upstream_connect_success_total 679
telemt_upstream_connect_attempts_per_request{bucket="1"} 679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 677
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 314036474 (299.49 MB)
telemt_user_octets_to_client{user="hello"} 131817673 (125.71 MB)
telemt_user_msgs_from_client{user="hello"} 118322
telemt_user_msgs_to_client{user="hello"} 46406
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 11220.7 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1530
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 1267
telemt_upstream_connect_success_total 1267
telemt_upstream_connect_attempts_per_request{bucket="1"} 1267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 294
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1265
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 10300290 (9.82 MB)
telemt_user_octets_to_client{user="hello"} 675774954 (644.47 MB)
telemt_user_msgs_from_client{user="hello"} 26478
telemt_user_msgs_to_client{user="hello"} 193513
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 11226.4 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3089
telemt_connections_bad_total 2018
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1043
telemt_upstream_connect_success_total 1043
telemt_upstream_connect_attempts_per_request{bucket="1"} 1043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1041
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 7563579 (7.21 MB)
telemt_user_octets_to_client{user="hello"} 1313234410 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 20887
telemt_user_msgs_to_client{user="hello"} 164487
telemt_user_unique_ips_current{user="hello"} 4
```