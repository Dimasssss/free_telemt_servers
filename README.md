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

# Server Metrics 2026-03-05 23:15:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 3624.5 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55131
telemt_connections_bad_total 51890
telemt_handshake_timeouts_total 934
telemt_upstream_connect_attempt_total 2279
telemt_upstream_connect_success_total 2279
telemt_upstream_connect_attempts_per_request{bucket="1"} 2279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2277
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 32507749 (31.00 MB)
telemt_user_octets_to_client{user="hello"} 4142884103 (3.86 GB)
telemt_user_msgs_from_client{user="hello"} 78249
telemt_user_msgs_to_client{user="hello"} 584395
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 3622.2 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334
telemt_connections_bad_total 16
telemt_upstream_connect_attempt_total 319
telemt_upstream_connect_success_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 317
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1672121 (1.59 MB)
telemt_user_octets_to_client{user="hello"} 88972005 (84.85 MB)
telemt_user_msgs_from_client{user="hello"} 4556
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 3622.6 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210
telemt_connections_bad_total 25
telemt_upstream_connect_attempt_total 187
telemt_upstream_connect_success_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 185
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 591240 (577.38 KB)
telemt_user_octets_to_client{user="hello"} 15676555 (14.95 MB)
telemt_user_msgs_from_client{user="hello"} 1499
telemt_user_msgs_to_client{user="hello"} 5194
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 3625.3 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477
telemt_connections_bad_total 53
telemt_upstream_connect_attempt_total 415
telemt_upstream_connect_success_total 415
telemt_upstream_connect_attempts_per_request{bucket="1"} 415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 70
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 413
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 12390720 (11.82 MB)
telemt_user_octets_to_client{user="hello"} 2017466543 (1.88 GB)
telemt_user_msgs_from_client{user="hello"} 35248
telemt_user_msgs_to_client{user="hello"} 349593
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 3625.2 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1164
telemt_connections_bad_total 656
telemt_upstream_connect_attempt_total 496
telemt_upstream_connect_success_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 95
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 494
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 15871174 (15.14 MB)
telemt_user_octets_to_client{user="hello"} 4043722432 (3.77 GB)
telemt_user_msgs_from_client{user="hello"} 43017
telemt_user_msgs_to_client{user="hello"} 716306
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```