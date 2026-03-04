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

# Server Metrics 2026-03-04 08:38:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 931.3 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1538
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 1449
telemt_upstream_connect_success_total 1449
telemt_upstream_connect_attempts_per_request{bucket="1"} 1449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1447
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 20265691 (19.33 MB)
telemt_user_octets_to_client{user="hello"} 1391752393 (1.30 GB)
telemt_user_msgs_from_client{user="hello"} 39292
telemt_user_msgs_to_client{user="hello"} 234070
telemt_user_unique_ips_current{user="hello"} 11
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 942.6 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 130
telemt_upstream_connect_success_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 128
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 687669 (671.55 KB)
telemt_user_octets_to_client{user="hello"} 5555777 (5.30 MB)
telemt_user_msgs_from_client{user="hello"} 1835
telemt_user_msgs_to_client{user="hello"} 5439
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 927.3 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154
telemt_connections_bad_total 55
telemt_upstream_connect_attempt_total 99
telemt_upstream_connect_success_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 99
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 457829 (447.10 KB)
telemt_user_octets_to_client{user="hello"} 36386430 (34.70 MB)
telemt_user_msgs_from_client{user="hello"} 1079
telemt_user_msgs_to_client{user="hello"} 7006
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 917.9 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 173
telemt_upstream_connect_success_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 171
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 844760 (824.96 KB)
telemt_user_octets_to_client{user="hello"} 23801703 (22.70 MB)
telemt_user_msgs_from_client{user="hello"} 1816
telemt_user_msgs_to_client{user="hello"} 8740
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 929.2 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 629
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 416
telemt_upstream_connect_success_total 416
telemt_upstream_connect_attempts_per_request{bucket="1"} 416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 414
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 4313698 (4.11 MB)
telemt_user_octets_to_client{user="hello"} 176810147 (168.62 MB)
telemt_user_msgs_from_client{user="hello"} 9839
telemt_user_msgs_to_client{user="hello"} 46811
telemt_user_unique_ips_current{user="hello"} 2
```