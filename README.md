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

# Server Metrics 2026-03-06 04:54:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 23937.5 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75141
telemt_connections_bad_total 51936
telemt_handshake_timeouts_total 2441
telemt_upstream_connect_attempt_total 19265
telemt_upstream_connect_success_total 19263
telemt_upstream_connect_attempts_per_request{bucket="1"} 19261
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19259
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 254344776 (242.56 MB)
telemt_user_octets_to_client{user="hello"} 17096590399 (15.92 GB)
telemt_user_msgs_from_client{user="hello"} 469171
telemt_user_msgs_to_client{user="hello"} 2551251
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 23935.6 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2557
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 2371
telemt_upstream_connect_success_total 2370
telemt_upstream_connect_attempts_per_request{bucket="1"} 2369
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 93
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2368
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 54903869 (52.36 MB)
telemt_user_octets_to_client{user="hello"} 1059542167 (1010.46 MB)
telemt_user_msgs_from_client{user="hello"} 75654
telemt_user_msgs_to_client{user="hello"} 338930
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 23935.9 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1542
telemt_connections_bad_total 198
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1331
telemt_upstream_connect_success_total 1331
telemt_upstream_connect_attempts_per_request{bucket="1"} 1331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 165
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1327
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 37587189 (35.85 MB)
telemt_user_octets_to_client{user="hello"} 1790946489 (1.67 GB)
telemt_user_msgs_from_client{user="hello"} 48700
telemt_user_msgs_to_client{user="hello"} 360959
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 23939.0 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3179
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 303
telemt_upstream_connect_attempt_total 2663
telemt_upstream_connect_success_total 2663
telemt_upstream_connect_attempts_per_request{bucket="1"} 2663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 389
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2659
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 96207322 (91.75 MB)
telemt_user_octets_to_client{user="hello"} 5687772766 (5.30 GB)
telemt_user_msgs_from_client{user="hello"} 136324
telemt_user_msgs_to_client{user="hello"} 1196912
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 23938.5 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8090
telemt_connections_bad_total 4354
telemt_handshake_timeouts_total 153
telemt_upstream_connect_attempt_total 3493
telemt_upstream_connect_success_total 3493
telemt_upstream_connect_attempts_per_request{bucket="1"} 3493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3489
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 70583905 (67.31 MB)
telemt_user_octets_to_client{user="hello"} 13794119485 (12.85 GB)
telemt_user_msgs_from_client{user="hello"} 180186
telemt_user_msgs_to_client{user="hello"} 2644212
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```