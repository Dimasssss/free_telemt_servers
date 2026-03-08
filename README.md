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

# Server Metrics 2026-03-08 09:05:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 7012.7 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15427
telemt_connections_bad_total 2400
telemt_handshake_timeouts_total 64
telemt_upstream_connect_attempt_total 12380
telemt_upstream_connect_success_total 12372
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 12380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12370
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 347367662 (331.28 MB)
telemt_user_octets_to_client{user="hello"} 7439786599 (6.93 GB)
telemt_user_msgs_from_client{user="hello"} 303137
telemt_user_msgs_to_client{user="hello"} 385273
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 7012.1 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3219
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 3056
telemt_upstream_connect_success_total 3056
telemt_upstream_connect_attempts_per_request{bucket="1"} 3056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3054
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 39578388 (37.74 MB)
telemt_user_octets_to_client{user="hello"} 2193427706 (2.04 GB)
telemt_user_msgs_from_client{user="hello"} 74472
telemt_user_msgs_to_client{user="hello"} 548667
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 7011.4 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2835
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2761
telemt_upstream_connect_success_total 2761
telemt_upstream_connect_attempts_per_request{bucket="1"} 2761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2759
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 27197023 (25.94 MB)
telemt_user_octets_to_client{user="hello"} 492400399 (469.59 MB)
telemt_user_msgs_from_client{user="hello"} 24161
telemt_user_msgs_to_client{user="hello"} 96936
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 7011.2 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2539
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2435
telemt_upstream_connect_success_total 2431
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 2435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2429
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 52253571 (49.83 MB)
telemt_user_octets_to_client{user="hello"} 765222153 (729.77 MB)
telemt_user_msgs_from_client{user="hello"} 41932
telemt_user_msgs_to_client{user="hello"} 201494
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 7011.6 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4380
telemt_connections_bad_total 1313
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 3033
telemt_upstream_connect_success_total 3033
telemt_upstream_connect_attempts_per_request{bucket="1"} 3033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3031
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 40855920 (38.96 MB)
telemt_user_octets_to_client{user="hello"} 2945364242 (2.74 GB)
telemt_user_msgs_from_client{user="hello"} 70139
telemt_user_msgs_to_client{user="hello"} 322667
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```