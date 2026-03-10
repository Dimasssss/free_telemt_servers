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

# Server Metrics 2026-03-10 18:50:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15861.6 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62446
telemt_connections_bad_total 1885
telemt_handshake_timeouts_total 1501
telemt_upstream_connect_attempt_total 55980
telemt_upstream_connect_success_total 55968
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 55980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55966
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 1811953641 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 42189206615 (39.29 GB)
telemt_user_msgs_from_client{user="hello"} 1650592
telemt_user_msgs_to_client{user="hello"} 3170028
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 15860.9 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23501
telemt_connections_bad_total 209
telemt_handshake_timeouts_total 385
telemt_upstream_connect_attempt_total 21503
telemt_upstream_connect_success_total 21496
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 21503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21494
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 715396252 (682.26 MB)
telemt_user_octets_to_client{user="hello"} 11520095018 (10.73 GB)
telemt_user_msgs_from_client{user="hello"} 659285
telemt_user_msgs_to_client{user="hello"} 3599002
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 15860.7 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36102
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 3086
telemt_upstream_connect_attempt_total 30642
telemt_upstream_connect_success_total 30642
telemt_upstream_connect_attempts_per_request{bucket="1"} 30642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30640
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 442489209 (421.99 MB)
telemt_user_octets_to_client{user="hello"} 32141012135 (29.93 GB)
telemt_user_msgs_from_client{user="hello"} 668276
telemt_user_msgs_to_client{user="hello"} 4713403
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 15859.6 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34133
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 269
telemt_upstream_connect_attempt_total 32655
telemt_upstream_connect_success_total 32560
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 32655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32558
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 486141711 (463.62 MB)
telemt_user_octets_to_client{user="hello"} 27617580297 (25.72 GB)
telemt_user_msgs_from_client{user="hello"} 663655
telemt_user_msgs_to_client{user="hello"} 4939124
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15860.8 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49492
telemt_connections_bad_total 4590
telemt_handshake_timeouts_total 1079
telemt_upstream_connect_attempt_total 41891
telemt_upstream_connect_success_total 41651
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 41891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41649
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 1418911275 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 27932945282 (26.01 GB)
telemt_user_msgs_from_client{user="hello"} 1192507
telemt_user_msgs_to_client{user="hello"} 4217752
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 26
```