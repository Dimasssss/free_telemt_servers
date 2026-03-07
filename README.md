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

# Server Metrics 2026-03-07 00:40:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 23514.1 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31407
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 486
telemt_upstream_connect_attempt_total 29304
telemt_upstream_connect_success_total 29297
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 29304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29293
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 2071712318 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 32906146565 (30.65 GB)
telemt_user_msgs_from_client{user="hello"} 1362179
telemt_user_msgs_to_client{user="hello"} 5176992
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 23513.0 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6682
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 6258
telemt_upstream_connect_success_total 6255
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6251
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 215192438 (205.22 MB)
telemt_user_octets_to_client{user="hello"} 3894271404 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 201540
telemt_user_msgs_to_client{user="hello"} 1088630
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 23513.1 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3102
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2834
telemt_upstream_connect_success_total 2834
telemt_upstream_connect_attempts_per_request{bucket="1"} 2834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 231
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2830
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 64984463 (61.97 MB)
telemt_user_octets_to_client{user="hello"} 1861630793 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 63777
telemt_user_msgs_to_client{user="hello"} 392291
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 23513.2 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4243
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 4096
telemt_upstream_connect_success_total 4089
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4085
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 100212356 (95.57 MB)
telemt_user_octets_to_client{user="hello"} 1349990072 (1.26 GB)
telemt_user_msgs_from_client{user="hello"} 84547
telemt_user_msgs_to_client{user="hello"} 345801
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 23513.5 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11871
telemt_connections_bad_total 5164
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6565
telemt_upstream_connect_success_total 6564
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6560
telemt_user_octets_from_client{user="hello"} 227578516 (217.04 MB)
telemt_user_octets_to_client{user="hello"} 7416448755 (6.91 GB)
telemt_user_msgs_from_client{user="hello"} 214054
telemt_user_msgs_to_client{user="hello"} 1525517
```