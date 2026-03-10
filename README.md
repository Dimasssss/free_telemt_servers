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

# Server Metrics 2026-03-10 18:09:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13407.3 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54016
telemt_connections_bad_total 1457
telemt_handshake_timeouts_total 1436
telemt_upstream_connect_attempt_total 48379
telemt_upstream_connect_success_total 48369
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 48379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48367
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 1436844768 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 36449628765 (33.95 GB)
telemt_user_msgs_from_client{user="hello"} 1361802
telemt_user_msgs_to_client{user="hello"} 2711099
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 13406.5 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19458
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 340
telemt_upstream_connect_attempt_total 17776
telemt_upstream_connect_success_total 17772
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 17776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17770
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 543873690 (518.68 MB)
telemt_user_octets_to_client{user="hello"} 9357980816 (8.72 GB)
telemt_user_msgs_from_client{user="hello"} 526997
telemt_user_msgs_to_client{user="hello"} 2950906
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 13406.3 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30050
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 2666
telemt_upstream_connect_attempt_total 25508
telemt_upstream_connect_success_total 25508
telemt_upstream_connect_attempts_per_request{bucket="1"} 25508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25506
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 336089645 (320.52 MB)
telemt_user_octets_to_client{user="hello"} 22964011156 (21.39 GB)
telemt_user_msgs_from_client{user="hello"} 536828
telemt_user_msgs_to_client{user="hello"} 3651641
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 13405.1 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29637
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 265
telemt_upstream_connect_attempt_total 28319
telemt_upstream_connect_success_total 28233
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 28319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3286
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28231
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 387084899 (369.15 MB)
telemt_user_octets_to_client{user="hello"} 26469879875 (24.65 GB)
telemt_user_msgs_from_client{user="hello"} 573513
telemt_user_msgs_to_client{user="hello"} 4614401
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13406.4 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41686
telemt_connections_bad_total 3772
telemt_handshake_timeouts_total 753
telemt_upstream_connect_attempt_total 35570
telemt_upstream_connect_success_total 35333
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 35570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35331
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1349976223 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 22430848338 (20.89 GB)
telemt_user_msgs_from_client{user="hello"} 1044486
telemt_user_msgs_to_client{user="hello"} 3322917
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 22
```