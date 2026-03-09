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

# Server Metrics 2026-03-09 02:37:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 11838.0 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9628
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 8849
telemt_upstream_connect_success_total 8846
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 8849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8844
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 106604667 (101.67 MB)
telemt_user_octets_to_client{user="hello"} 8417523986 (7.84 GB)
telemt_user_msgs_from_client{user="hello"} 209579
telemt_user_msgs_to_client{user="hello"} 339287
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 11836.7 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 684
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 652
telemt_upstream_connect_success_total 652
telemt_upstream_connect_attempts_per_request{bucket="1"} 652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 650
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 8384840 (8.00 MB)
telemt_user_octets_to_client{user="hello"} 466953658 (445.32 MB)
telemt_user_msgs_from_client{user="hello"} 23524
telemt_user_msgs_to_client{user="hello"} 94140
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 11837.2 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 800
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 713
telemt_upstream_connect_success_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 711
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 314142935 (299.59 MB)
telemt_user_octets_to_client{user="hello"} 135945748 (129.65 MB)
telemt_user_msgs_from_client{user="hello"} 118614
telemt_user_msgs_to_client{user="hello"} 47801
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 11832.0 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1624
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 197
telemt_upstream_connect_attempt_total 1319
telemt_upstream_connect_success_total 1319
telemt_upstream_connect_attempts_per_request{bucket="1"} 1319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1317
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 10742544 (10.24 MB)
telemt_user_octets_to_client{user="hello"} 692312650 (660.24 MB)
telemt_user_msgs_from_client{user="hello"} 27533
telemt_user_msgs_to_client{user="hello"} 198701
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 11837.5 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3247
telemt_connections_bad_total 2147
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1071
telemt_upstream_connect_success_total 1071
telemt_upstream_connect_attempts_per_request{bucket="1"} 1071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1069
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 7636659 (7.28 MB)
telemt_user_octets_to_client{user="hello"} 1314697903 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 21074
telemt_user_msgs_to_client{user="hello"} 164886
telemt_user_unique_ips_current{user="hello"} 5
```