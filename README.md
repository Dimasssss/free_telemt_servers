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

# Server Metrics 2026-03-08 22:27:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 55124.3 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116566
telemt_connections_bad_total 5589
telemt_handshake_timeouts_total 1282
telemt_upstream_connect_attempt_total 105871
telemt_upstream_connect_success_total 105833
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 105871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105827
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2586214001 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 70922259132 (66.05 GB)
telemt_user_msgs_from_client{user="hello"} 2646448
telemt_user_msgs_to_client{user="hello"} 3655777
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 55123.4 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27347
telemt_connections_bad_total 292
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 26450
telemt_upstream_connect_success_total 26443
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26437
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 840566613 (801.63 MB)
telemt_user_octets_to_client{user="hello"} 22844641324 (21.28 GB)
telemt_user_msgs_from_client{user="hello"} 983327
telemt_user_msgs_to_client{user="hello"} 6189161
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 55123.1 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15554
telemt_connections_bad_total 235
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 14136
telemt_upstream_connect_success_total 14060
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14054
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1564666706 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 5693648833 (5.30 GB)
telemt_user_msgs_from_client{user="hello"} 701583
telemt_user_msgs_to_client{user="hello"} 977888
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 55122.9 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21357
telemt_connections_bad_total 213
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 20487
telemt_upstream_connect_success_total 20447
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 20487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20441
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1068058043 (1018.58 MB)
telemt_user_octets_to_client{user="hello"} 6595075943 (6.14 GB)
telemt_user_msgs_from_client{user="hello"} 576582
telemt_user_msgs_to_client{user="hello"} 1501790
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 55123.2 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31954
telemt_connections_bad_total 10495
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 20709
telemt_upstream_connect_success_total 20702
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 20709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20696
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 382218141 (364.51 MB)
telemt_user_octets_to_client{user="hello"} 18144785356 (16.90 GB)
telemt_user_msgs_from_client{user="hello"} 555286
telemt_user_msgs_to_client{user="hello"} 2345304
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```