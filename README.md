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

# Server Metrics 2026-03-08 10:58:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 13796.0 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28287
telemt_connections_bad_total 2559
telemt_handshake_timeouts_total 187
telemt_upstream_connect_attempt_total 24447
telemt_upstream_connect_success_total 24432
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 24447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24430
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 876877359 (836.26 MB)
telemt_user_octets_to_client{user="hello"} 14345315833 (13.36 GB)
telemt_user_msgs_from_client{user="hello"} 701676
telemt_user_msgs_to_client{user="hello"} 808053
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 13795.1 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7199
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 6850
telemt_upstream_connect_success_total 6850
telemt_upstream_connect_attempts_per_request{bucket="1"} 6850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6848
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 101379487 (96.68 MB)
telemt_user_octets_to_client{user="hello"} 4521690672 (4.21 GB)
telemt_user_msgs_from_client{user="hello"} 179113
telemt_user_msgs_to_client{user="hello"} 1184586
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 13794.7 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4780
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 4671
telemt_upstream_connect_success_total 4671
telemt_upstream_connect_attempts_per_request{bucket="1"} 4671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4669
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 108537031 (103.51 MB)
telemt_user_octets_to_client{user="hello"} 1337992953 (1.25 GB)
telemt_user_msgs_from_client{user="hello"} 74786
telemt_user_msgs_to_client{user="hello"} 228686
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 13794.6 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6456
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 6164
telemt_upstream_connect_success_total 6154
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 6164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6152
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 876450131 (835.85 MB)
telemt_user_octets_to_client{user="hello"} 2618909504 (2.44 GB)
telemt_user_msgs_from_client{user="hello"} 362546
telemt_user_msgs_to_client{user="hello"} 567124
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 13795.0 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8487
telemt_connections_bad_total 2573
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 5788
telemt_upstream_connect_success_total 5787
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5785
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 83657699 (79.78 MB)
telemt_user_octets_to_client{user="hello"} 4175856924 (3.89 GB)
telemt_user_msgs_from_client{user="hello"} 135852
telemt_user_msgs_to_client{user="hello"} 586240
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```