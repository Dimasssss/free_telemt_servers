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

# Server Metrics 2026-03-06 18:20:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 724.4 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1221
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 1110
telemt_upstream_connect_success_total 1108
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 62
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1106
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 86230067 (82.24 MB)
telemt_user_octets_to_client{user="hello"} 1503801481 (1.40 GB)
telemt_user_msgs_from_client{user="hello"} 57119
telemt_user_msgs_to_client{user="hello"} 235146
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 722.6 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 365
telemt_upstream_connect_success_total 365
telemt_upstream_connect_attempts_per_request{bucket="1"} 365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 363
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 3240227 (3.09 MB)
telemt_user_octets_to_client{user="hello"} 244635019 (233.30 MB)
telemt_user_msgs_from_client{user="hello"} 7638
telemt_user_msgs_to_client{user="hello"} 63064
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 722.5 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 327
telemt_upstream_connect_success_total 327
telemt_upstream_connect_attempts_per_request{bucket="1"} 327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 325
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 5507449 (5.25 MB)
telemt_user_octets_to_client{user="hello"} 85397475 (81.44 MB)
telemt_user_msgs_from_client{user="hello"} 5322
telemt_user_msgs_to_client{user="hello"} 22532
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 722.6 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 259
telemt_upstream_connect_success_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 257
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 19514079 (18.61 MB)
telemt_user_octets_to_client{user="hello"} 157058699 (149.78 MB)
telemt_user_msgs_from_client{user="hello"} 11962
telemt_user_msgs_to_client{user="hello"} 39750
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 722.9 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 479
telemt_connections_bad_total 132
telemt_upstream_connect_attempt_total 341
telemt_upstream_connect_success_total 341
telemt_upstream_connect_attempts_per_request{bucket="1"} 341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 58
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 339
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 2907054 (2.77 MB)
telemt_user_octets_to_client{user="hello"} 153364455 (146.26 MB)
telemt_user_msgs_from_client{user="hello"} 7120
telemt_user_msgs_to_client{user="hello"} 36767
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```