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

# Server Metrics 2026-03-05 12:59:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 91936.1 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135744
telemt_connections_bad_total 532
telemt_handshake_timeouts_total 4233
telemt_upstream_connect_attempt_total 120314
telemt_upstream_connect_success_total 120283
telemt_upstream_connect_attempts_per_request{bucket="1"} 120252
telemt_upstream_connect_attempts_per_request{bucket="2"} 31
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 120273
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 3398840901 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 81839683434 (76.22 GB)
telemt_user_msgs_from_client{user="hello"} 3404549
telemt_user_msgs_to_client{user="hello"} 13366477
telemt_user_unique_ips_current{user="hello"} 10
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 91939.0 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25049
telemt_connections_bad_total 496
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 20124
telemt_upstream_connect_success_total 20120
telemt_upstream_connect_attempts_per_request{bucket="1"} 20116
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20110
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 1202874636 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 16339734346 (15.22 GB)
telemt_user_msgs_from_client{user="hello"} 890811
telemt_user_msgs_to_client{user="hello"} 5212217
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 91937.3 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21953
telemt_connections_bad_total 416
telemt_handshake_timeouts_total 41
telemt_upstream_connect_attempt_total 17602
telemt_upstream_connect_success_total 17602
telemt_upstream_connect_attempts_per_request{bucket="1"} 17602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17592
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 462928972 (441.48 MB)
telemt_user_octets_to_client{user="hello"} 10465263170 (9.75 GB)
telemt_user_msgs_from_client{user="hello"} 484683
telemt_user_msgs_to_client{user="hello"} 2256136
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 91935.1 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36533
telemt_connections_bad_total 1061
telemt_handshake_timeouts_total 642
telemt_upstream_connect_attempt_total 32284
telemt_upstream_connect_success_total 32269
telemt_upstream_connect_attempts_per_request{bucket="1"} 32254
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32259
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 533361635 (508.65 MB)
telemt_user_octets_to_client{user="hello"} 19044416009 (17.74 GB)
telemt_user_msgs_from_client{user="hello"} 595530
telemt_user_msgs_to_client{user="hello"} 4258182
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 91936.7 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36094
telemt_connections_bad_total 16602
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 18876
telemt_upstream_connect_success_total 18871
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18868
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18861
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 670881440 (639.80 MB)
telemt_user_octets_to_client{user="hello"} 29252076748 (27.24 GB)
telemt_user_msgs_from_client{user="hello"} 790920
telemt_user_msgs_to_client{user="hello"} 5617961
telemt_user_unique_ips_current{user="hello"} 1
```