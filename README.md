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

# Server Metrics 2026-03-08 04:28:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 42194.0 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60603
telemt_connections_bad_total 6026
telemt_handshake_timeouts_total 439
telemt_upstream_connect_attempt_total 50960
telemt_upstream_connect_success_total 50953
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 50960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50949
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 2395352588 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 33402879085 (31.11 GB)
telemt_user_msgs_from_client{user="hello"} 1563241
telemt_user_msgs_to_client{user="hello"} 5235702
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 42193.4 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8251
telemt_connections_bad_total 368
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 7744
telemt_upstream_connect_success_total 7736
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7730
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 192563056 (183.64 MB)
telemt_user_octets_to_client{user="hello"} 10870382904 (10.12 GB)
telemt_user_msgs_from_client{user="hello"} 350033
telemt_user_msgs_to_client{user="hello"} 2548106
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 42192.9 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5069
telemt_connections_bad_total 259
telemt_handshake_timeouts_total 62
telemt_upstream_connect_attempt_total 4668
telemt_upstream_connect_success_total 4668
telemt_upstream_connect_attempts_per_request{bucket="1"} 4668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4664
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 124807380 (119.03 MB)
telemt_user_octets_to_client{user="hello"} 14485458584 (13.49 GB)
telemt_user_msgs_from_client{user="hello"} 227632
telemt_user_msgs_to_client{user="hello"} 3076017
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 42021.2 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13736
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 13180
telemt_upstream_connect_success_total 13154
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 13180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13150
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 352754640 (336.41 MB)
telemt_user_octets_to_client{user="hello"} 12139984231 (11.31 GB)
telemt_user_msgs_from_client{user="hello"} 383867
telemt_user_msgs_to_client{user="hello"} 3453234
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 42193.2 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16671
telemt_connections_bad_total 7814
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 8600
telemt_upstream_connect_success_total 8592
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 8600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8588
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 1627203893 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 8727189863 (8.13 GB)
telemt_user_msgs_from_client{user="hello"} 822711
telemt_user_msgs_to_client{user="hello"} 1913449
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```