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

# Server Metrics 2026-03-08 11:24:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 15335.3 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32249
telemt_connections_bad_total 2571
telemt_handshake_timeouts_total 199
telemt_upstream_connect_attempt_total 28187
telemt_upstream_connect_success_total 28171
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 28187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28169
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 992949820 (946.95 MB)
telemt_user_octets_to_client{user="hello"} 15848972061 (14.76 GB)
telemt_user_msgs_from_client{user="hello"} 779895
telemt_user_msgs_to_client{user="hello"} 913456
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 15334.7 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8095
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 7735
telemt_upstream_connect_success_total 7735
telemt_upstream_connect_attempts_per_request{bucket="1"} 7735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7733
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 112395431 (107.19 MB)
telemt_user_octets_to_client{user="hello"} 5352956946 (4.99 GB)
telemt_user_msgs_from_client{user="hello"} 205148
telemt_user_msgs_to_client{user="hello"} 1377776
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 15334.4 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5014
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 4884
telemt_upstream_connect_success_total 4884
telemt_upstream_connect_attempts_per_request{bucket="1"} 4884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4882
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 112094413 (106.90 MB)
telemt_user_octets_to_client{user="hello"} 1385927446 (1.29 GB)
telemt_user_msgs_from_client{user="hello"} 79398
telemt_user_msgs_to_client{user="hello"} 239439
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 15334.3 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7158
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 6836
telemt_upstream_connect_success_total 6825
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 6836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 440
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6823
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 880685730 (839.89 MB)
telemt_user_octets_to_client{user="hello"} 2817909355 (2.62 GB)
telemt_user_msgs_from_client{user="hello"} 372525
telemt_user_msgs_to_client{user="hello"} 613653
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 15334.5 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9584
telemt_connections_bad_total 2859
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 6576
telemt_upstream_connect_success_total 6575
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6573
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 105730145 (100.83 MB)
telemt_user_octets_to_client{user="hello"} 4584525349 (4.27 GB)
telemt_user_msgs_from_client{user="hello"} 153243
telemt_user_msgs_to_client{user="hello"} 652547
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```