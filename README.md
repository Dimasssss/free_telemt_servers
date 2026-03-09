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

# Server Metrics 2026-03-09 16:03:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 60219.3 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109469
telemt_connections_bad_total 1655
telemt_handshake_timeouts_total 967
telemt_upstream_connect_attempt_total 102316
telemt_upstream_connect_success_total 102277
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 102316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 102271
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 2616066332 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 53344964612 (49.68 GB)
telemt_user_msgs_from_client{user="hello"} 2479036
telemt_user_msgs_to_client{user="hello"} 3565354
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 60218.6 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28307
telemt_connections_bad_total 220
telemt_handshake_timeouts_total 345
telemt_upstream_connect_attempt_total 26660
telemt_upstream_connect_success_total 26643
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 26660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26637
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 846386436 (807.18 MB)
telemt_user_octets_to_client{user="hello"} 15236259979 (14.19 GB)
telemt_user_msgs_from_client{user="hello"} 761586
telemt_user_msgs_to_client{user="hello"} 4172808
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 60219.4 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35651
telemt_connections_bad_total 646
telemt_handshake_timeouts_total 1623
telemt_upstream_connect_attempt_total 26582
telemt_upstream_connect_success_total 26582
telemt_upstream_connect_attempts_per_request{bucket="1"} 26582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26576
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 4402457656 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 16931207398 (15.77 GB)
telemt_user_msgs_from_client{user="hello"} 1916596
telemt_user_msgs_to_client{user="hello"} 2248950
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 60213.6 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40163
telemt_connections_bad_total 197
telemt_handshake_timeouts_total 853
telemt_upstream_connect_attempt_total 36943
telemt_upstream_connect_success_total 36848
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 36943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36842
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 1910823999 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 29232600274 (27.22 GB)
telemt_user_msgs_from_client{user="hello"} 1223981
telemt_user_msgs_to_client{user="hello"} 7575571
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 60219.1 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67649
telemt_connections_bad_total 14472
telemt_handshake_timeouts_total 1580
telemt_upstream_connect_attempt_total 48431
telemt_upstream_connect_success_total 48429
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 48431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48423
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 810918016 (773.35 MB)
telemt_user_octets_to_client{user="hello"} 49823328305 (46.40 GB)
telemt_user_msgs_from_client{user="hello"} 1113048
telemt_user_msgs_to_client{user="hello"} 6127774
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```