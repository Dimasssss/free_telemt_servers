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

# Server Metrics 2026-03-09 15:38:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 58689.5 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105668
telemt_connections_bad_total 1655
telemt_handshake_timeouts_total 950
telemt_upstream_connect_attempt_total 98618
telemt_upstream_connect_success_total 98580
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 98618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98574
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 2566819424 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 51325464834 (47.80 GB)
telemt_user_msgs_from_client{user="hello"} 2396792
telemt_user_msgs_to_client{user="hello"} 3407698
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 58688.4 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27030
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 330
telemt_upstream_connect_attempt_total 25430
telemt_upstream_connect_success_total 25413
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 25430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25407
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 826695187 (788.40 MB)
telemt_user_octets_to_client{user="hello"} 14545509790 (13.55 GB)
telemt_user_msgs_from_client{user="hello"} 734782
telemt_user_msgs_to_client{user="hello"} 3965266
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 58689.3 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33581
telemt_connections_bad_total 644
telemt_handshake_timeouts_total 1584
telemt_upstream_connect_attempt_total 24662
telemt_upstream_connect_success_total 24662
telemt_upstream_connect_attempts_per_request{bucket="1"} 24662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24656
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 4390760840 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 15259222170 (14.21 GB)
telemt_user_msgs_from_client{user="hello"} 1888332
telemt_user_msgs_to_client{user="hello"} 2107163
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 58683.8 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37510
telemt_connections_bad_total 190
telemt_handshake_timeouts_total 835
telemt_upstream_connect_attempt_total 34424
telemt_upstream_connect_success_total 34333
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 34424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34327
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 1871885280 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 27157108497 (25.29 GB)
telemt_user_msgs_from_client{user="hello"} 1167379
telemt_user_msgs_to_client{user="hello"} 7047750
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 58689.1 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64884
telemt_connections_bad_total 14117
telemt_handshake_timeouts_total 1562
telemt_upstream_connect_attempt_total 46163
telemt_upstream_connect_success_total 46161
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 46163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46155
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 784341743 (748.01 MB)
telemt_user_octets_to_client{user="hello"} 48703873217 (45.36 GB)
telemt_user_msgs_from_client{user="hello"} 1060639
telemt_user_msgs_to_client{user="hello"} 5879015
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```