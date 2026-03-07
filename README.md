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

# Server Metrics 2026-03-07 07:56:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 2905.7 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3558
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 3436
telemt_upstream_connect_success_total 3436
telemt_upstream_connect_attempts_per_request{bucket="1"} 3436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 133
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3434
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 78244764 (74.62 MB)
telemt_user_octets_to_client{user="hello"} 4048785559 (3.77 GB)
telemt_user_msgs_from_client{user="hello"} 95941
telemt_user_msgs_to_client{user="hello"} 745425
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 2905.4 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 920
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 857
telemt_upstream_connect_success_total 856
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 854
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 5478131 (5.22 MB)
telemt_user_octets_to_client{user="hello"} 330958327 (315.63 MB)
telemt_user_msgs_from_client{user="hello"} 12586
telemt_user_msgs_to_client{user="hello"} 87110
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 2905.1 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 850
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 829
telemt_upstream_connect_success_total 829
telemt_upstream_connect_attempts_per_request{bucket="1"} 829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 827
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 27321650 (26.06 MB)
telemt_user_octets_to_client{user="hello"} 207703804 (198.08 MB)
telemt_user_msgs_from_client{user="hello"} 18367
telemt_user_msgs_to_client{user="hello"} 57124
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 2904.9 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1072
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1033
telemt_upstream_connect_success_total 1032
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1030
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 7282570 (6.95 MB)
telemt_user_octets_to_client{user="hello"} 275539030 (262.77 MB)
telemt_user_msgs_from_client{user="hello"} 14564
telemt_user_msgs_to_client{user="hello"} 74697
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 2905.4 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2095
telemt_connections_bad_total 522
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 1476
telemt_upstream_connect_success_total 1474
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1472
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 23453504 (22.37 MB)
telemt_user_octets_to_client{user="hello"} 4096699133 (3.82 GB)
telemt_user_msgs_from_client{user="hello"} 36920
telemt_user_msgs_to_client{user="hello"} 706574
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```