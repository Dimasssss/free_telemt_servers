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

# Server Metrics 2026-03-06 18:40:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 1957.3 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3242
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 2997
telemt_upstream_connect_success_total 2995
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2993
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 491616381 (468.84 MB)
telemt_user_octets_to_client{user="hello"} 6731917441 (6.27 GB)
telemt_user_msgs_from_client{user="hello"} 274934
telemt_user_msgs_to_client{user="hello"} 1084081
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 1955.9 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1028
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 1013
telemt_upstream_connect_success_total 1013
telemt_upstream_connect_attempts_per_request{bucket="1"} 1013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1011
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 9353251 (8.92 MB)
telemt_user_octets_to_client{user="hello"} 546064016 (520.77 MB)
telemt_user_msgs_from_client{user="hello"} 21055
telemt_user_msgs_to_client{user="hello"} 156545
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 1955.8 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 603
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 602
telemt_upstream_connect_success_total 602
telemt_upstream_connect_attempts_per_request{bucket="1"} 602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 600
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 9354040 (8.92 MB)
telemt_user_octets_to_client{user="hello"} 139804357 (133.33 MB)
telemt_user_msgs_from_client{user="hello"} 11836
telemt_user_msgs_to_client{user="hello"} 39615
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 1955.8 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 583
telemt_upstream_connect_success_total 581
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 50
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 579
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 21844445 (20.83 MB)
telemt_user_octets_to_client{user="hello"} 385062519 (367.22 MB)
telemt_user_msgs_from_client{user="hello"} 17725
telemt_user_msgs_to_client{user="hello"} 90242
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 1956.2 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1737
telemt_connections_bad_total 359
telemt_upstream_connect_attempt_total 1363
telemt_upstream_connect_success_total 1363
telemt_upstream_connect_attempts_per_request{bucket="1"} 1363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1361
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 14673323 (13.99 MB)
telemt_user_octets_to_client{user="hello"} 1076843461 (1.00 GB)
telemt_user_msgs_from_client{user="hello"} 31508
telemt_user_msgs_to_client{user="hello"} 222810
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```