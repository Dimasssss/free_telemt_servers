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

# Server Metrics 2026-03-07 00:09:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 21667.5 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30104
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 480
telemt_upstream_connect_attempt_total 28120
telemt_upstream_connect_success_total 28113
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 28120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28109
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 2058275336 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 31342893609 (29.19 GB)
telemt_user_msgs_from_client{user="hello"} 1326518
telemt_user_msgs_to_client{user="hello"} 4949415
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 21666.4 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6653
telemt_connections_bad_total 162
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 6238
telemt_upstream_connect_success_total 6235
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6231
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 215088989 (205.12 MB)
telemt_user_octets_to_client{user="hello"} 3893869958 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 201188
telemt_user_msgs_to_client{user="hello"} 1088188
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 21666.4 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3047
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2785
telemt_upstream_connect_success_total 2785
telemt_upstream_connect_attempts_per_request{bucket="1"} 2785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 222
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2783
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 64782706 (61.78 MB)
telemt_user_octets_to_client{user="hello"} 1854020580 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 63222
telemt_user_msgs_to_client{user="hello"} 390120
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 21666.4 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4154
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 4013
telemt_upstream_connect_success_total 4006
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 334
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4002
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 99770090 (95.15 MB)
telemt_user_octets_to_client{user="hello"} 1330981184 (1.24 GB)
telemt_user_msgs_from_client{user="hello"} 83484
telemt_user_msgs_to_client{user="hello"} 339944
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 21666.8 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11374
telemt_connections_bad_total 4830
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6403
telemt_upstream_connect_success_total 6402
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6400
telemt_user_octets_from_client{user="hello"} 226956365 (216.44 MB)
telemt_user_octets_to_client{user="hello"} 7337480112 (6.83 GB)
telemt_user_msgs_from_client{user="hello"} 212380
telemt_user_msgs_to_client{user="hello"} 1510258
```