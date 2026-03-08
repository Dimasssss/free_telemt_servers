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

# Server Metrics 2026-03-08 18:25:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 40631.9 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95424
telemt_connections_bad_total 5047
telemt_handshake_timeouts_total 1249
telemt_upstream_connect_attempt_total 85964
telemt_upstream_connect_success_total 85935
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 85964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85929
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 2053459350 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 53615116549 (49.93 GB)
telemt_user_msgs_from_client{user="hello"} 2060212
telemt_user_msgs_to_client{user="hello"} 2933374
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 40630.9 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21413
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 20719
telemt_upstream_connect_success_total 20714
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 20719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20710
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 724903831 (691.32 MB)
telemt_user_octets_to_client{user="hello"} 19501762357 (18.16 GB)
telemt_user_msgs_from_client{user="hello"} 834937
telemt_user_msgs_to_client{user="hello"} 5344150
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 40630.7 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13158
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 11843
telemt_upstream_connect_success_total 11767
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11763
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 236539867 (225.58 MB)
telemt_user_octets_to_client{user="hello"} 4209857195 (3.92 GB)
telemt_user_msgs_from_client{user="hello"} 203618
telemt_user_msgs_to_client{user="hello"} 749130
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 40630.6 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16859
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 16125
telemt_upstream_connect_success_total 16091
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 16125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16087
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 1021431151 (974.11 MB)
telemt_user_octets_to_client{user="hello"} 5779642184 (5.38 GB)
telemt_user_msgs_from_client{user="hello"} 532421
telemt_user_msgs_to_client{user="hello"} 1310401
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 40630.8 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23940
telemt_connections_bad_total 7704
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 15642
telemt_upstream_connect_success_total 15636
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 15642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15632
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 282191743 (269.12 MB)
telemt_user_octets_to_client{user="hello"} 12038046986 (11.21 GB)
telemt_user_msgs_from_client{user="hello"} 376131
telemt_user_msgs_to_client{user="hello"} 1581299
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```