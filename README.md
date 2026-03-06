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

# Server Metrics 2026-03-06 16:06:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 20679.4 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48704
telemt_connections_bad_total 3100
telemt_handshake_timeouts_total 187
telemt_upstream_connect_attempt_total 41892
telemt_upstream_connect_success_total 41880
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 41892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41878
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 2315867144 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 26986727187 (25.13 GB)
telemt_user_msgs_from_client{user="hello"} 1519116
telemt_user_msgs_to_client{user="hello"} 4269706
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 20678.7 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9232
telemt_connections_bad_total 169
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 8743
telemt_upstream_connect_success_total 8725
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 8743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 514
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8723
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 95425956 (91.01 MB)
telemt_user_octets_to_client{user="hello"} 4988674987 (4.65 GB)
telemt_user_msgs_from_client{user="hello"} 177040
telemt_user_msgs_to_client{user="hello"} 1562292
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 20678.0 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7636
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 7351
telemt_upstream_connect_success_total 7349
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7347
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 110820861 (105.69 MB)
telemt_user_octets_to_client{user="hello"} 4557486605 (4.24 GB)
telemt_user_msgs_from_client{user="hello"} 167555
telemt_user_msgs_to_client{user="hello"} 1074456
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 20677.2 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10793
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 10022
telemt_upstream_connect_success_total 9987
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 10022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9985
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 145063563 (138.34 MB)
telemt_user_octets_to_client{user="hello"} 3368421957 (3.14 GB)
telemt_user_msgs_from_client{user="hello"} 178056
telemt_user_msgs_to_client{user="hello"} 872314
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 20678.6 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15245
telemt_connections_bad_total 5275
telemt_handshake_timeouts_total 551
telemt_upstream_connect_attempt_total 9148
telemt_upstream_connect_success_total 9148
telemt_upstream_connect_attempts_per_request{bucket="1"} 9148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9146
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 226983318 (216.47 MB)
telemt_user_octets_to_client{user="hello"} 20892158397 (19.46 GB)
telemt_user_msgs_from_client{user="hello"} 372250
telemt_user_msgs_to_client{user="hello"} 3755333
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```