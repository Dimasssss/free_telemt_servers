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

# Server Metrics 2026-03-06 10:38:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 969.2 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1709
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1650
telemt_upstream_connect_success_total 1650
telemt_upstream_connect_attempts_per_request{bucket="1"} 1650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1648
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 47923093 (45.70 MB)
telemt_user_octets_to_client{user="hello"} 1048372117 (999.81 MB)
telemt_user_msgs_from_client{user="hello"} 51344
telemt_user_msgs_to_client{user="hello"} 177450
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 968.4 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 257
telemt_upstream_connect_success_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 255
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 2142160 (2.04 MB)
telemt_user_octets_to_client{user="hello"} 42206943 (40.25 MB)
telemt_user_msgs_from_client{user="hello"} 4784
telemt_user_msgs_to_client{user="hello"} 18223
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 968.3 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 310
telemt_upstream_connect_success_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 308
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 10713823 (10.22 MB)
telemt_user_octets_to_client{user="hello"} 106233735 (101.31 MB)
telemt_user_msgs_from_client{user="hello"} 9587
telemt_user_msgs_to_client{user="hello"} 24637
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 967.0 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 477
telemt_upstream_connect_success_total 472
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 470
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 2248398 (2.14 MB)
telemt_user_octets_to_client{user="hello"} 53313774 (50.84 MB)
telemt_user_msgs_from_client{user="hello"} 4465
telemt_user_msgs_to_client{user="hello"} 17986
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 968.3 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 633
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 409
telemt_upstream_connect_success_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 407
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 9680701 (9.23 MB)
telemt_user_octets_to_client{user="hello"} 151811354 (144.78 MB)
telemt_user_msgs_from_client{user="hello"} 7143
telemt_user_msgs_to_client{user="hello"} 31179
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```