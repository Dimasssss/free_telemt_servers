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

# Server Metrics 2026-03-08 21:15:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 50798.5 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112267
telemt_connections_bad_total 5494
telemt_handshake_timeouts_total 1279
telemt_upstream_connect_attempt_total 101734
telemt_upstream_connect_success_total 101698
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 101734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101692
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 2455123948 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 63938225212 (59.55 GB)
telemt_user_msgs_from_client{user="hello"} 2503234
telemt_user_msgs_to_client{user="hello"} 3457167
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 50797.6 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26381
telemt_connections_bad_total 283
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 25504
telemt_upstream_connect_success_total 25497
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 25504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25491
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 836493771 (797.74 MB)
telemt_user_octets_to_client{user="hello"} 22605420107 (21.05 GB)
telemt_user_msgs_from_client{user="hello"} 971173
telemt_user_msgs_to_client{user="hello"} 6127993
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 50797.4 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15094
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13691
telemt_upstream_connect_success_total 13615
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13609
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1553728631 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 5651523692 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 695308
telemt_user_msgs_to_client{user="hello"} 966724
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 50797.2 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20216
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 19366
telemt_upstream_connect_success_total 19327
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 19366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19321
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 1065066657 (1015.73 MB)
telemt_user_octets_to_client{user="hello"} 6467849033 (6.02 GB)
telemt_user_msgs_from_client{user="hello"} 568831
telemt_user_msgs_to_client{user="hello"} 1464614
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 50797.5 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29816
telemt_connections_bad_total 9668
telemt_handshake_timeouts_total 239
telemt_upstream_connect_attempt_total 19432
telemt_upstream_connect_success_total 19425
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19419
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 361477821 (344.73 MB)
telemt_user_octets_to_client{user="hello"} 16674257412 (15.53 GB)
telemt_user_msgs_from_client{user="hello"} 506306
telemt_user_msgs_to_client{user="hello"} 2157041
telemt_user_unique_ips_current{user="hello"} 6
```