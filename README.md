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

# Server Metrics 2026-03-08 19:17:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 43712.6 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100638
telemt_connections_bad_total 5056
telemt_handshake_timeouts_total 1258
telemt_upstream_connect_attempt_total 91052
telemt_upstream_connect_success_total 91021
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 91052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91015
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 2227299239 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 56680051343 (52.79 GB)
telemt_user_msgs_from_client{user="hello"} 2215985
telemt_user_msgs_to_client{user="hello"} 3106692
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 43711.8 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23074
telemt_connections_bad_total 227
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 22319
telemt_upstream_connect_success_total 22314
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22310
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 745324645 (710.80 MB)
telemt_user_octets_to_client{user="hello"} 20813383361 (19.38 GB)
telemt_user_msgs_from_client{user="hello"} 877404
telemt_user_msgs_to_client{user="hello"} 5669390
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 43711.7 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13965
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12633
telemt_upstream_connect_success_total 12557
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12553
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 258842179 (246.85 MB)
telemt_user_octets_to_client{user="hello"} 4360082404 (4.06 GB)
telemt_user_msgs_from_client{user="hello"} 217072
telemt_user_msgs_to_client{user="hello"} 780930
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 43711.4 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17967
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 17204
telemt_upstream_connect_success_total 17168
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 17204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1270
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17164
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 1040068878 (991.89 MB)
telemt_user_octets_to_client{user="hello"} 6054981882 (5.64 GB)
telemt_user_msgs_from_client{user="hello"} 544726
telemt_user_msgs_to_client{user="hello"} 1371062
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 43711.7 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25898
telemt_connections_bad_total 8265
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 16986
telemt_upstream_connect_success_total 16979
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16973
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 317786495 (303.06 MB)
telemt_user_octets_to_client{user="hello"} 13209111460 (12.30 GB)
telemt_user_msgs_from_client{user="hello"} 419198
telemt_user_msgs_to_client{user="hello"} 1734447
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```