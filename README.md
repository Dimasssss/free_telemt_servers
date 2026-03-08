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

# Server Metrics 2026-03-08 10:43:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 12871.7 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26364
telemt_connections_bad_total 2559
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 22586
telemt_upstream_connect_success_total 22571
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 22586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22569
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 836606167 (797.85 MB)
telemt_user_octets_to_client{user="hello"} 13589577064 (12.66 GB)
telemt_user_msgs_from_client{user="hello"} 662426
telemt_user_msgs_to_client{user="hello"} 760850
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 12870.6 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6600
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 6265
telemt_upstream_connect_success_total 6265
telemt_upstream_connect_attempts_per_request{bucket="1"} 6265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6263
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 89967160 (85.80 MB)
telemt_user_octets_to_client{user="hello"} 4260315985 (3.97 GB)
telemt_user_msgs_from_client{user="hello"} 163654
telemt_user_msgs_to_client{user="hello"} 1119522
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 12870.8 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4540
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 4433
telemt_upstream_connect_success_total 4433
telemt_upstream_connect_attempts_per_request{bucket="1"} 4433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4431
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 38157862 (36.39 MB)
telemt_user_octets_to_client{user="hello"} 1316617531 (1.23 GB)
telemt_user_msgs_from_client{user="hello"} 48641
telemt_user_msgs_to_client{user="hello"} 222493
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 12870.3 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6108
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 5834
telemt_upstream_connect_success_total 5824
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 5834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5822
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 871974499 (831.58 MB)
telemt_user_octets_to_client{user="hello"} 2568407258 (2.39 GB)
telemt_user_msgs_from_client{user="hello"} 358139
telemt_user_msgs_to_client{user="hello"} 554896
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 12870.6 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7843
telemt_connections_bad_total 2407
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 5344
telemt_upstream_connect_success_total 5343
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5341
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 67990356 (64.84 MB)
telemt_user_octets_to_client{user="hello"} 4087799130 (3.81 GB)
telemt_user_msgs_from_client{user="hello"} 127494
telemt_user_msgs_to_client{user="hello"} 568600
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```