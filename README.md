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

# Server Metrics 2026-03-08 09:15:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 7628.8 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16769
telemt_connections_bad_total 2452
telemt_handshake_timeouts_total 90
telemt_upstream_connect_attempt_total 13566
telemt_upstream_connect_success_total 13557
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13555
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 445971420 (425.31 MB)
telemt_user_octets_to_client{user="hello"} 8495796542 (7.91 GB)
telemt_user_msgs_from_client{user="hello"} 365433
telemt_user_msgs_to_client{user="hello"} 436999
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 7627.9 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3558
telemt_connections_bad_total 50
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 3368
telemt_upstream_connect_success_total 3368
telemt_upstream_connect_attempts_per_request{bucket="1"} 3368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3366
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 43877127 (41.84 MB)
telemt_user_octets_to_client{user="hello"} 2447862084 (2.28 GB)
telemt_user_msgs_from_client{user="hello"} 83255
telemt_user_msgs_to_client{user="hello"} 617230
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 7627.5 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3064
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2989
telemt_upstream_connect_success_total 2989
telemt_upstream_connect_attempts_per_request{bucket="1"} 2989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2987
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 30570192 (29.15 MB)
telemt_user_octets_to_client{user="hello"} 568472525 (542.14 MB)
telemt_user_msgs_from_client{user="hello"} 26871
telemt_user_msgs_to_client{user="hello"} 106139
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 7627.4 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3195
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 3030
telemt_upstream_connect_success_total 3026
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 3030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3024
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 75993727 (72.47 MB)
telemt_user_octets_to_client{user="hello"} 1016902325 (969.79 MB)
telemt_user_msgs_from_client{user="hello"} 54189
telemt_user_msgs_to_client{user="hello"} 261301
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 7627.6 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4801
telemt_connections_bad_total 1430
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 3324
telemt_upstream_connect_success_total 3324
telemt_upstream_connect_attempts_per_request{bucket="1"} 3324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3322
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 42557386 (40.59 MB)
telemt_user_octets_to_client{user="hello"} 2982976375 (2.78 GB)
telemt_user_msgs_from_client{user="hello"} 73597
telemt_user_msgs_to_client{user="hello"} 333912
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```