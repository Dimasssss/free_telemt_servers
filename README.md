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

# Server Metrics 2026-03-10 01:26:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 93969.8 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173113
telemt_connections_bad_total 2331
telemt_handshake_timeouts_total 1728
telemt_upstream_connect_attempt_total 162274
telemt_upstream_connect_success_total 162223
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 162274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 149311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 162213
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 4889854192 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 99617268591 (92.78 GB)
telemt_user_msgs_from_client{user="hello"} 4385539
telemt_user_msgs_to_client{user="hello"} 6350350
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 93968.5 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53636
telemt_connections_bad_total 3056
telemt_handshake_timeouts_total 795
telemt_upstream_connect_attempt_total 47028
telemt_upstream_connect_success_total 46987
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 47028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46977
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 2129102156 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 23160234487 (21.57 GB)
telemt_user_msgs_from_client{user="hello"} 1525411
telemt_user_msgs_to_client{user="hello"} 6645490
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 93969.0 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64474
telemt_connections_bad_total 839
telemt_handshake_timeouts_total 3725
telemt_upstream_connect_attempt_total 50921
telemt_upstream_connect_success_total 50919
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 50921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50909
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 6010308828 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 54136899170 (50.42 GB)
telemt_user_msgs_from_client{user="hello"} 3266789
telemt_user_msgs_to_client{user="hello"} 7831667
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 93963.8 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71109
telemt_connections_bad_total 367
telemt_handshake_timeouts_total 1039
telemt_upstream_connect_attempt_total 65705
telemt_upstream_connect_success_total 65545
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 65705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65535
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 2282007247 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 46293279437 (43.11 GB)
telemt_user_msgs_from_client{user="hello"} 1838945
telemt_user_msgs_to_client{user="hello"} 11161541
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 93969.3 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118156
telemt_connections_bad_total 21105
telemt_handshake_timeouts_total 3003
telemt_upstream_connect_attempt_total 89031
telemt_upstream_connect_success_total 89020
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 89031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89010
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 1541785160 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 83231440672 (77.52 GB)
telemt_user_msgs_from_client{user="hello"} 2045983
telemt_user_msgs_to_client{user="hello"} 10788479
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```