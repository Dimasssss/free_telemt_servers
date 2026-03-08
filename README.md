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

# Server Metrics 2026-03-08 09:56:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 10093.0 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21044
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 132
telemt_upstream_connect_attempt_total 17540
telemt_upstream_connect_success_total 17526
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 17540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17524
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 588054855 (560.81 MB)
telemt_user_octets_to_client{user="hello"} 11033388007 (10.28 GB)
telemt_user_msgs_from_client{user="hello"} 495694
telemt_user_msgs_to_client{user="hello"} 588741
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 10092.6 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4674
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 4444
telemt_upstream_connect_success_total 4444
telemt_upstream_connect_attempts_per_request{bucket="1"} 4444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4442
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 57405932 (54.75 MB)
telemt_user_octets_to_client{user="hello"} 3139618656 (2.92 GB)
telemt_user_msgs_from_client{user="hello"} 111803
telemt_user_msgs_to_client{user="hello"} 824057
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 10092.1 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3835
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3752
telemt_upstream_connect_success_total 3752
telemt_upstream_connect_attempts_per_request{bucket="1"} 3752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3750
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 34871741 (33.26 MB)
telemt_user_octets_to_client{user="hello"} 1166899383 (1.09 GB)
telemt_user_msgs_from_client{user="hello"} 39282
telemt_user_msgs_to_client{user="hello"} 188364
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 10091.8 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4427
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 4233
telemt_upstream_connect_success_total 4226
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4224
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 147069656 (140.26 MB)
telemt_user_octets_to_client{user="hello"} 1730207837 (1.61 GB)
telemt_user_msgs_from_client{user="hello"} 83473
telemt_user_msgs_to_client{user="hello"} 403954
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 10092.1 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6074
telemt_connections_bad_total 1907
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 4107
telemt_upstream_connect_success_total 4107
telemt_upstream_connect_attempts_per_request{bucket="1"} 4107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4105
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 52152424 (49.74 MB)
telemt_user_octets_to_client{user="hello"} 3426218374 (3.19 GB)
telemt_user_msgs_from_client{user="hello"} 97086
telemt_user_msgs_to_client{user="hello"} 411810
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```