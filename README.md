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

# Server Metrics 2026-03-08 07:58:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 3008.3 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5219
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 5042
telemt_upstream_connect_success_total 5039
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5037
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 78203444 (74.58 MB)
telemt_user_octets_to_client{user="hello"} 1831367228 (1.71 GB)
telemt_user_msgs_from_client{user="hello"} 106397
telemt_user_msgs_to_client{user="hello"} 131938
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 3007.5 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1195
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1151
telemt_upstream_connect_success_total 1151
telemt_upstream_connect_attempts_per_request{bucket="1"} 1151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 66
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1149
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 14233632 (13.57 MB)
telemt_user_octets_to_client{user="hello"} 660987785 (630.37 MB)
telemt_user_msgs_from_client{user="hello"} 24889
telemt_user_msgs_to_client{user="hello"} 155711
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 3007.1 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1158
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1133
telemt_upstream_connect_success_total 1133
telemt_upstream_connect_attempts_per_request{bucket="1"} 1133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1131
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 4527172 (4.32 MB)
telemt_user_octets_to_client{user="hello"} 326053320 (310.95 MB)
telemt_user_msgs_from_client{user="hello"} 9186
telemt_user_msgs_to_client{user="hello"} 49318
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 3007.2 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1184
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 1143
telemt_upstream_connect_success_total 1140
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1138
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 35801708 (34.14 MB)
telemt_user_octets_to_client{user="hello"} 299896626 (286.00 MB)
telemt_user_msgs_from_client{user="hello"} 18837
telemt_user_msgs_to_client{user="hello"} 83029
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 3007.3 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2089
telemt_connections_bad_total 538
telemt_upstream_connect_attempt_total 1536
telemt_upstream_connect_success_total 1536
telemt_upstream_connect_attempts_per_request{bucket="1"} 1536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1534
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 11489263 (10.96 MB)
telemt_user_octets_to_client{user="hello"} 315862227 (301.23 MB)
telemt_user_msgs_from_client{user="hello"} 19196
telemt_user_msgs_to_client{user="hello"} 63178
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```