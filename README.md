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

# Server Metrics 2026-03-09 01:20:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 7253.3 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6087
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 5475
telemt_upstream_connect_success_total 5473
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5471
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 60988182 (58.16 MB)
telemt_user_octets_to_client{user="hello"} 6839726703 (6.37 GB)
telemt_user_msgs_from_client{user="hello"} 145527
telemt_user_msgs_to_client{user="hello"} 245765
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 7251.5 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 436
telemt_upstream_connect_success_total 436
telemt_upstream_connect_attempts_per_request{bucket="1"} 436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 434
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 6438339 (6.14 MB)
telemt_user_octets_to_client{user="hello"} 421888769 (402.34 MB)
telemt_user_msgs_from_client{user="hello"} 18017
telemt_user_msgs_to_client{user="hello"} 81459
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 7252.0 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 477
telemt_upstream_connect_success_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 475
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 29758451 (28.38 MB)
telemt_user_octets_to_client{user="hello"} 80544621 (76.81 MB)
telemt_user_msgs_from_client{user="hello"} 16301
telemt_user_msgs_to_client{user="hello"} 25487
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 7246.9 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 867
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 853
telemt_upstream_connect_success_total 853
telemt_upstream_connect_attempts_per_request{bucket="1"} 853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 168
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 851
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 6913177 (6.59 MB)
telemt_user_octets_to_client{user="hello"} 427266110 (407.47 MB)
telemt_user_msgs_from_client{user="hello"} 17933
telemt_user_msgs_to_client{user="hello"} 117312
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 7252.4 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2113
telemt_connections_bad_total 1302
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 796
telemt_upstream_connect_success_total 796
telemt_upstream_connect_attempts_per_request{bucket="1"} 796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 114
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 794
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 6841760 (6.52 MB)
telemt_user_octets_to_client{user="hello"} 1285126053 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 19095
telemt_user_msgs_to_client{user="hello"} 158788
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```