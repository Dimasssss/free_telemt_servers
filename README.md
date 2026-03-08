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

# Server Metrics 2026-03-08 15:41:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 30770.9 (8h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75444
telemt_connections_bad_total 5033
telemt_handshake_timeouts_total 1054
telemt_upstream_connect_attempt_total 66708
telemt_upstream_connect_success_total 66685
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 66708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66681
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 1728425877 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 35888024882 (33.42 GB)
telemt_user_msgs_from_client{user="hello"} 1576843
telemt_user_msgs_to_client{user="hello"} 2158813
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 30770.0 (8h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15861
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 15323
telemt_upstream_connect_success_total 15322
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15318
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 572209126 (545.70 MB)
telemt_user_octets_to_client{user="hello"} 13159298543 (12.26 GB)
telemt_user_msgs_from_client{user="hello"} 583232
telemt_user_msgs_to_client{user="hello"} 3449277
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 30769.9 (8h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10163
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9533
telemt_upstream_connect_success_total 9457
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9453
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 217118215 (207.06 MB)
telemt_user_octets_to_client{user="hello"} 3201518045 (2.98 GB)
telemt_user_msgs_from_client{user="hello"} 161040
telemt_user_msgs_to_client{user="hello"} 551054
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 30769.6 (8h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13111
telemt_connections_bad_total 156
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 12499
telemt_upstream_connect_success_total 12471
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 12499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12467
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 955172119 (910.92 MB)
telemt_user_octets_to_client{user="hello"} 4664149992 (4.34 GB)
telemt_user_msgs_from_client{user="hello"} 472473
telemt_user_msgs_to_client{user="hello"} 1052461
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 30769.8 (8h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17547
telemt_connections_bad_total 5661
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 11501
telemt_upstream_connect_success_total 11497
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11493
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 234620114 (223.75 MB)
telemt_user_octets_to_client{user="hello"} 8482297546 (7.90 GB)
telemt_user_msgs_from_client{user="hello"} 286204
telemt_user_msgs_to_client{user="hello"} 1191478
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```