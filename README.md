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

# Server Metrics 2026-03-09 04:59:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 20401.5 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18571
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 553
telemt_upstream_connect_attempt_total 16715
telemt_upstream_connect_success_total 16710
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16708
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 157884742 (150.57 MB)
telemt_user_octets_to_client{user="hello"} 9633650021 (8.97 GB)
telemt_user_msgs_from_client{user="hello"} 304179
telemt_user_msgs_to_client{user="hello"} 455770
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 20400.1 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2015
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 1853
telemt_upstream_connect_success_total 1853
telemt_upstream_connect_attempts_per_request{bucket="1"} 1853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1851
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 33349625 (31.80 MB)
telemt_user_octets_to_client{user="hello"} 1532499047 (1.43 GB)
telemt_user_msgs_from_client{user="hello"} 68747
telemt_user_msgs_to_client{user="hello"} 302678
telemt_user_unique_ips_current{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 20400.5 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1371
telemt_connections_bad_total 86
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1269
telemt_upstream_connect_success_total 1269
telemt_upstream_connect_attempts_per_request{bucket="1"} 1269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1267
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 463959012 (442.47 MB)
telemt_user_octets_to_client{user="hello"} 1017570999 (970.43 MB)
telemt_user_msgs_from_client{user="hello"} 188384
telemt_user_msgs_to_client{user="hello"} 196854
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 20395.3 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2648
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 2133
telemt_upstream_connect_success_total 2133
telemt_upstream_connect_attempts_per_request{bucket="1"} 2133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2131
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 17320861 (16.52 MB)
telemt_user_octets_to_client{user="hello"} 1377824863 (1.28 GB)
telemt_user_msgs_from_client{user="hello"} 44506
telemt_user_msgs_to_client{user="hello"} 337991
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 20400.8 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5700
telemt_connections_bad_total 3706
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1952
telemt_upstream_connect_success_total 1952
telemt_upstream_connect_attempts_per_request{bucket="1"} 1952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1950
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 14628587 (13.95 MB)
telemt_user_octets_to_client{user="hello"} 1736233857 (1.62 GB)
telemt_user_msgs_from_client{user="hello"} 37407
telemt_user_msgs_to_client{user="hello"} 219724
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```