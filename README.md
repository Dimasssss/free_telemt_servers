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

# Server Metrics 2026-03-06 17:33:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 25917.7 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60458
telemt_connections_bad_total 3258
telemt_handshake_timeouts_total 254
telemt_upstream_connect_attempt_total 53049
telemt_upstream_connect_success_total 53037
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 53049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53033
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 2735440862 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 35372749355 (32.94 GB)
telemt_user_msgs_from_client{user="hello"} 1875324
telemt_user_msgs_to_client{user="hello"} 5571256
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 25917.6 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11602
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 11040
telemt_upstream_connect_success_total 11021
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 11040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11017
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 145680425 (138.93 MB)
telemt_user_octets_to_client{user="hello"} 6070485412 (5.65 GB)
telemt_user_msgs_from_client{user="hello"} 234121
telemt_user_msgs_to_client{user="hello"} 1875724
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 25916.8 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9323
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 8985
telemt_upstream_connect_success_total 8983
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8981
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 129101383 (123.12 MB)
telemt_user_octets_to_client{user="hello"} 5303454450 (4.94 GB)
telemt_user_msgs_from_client{user="hello"} 201892
telemt_user_msgs_to_client{user="hello"} 1254183
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 25916.0 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13227
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 12310
telemt_upstream_connect_success_total 12269
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 12310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 830
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12265
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 176638486 (168.46 MB)
telemt_user_octets_to_client{user="hello"} 5239732422 (4.88 GB)
telemt_user_msgs_from_client{user="hello"} 222570
telemt_user_msgs_to_client{user="hello"} 1244109
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 25917.4 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18597
telemt_connections_bad_total 6219
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 11476
telemt_upstream_connect_success_total 11476
telemt_upstream_connect_attempts_per_request{bucket="1"} 11476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11472
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 259253137 (247.24 MB)
telemt_user_octets_to_client{user="hello"} 24129035008 (22.47 GB)
telemt_user_msgs_from_client{user="hello"} 444033
telemt_user_msgs_to_client{user="hello"} 4378916
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```