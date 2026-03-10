# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

# Server Metrics 2026-03-10 19:46:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 19237.5 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73007
telemt_connections_bad_total 2476
telemt_handshake_timeouts_total 2024
telemt_upstream_connect_attempt_total 65064
telemt_upstream_connect_success_total 65051
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 65064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65049
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 2047620914 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 48040507777 (44.74 GB)
telemt_user_msgs_from_client{user="hello"} 1906348
telemt_user_msgs_to_client{user="hello"} 3554755
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 19237.1 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28336
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 459
telemt_upstream_connect_attempt_total 25959
telemt_upstream_connect_success_total 25952
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 25959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25950
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 850456700 (811.06 MB)
telemt_user_octets_to_client{user="hello"} 20321841228 (18.93 GB)
telemt_user_msgs_from_client{user="hello"} 861375
telemt_user_msgs_to_client{user="hello"} 6187900
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 19236.5 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44006
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 3586
telemt_upstream_connect_attempt_total 37671
telemt_upstream_connect_success_total 37670
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 37671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37668
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 600483646 (572.67 MB)
telemt_user_octets_to_client{user="hello"} 36804767265 (34.28 GB)
telemt_user_msgs_from_client{user="hello"} 827444
telemt_user_msgs_to_client{user="hello"} 5488633
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 19235.3 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40559
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 38914
telemt_upstream_connect_success_total 38799
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 38914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38797
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 636313565 (606.84 MB)
telemt_user_octets_to_client{user="hello"} 30565856609 (28.47 GB)
telemt_user_msgs_from_client{user="hello"} 828553
telemt_user_msgs_to_client{user="hello"} 5717974
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 19236.7 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59133
telemt_connections_bad_total 5221
telemt_handshake_timeouts_total 1262
telemt_upstream_connect_attempt_total 50235
telemt_upstream_connect_success_total 49992
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 50235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49990
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 1513480196 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 38414887731 (35.78 GB)
telemt_user_msgs_from_client{user="hello"} 1387015
telemt_user_msgs_to_client{user="hello"} 5422585
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 14
```