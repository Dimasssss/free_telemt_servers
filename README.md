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

# Server Metrics 2026-03-10 13:17:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 136666.5 (37h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308836
telemt_connections_bad_total 3472
telemt_handshake_timeouts_total 3156
telemt_upstream_connect_attempt_total 289337
telemt_upstream_connect_success_total 289180
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 289337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 267450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 289166
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 6736777651 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 191601079347 (178.44 GB)
telemt_user_msgs_from_client{user="hello"} 6968930
telemt_user_msgs_to_client{user="hello"} 11342266
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 136665.3 (37h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95318
telemt_connections_bad_total 3272
telemt_handshake_timeouts_total 1282
telemt_upstream_connect_attempt_total 85868
telemt_upstream_connect_success_total 85824
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 85868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8201
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 427
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85810
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 2807120238 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 36487784527 (33.98 GB)
telemt_user_msgs_from_client{user="hello"} 2269378
telemt_user_msgs_to_client{user="hello"} 10552103
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 136665.8 (37h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135358
telemt_connections_bad_total 1228
telemt_handshake_timeouts_total 6411
telemt_upstream_connect_attempt_total 100806
telemt_upstream_connect_success_total 100803
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 100806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100789
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 6649570495 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 68193050309 (63.51 GB)
telemt_user_msgs_from_client{user="hello"} 4475978
telemt_user_msgs_to_client{user="hello"} 11442184
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 136660.6 (37h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140416
telemt_connections_bad_total 1059
telemt_handshake_timeouts_total 2930
telemt_upstream_connect_attempt_total 129651
telemt_upstream_connect_success_total 129361
telemt_upstream_connect_fail_total 290
telemt_upstream_connect_attempts_per_request{bucket="1"} 129651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 327
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 290
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 129347
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 4792811571 (4.46 GB)
telemt_user_octets_to_client{user="hello"} 89475362200 (83.33 GB)
telemt_user_msgs_from_client{user="hello"} 3716223
telemt_user_msgs_to_client{user="hello"} 20325512
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 136665.9 (37h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206939
telemt_connections_bad_total 30517
telemt_handshake_timeouts_total 5587
telemt_upstream_connect_attempt_total 162128
telemt_upstream_connect_success_total 161166
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 162128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 139528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 161152
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 3484159772 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 117348846594 (109.29 GB)
telemt_user_msgs_from_client{user="hello"} 3705478
telemt_user_msgs_to_client{user="hello"} 16019078
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 31
```