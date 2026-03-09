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

# Server Metrics 2026-03-09 00:55:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 5724.3 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4898
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 4374
telemt_upstream_connect_success_total 4372
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4370
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 53131118 (50.67 MB)
telemt_user_octets_to_client{user="hello"} 6340794386 (5.91 GB)
telemt_user_msgs_from_client{user="hello"} 124748
telemt_user_msgs_to_client{user="hello"} 214366
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 5722.6 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 332
telemt_upstream_connect_success_total 332
telemt_upstream_connect_attempts_per_request{bucket="1"} 332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 330
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 2296436 (2.19 MB)
telemt_user_octets_to_client{user="hello"} 57747940 (55.07 MB)
telemt_user_msgs_from_client{user="hello"} 6493
telemt_user_msgs_to_client{user="hello"} 17708
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 5723.1 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410
telemt_connections_bad_total 45
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 353
telemt_upstream_connect_success_total 353
telemt_upstream_connect_attempts_per_request{bucket="1"} 353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 351
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 16222835 (15.47 MB)
telemt_user_octets_to_client{user="hello"} 49320591 (47.04 MB)
telemt_user_msgs_from_client{user="hello"} 9663
telemt_user_msgs_to_client{user="hello"} 13683
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 5718.0 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 692
telemt_connections_bad_total 4
telemt_upstream_connect_attempt_total 681
telemt_upstream_connect_success_total 681
telemt_upstream_connect_attempts_per_request{bucket="1"} 681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 679
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 4397975 (4.19 MB)
telemt_user_octets_to_client{user="hello"} 191969422 (183.08 MB)
telemt_user_msgs_from_client{user="hello"} 11109
telemt_user_msgs_to_client{user="hello"} 40966
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 5723.5 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1741
telemt_connections_bad_total 1029
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 698
telemt_upstream_connect_success_total 698
telemt_upstream_connect_attempts_per_request{bucket="1"} 698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 696
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 6595436 (6.29 MB)
telemt_user_octets_to_client{user="hello"} 1269872547 (1.18 GB)
telemt_user_msgs_from_client{user="hello"} 18390
telemt_user_msgs_to_client{user="hello"} 156192
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```