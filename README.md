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

# Server Metrics 2026-03-08 23:59:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 2361.4 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2075
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 160
telemt_upstream_connect_attempt_total 1658
telemt_upstream_connect_success_total 1658
telemt_upstream_connect_attempts_per_request{bucket="1"} 1658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1656
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 17948478 (17.12 MB)
telemt_user_octets_to_client{user="hello"} 1696927322 (1.58 GB)
telemt_user_msgs_from_client{user="hello"} 44633
telemt_user_msgs_to_client{user="hello"} 72326
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 2359.6 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 179
telemt_upstream_connect_success_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 177
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 1422650 (1.36 MB)
telemt_user_octets_to_client{user="hello"} 43233005 (41.23 MB)
telemt_user_msgs_from_client{user="hello"} 3667
telemt_user_msgs_to_client{user="hello"} 12113
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 2360.1 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204
telemt_connections_bad_total 26
telemt_upstream_connect_attempt_total 177
telemt_upstream_connect_success_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 175
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 11725899 (11.18 MB)
telemt_user_octets_to_client{user="hello"} 21179776 (20.20 MB)
telemt_user_msgs_from_client{user="hello"} 6248
telemt_user_msgs_to_client{user="hello"} 7063
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 2355.1 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 309
telemt_upstream_connect_success_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 307
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 1057849 (1.01 MB)
telemt_user_octets_to_client{user="hello"} 31393671 (29.94 MB)
telemt_user_msgs_from_client{user="hello"} 3153
telemt_user_msgs_to_client{user="hello"} 9623
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 2360.5 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635
telemt_connections_bad_total 423
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 206
telemt_upstream_connect_success_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 204
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 3785465 (3.61 MB)
telemt_user_octets_to_client{user="hello"} 998923241 (952.65 MB)
telemt_user_msgs_from_client{user="hello"} 10730
telemt_user_msgs_to_client{user="hello"} 108451
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```