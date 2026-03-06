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

# Server Metrics 2026-03-06 11:14:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 3125.8 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9717
telemt_connections_bad_total 3023
telemt_handshake_timeouts_total 91
telemt_upstream_connect_attempt_total 6345
telemt_upstream_connect_success_total 6345
telemt_upstream_connect_attempts_per_request{bucket="1"} 6345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6343
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 107989453 (102.99 MB)
telemt_user_octets_to_client{user="hello"} 4149084773 (3.86 GB)
telemt_user_msgs_from_client{user="hello"} 148755
telemt_user_msgs_to_client{user="hello"} 661094
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 3124.8 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1359
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 1299
telemt_upstream_connect_success_total 1298
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 76
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1296
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 15853410 (15.12 MB)
telemt_user_octets_to_client{user="hello"} 550270779 (524.78 MB)
telemt_user_msgs_from_client{user="hello"} 32028
telemt_user_msgs_to_client{user="hello"} 170314
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 3124.6 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1125
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1093
telemt_upstream_connect_success_total 1093
telemt_upstream_connect_attempts_per_request{bucket="1"} 1093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1091
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 29884693 (28.50 MB)
telemt_user_octets_to_client{user="hello"} 485688388 (463.19 MB)
telemt_user_msgs_from_client{user="hello"} 29660
telemt_user_msgs_to_client{user="hello"} 103254
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 3123.4 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2546
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 2344
telemt_upstream_connect_success_total 2333
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2331
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 33435927 (31.89 MB)
telemt_user_octets_to_client{user="hello"} 499759160 (476.61 MB)
telemt_user_msgs_from_client{user="hello"} 35754
telemt_user_msgs_to_client{user="hello"} 147626
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 3124.8 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2205
telemt_connections_bad_total 564
telemt_handshake_timeouts_total 295
telemt_upstream_connect_attempt_total 1296
telemt_upstream_connect_success_total 1296
telemt_upstream_connect_attempts_per_request{bucket="1"} 1296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1294
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 30477963 (29.07 MB)
telemt_user_octets_to_client{user="hello"} 333536657 (318.09 MB)
telemt_user_msgs_from_client{user="hello"} 25182
telemt_user_msgs_to_client{user="hello"} 77263
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```