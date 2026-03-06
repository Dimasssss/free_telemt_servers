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

# Server Metrics 2026-03-06 18:45:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 2265.3 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3823
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 64
telemt_upstream_connect_attempt_total 3505
telemt_upstream_connect_success_total 3502
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3500
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 522588442 (498.38 MB)
telemt_user_octets_to_client{user="hello"} 7464703021 (6.95 GB)
telemt_user_msgs_from_client{user="hello"} 299006
telemt_user_msgs_to_client{user="hello"} 1188816
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 2264.0 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1075
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 1060
telemt_upstream_connect_success_total 1060
telemt_upstream_connect_attempts_per_request{bucket="1"} 1060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1058
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 11587546 (11.05 MB)
telemt_user_octets_to_client{user="hello"} 863262516 (823.27 MB)
telemt_user_msgs_from_client{user="hello"} 25707
telemt_user_msgs_to_client{user="hello"} 239786
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 2263.9 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 664
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 662
telemt_upstream_connect_success_total 662
telemt_upstream_connect_attempts_per_request{bucket="1"} 662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 660
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 10568372 (10.08 MB)
telemt_user_octets_to_client{user="hello"} 481900859 (459.58 MB)
telemt_user_msgs_from_client{user="hello"} 15287
telemt_user_msgs_to_client{user="hello"} 109200
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 2264.0 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 653
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 627
telemt_upstream_connect_success_total 625
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 623
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 22779694 (21.72 MB)
telemt_user_octets_to_client{user="hello"} 385718930 (367.85 MB)
telemt_user_msgs_from_client{user="hello"} 19154
telemt_user_msgs_to_client{user="hello"} 91936
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 2264.5 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1969
telemt_connections_bad_total 415
telemt_upstream_connect_attempt_total 1539
telemt_upstream_connect_success_total 1539
telemt_upstream_connect_attempts_per_request{bucket="1"} 1539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1537
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 17709270 (16.89 MB)
telemt_user_octets_to_client{user="hello"} 1241809951 (1.16 GB)
telemt_user_msgs_from_client{user="hello"} 36934
telemt_user_msgs_to_client{user="hello"} 255868
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 7
```