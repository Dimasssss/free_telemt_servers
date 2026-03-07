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

# Server Metrics 2026-03-07 22:54:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 22173.9 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33559
telemt_connections_bad_total 224
telemt_handshake_timeouts_total 183
telemt_upstream_connect_attempt_total 32278
telemt_upstream_connect_success_total 32274
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32272
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 2131997427 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 22934127446 (21.36 GB)
telemt_user_msgs_from_client{user="hello"} 1153563
telemt_user_msgs_to_client{user="hello"} 3556452
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 22172.7 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6181
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 5892
telemt_upstream_connect_success_total 5885
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5881
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 111685457 (106.51 MB)
telemt_user_octets_to_client{user="hello"} 4345864852 (4.05 GB)
telemt_user_msgs_from_client{user="hello"} 176355
telemt_user_msgs_to_client{user="hello"} 1200345
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 22172.5 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3789
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3604
telemt_upstream_connect_success_total 3604
telemt_upstream_connect_attempts_per_request{bucket="1"} 3604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3602
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 105003778 (100.14 MB)
telemt_user_octets_to_client{user="hello"} 10799803457 (10.06 GB)
telemt_user_msgs_from_client{user="hello"} 174293
telemt_user_msgs_to_client{user="hello"} 2312767
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 22000.7 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9943
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9568
telemt_upstream_connect_success_total 9545
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 9568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9543
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 192193822 (183.29 MB)
telemt_user_octets_to_client{user="hello"} 9382903052 (8.74 GB)
telemt_user_msgs_from_client{user="hello"} 255931
telemt_user_msgs_to_client{user="hello"} 2768722
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 22172.6 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11048
telemt_connections_bad_total 4110
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 6731
telemt_upstream_connect_success_total 6723
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 6731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6721
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 1603640217 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 6347730987 (5.91 GB)
telemt_user_msgs_from_client{user="hello"} 760264
telemt_user_msgs_to_client{user="hello"} 1443339
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```