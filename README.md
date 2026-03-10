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

# Server Metrics 2026-03-10 17:33:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11262.3 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46095
telemt_connections_bad_total 650
telemt_handshake_timeouts_total 1377
telemt_upstream_connect_attempt_total 41546
telemt_upstream_connect_success_total 41536
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 41546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41534
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 1318261625 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 30672733660 (28.57 GB)
telemt_user_msgs_from_client{user="hello"} 1187879
telemt_user_msgs_to_client{user="hello"} 2320158
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 11261.6 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16600
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 319
telemt_upstream_connect_attempt_total 15061
telemt_upstream_connect_success_total 15058
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 15061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15056
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 461795418 (440.40 MB)
telemt_user_octets_to_client{user="hello"} 8099253663 (7.54 GB)
telemt_user_msgs_from_client{user="hello"} 443633
telemt_user_msgs_to_client{user="hello"} 2537296
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 11261.1 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25930
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 2335
telemt_upstream_connect_attempt_total 21993
telemt_upstream_connect_success_total 21993
telemt_upstream_connect_attempts_per_request{bucket="1"} 21993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21991
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 194831432 (185.81 MB)
telemt_user_octets_to_client{user="hello"} 12600525135 (11.74 GB)
telemt_user_msgs_from_client{user="hello"} 428829
telemt_user_msgs_to_client{user="hello"} 2448596
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 11260.1 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25348
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 248
telemt_upstream_connect_attempt_total 24172
telemt_upstream_connect_success_total 24105
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 24171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24103
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 334581319 (319.08 MB)
telemt_user_octets_to_client{user="hello"} 23821959711 (22.19 GB)
telemt_user_msgs_from_client{user="hello"} 504333
telemt_user_msgs_to_client{user="hello"} 4154250
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11261.4 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34704
telemt_connections_bad_total 2262
telemt_handshake_timeouts_total 612
telemt_upstream_connect_attempt_total 30427
telemt_upstream_connect_success_total 30190
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 30427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30188
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 1280704268 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 19341864696 (18.01 GB)
telemt_user_msgs_from_client{user="hello"} 919961
telemt_user_msgs_to_client{user="hello"} 2819863
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 31
```