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

# Server Metrics 2026-03-08 11:55:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 17213.0 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36941
telemt_connections_bad_total 2571
telemt_handshake_timeouts_total 265
telemt_upstream_connect_attempt_total 32573
telemt_upstream_connect_success_total 32554
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 32573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32552
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 1029207829 (981.53 MB)
telemt_user_octets_to_client{user="hello"} 17372350889 (16.18 GB)
telemt_user_msgs_from_client{user="hello"} 841829
telemt_user_msgs_to_client{user="hello"} 1027512
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 17212.2 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9389
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 100
telemt_upstream_connect_attempt_total 9010
telemt_upstream_connect_success_total 9010
telemt_upstream_connect_attempts_per_request{bucket="1"} 9010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9008
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 366691286 (349.70 MB)
telemt_user_octets_to_client{user="hello"} 5788272907 (5.39 GB)
telemt_user_msgs_from_client{user="hello"} 312523
telemt_user_msgs_to_client{user="hello"} 1500896
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 17212.0 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5923
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 5712
telemt_upstream_connect_success_total 5637
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 5712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5635
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 131315183 (125.23 MB)
telemt_user_octets_to_client{user="hello"} 1600509634 (1.49 GB)
telemt_user_msgs_from_client{user="hello"} 89140
telemt_user_msgs_to_client{user="hello"} 271219
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 17211.9 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7860
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 7514
telemt_upstream_connect_success_total 7500
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 7514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 463
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7498
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 885009680 (844.01 MB)
telemt_user_octets_to_client{user="hello"} 2947193798 (2.74 GB)
telemt_user_msgs_from_client{user="hello"} 381199
telemt_user_msgs_to_client{user="hello"} 650426
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 17212.1 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10445
telemt_connections_bad_total 3213
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 7077
telemt_upstream_connect_success_total 7076
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7074
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 118597572 (113.10 MB)
telemt_user_octets_to_client{user="hello"} 6414719873 (5.97 GB)
telemt_user_msgs_from_client{user="hello"} 186599
telemt_user_msgs_to_client{user="hello"} 881943
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```