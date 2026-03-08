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

# Server Metrics 2026-03-08 22:06:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 53891.6 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115400
telemt_connections_bad_total 5528
telemt_handshake_timeouts_total 1282
telemt_upstream_connect_attempt_total 104784
telemt_upstream_connect_success_total 104746
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 104784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104740
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 2573481792 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 69395812999 (64.63 GB)
telemt_user_msgs_from_client{user="hello"} 2615946
telemt_user_msgs_to_client{user="hello"} 3606043
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 53890.9 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27182
telemt_connections_bad_total 292
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 26287
telemt_upstream_connect_success_total 26280
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26274
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 839226962 (800.35 MB)
telemt_user_octets_to_client{user="hello"} 22731568647 (21.17 GB)
telemt_user_msgs_from_client{user="hello"} 979438
telemt_user_msgs_to_client{user="hello"} 6162611
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 53890.7 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15481
telemt_connections_bad_total 231
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 14069
telemt_upstream_connect_success_total 13993
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13987
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 1554599040 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 5691356139 (5.30 GB)
telemt_user_msgs_from_client{user="hello"} 697664
telemt_user_msgs_to_client{user="hello"} 976786
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 53890.6 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21228
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 20359
telemt_upstream_connect_success_total 20319
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 20359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20313
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1067749537 (1018.29 MB)
telemt_user_octets_to_client{user="hello"} 6582102507 (6.13 GB)
telemt_user_msgs_from_client{user="hello"} 575731
telemt_user_msgs_to_client{user="hello"} 1496403
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 53890.9 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31367
telemt_connections_bad_total 10228
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 20395
telemt_upstream_connect_success_total 20388
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 20395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20382
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 375027742 (357.65 MB)
telemt_user_octets_to_client{user="hello"} 17554051140 (16.35 GB)
telemt_user_msgs_from_client{user="hello"} 537800
telemt_user_msgs_to_client{user="hello"} 2277853
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```