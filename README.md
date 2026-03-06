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

# Server Metrics 2026-03-06 15:15:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 17599.9 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42168
telemt_connections_bad_total 3088
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 35558
telemt_upstream_connect_success_total 35548
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35546
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 1997289942 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 23144731911 (21.56 GB)
telemt_user_msgs_from_client{user="hello"} 1315525
telemt_user_msgs_to_client{user="hello"} 3660225
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 17599.0 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7691
telemt_connections_bad_total 160
telemt_handshake_timeouts_total 89
telemt_upstream_connect_attempt_total 7233
telemt_upstream_connect_success_total 7231
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7229
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 79008488 (75.35 MB)
telemt_user_octets_to_client{user="hello"} 4056101126 (3.78 GB)
telemt_user_msgs_from_client{user="hello"} 151449
telemt_user_msgs_to_client{user="hello"} 1331623
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 17598.5 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6715
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 6506
telemt_upstream_connect_success_total 6505
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6503
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 96147605 (91.69 MB)
telemt_user_octets_to_client{user="hello"} 4158261183 (3.87 GB)
telemt_user_msgs_from_client{user="hello"} 144836
telemt_user_msgs_to_client{user="hello"} 971824
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 17597.6 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9493
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 8800
telemt_upstream_connect_success_total 8770
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 8800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8768
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 135152789 (128.89 MB)
telemt_user_octets_to_client{user="hello"} 3040351287 (2.83 GB)
telemt_user_msgs_from_client{user="hello"} 158431
telemt_user_msgs_to_client{user="hello"} 780312
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 17599.0 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13148
telemt_connections_bad_total 4686
telemt_handshake_timeouts_total 538
telemt_upstream_connect_attempt_total 7716
telemt_upstream_connect_success_total 7716
telemt_upstream_connect_attempts_per_request{bucket="1"} 7716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7714
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 207243379 (197.64 MB)
telemt_user_octets_to_client{user="hello"} 19252408832 (17.93 GB)
telemt_user_msgs_from_client{user="hello"} 331139
telemt_user_msgs_to_client{user="hello"} 3438429
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```