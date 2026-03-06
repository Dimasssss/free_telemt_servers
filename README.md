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

# Server Metrics 2026-03-06 10:02:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 6701.8 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12848
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 90
telemt_upstream_connect_attempt_total 12375
telemt_upstream_connect_success_total 12374
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12372
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 389815794 (371.76 MB)
telemt_user_octets_to_client{user="hello"} 7511198392 (7.00 GB)
telemt_user_msgs_from_client{user="hello"} 354313
telemt_user_msgs_to_client{user="hello"} 1248341
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 6702.0 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2026
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 1917
telemt_upstream_connect_success_total 1917
telemt_upstream_connect_attempts_per_request{bucket="1"} 1917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1915
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 20035732 (19.11 MB)
telemt_user_octets_to_client{user="hello"} 614681657 (586.21 MB)
telemt_user_msgs_from_client{user="hello"} 40642
telemt_user_msgs_to_client{user="hello"} 205154
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 6699.9 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2213
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2080
telemt_upstream_connect_success_total 2080
telemt_upstream_connect_attempts_per_request{bucket="1"} 2080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2078
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 130806469 (124.75 MB)
telemt_user_octets_to_client{user="hello"} 1754963021 (1.63 GB)
telemt_user_msgs_from_client{user="hello"} 83843
telemt_user_msgs_to_client{user="hello"} 335663
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 6702.5 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3781
telemt_connections_bad_total 116
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 3335
telemt_upstream_connect_success_total 3325
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 187
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3323
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 33283189 (31.74 MB)
telemt_user_octets_to_client{user="hello"} 951498429 (907.42 MB)
telemt_user_msgs_from_client{user="hello"} 52354
telemt_user_msgs_to_client{user="hello"} 256214
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 6704.2 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4128
telemt_connections_bad_total 1753
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 2195
telemt_upstream_connect_success_total 2194
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2192
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 119951626 (114.39 MB)
telemt_user_octets_to_client{user="hello"} 3337374611 (3.11 GB)
telemt_user_msgs_from_client{user="hello"} 97360
telemt_user_msgs_to_client{user="hello"} 601248
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```