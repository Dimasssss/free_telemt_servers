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

# Server Metrics 2026-03-04 08:54:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 1855.9 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3377
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 77
telemt_upstream_connect_attempt_total 2760
telemt_upstream_connect_success_total 2760
telemt_upstream_connect_attempts_per_request{bucket="1"} 2760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2758
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 36425586 (34.74 MB)
telemt_user_octets_to_client{user="hello"} 1617714361 (1.51 GB)
telemt_user_msgs_from_client{user="hello"} 57443
telemt_user_msgs_to_client{user="hello"} 278233
telemt_user_unique_ips_current{user="hello"} 11
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 1867.2 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211
telemt_connections_bad_total 4
telemt_upstream_connect_attempt_total 206
telemt_upstream_connect_success_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 204
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 2281517 (2.18 MB)
telemt_user_octets_to_client{user="hello"} 12845373 (12.25 MB)
telemt_user_msgs_from_client{user="hello"} 3792
telemt_user_msgs_to_client{user="hello"} 10608
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 1851.8 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250
telemt_connections_bad_total 55
telemt_upstream_connect_attempt_total 191
telemt_upstream_connect_success_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 189
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 1097041 (1.05 MB)
telemt_user_octets_to_client{user="hello"} 56667052 (54.04 MB)
telemt_user_msgs_from_client{user="hello"} 2628
telemt_user_msgs_to_client{user="hello"} 13453
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 1842.4 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 501
telemt_upstream_connect_success_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 499
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 1767658 (1.69 MB)
telemt_user_octets_to_client{user="hello"} 50571906 (48.23 MB)
telemt_user_msgs_from_client{user="hello"} 3989
telemt_user_msgs_to_client{user="hello"} 18602
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 1853.8 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 860
telemt_connections_bad_total 330
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 482
telemt_upstream_connect_success_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 480
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 5879866 (5.61 MB)
telemt_user_octets_to_client{user="hello"} 214838920 (204.89 MB)
telemt_user_msgs_from_client{user="hello"} 13633
telemt_user_msgs_to_client{user="hello"} 58978
telemt_user_unique_ips_current{user="hello"} 2
```