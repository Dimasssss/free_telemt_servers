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

# Server Metrics 2026-03-05 22:24:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 545.4 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9080
telemt_connections_bad_total 8355
telemt_handshake_timeouts_total 284
telemt_upstream_connect_attempt_total 415
telemt_upstream_connect_success_total 415
telemt_upstream_connect_attempts_per_request{bucket="1"} 415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 413
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 3963961 (3.78 MB)
telemt_user_octets_to_client{user="hello"} 255852391 (244.00 MB)
telemt_user_msgs_from_client{user="hello"} 10251
telemt_user_msgs_to_client{user="hello"} 43588
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 542.9 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 99
telemt_upstream_connect_success_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 99
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 696146 (679.83 KB)
telemt_user_octets_to_client{user="hello"} 61264443 (58.43 MB)
telemt_user_msgs_from_client{user="hello"} 1744
telemt_user_msgs_to_client{user="hello"} 15592
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 543.2 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39
telemt_upstream_connect_attempt_total 41
telemt_upstream_connect_success_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 93940 (91.74 KB)
telemt_user_octets_to_client{user="hello"} 2557614 (2.44 MB)
telemt_user_msgs_from_client{user="hello"} 250
telemt_user_msgs_to_client{user="hello"} 874
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 545.9 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119
telemt_upstream_connect_attempt_total 118
telemt_upstream_connect_success_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 1852440 (1.77 MB)
telemt_user_octets_to_client{user="hello"} 198612798 (189.41 MB)
telemt_user_msgs_from_client{user="hello"} 5355
telemt_user_msgs_to_client{user="hello"} 42540
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 545.7 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189
telemt_connections_bad_total 108
telemt_upstream_connect_attempt_total 83
telemt_upstream_connect_success_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 4157008 (3.96 MB)
telemt_user_octets_to_client{user="hello"} 971418384 (926.42 MB)
telemt_user_msgs_from_client{user="hello"} 11544
telemt_user_msgs_to_client{user="hello"} 184589
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```