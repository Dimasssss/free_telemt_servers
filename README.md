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

# Server Metrics 2026-03-07 07:30:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 1366.5 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1733
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1659
telemt_upstream_connect_success_total 1659
telemt_upstream_connect_attempts_per_request{bucket="1"} 1659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 58
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1657
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 27554348 (26.28 MB)
telemt_user_octets_to_client{user="hello"} 2797246730 (2.61 GB)
telemt_user_msgs_from_client{user="hello"} 47263
telemt_user_msgs_to_client{user="hello"} 554035
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 1365.8 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427
telemt_connections_bad_total 4
telemt_upstream_connect_attempt_total 414
telemt_upstream_connect_success_total 413
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 411
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 1865145 (1.78 MB)
telemt_user_octets_to_client{user="hello"} 92882379 (88.58 MB)
telemt_user_msgs_from_client{user="hello"} 5203
telemt_user_msgs_to_client{user="hello"} 33266
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 1365.5 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 394
telemt_upstream_connect_success_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 392
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 9754125 (9.30 MB)
telemt_user_octets_to_client{user="hello"} 123974008 (118.23 MB)
telemt_user_msgs_from_client{user="hello"} 6671
telemt_user_msgs_to_client{user="hello"} 30696
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 1365.3 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 576
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 553
telemt_upstream_connect_success_total 552
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 550
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 5039968 (4.81 MB)
telemt_user_octets_to_client{user="hello"} 134922487 (128.67 MB)
telemt_user_msgs_from_client{user="hello"} 8761
telemt_user_msgs_to_client{user="hello"} 38334
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 1365.9 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1003
telemt_connections_bad_total 246
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 683
telemt_upstream_connect_success_total 683
telemt_upstream_connect_attempts_per_request{bucket="1"} 683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 128
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 681
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 5078094 (4.84 MB)
telemt_user_octets_to_client{user="hello"} 1177931191 (1.10 GB)
telemt_user_msgs_from_client{user="hello"} 12387
telemt_user_msgs_to_client{user="hello"} 217108
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 6
```