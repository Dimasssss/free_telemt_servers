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

# Server Metrics 2026-03-10 12:41:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 134516.6 (37h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300029
telemt_connections_bad_total 3468
telemt_handshake_timeouts_total 3100
telemt_upstream_connect_attempt_total 280941
telemt_upstream_connect_success_total 280788
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 280941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 259638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 280776
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 6600830118 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 187288750872 (174.43 GB)
telemt_user_msgs_from_client{user="hello"} 6796708
telemt_user_msgs_to_client{user="hello"} 11000926
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 134515.5 (37h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92117
telemt_connections_bad_total 3271
telemt_handshake_timeouts_total 1275
telemt_upstream_connect_attempt_total 82783
telemt_upstream_connect_success_total 82739
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 82783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82725
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 2784808554 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 35389364307 (32.96 GB)
telemt_user_msgs_from_client{user="hello"} 2220401
telemt_user_msgs_to_client{user="hello"} 10234977
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 134516.0 (37h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130735
telemt_connections_bad_total 1219
telemt_handshake_timeouts_total 6301
telemt_upstream_connect_attempt_total 96522
telemt_upstream_connect_success_total 96519
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 96522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 96507
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 6613164388 (6.16 GB)
telemt_user_octets_to_client{user="hello"} 67117156949 (62.51 GB)
telemt_user_msgs_from_client{user="hello"} 4400549
telemt_user_msgs_to_client{user="hello"} 11201379
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 134510.7 (37h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135749
telemt_connections_bad_total 1053
telemt_handshake_timeouts_total 2911
telemt_upstream_connect_attempt_total 125149
telemt_upstream_connect_success_total 124875
telemt_upstream_connect_fail_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 125148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 80
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 319
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 273
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 124861
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 4007195811 (3.73 GB)
telemt_user_octets_to_client{user="hello"} 86947296451 (80.98 GB)
telemt_user_msgs_from_client{user="hello"} 3366952
telemt_user_msgs_to_client{user="hello"} 19789339
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 134516.2 (37h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201851
telemt_connections_bad_total 30086
telemt_handshake_timeouts_total 5478
telemt_upstream_connect_attempt_total 157812
telemt_upstream_connect_success_total 156851
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 157812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 156837
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 3439199885 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 115573952919 (107.64 GB)
telemt_user_msgs_from_client{user="hello"} 3622328
telemt_user_msgs_to_client{user="hello"} 15755313
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 17
```