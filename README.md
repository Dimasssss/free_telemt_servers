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

# Server Metrics 2026-03-10 19:00:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16477.5 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64297
telemt_connections_bad_total 2024
telemt_handshake_timeouts_total 1506
telemt_upstream_connect_attempt_total 57608
telemt_upstream_connect_success_total 57596
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 57608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57594
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 1910625466 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 43054292513 (40.10 GB)
telemt_user_msgs_from_client{user="hello"} 1717374
telemt_user_msgs_to_client{user="hello"} 3241262
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16477.0 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24558
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 404
telemt_upstream_connect_attempt_total 22450
telemt_upstream_connect_success_total 22443
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 22450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22441
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 759727076 (724.53 MB)
telemt_user_octets_to_client{user="hello"} 12588156173 (11.72 GB)
telemt_user_msgs_from_client{user="hello"} 697128
telemt_user_msgs_to_client{user="hello"} 3913235
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 16476.6 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37462
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 3232
telemt_upstream_connect_attempt_total 31803
telemt_upstream_connect_success_total 31803
telemt_upstream_connect_attempts_per_request{bucket="1"} 31803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31801
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 519290319 (495.23 MB)
telemt_user_octets_to_client{user="hello"} 33148773647 (30.87 GB)
telemt_user_msgs_from_client{user="hello"} 710660
telemt_user_msgs_to_client{user="hello"} 4841815
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16475.6 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35195
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 270
telemt_upstream_connect_attempt_total 33703
telemt_upstream_connect_success_total 33604
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 33702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33602
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 582813015 (555.81 MB)
telemt_user_octets_to_client{user="hello"} 28108128188 (26.18 GB)
telemt_user_msgs_from_client{user="hello"} 715771
telemt_user_msgs_to_client{user="hello"} 5056588
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16476.7 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51507
telemt_connections_bad_total 4705
telemt_handshake_timeouts_total 1084
telemt_upstream_connect_attempt_total 43644
telemt_upstream_connect_success_total 43403
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 43644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43401
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 1450702039 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 30039233431 (27.98 GB)
telemt_user_msgs_from_client{user="hello"} 1235912
telemt_user_msgs_to_client{user="hello"} 4496902
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 36
```