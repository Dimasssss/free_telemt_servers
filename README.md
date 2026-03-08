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

# Server Metrics 2026-03-08 21:46:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 52660.8 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114204
telemt_connections_bad_total 5495
telemt_handshake_timeouts_total 1281
telemt_upstream_connect_attempt_total 103633
telemt_upstream_connect_success_total 103595
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 103633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103589
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 2497284916 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 66649030519 (62.07 GB)
telemt_user_msgs_from_client{user="hello"} 2563741
telemt_user_msgs_to_client{user="hello"} 3540930
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 52659.9 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27023
telemt_connections_bad_total 291
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 26129
telemt_upstream_connect_success_total 26122
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26116
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 838291009 (799.46 MB)
telemt_user_octets_to_client{user="hello"} 22655063948 (21.10 GB)
telemt_user_msgs_from_client{user="hello"} 976775
telemt_user_msgs_to_client{user="hello"} 6149672
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 52659.6 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15247
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13842
telemt_upstream_connect_success_total 13766
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13760
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 1554173440 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 5664086834 (5.28 GB)
telemt_user_msgs_from_client{user="hello"} 696494
telemt_user_msgs_to_client{user="hello"} 970761
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 52659.4 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20822
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 19968
telemt_upstream_connect_success_total 19928
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 19968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1492
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19922
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1066984988 (1017.56 MB)
telemt_user_octets_to_client{user="hello"} 6554729726 (6.10 GB)
telemt_user_msgs_from_client{user="hello"} 573571
telemt_user_msgs_to_client{user="hello"} 1486124
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 52659.7 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30739
telemt_connections_bad_total 10001
telemt_handshake_timeouts_total 239
telemt_upstream_connect_attempt_total 20006
telemt_upstream_connect_success_total 19999
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 20006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19993
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 372143235 (354.90 MB)
telemt_user_octets_to_client{user="hello"} 17393559062 (16.20 GB)
telemt_user_msgs_from_client{user="hello"} 530758
telemt_user_msgs_to_client{user="hello"} 2256058
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```