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

# Server Metrics 2026-03-06 06:31:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 29786.3 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83669
telemt_connections_bad_total 51942
telemt_handshake_timeouts_total 2472
telemt_upstream_connect_attempt_total 27444
telemt_upstream_connect_success_total 27440
telemt_upstream_connect_attempts_per_request{bucket="1"} 27436
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27436
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 392218003 (374.05 MB)
telemt_user_octets_to_client{user="hello"} 23215647331 (21.62 GB)
telemt_user_msgs_from_client{user="hello"} 684099
telemt_user_msgs_to_client{user="hello"} 3529505
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 29783.9 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3587
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 3376
telemt_upstream_connect_success_total 3375
telemt_upstream_connect_attempts_per_request{bucket="1"} 3374
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3371
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 70016545 (66.77 MB)
telemt_user_octets_to_client{user="hello"} 1437891466 (1.34 GB)
telemt_user_msgs_from_client{user="hello"} 98315
telemt_user_msgs_to_client{user="hello"} 461781
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 29784.3 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2905
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2650
telemt_upstream_connect_success_total 2650
telemt_upstream_connect_attempts_per_request{bucket="1"} 2650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2646
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 59362554 (56.61 MB)
telemt_user_octets_to_client{user="hello"} 2728849667 (2.54 GB)
telemt_user_msgs_from_client{user="hello"} 86837
telemt_user_msgs_to_client{user="hello"} 585039
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 29787.0 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5494
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 311
telemt_upstream_connect_attempt_total 4751
telemt_upstream_connect_success_total 4750
telemt_upstream_connect_attempts_per_request{bucket="1"} 4749
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4746
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 109667130 (104.59 MB)
telemt_user_octets_to_client{user="hello"} 7517832005 (7.00 GB)
telemt_user_msgs_from_client{user="hello"} 171526
telemt_user_msgs_to_client{user="hello"} 1595171
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 29786.8 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10169
telemt_connections_bad_total 5449
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 4439
telemt_upstream_connect_success_total 4439
telemt_upstream_connect_attempts_per_request{bucket="1"} 4439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4435
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 99997249 (95.36 MB)
telemt_user_octets_to_client{user="hello"} 20628230918 (19.21 GB)
telemt_user_msgs_from_client{user="hello"} 253633
telemt_user_msgs_to_client{user="hello"} 3856243
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```