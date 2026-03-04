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

# Server Metrics 2026-03-04 08:48:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 1548.2 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2768
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 2401
telemt_upstream_connect_success_total 2401
telemt_upstream_connect_attempts_per_request{bucket="1"} 2401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2399
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 33872023 (32.30 MB)
telemt_user_octets_to_client{user="hello"} 1548329290 (1.44 GB)
telemt_user_msgs_from_client{user="hello"} 52653
telemt_user_msgs_to_client{user="hello"} 264796
telemt_user_unique_ips_current{user="hello"} 12
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 1559.5 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 161
telemt_upstream_connect_success_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 159
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 976210 (953.33 KB)
telemt_user_octets_to_client{user="hello"} 7994772 (7.62 MB)
telemt_user_msgs_from_client{user="hello"} 2785
telemt_user_msgs_to_client{user="hello"} 7879
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 1544.1 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224
telemt_connections_bad_total 55
telemt_upstream_connect_attempt_total 168
telemt_upstream_connect_success_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 166
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 867500 (847.17 KB)
telemt_user_octets_to_client{user="hello"} 51348000 (48.97 MB)
telemt_user_msgs_from_client{user="hello"} 2085
telemt_user_msgs_to_client{user="hello"} 11458
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 1534.6 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 420
telemt_upstream_connect_success_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 418
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1535784 (1.46 MB)
telemt_user_octets_to_client{user="hello"} 44797487 (42.72 MB)
telemt_user_msgs_from_client{user="hello"} 3564
telemt_user_msgs_to_client{user="hello"} 16681
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 1546.0 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 777
telemt_connections_bad_total 278
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 452
telemt_upstream_connect_success_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 450
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 5347850 (5.10 MB)
telemt_user_octets_to_client{user="hello"} 204285324 (194.82 MB)
telemt_user_msgs_from_client{user="hello"} 12657
telemt_user_msgs_to_client{user="hello"} 55318
```