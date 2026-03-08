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

# Server Metrics 2026-03-08 20:03:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 46486.3 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105946
telemt_connections_bad_total 5069
telemt_handshake_timeouts_total 1273
telemt_upstream_connect_attempt_total 96227
telemt_upstream_connect_success_total 96192
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 96226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 96186
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 2289692241 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 60771600930 (56.60 GB)
telemt_user_msgs_from_client{user="hello"} 2328513
telemt_user_msgs_to_client{user="hello"} 3274673
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 46485.3 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24547
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 23757
telemt_upstream_connect_success_total 23751
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 23757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23745
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 797489877 (760.55 MB)
telemt_user_octets_to_client{user="hello"} 21445642485 (19.97 GB)
telemt_user_msgs_from_client{user="hello"} 920382
telemt_user_msgs_to_client{user="hello"} 5821765
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 46485.3 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14546
telemt_connections_bad_total 179
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13201
telemt_upstream_connect_success_total 13125
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13119
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 1168552350 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 5489592524 (5.11 GB)
telemt_user_msgs_from_client{user="hello"} 553105
telemt_user_msgs_to_client{user="hello"} 922695
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 46484.9 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18876
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 18061
telemt_upstream_connect_success_total 18024
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 18061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1326
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18020
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 1057978812 (1008.97 MB)
telemt_user_octets_to_client{user="hello"} 6295291742 (5.86 GB)
telemt_user_msgs_from_client{user="hello"} 558360
telemt_user_msgs_to_client{user="hello"} 1415610
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 46485.1 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27546
telemt_connections_bad_total 8869
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 18001
telemt_upstream_connect_success_total 17994
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17988
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 338036593 (322.38 MB)
telemt_user_octets_to_client{user="hello"} 15424810394 (14.37 GB)
telemt_user_msgs_from_client{user="hello"} 467088
telemt_user_msgs_to_client{user="hello"} 2017463
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```