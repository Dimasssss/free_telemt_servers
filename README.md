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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-12 04:00:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22523.5 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47403
telemt_connections_bad_total 1981
telemt_handshake_timeouts_total 365
telemt_upstream_connect_attempt_total 42938
telemt_upstream_connect_success_total 42925
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 42938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42921
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 483317165 (460.93 MB)
telemt_user_octets_to_client{user="hello"} 13910236260 (12.95 GB)
telemt_user_msgs_from_client{user="hello"} 700756
telemt_user_msgs_to_client{user="hello"} 1693399
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 22511.6 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18637
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 17744
telemt_upstream_connect_success_total 17742
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 17744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17738
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 159538490 (152.15 MB)
telemt_user_octets_to_client{user="hello"} 9534459568 (8.88 GB)
telemt_user_msgs_from_client{user="hello"} 335304
telemt_user_msgs_to_client{user="hello"} 2649581
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 22485.3 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32251
telemt_connections_bad_total 405
telemt_handshake_timeouts_total 921
telemt_upstream_connect_attempt_total 28537
telemt_upstream_connect_success_total 28537
telemt_upstream_connect_attempts_per_request{bucket="1"} 28537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28533
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 5258519571 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 17989428450 (16.75 GB)
telemt_user_msgs_from_client{user="hello"} 2335311
telemt_user_msgs_to_client{user="hello"} 3501825
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 22510.8 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33442
telemt_connections_bad_total 8602
telemt_handshake_timeouts_total 730
telemt_upstream_connect_attempt_total 23083
telemt_upstream_connect_success_total 21385
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 23083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21381
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 196999946 (187.87 MB)
telemt_user_octets_to_client{user="hello"} 17652629307 (16.44 GB)
telemt_user_msgs_from_client{user="hello"} 405858
telemt_user_msgs_to_client{user="hello"} 7403037
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 22511.4 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27418
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 158
telemt_upstream_connect_attempt_total 25457
telemt_upstream_connect_success_total 25456
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 25457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25454
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 584719501 (557.63 MB)
telemt_user_octets_to_client{user="hello"} 30585787922 (28.49 GB)
telemt_user_msgs_from_client{user="hello"} 786659
telemt_user_msgs_to_client{user="hello"} 3889167
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 14
```