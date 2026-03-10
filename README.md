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

# Server Metrics 2026-03-10 18:45:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15555.0 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61347
telemt_connections_bad_total 1833
telemt_handshake_timeouts_total 1496
telemt_upstream_connect_attempt_total 55047
telemt_upstream_connect_success_total 55035
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 55047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55033
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 1799216945 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 41476754235 (38.63 GB)
telemt_user_msgs_from_client{user="hello"} 1623192
telemt_user_msgs_to_client{user="hello"} 3126404
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 15554.5 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22827
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 373
telemt_upstream_connect_attempt_total 20902
telemt_upstream_connect_success_total 20895
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 20902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20893
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 661873189 (631.21 MB)
telemt_user_octets_to_client{user="hello"} 10924591776 (10.17 GB)
telemt_user_msgs_from_client{user="hello"} 628448
telemt_user_msgs_to_client{user="hello"} 3440275
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 15553.9 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35204
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 3018
telemt_upstream_connect_attempt_total 29865
telemt_upstream_connect_success_total 29865
telemt_upstream_connect_attempts_per_request{bucket="1"} 29865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29863
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 438164185 (417.87 MB)
telemt_user_octets_to_client{user="hello"} 31826160337 (29.64 GB)
telemt_user_msgs_from_client{user="hello"} 656934
telemt_user_msgs_to_client{user="hello"} 4667411
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 15553.0 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33584
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 269
telemt_upstream_connect_attempt_total 32114
telemt_upstream_connect_success_total 32020
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 32114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32018
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 480320994 (458.07 MB)
telemt_user_octets_to_client{user="hello"} 27193509289 (25.33 GB)
telemt_user_msgs_from_client{user="hello"} 649547
telemt_user_msgs_to_client{user="hello"} 4850524
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15554.2 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48495
telemt_connections_bad_total 4518
telemt_handshake_timeouts_total 1074
telemt_upstream_connect_attempt_total 41047
telemt_upstream_connect_success_total 40808
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 41046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40806
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 1409423869 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 26682409751 (24.85 GB)
telemt_user_msgs_from_client{user="hello"} 1168852
telemt_user_msgs_to_client{user="hello"} 4015419
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 26
```