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

# Server Metrics 2026-03-09 17:35:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 65746.4 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123244
telemt_connections_bad_total 1662
telemt_handshake_timeouts_total 1038
telemt_upstream_connect_attempt_total 115499
telemt_upstream_connect_success_total 115457
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 115499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 115449
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 3139088685 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 62827675325 (58.51 GB)
telemt_user_msgs_from_client{user="hello"} 2895444
telemt_user_msgs_to_client{user="hello"} 4038043
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 65745.2 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34190
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 395
telemt_upstream_connect_attempt_total 32197
telemt_upstream_connect_success_total 32178
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 32197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32172
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 1040929081 (992.71 MB)
telemt_user_octets_to_client{user="hello"} 16648157943 (15.50 GB)
telemt_user_msgs_from_client{user="hello"} 899560
telemt_user_msgs_to_client{user="hello"} 4680746
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 65745.8 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43544
telemt_connections_bad_total 659
telemt_handshake_timeouts_total 1956
telemt_upstream_connect_attempt_total 33685
telemt_upstream_connect_success_total 33685
telemt_upstream_connect_attempts_per_request{bucket="1"} 33685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33677
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 4544419795 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 23310077984 (21.71 GB)
telemt_user_msgs_from_client{user="hello"} 2078914
telemt_user_msgs_to_client{user="hello"} 3100452
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 65740.4 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49130
telemt_connections_bad_total 202
telemt_handshake_timeouts_total 901
telemt_upstream_connect_attempt_total 44770
telemt_upstream_connect_success_total 44660
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 44770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44652
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 2007796717 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 33364325037 (31.07 GB)
telemt_user_msgs_from_client{user="hello"} 1368064
telemt_user_msgs_to_client{user="hello"} 8381518
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 65746.0 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79591
telemt_connections_bad_total 15747
telemt_handshake_timeouts_total 2072
telemt_upstream_connect_attempt_total 58160
telemt_upstream_connect_success_total 58158
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 58160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58150
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 957310020 (912.96 MB)
telemt_user_octets_to_client{user="hello"} 57317287898 (53.38 GB)
telemt_user_msgs_from_client{user="hello"} 1335301
telemt_user_msgs_to_client{user="hello"} 7223645
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 14
```