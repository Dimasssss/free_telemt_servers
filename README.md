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

# Server Metrics 2026-03-12 05:32:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 28035.0 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69482
telemt_connections_bad_total 2108
telemt_handshake_timeouts_total 1874
telemt_upstream_connect_attempt_total 62299
telemt_upstream_connect_success_total 62281
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 62299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62277
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 645187133 (615.30 MB)
telemt_user_octets_to_client{user="hello"} 20285314270 (18.89 GB)
telemt_user_msgs_from_client{user="hello"} 952279
telemt_user_msgs_to_client{user="hello"} 2296804
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 28023.1 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27508
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 149
telemt_upstream_connect_attempt_total 26184
telemt_upstream_connect_success_total 26178
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26174
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 236820400 (225.85 MB)
telemt_user_octets_to_client{user="hello"} 14211352952 (13.24 GB)
telemt_user_msgs_from_client{user="hello"} 489637
telemt_user_msgs_to_client{user="hello"} 4204072
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 27996.8 (7h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42986
telemt_connections_bad_total 583
telemt_handshake_timeouts_total 1032
telemt_upstream_connect_attempt_total 38514
telemt_upstream_connect_success_total 38513
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 38514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38509
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 5340675444 (4.97 GB)
telemt_user_octets_to_client{user="hello"} 23370136509 (21.77 GB)
telemt_user_msgs_from_client{user="hello"} 2526328
telemt_user_msgs_to_client{user="hello"} 4202888
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 28022.0 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47356
telemt_connections_bad_total 11617
telemt_handshake_timeouts_total 823
telemt_upstream_connect_attempt_total 33148
telemt_upstream_connect_success_total 31448
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 33148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31444
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 285631571 (272.40 MB)
telemt_user_octets_to_client{user="hello"} 22175485695 (20.65 GB)
telemt_user_msgs_from_client{user="hello"} 568886
telemt_user_msgs_to_client{user="hello"} 9179628
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 28022.9 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41116
telemt_connections_bad_total 761
telemt_handshake_timeouts_total 214
telemt_upstream_connect_attempt_total 38012
telemt_upstream_connect_success_total 38011
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 38012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38007
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 722893375 (689.40 MB)
telemt_user_octets_to_client{user="hello"} 35679274283 (33.23 GB)
telemt_user_msgs_from_client{user="hello"} 1009674
telemt_user_msgs_to_client{user="hello"} 4849936
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 28
```