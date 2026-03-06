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

# Server Metrics 2026-03-06 04:08:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 21167.2 (5h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71495
telemt_connections_bad_total 51933
telemt_handshake_timeouts_total 2427
telemt_upstream_connect_attempt_total 15753
telemt_upstream_connect_success_total 15751
telemt_upstream_connect_attempts_per_request{bucket="1"} 15749
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15749
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 203300495 (193.88 MB)
telemt_user_octets_to_client{user="hello"} 14273349034 (13.29 GB)
telemt_user_msgs_from_client{user="hello"} 366583
telemt_user_msgs_to_client{user="hello"} 2106154
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 21164.4 (5h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2000
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1832
telemt_upstream_connect_success_total 1831
telemt_upstream_connect_attempts_per_request{bucket="1"} 1830
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1829
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 50492878 (48.15 MB)
telemt_user_octets_to_client{user="hello"} 908165198 (866.09 MB)
telemt_user_msgs_from_client{user="hello"} 65456
telemt_user_msgs_to_client{user="hello"} 282896
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 21164.8 (5h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1383
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1180
telemt_upstream_connect_success_total 1180
telemt_upstream_connect_attempts_per_request{bucket="1"} 1180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1176
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 36621246 (34.92 MB)
telemt_user_octets_to_client{user="hello"} 1730926502 (1.61 GB)
telemt_user_msgs_from_client{user="hello"} 46363
telemt_user_msgs_to_client{user="hello"} 347204
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 21167.7 (5h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2793
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 2297
telemt_upstream_connect_success_total 2297
telemt_upstream_connect_attempts_per_request{bucket="1"} 2297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2293
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 95148900 (90.74 MB)
telemt_user_octets_to_client{user="hello"} 5655306938 (5.27 GB)
telemt_user_msgs_from_client{user="hello"} 133744
telemt_user_msgs_to_client{user="hello"} 1185834
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 21167.4 (5h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6843
telemt_connections_bad_total 3858
telemt_handshake_timeouts_total 142
telemt_upstream_connect_attempt_total 2771
telemt_upstream_connect_success_total 2771
telemt_upstream_connect_attempts_per_request{bucket="1"} 2771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2769
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 50559715 (48.22 MB)
telemt_user_octets_to_client{user="hello"} 11300551423 (10.52 GB)
telemt_user_msgs_from_client{user="hello"} 133547
telemt_user_msgs_to_client{user="hello"} 2054563
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```