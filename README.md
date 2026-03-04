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

# Server Metrics 2026-03-04 10:16:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 6781.1 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11675
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 191
telemt_upstream_connect_attempt_total 10481
telemt_upstream_connect_success_total 10480
telemt_upstream_connect_attempts_per_request{bucket="1"} 10479
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10478
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 141382938 (134.83 MB)
telemt_user_octets_to_client{user="hello"} 5174240383 (4.82 GB)
telemt_user_msgs_from_client{user="hello"} 230884
telemt_user_msgs_to_client{user="hello"} 874830
telemt_user_unique_ips_current{user="hello"} 11
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 6792.4 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1581
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 1443
telemt_upstream_connect_success_total 1441
telemt_upstream_connect_attempts_per_request{bucket="1"} 1439
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1439
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 60242207 (57.45 MB)
telemt_user_octets_to_client{user="hello"} 747579473 (712.95 MB)
telemt_user_msgs_from_client{user="hello"} 53134
telemt_user_msgs_to_client{user="hello"} 227938
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 6777.2 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1390
telemt_connections_bad_total 75
telemt_upstream_connect_attempt_total 1291
telemt_upstream_connect_success_total 1291
telemt_upstream_connect_attempts_per_request{bucket="1"} 1291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1289
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 36825791 (35.12 MB)
telemt_user_octets_to_client{user="hello"} 2736125132 (2.55 GB)
telemt_user_msgs_from_client{user="hello"} 75011
telemt_user_msgs_to_client{user="hello"} 518296
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 6767.6 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2678
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 2396
telemt_upstream_connect_success_total 2395
telemt_upstream_connect_attempts_per_request{bucket="1"} 2394
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2393
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 16019615 (15.28 MB)
telemt_user_octets_to_client{user="hello"} 463997783 (442.50 MB)
telemt_user_msgs_from_client{user="hello"} 25044
telemt_user_msgs_to_client{user="hello"} 128313
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 6778.9 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2391
telemt_connections_bad_total 1228
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1102
telemt_upstream_connect_success_total 1102
telemt_upstream_connect_attempts_per_request{bucket="1"} 1102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 158
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1100
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 16282435 (15.53 MB)
telemt_user_octets_to_client{user="hello"} 572802850 (546.27 MB)
telemt_user_msgs_from_client{user="hello"} 34207
telemt_user_msgs_to_client{user="hello"} 146379
telemt_user_unique_ips_current{user="hello"} 2
```