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

# Server Metrics 2026-03-06 19:37:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 5346.0 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9959
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 360
telemt_upstream_connect_attempt_total 8867
telemt_upstream_connect_success_total 8863
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 8867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8861
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 916618604 (874.16 MB)
telemt_user_octets_to_client{user="hello"} 12482959068 (11.63 GB)
telemt_user_msgs_from_client{user="hello"} 562034
telemt_user_msgs_to_client{user="hello"} 1967281
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 5344.8 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2649
telemt_connections_bad_total 62
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 2466
telemt_upstream_connect_success_total 2466
telemt_upstream_connect_attempts_per_request{bucket="1"} 2466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2464
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 62839061 (59.93 MB)
telemt_user_octets_to_client{user="hello"} 1765159062 (1.64 GB)
telemt_user_msgs_from_client{user="hello"} 65365
telemt_user_msgs_to_client{user="hello"} 497008
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 5344.8 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1370
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1294
telemt_upstream_connect_success_total 1294
telemt_upstream_connect_attempts_per_request{bucket="1"} 1294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1292
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 16142220 (15.39 MB)
telemt_user_octets_to_client{user="hello"} 651654443 (621.47 MB)
telemt_user_msgs_from_client{user="hello"} 25467
telemt_user_msgs_to_client{user="hello"} 152958
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 5344.7 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1238
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1200
telemt_upstream_connect_success_total 1196
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 94
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1194
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 25488631 (24.31 MB)
telemt_user_octets_to_client{user="hello"} 482710730 (460.35 MB)
telemt_user_msgs_from_client{user="hello"} 26357
telemt_user_msgs_to_client{user="hello"} 124436
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 5345.2 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4321
telemt_connections_bad_total 989
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3303
telemt_upstream_connect_success_total 3303
telemt_upstream_connect_attempts_per_request{bucket="1"} 3303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3301
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 77526904 (73.94 MB)
telemt_user_octets_to_client{user="hello"} 2272823245 (2.12 GB)
telemt_user_msgs_from_client{user="hello"} 85185
telemt_user_msgs_to_client{user="hello"} 515381
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```