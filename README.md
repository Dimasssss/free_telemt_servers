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

# Server Metrics 2026-03-10 17:08:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9727.8 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41038
telemt_connections_bad_total 381
telemt_handshake_timeouts_total 1343
telemt_upstream_connect_attempt_total 36963
telemt_upstream_connect_success_total 36954
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 36963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36952
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 1158280801 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 25610441150 (23.85 GB)
telemt_user_msgs_from_client{user="hello"} 1046809
telemt_user_msgs_to_client{user="hello"} 1721157
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 9727.1 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13912
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 315
telemt_upstream_connect_attempt_total 12549
telemt_upstream_connect_success_total 12547
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 12549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12545
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 391350594 (373.22 MB)
telemt_user_octets_to_client{user="hello"} 7403754520 (6.90 GB)
telemt_user_msgs_from_client{user="hello"} 385580
telemt_user_msgs_to_client{user="hello"} 2315499
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 9726.8 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22489
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 1860
telemt_upstream_connect_attempt_total 19237
telemt_upstream_connect_success_total 19237
telemt_upstream_connect_attempts_per_request{bucket="1"} 19237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19235
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 173989754 (165.93 MB)
telemt_user_octets_to_client{user="hello"} 9184438727 (8.55 GB)
telemt_user_msgs_from_client{user="hello"} 373506
telemt_user_msgs_to_client{user="hello"} 1981037
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 9725.9 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21846
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 20805
telemt_upstream_connect_success_total 20746
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 20805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20744
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 300001076 (286.10 MB)
telemt_user_octets_to_client{user="hello"} 21833304083 (20.33 GB)
telemt_user_msgs_from_client{user="hello"} 442359
telemt_user_msgs_to_client{user="hello"} 3764270
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9727.0 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29902
telemt_connections_bad_total 1987
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 26122
telemt_upstream_connect_success_total 25886
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 26122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25884
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1243868569 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 17564128365 (16.36 GB)
telemt_user_msgs_from_client{user="hello"} 838345
telemt_user_msgs_to_client{user="hello"} 2542862
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 23
```