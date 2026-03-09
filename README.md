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

# Server Metrics 2026-03-09 00:24:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 3889.8 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3320
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 166
telemt_upstream_connect_attempt_total 2830
telemt_upstream_connect_success_total 2829
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2827
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 33536442 (31.98 MB)
telemt_user_octets_to_client{user="hello"} 4039094247 (3.76 GB)
telemt_user_msgs_from_client{user="hello"} 80275
telemt_user_msgs_to_client{user="hello"} 141544
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 3887.9 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 251
telemt_upstream_connect_success_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 249
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 1744249 (1.66 MB)
telemt_user_octets_to_client{user="hello"} 45731614 (43.61 MB)
telemt_user_msgs_from_client{user="hello"} 4826
telemt_user_msgs_to_client{user="hello"} 14053
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 3888.5 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304
telemt_connections_bad_total 27
telemt_upstream_connect_attempt_total 274
telemt_upstream_connect_success_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 272
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 15798816 (15.07 MB)
telemt_user_octets_to_client{user="hello"} 24251309 (23.13 MB)
telemt_user_msgs_from_client{user="hello"} 8466
telemt_user_msgs_to_client{user="hello"} 8874
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 3883.4 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 500
telemt_upstream_connect_success_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 83
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 498
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 3483343 (3.32 MB)
telemt_user_octets_to_client{user="hello"} 178573550 (170.30 MB)
telemt_user_msgs_from_client{user="hello"} 8551
telemt_user_msgs_to_client{user="hello"} 34402
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 3888.9 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1284
telemt_connections_bad_total 697
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 576
telemt_upstream_connect_success_total 576
telemt_upstream_connect_attempts_per_request{bucket="1"} 576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 574
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 6072492 (5.79 MB)
telemt_user_octets_to_client{user="hello"} 1258680682 (1.17 GB)
telemt_user_msgs_from_client{user="hello"} 17255
telemt_user_msgs_to_client{user="hello"} 152449
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```