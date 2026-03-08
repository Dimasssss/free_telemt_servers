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

# Server Metrics 2026-03-08 13:17:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 22143.0 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48981
telemt_connections_bad_total 2661
telemt_handshake_timeouts_total 290
telemt_upstream_connect_attempt_total 44038
telemt_upstream_connect_success_total 44017
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44013
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 1334766090 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 21695490052 (20.21 GB)
telemt_user_msgs_from_client{user="hello"} 1085077
telemt_user_msgs_to_client{user="hello"} 1335443
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 22142.2 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11436
telemt_connections_bad_total 86
telemt_handshake_timeouts_total 108
telemt_upstream_connect_attempt_total 11010
telemt_upstream_connect_success_total 11009
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11007
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 441648982 (421.19 MB)
telemt_user_octets_to_client{user="hello"} 7366019314 (6.86 GB)
telemt_user_msgs_from_client{user="hello"} 385997
telemt_user_msgs_to_client{user="hello"} 1891388
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 22141.8 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7682
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 7246
telemt_upstream_connect_success_total 7171
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 7246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7167
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 164950102 (157.31 MB)
telemt_user_octets_to_client{user="hello"} 2086423151 (1.94 GB)
telemt_user_msgs_from_client{user="hello"} 112711
telemt_user_msgs_to_client{user="hello"} 363286
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 22141.7 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9900
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 9485
telemt_upstream_connect_success_total 9466
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 9485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9464
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 901672687 (859.90 MB)
telemt_user_octets_to_client{user="hello"} 3879448447 (3.61 GB)
telemt_user_msgs_from_client{user="hello"} 414468
telemt_user_msgs_to_client{user="hello"} 841995
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 22142.0 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13047
telemt_connections_bad_total 4111
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 8709
telemt_upstream_connect_success_total 8706
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 8709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8702
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 214437452 (204.50 MB)
telemt_user_octets_to_client{user="hello"} 7661359565 (7.14 GB)
telemt_user_msgs_from_client{user="hello"} 241917
telemt_user_msgs_to_client{user="hello"} 1045347
telemt_user_unique_ips_current{user="hello"} 5
```