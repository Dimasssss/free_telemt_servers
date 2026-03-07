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

# Server Metrics 2026-03-07 20:00:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 11700.1 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20579
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 19780
telemt_upstream_connect_success_total 19777
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19775
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1767216656 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 14062565643 (13.10 GB)
telemt_user_msgs_from_client{user="hello"} 772629
telemt_user_msgs_to_client{user="hello"} 2132741
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 11699.1 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4608
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4427
telemt_upstream_connect_success_total 4425
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4423
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 72440440 (69.08 MB)
telemt_user_octets_to_client{user="hello"} 2833638703 (2.64 GB)
telemt_user_msgs_from_client{user="hello"} 114924
telemt_user_msgs_to_client{user="hello"} 812706
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 11698.8 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2296
telemt_connections_bad_total 90
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2180
telemt_upstream_connect_success_total 2180
telemt_upstream_connect_attempts_per_request{bucket="1"} 2180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 214
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2178
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 72512786 (69.15 MB)
telemt_user_octets_to_client{user="hello"} 2989612031 (2.78 GB)
telemt_user_msgs_from_client{user="hello"} 82158
telemt_user_msgs_to_client{user="hello"} 612961
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 11527.1 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4880
telemt_connections_bad_total 88
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4692
telemt_upstream_connect_success_total 4681
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 4692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4679
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 71589765 (68.27 MB)
telemt_user_octets_to_client{user="hello"} 4457180941 (4.15 GB)
telemt_user_msgs_from_client{user="hello"} 119617
telemt_user_msgs_to_client{user="hello"} 1367349
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 11699.0 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6728
telemt_connections_bad_total 2157
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 4456
telemt_upstream_connect_success_total 4449
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4447
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 1562912755 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 2698948965 (2.51 GB)
telemt_user_msgs_from_client{user="hello"} 654451
telemt_user_msgs_to_client{user="hello"} 647918
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```