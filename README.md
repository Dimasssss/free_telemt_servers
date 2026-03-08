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

# Server Metrics 2026-03-08 11:19:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 15027.6 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31546
telemt_connections_bad_total 2561
telemt_handshake_timeouts_total 194
telemt_upstream_connect_attempt_total 27538
telemt_upstream_connect_success_total 27522
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 27538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27520
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 973287202 (928.20 MB)
telemt_user_octets_to_client{user="hello"} 15525400049 (14.46 GB)
telemt_user_msgs_from_client{user="hello"} 763187
telemt_user_msgs_to_client{user="hello"} 891775
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 15026.9 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7997
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 7639
telemt_upstream_connect_success_total 7639
telemt_upstream_connect_attempts_per_request{bucket="1"} 7639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7637
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 111202176 (106.05 MB)
telemt_user_octets_to_client{user="hello"} 5300013200 (4.94 GB)
telemt_user_msgs_from_client{user="hello"} 201816
telemt_user_msgs_to_client{user="hello"} 1365503
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 15026.6 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4968
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 4841
telemt_upstream_connect_success_total 4841
telemt_upstream_connect_attempts_per_request{bucket="1"} 4841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4839
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 110734140 (105.60 MB)
telemt_user_octets_to_client{user="hello"} 1383583379 (1.29 GB)
telemt_user_msgs_from_client{user="hello"} 78480
telemt_user_msgs_to_client{user="hello"} 238393
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 15026.4 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6971
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 6650
telemt_upstream_connect_success_total 6639
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 6650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6637
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 879434239 (838.69 MB)
telemt_user_octets_to_client{user="hello"} 2763320168 (2.57 GB)
telemt_user_msgs_from_client{user="hello"} 369547
telemt_user_msgs_to_client{user="hello"} 602544
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 15026.8 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9376
telemt_connections_bad_total 2804
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 6424
telemt_upstream_connect_success_total 6423
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6421
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 103315587 (98.53 MB)
telemt_user_octets_to_client{user="hello"} 4414830555 (4.11 GB)
telemt_user_msgs_from_client{user="hello"} 146907
telemt_user_msgs_to_client{user="hello"} 629690
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```