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

# Server Metrics 2026-03-08 15:26:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 29846.8 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73190
telemt_connections_bad_total 5024
telemt_handshake_timeouts_total 1051
telemt_upstream_connect_attempt_total 64505
telemt_upstream_connect_success_total 64482
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 64505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64478
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1692640452 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 33697919766 (31.38 GB)
telemt_user_msgs_from_client{user="hello"} 1521707
telemt_user_msgs_to_client{user="hello"} 2025526
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 29845.8 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15536
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 15001
telemt_upstream_connect_success_total 15000
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14996
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 566649730 (540.40 MB)
telemt_user_octets_to_client{user="hello"} 12923766435 (12.04 GB)
telemt_user_msgs_from_client{user="hello"} 574738
telemt_user_msgs_to_client{user="hello"} 3399155
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 29845.6 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9969
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9341
telemt_upstream_connect_success_total 9265
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9261
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 216487910 (206.46 MB)
telemt_user_octets_to_client{user="hello"} 3182864136 (2.96 GB)
telemt_user_msgs_from_client{user="hello"} 159200
telemt_user_msgs_to_client{user="hello"} 545715
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 29845.5 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12851
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 12246
telemt_upstream_connect_success_total 12218
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 12246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12214
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 947481978 (903.59 MB)
telemt_user_octets_to_client{user="hello"} 4592058871 (4.28 GB)
telemt_user_msgs_from_client{user="hello"} 466732
telemt_user_msgs_to_client{user="hello"} 1034649
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 29845.8 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16960
telemt_connections_bad_total 5493
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 11101
telemt_upstream_connect_success_total 11097
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11093
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 232832168 (222.05 MB)
telemt_user_octets_to_client{user="hello"} 8406724295 (7.83 GB)
telemt_user_msgs_from_client{user="hello"} 281441
telemt_user_msgs_to_client{user="hello"} 1178424
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```