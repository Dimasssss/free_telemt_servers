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

# Server Metrics 2026-03-08 15:46:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 31078.7 (8h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76113
telemt_connections_bad_total 5033
telemt_handshake_timeouts_total 1055
telemt_upstream_connect_attempt_total 67362
telemt_upstream_connect_success_total 67339
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 67362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67335
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 1736194600 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 36170997879 (33.69 GB)
telemt_user_msgs_from_client{user="hello"} 1589181
telemt_user_msgs_to_client{user="hello"} 2178991
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 31078.0 (8h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16036
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 15488
telemt_upstream_connect_success_total 15487
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15483
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 575142757 (548.50 MB)
telemt_user_octets_to_client{user="hello"} 13662607611 (12.72 GB)
telemt_user_msgs_from_client{user="hello"} 590518
telemt_user_msgs_to_client{user="hello"} 3609366
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 31077.7 (8h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10213
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9581
telemt_upstream_connect_success_total 9505
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9501
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 217214383 (207.15 MB)
telemt_user_octets_to_client{user="hello"} 3204158697 (2.98 GB)
telemt_user_msgs_from_client{user="hello"} 161331
telemt_user_msgs_to_client{user="hello"} 551909
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 31077.5 (8h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13217
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 12604
telemt_upstream_connect_success_total 12576
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 12604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 928
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12572
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 955778684 (911.50 MB)
telemt_user_octets_to_client{user="hello"} 4684669290 (4.36 GB)
telemt_user_msgs_from_client{user="hello"} 473814
telemt_user_msgs_to_client{user="hello"} 1056545
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 31077.7 (8h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17660
telemt_connections_bad_total 5717
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 11558
telemt_upstream_connect_success_total 11554
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11550
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 234932663 (224.05 MB)
telemt_user_octets_to_client{user="hello"} 8487850326 (7.90 GB)
telemt_user_msgs_from_client{user="hello"} 287071
telemt_user_msgs_to_client{user="hello"} 1193055
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```