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

# Server Metrics 2026-03-05 23:10:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 3316.6 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54620
telemt_connections_bad_total 51578
telemt_handshake_timeouts_total 934
telemt_upstream_connect_attempt_total 2081
telemt_upstream_connect_success_total 2081
telemt_upstream_connect_attempts_per_request{bucket="1"} 2081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2079
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 29450117 (28.09 MB)
telemt_user_octets_to_client{user="hello"} 3722155021 (3.47 GB)
telemt_user_msgs_from_client{user="hello"} 70351
telemt_user_msgs_to_client{user="hello"} 525304
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 3314.5 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295
telemt_connections_bad_total 9
telemt_upstream_connect_attempt_total 287
telemt_upstream_connect_success_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 285
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 1592669 (1.52 MB)
telemt_user_octets_to_client{user="hello"} 86190914 (82.20 MB)
telemt_user_msgs_from_client{user="hello"} 4274
telemt_user_msgs_to_client{user="hello"} 30060
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 3314.9 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197
telemt_connections_bad_total 23
telemt_upstream_connect_attempt_total 176
telemt_upstream_connect_success_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 174
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 567092 (553.80 KB)
telemt_user_octets_to_client{user="hello"} 15499260 (14.78 MB)
telemt_user_msgs_from_client{user="hello"} 1427
telemt_user_msgs_to_client{user="hello"} 5066
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 3317.6 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444
telemt_connections_bad_total 53
telemt_upstream_connect_attempt_total 382
telemt_upstream_connect_success_total 382
telemt_upstream_connect_attempts_per_request{bucket="1"} 382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 63
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 380
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 11420347 (10.89 MB)
telemt_user_octets_to_client{user="hello"} 1835770868 (1.71 GB)
telemt_user_msgs_from_client{user="hello"} 32508
telemt_user_msgs_to_client{user="hello"} 320390
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 3317.4 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1054
telemt_connections_bad_total 601
telemt_upstream_connect_attempt_total 443
telemt_upstream_connect_success_total 443
telemt_upstream_connect_attempts_per_request{bucket="1"} 443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 70
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 441
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 12222650 (11.66 MB)
telemt_user_octets_to_client{user="hello"} 2843592221 (2.65 GB)
telemt_user_msgs_from_client{user="hello"} 33144
telemt_user_msgs_to_client{user="hello"} 511553
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```