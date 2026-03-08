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

# Server Metrics 2026-03-08 11:45:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 16597.0 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35350
telemt_connections_bad_total 2571
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 31082
telemt_upstream_connect_success_total 31063
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 31082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31061
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 1017291362 (970.16 MB)
telemt_user_octets_to_client{user="hello"} 16885061698 (15.73 GB)
telemt_user_msgs_from_client{user="hello"} 819378
telemt_user_msgs_to_client{user="hello"} 992026
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 16596.3 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8702
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 8326
telemt_upstream_connect_success_total 8326
telemt_upstream_connect_attempts_per_request{bucket="1"} 8326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8324
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 128086621 (122.15 MB)
telemt_user_octets_to_client{user="hello"} 5535509588 (5.16 GB)
telemt_user_msgs_from_client{user="hello"} 220809
telemt_user_msgs_to_client{user="hello"} 1425679
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 16596.2 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5352
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 5203
telemt_upstream_connect_success_total 5145
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 5203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5143
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 119635591 (114.09 MB)
telemt_user_octets_to_client{user="hello"} 1431837788 (1.33 GB)
telemt_user_msgs_from_client{user="hello"} 84672
telemt_user_msgs_to_client{user="hello"} 250281
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 16595.8 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7662
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 7318
telemt_upstream_connect_success_total 7305
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 7318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7303
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 884109136 (843.15 MB)
telemt_user_octets_to_client{user="hello"} 2910540596 (2.71 GB)
telemt_user_msgs_from_client{user="hello"} 379070
telemt_user_msgs_to_client{user="hello"} 640107
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 16596.2 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10171
telemt_connections_bad_total 3087
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 6930
telemt_upstream_connect_success_total 6929
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6927
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 117550470 (112.10 MB)
telemt_user_octets_to_client{user="hello"} 6358363187 (5.92 GB)
telemt_user_msgs_from_client{user="hello"} 184111
telemt_user_msgs_to_client{user="hello"} 874250
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```