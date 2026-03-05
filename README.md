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

# Server Metrics 2026-03-05 00:50:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 48201.6 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69242
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 1557
telemt_upstream_connect_attempt_total 62593
telemt_upstream_connect_success_total 62578
telemt_upstream_connect_attempts_per_request{bucket="1"} 62563
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62572
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 2351117783 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 48018415716 (44.72 GB)
telemt_user_msgs_from_client{user="hello"} 2024453
telemt_user_msgs_to_client{user="hello"} 7651680
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 48204.4 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15960
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 11453
telemt_upstream_connect_success_total 11451
telemt_upstream_connect_attempts_per_request{bucket="1"} 11449
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11445
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 1056547581 (1007.60 MB)
telemt_user_octets_to_client{user="hello"} 11093709196 (10.33 GB)
telemt_user_msgs_from_client{user="hello"} 650378
telemt_user_msgs_to_client{user="hello"} 3737923
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 48202.7 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11318
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 7421
telemt_upstream_connect_success_total 7421
telemt_upstream_connect_attempts_per_request{bucket="1"} 7421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7415
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 308427077 (294.14 MB)
telemt_user_octets_to_client{user="hello"} 5259560972 (4.90 GB)
telemt_user_msgs_from_client{user="hello"} 269457
telemt_user_msgs_to_client{user="hello"} 1136768
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 48200.6 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16070
telemt_connections_bad_total 688
telemt_handshake_timeouts_total 81
telemt_upstream_connect_attempt_total 13991
telemt_upstream_connect_success_total 13986
telemt_upstream_connect_attempts_per_request{bucket="1"} 13981
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13980
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 395830310 (377.49 MB)
telemt_user_octets_to_client{user="hello"} 5646568303 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 307921
telemt_user_msgs_to_client{user="hello"} 1413855
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 48202.3 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18871
telemt_connections_bad_total 8679
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9823
telemt_upstream_connect_success_total 9819
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9817
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9813
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 519877763 (495.79 MB)
telemt_user_octets_to_client{user="hello"} 22395686339 (20.86 GB)
telemt_user_msgs_from_client{user="hello"} 560900
telemt_user_msgs_to_client{user="hello"} 4250812
```