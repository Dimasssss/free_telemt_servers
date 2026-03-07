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

# Server Metrics 2026-03-07 08:22:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 4445.8 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6172
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 5954
telemt_upstream_connect_success_total 5954
telemt_upstream_connect_attempts_per_request{bucket="1"} 5954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5952
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 270384924 (257.86 MB)
telemt_user_octets_to_client{user="hello"} 6301816654 (5.87 GB)
telemt_user_msgs_from_client{user="hello"} 218428
telemt_user_msgs_to_client{user="hello"} 1112440
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 4444.8 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1718
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1626
telemt_upstream_connect_success_total 1625
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1623
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 72447505 (69.09 MB)
telemt_user_octets_to_client{user="hello"} 805080579 (767.78 MB)
telemt_user_msgs_from_client{user="hello"} 49784
telemt_user_msgs_to_client{user="hello"} 231092
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 4444.4 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1296
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1266
telemt_upstream_connect_success_total 1266
telemt_upstream_connect_attempts_per_request{bucket="1"} 1266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1264
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 32062619 (30.58 MB)
telemt_user_octets_to_client{user="hello"} 354140047 (337.73 MB)
telemt_user_msgs_from_client{user="hello"} 24688
telemt_user_msgs_to_client{user="hello"} 90361
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 4444.4 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1510
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1464
telemt_upstream_connect_success_total 1461
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 75
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1459
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 10834955 (10.33 MB)
telemt_user_octets_to_client{user="hello"} 533499347 (508.78 MB)
telemt_user_msgs_from_client{user="hello"} 24429
telemt_user_msgs_to_client{user="hello"} 137916
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 4444.8 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3321
telemt_connections_bad_total 843
telemt_handshake_timeouts_total 249
telemt_upstream_connect_attempt_total 2137
telemt_upstream_connect_success_total 2136
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2134
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 42216604 (40.26 MB)
telemt_user_octets_to_client{user="hello"} 9568215021 (8.91 GB)
telemt_user_msgs_from_client{user="hello"} 63408
telemt_user_msgs_to_client{user="hello"} 1685205
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```