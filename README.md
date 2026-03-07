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

# Server Metrics 2026-03-07 00:55:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 24437.3 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31918
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 487
telemt_upstream_connect_attempt_total 29757
telemt_upstream_connect_success_total 29750
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 29757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29746
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 2073995178 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 32958592025 (30.70 GB)
telemt_user_msgs_from_client{user="hello"} 1367654
telemt_user_msgs_to_client{user="hello"} 5187661
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 24436.1 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6693
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 6264
telemt_upstream_connect_success_total 6261
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6257
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 215245444 (205.27 MB)
telemt_user_octets_to_client{user="hello"} 3894394538 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 201722
telemt_user_msgs_to_client{user="hello"} 1088808
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 24436.1 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3146
telemt_connections_bad_total 161
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2865
telemt_upstream_connect_success_total 2865
telemt_upstream_connect_attempts_per_request{bucket="1"} 2865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2861
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 65080976 (62.07 MB)
telemt_user_octets_to_client{user="hello"} 1861894377 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 64045
telemt_user_msgs_to_client{user="hello"} 392538
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 24436.1 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4322
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4167
telemt_upstream_connect_success_total 4160
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4156
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 100672615 (96.01 MB)
telemt_user_octets_to_client{user="hello"} 1361382621 (1.27 GB)
telemt_user_msgs_from_client{user="hello"} 85728
telemt_user_msgs_to_client{user="hello"} 349983
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 24436.6 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12087
telemt_connections_bad_total 5328
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6613
telemt_upstream_connect_success_total 6612
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6608
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 227629093 (217.08 MB)
telemt_user_octets_to_client{user="hello"} 7417688782 (6.91 GB)
telemt_user_msgs_from_client{user="hello"} 214189
telemt_user_msgs_to_client{user="hello"} 1525957
telemt_user_unique_ips_current{user="hello"} 1
telemt_user_unique_ips_recent_window{user="hello"} 1
```