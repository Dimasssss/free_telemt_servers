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

# Server Metrics 2026-03-09 01:10:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 6641.7 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5490
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 4964
telemt_upstream_connect_success_total 4962
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4960
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 57785395 (55.11 MB)
telemt_user_octets_to_client{user="hello"} 6665418305 (6.21 GB)
telemt_user_msgs_from_client{user="hello"} 137584
telemt_user_msgs_to_client{user="hello"} 233536
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 6639.8 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 389
telemt_upstream_connect_success_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 387
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 5439680 (5.19 MB)
telemt_user_octets_to_client{user="hello"} 327294139 (312.13 MB)
telemt_user_msgs_from_client{user="hello"} 15129
telemt_user_msgs_to_client{user="hello"} 68723
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 6640.2 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 435
telemt_upstream_connect_success_total 435
telemt_upstream_connect_attempts_per_request{bucket="1"} 435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 433
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 29263368 (27.91 MB)
telemt_user_octets_to_client{user="hello"} 66599449 (63.51 MB)
telemt_user_msgs_from_client{user="hello"} 15069
telemt_user_msgs_to_client{user="hello"} 21043
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 6635.1 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 804
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 791
telemt_upstream_connect_success_total 791
telemt_upstream_connect_attempts_per_request{bucket="1"} 791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 789
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 6299353 (6.01 MB)
telemt_user_octets_to_client{user="hello"} 317329136 (302.63 MB)
telemt_user_msgs_from_client{user="hello"} 16113
telemt_user_msgs_to_client{user="hello"} 80635
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 6640.6 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1972
telemt_connections_bad_total 1193
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 764
telemt_upstream_connect_success_total 764
telemt_upstream_connect_attempts_per_request{bucket="1"} 764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 762
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 6793381 (6.48 MB)
telemt_user_octets_to_client{user="hello"} 1283618710 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 18959
telemt_user_msgs_to_client{user="hello"} 158414
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```