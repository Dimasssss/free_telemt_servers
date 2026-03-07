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

# Server Metrics 2026-03-07 07:10:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 134.2 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 355
telemt_upstream_connect_success_total 355
telemt_upstream_connect_attempts_per_request{bucket="1"} 355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 353
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 2320734 (2.21 MB)
telemt_user_octets_to_client{user="hello"} 193773996 (184.80 MB)
telemt_user_msgs_from_client{user="hello"} 5365
telemt_user_msgs_to_client{user="hello"} 31813
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 132.9 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66
telemt_upstream_connect_attempt_total 68
telemt_upstream_connect_success_total 67
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 68
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 204073 (199.29 KB)
telemt_user_octets_to_client{user="hello"} 17492837 (16.68 MB)
telemt_user_msgs_from_client{user="hello"} 578
telemt_user_msgs_to_client{user="hello"} 5785
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 132.7 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50
telemt_upstream_connect_attempt_total 51
telemt_upstream_connect_success_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 249090 (243.25 KB)
telemt_user_octets_to_client{user="hello"} 15290745 (14.58 MB)
telemt_user_msgs_from_client{user="hello"} 594
telemt_user_msgs_to_client{user="hello"} 3897
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 132.5 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89
telemt_upstream_connect_attempt_total 90
telemt_upstream_connect_success_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 90
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 388277 (379.18 KB)
telemt_user_octets_to_client{user="hello"} 9604507 (9.16 MB)
telemt_user_msgs_from_client{user="hello"} 928
telemt_user_msgs_to_client{user="hello"} 2866
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 133.0 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129
telemt_connections_bad_total 23
telemt_upstream_connect_attempt_total 108
telemt_upstream_connect_success_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 1136066 (1.08 MB)
telemt_user_octets_to_client{user="hello"} 478638906 (456.47 MB)
telemt_user_msgs_from_client{user="hello"} 2543
telemt_user_msgs_to_client{user="hello"} 90327
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 6
```