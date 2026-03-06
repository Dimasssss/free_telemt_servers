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

# Server Metrics 2026-03-06 19:42:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 5654.3 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10394
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 360
telemt_upstream_connect_attempt_total 9279
telemt_upstream_connect_success_total 9275
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 9279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9273
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 920754579 (878.10 MB)
telemt_user_octets_to_client{user="hello"} 12709428821 (11.84 GB)
telemt_user_msgs_from_client{user="hello"} 572658
telemt_user_msgs_to_client{user="hello"} 2005337
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 5653.1 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2701
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 2517
telemt_upstream_connect_success_total 2517
telemt_upstream_connect_attempts_per_request{bucket="1"} 2517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2515
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 62978034 (60.06 MB)
telemt_user_octets_to_client{user="hello"} 1766057281 (1.64 GB)
telemt_user_msgs_from_client{user="hello"} 65881
telemt_user_msgs_to_client{user="hello"} 498008
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 5652.9 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1504
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 1408
telemt_upstream_connect_success_total 1408
telemt_upstream_connect_attempts_per_request{bucket="1"} 1408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1406
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 16616672 (15.85 MB)
telemt_user_octets_to_client{user="hello"} 659031836 (628.50 MB)
telemt_user_msgs_from_client{user="hello"} 26341
telemt_user_msgs_to_client{user="hello"} 155773
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 5652.8 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1312
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1272
telemt_upstream_connect_success_total 1268
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1266
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 25938780 (24.74 MB)
telemt_user_octets_to_client{user="hello"} 488091297 (465.48 MB)
telemt_user_msgs_from_client{user="hello"} 26988
telemt_user_msgs_to_client{user="hello"} 126852
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 5653.3 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4474
telemt_connections_bad_total 1044
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3401
telemt_upstream_connect_success_total 3401
telemt_upstream_connect_attempts_per_request{bucket="1"} 3401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3399
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 78143275 (74.52 MB)
telemt_user_octets_to_client{user="hello"} 2287601314 (2.13 GB)
telemt_user_msgs_from_client{user="hello"} 87023
telemt_user_msgs_to_client{user="hello"} 519744
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```