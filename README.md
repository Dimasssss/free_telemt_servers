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

# Server Metrics 2026-03-06 20:02:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 6887.0 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12228
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 367
telemt_upstream_connect_attempt_total 11061
telemt_upstream_connect_success_total 11057
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11055
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 964349992 (919.68 MB)
telemt_user_octets_to_client{user="hello"} 13747380228 (12.80 GB)
telemt_user_msgs_from_client{user="hello"} 621460
telemt_user_msgs_to_client{user="hello"} 2215771
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 6885.3 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3105
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 2913
telemt_upstream_connect_success_total 2910
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2908
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 66055260 (63.00 MB)
telemt_user_octets_to_client{user="hello"} 2164170717 (2.02 GB)
telemt_user_msgs_from_client{user="hello"} 74776
telemt_user_msgs_to_client{user="hello"} 608743
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 6885.3 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1782
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 1642
telemt_upstream_connect_success_total 1642
telemt_upstream_connect_attempts_per_request{bucket="1"} 1642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1640
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 17244696 (16.45 MB)
telemt_user_octets_to_client{user="hello"} 671117897 (640.03 MB)
telemt_user_msgs_from_client{user="hello"} 27530
telemt_user_msgs_to_client{user="hello"} 159675
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 6885.4 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1578
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1532
telemt_upstream_connect_success_total 1528
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1526
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 72454278 (69.10 MB)
telemt_user_octets_to_client{user="hello"} 549774734 (524.31 MB)
telemt_user_msgs_from_client{user="hello"} 47078
telemt_user_msgs_to_client{user="hello"} 146868
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 6885.7 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5287
telemt_connections_bad_total 1263
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3981
telemt_upstream_connect_success_total 3981
telemt_upstream_connect_attempts_per_request{bucket="1"} 3981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3979
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 139674649 (133.20 MB)
telemt_user_octets_to_client{user="hello"} 2423563280 (2.26 GB)
telemt_user_msgs_from_client{user="hello"} 115381
telemt_user_msgs_to_client{user="hello"} 552013
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 8
```