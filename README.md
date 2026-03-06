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

# Server Metrics 2026-03-06 19:57:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 6578.7 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11776
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 365
telemt_upstream_connect_attempt_total 10639
telemt_upstream_connect_success_total 10635
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10633
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 955728540 (911.45 MB)
telemt_user_octets_to_client{user="hello"} 13484982534 (12.56 GB)
telemt_user_msgs_from_client{user="hello"} 611704
telemt_user_msgs_to_client{user="hello"} 2146031
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 6576.9 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3026
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 2835
telemt_upstream_connect_success_total 2832
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2830
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 65455211 (62.42 MB)
telemt_user_octets_to_client{user="hello"} 2131740539 (1.99 GB)
telemt_user_msgs_from_client{user="hello"} 73125
telemt_user_msgs_to_client{user="hello"} 597939
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 6576.9 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1759
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 1620
telemt_upstream_connect_success_total 1620
telemt_upstream_connect_attempts_per_request{bucket="1"} 1620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1618
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 17186532 (16.39 MB)
telemt_user_octets_to_client{user="hello"} 670704472 (639.63 MB)
telemt_user_msgs_from_client{user="hello"} 27375
telemt_user_msgs_to_client{user="hello"} 159436
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 6577.1 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1514
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1470
telemt_upstream_connect_success_total 1466
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 112
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1464
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 72073099 (68.73 MB)
telemt_user_octets_to_client{user="hello"} 537068303 (512.19 MB)
telemt_user_msgs_from_client{user="hello"} 46271
telemt_user_msgs_to_client{user="hello"} 142604
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 6577.4 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4986
telemt_connections_bad_total 1208
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3744
telemt_upstream_connect_success_total 3744
telemt_upstream_connect_attempts_per_request{bucket="1"} 3744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3742
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 138416943 (132.00 MB)
telemt_user_octets_to_client{user="hello"} 2381910088 (2.22 GB)
telemt_user_msgs_from_client{user="hello"} 112511
telemt_user_msgs_to_client{user="hello"} 542064
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```