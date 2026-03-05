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

# Server Metrics 2026-03-05 23:41:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 5162.3 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56123
telemt_connections_bad_total 51892
telemt_handshake_timeouts_total 938
telemt_upstream_connect_attempt_total 3258
telemt_upstream_connect_success_total 3258
telemt_upstream_connect_attempts_per_request{bucket="1"} 3258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3256
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 47633856 (45.43 MB)
telemt_user_octets_to_client{user="hello"} 5883024190 (5.48 GB)
telemt_user_msgs_from_client{user="hello"} 110380
telemt_user_msgs_to_client{user="hello"} 831108
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 5160.1 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400
telemt_connections_bad_total 16
telemt_upstream_connect_attempt_total 385
telemt_upstream_connect_success_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 383
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 2042513 (1.95 MB)
telemt_user_octets_to_client{user="hello"} 97885007 (93.35 MB)
telemt_user_msgs_from_client{user="hello"} 5652
telemt_user_msgs_to_client{user="hello"} 37187
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 5160.6 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325
telemt_connections_bad_total 37
telemt_upstream_connect_attempt_total 290
telemt_upstream_connect_success_total 290
telemt_upstream_connect_attempts_per_request{bucket="1"} 290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 288
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 1033585 (1009.36 KB)
telemt_user_octets_to_client{user="hello"} 48320787 (46.08 MB)
telemt_user_msgs_from_client{user="hello"} 2669
telemt_user_msgs_to_client{user="hello"} 14159
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 5163.3 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 573
telemt_upstream_connect_success_total 573
telemt_upstream_connect_attempts_per_request{bucket="1"} 573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 571
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 16791960 (16.01 MB)
telemt_user_octets_to_client{user="hello"} 2643102806 (2.46 GB)
telemt_user_msgs_from_client{user="hello"} 48171
telemt_user_msgs_to_client{user="hello"} 469552
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 5163.0 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1673
telemt_connections_bad_total 931
telemt_upstream_connect_attempt_total 728
telemt_upstream_connect_success_total 728
telemt_upstream_connect_attempts_per_request{bucket="1"} 728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 726
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 28778067 (27.44 MB)
telemt_user_octets_to_client{user="hello"} 7848993943 (7.31 GB)
telemt_user_msgs_from_client{user="hello"} 78979
telemt_user_msgs_to_client{user="hello"} 1369464
telemt_user_unique_ips_current{user="hello"} 3
```