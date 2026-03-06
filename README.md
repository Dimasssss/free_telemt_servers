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

# Server Metrics 2026-03-06 00:01:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 6393.4 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56908
telemt_connections_bad_total 51892
telemt_handshake_timeouts_total 944
telemt_upstream_connect_attempt_total 4031
telemt_upstream_connect_success_total 4031
telemt_upstream_connect_attempts_per_request{bucket="1"} 4031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4029
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 63645663 (60.70 MB)
telemt_user_octets_to_client{user="hello"} 6955017567 (6.48 GB)
telemt_user_msgs_from_client{user="hello"} 136130
telemt_user_msgs_to_client{user="hello"} 986499
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 6391.3 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 444
telemt_upstream_connect_success_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 442
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 2238746 (2.14 MB)
telemt_user_octets_to_client{user="hello"} 113035736 (107.80 MB)
telemt_user_msgs_from_client{user="hello"} 6343
telemt_user_msgs_to_client{user="hello"} 41415
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 6391.8 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441
telemt_connections_bad_total 91
telemt_upstream_connect_attempt_total 351
telemt_upstream_connect_success_total 351
telemt_upstream_connect_attempts_per_request{bucket="1"} 351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 349
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 1245375 (1.19 MB)
telemt_user_octets_to_client{user="hello"} 56294362 (53.69 MB)
telemt_user_msgs_from_client{user="hello"} 3221
telemt_user_msgs_to_client{user="hello"} 17101
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 6394.5 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 783
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 680
telemt_upstream_connect_success_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 678
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 21115465 (20.14 MB)
telemt_user_octets_to_client{user="hello"} 3486208927 (3.25 GB)
telemt_user_msgs_from_client{user="hello"} 60862
telemt_user_msgs_to_client{user="hello"} 609531
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 6394.2 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2071
telemt_connections_bad_total 1204
telemt_upstream_connect_attempt_total 852
telemt_upstream_connect_success_total 852
telemt_upstream_connect_attempts_per_request{bucket="1"} 852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 850
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 29461686 (28.10 MB)
telemt_user_octets_to_client{user="hello"} 7875253889 (7.33 GB)
telemt_user_msgs_from_client{user="hello"} 80818
telemt_user_msgs_to_client{user="hello"} 1376243
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```