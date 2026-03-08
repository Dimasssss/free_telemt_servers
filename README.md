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

# Server Metrics 2026-03-08 10:38:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 12563.5 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25817
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 22063
telemt_upstream_connect_success_total 22048
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 22063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22046
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 821575848 (783.52 MB)
telemt_user_octets_to_client{user="hello"} 13448160019 (12.52 GB)
telemt_user_msgs_from_client{user="hello"} 652314
telemt_user_msgs_to_client{user="hello"} 747964
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 12562.6 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6384
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 6051
telemt_upstream_connect_success_total 6051
telemt_upstream_connect_attempts_per_request{bucket="1"} 6051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6049
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 87822233 (83.75 MB)
telemt_user_octets_to_client{user="hello"} 4129916462 (3.85 GB)
telemt_user_msgs_from_client{user="hello"} 158904
telemt_user_msgs_to_client{user="hello"} 1085938
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 12562.5 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4523
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 4417
telemt_upstream_connect_success_total 4417
telemt_upstream_connect_attempts_per_request{bucket="1"} 4417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4415
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 38117528 (36.35 MB)
telemt_user_octets_to_client{user="hello"} 1316368440 (1.23 GB)
telemt_user_msgs_from_client{user="hello"} 48534
telemt_user_msgs_to_client{user="hello"} 222321
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 12562.3 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5977
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 5707
telemt_upstream_connect_success_total 5697
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 5707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5695
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 571927584 (545.43 MB)
telemt_user_octets_to_client{user="hello"} 2547831185 (2.37 GB)
telemt_user_msgs_from_client{user="hello"} 251674
telemt_user_msgs_to_client{user="hello"} 546736
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 12562.6 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7620
telemt_connections_bad_total 2349
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 5181
telemt_upstream_connect_success_total 5181
telemt_upstream_connect_attempts_per_request{bucket="1"} 5181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5179
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 63350027 (60.42 MB)
telemt_user_octets_to_client{user="hello"} 4057003680 (3.78 GB)
telemt_user_msgs_from_client{user="hello"} 124076
telemt_user_msgs_to_client{user="hello"} 561860
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```