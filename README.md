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

# Server Metrics 2026-03-09 02:42:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 12143.8 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9805
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 185
telemt_upstream_connect_attempt_total 9021
telemt_upstream_connect_success_total 9018
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 9021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9016
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 107383161 (102.41 MB)
telemt_user_octets_to_client{user="hello"} 8423273828 (7.84 GB)
telemt_user_msgs_from_client{user="hello"} 211647
telemt_user_msgs_to_client{user="hello"} 341296
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 12141.7 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 701
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 668
telemt_upstream_connect_success_total 668
telemt_upstream_connect_attempts_per_request{bucket="1"} 668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 666
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 8445116 (8.05 MB)
telemt_user_octets_to_client{user="hello"} 467229987 (445.59 MB)
telemt_user_msgs_from_client{user="hello"} 23746
telemt_user_msgs_to_client{user="hello"} 94422
telemt_user_unique_ips_current{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 12142.3 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 805
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 718
telemt_upstream_connect_success_total 718
telemt_upstream_connect_attempts_per_request{bucket="1"} 718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 716
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 314153801 (299.60 MB)
telemt_user_octets_to_client{user="hello"} 135986616 (129.69 MB)
telemt_user_msgs_from_client{user="hello"} 118660
telemt_user_msgs_to_client{user="hello"} 47842
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 12137.1 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1662
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 197
telemt_upstream_connect_attempt_total 1347
telemt_upstream_connect_success_total 1347
telemt_upstream_connect_attempts_per_request{bucket="1"} 1347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1345
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 11092240 (10.58 MB)
telemt_user_octets_to_client{user="hello"} 712208526 (679.21 MB)
telemt_user_msgs_from_client{user="hello"} 28434
telemt_user_msgs_to_client{user="hello"} 203675
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 12142.6 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3336
telemt_connections_bad_total 2211
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1096
telemt_upstream_connect_success_total 1096
telemt_upstream_connect_attempts_per_request{bucket="1"} 1096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1094
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 8841489 (8.43 MB)
telemt_user_octets_to_client{user="hello"} 1543828934 (1.44 GB)
telemt_user_msgs_from_client{user="hello"} 23420
telemt_user_msgs_to_client{user="hello"} 184708
telemt_user_unique_ips_current{user="hello"} 5
```