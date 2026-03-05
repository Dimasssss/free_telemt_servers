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

# Server Metrics 2026-03-05 17:31:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.0

telemt_uptime_seconds 967.3 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3815
telemt_connections_bad_total 2470
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1317
telemt_upstream_connect_success_total 1316
telemt_upstream_connect_attempts_per_request{bucket="1"} 1315
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1314
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 12132334 (11.57 MB)
telemt_user_octets_to_client{user="hello"} 536015205 (511.18 MB)
telemt_user_msgs_from_client{user="hello"} 28575
telemt_user_msgs_to_client{user="hello"} 96729
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.0

telemt_uptime_seconds 969.9 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205
telemt_upstream_connect_attempt_total 207
telemt_upstream_connect_success_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 205
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 1294762 (1.23 MB)
telemt_user_octets_to_client{user="hello"} 69914599 (66.68 MB)
telemt_user_msgs_from_client{user="hello"} 3337
telemt_user_msgs_to_client{user="hello"} 19649
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.0

telemt_uptime_seconds 967.8 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 317
telemt_upstream_connect_success_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 315
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 1486012 (1.42 MB)
telemt_user_octets_to_client{user="hello"} 105694399 (100.80 MB)
telemt_user_msgs_from_client{user="hello"} 3938
telemt_user_msgs_to_client{user="hello"} 25108
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.0

telemt_uptime_seconds 965.4 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 273
telemt_upstream_connect_success_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 271
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 1308998 (1.25 MB)
telemt_user_octets_to_client{user="hello"} 56424651 (53.81 MB)
telemt_user_msgs_from_client{user="hello"} 3241
telemt_user_msgs_to_client{user="hello"} 16079
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.0

telemt_uptime_seconds 967.3 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 566
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 385
telemt_upstream_connect_success_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 383
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 18605065 (17.74 MB)
telemt_user_octets_to_client{user="hello"} 166921890 (159.19 MB)
telemt_user_msgs_from_client{user="hello"} 15634
telemt_user_msgs_to_client{user="hello"} 38699
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```