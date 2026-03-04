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

# Server Metrics 2026-03-04 12:29:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 3756.4 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6279
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 6043
telemt_upstream_connect_success_total 6043
telemt_upstream_connect_attempts_per_request{bucket="1"} 6043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6041
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 301889402 (287.90 MB)
telemt_user_octets_to_client{user="hello"} 7201328680 (6.71 GB)
telemt_user_msgs_from_client{user="hello"} 249906
telemt_user_msgs_to_client{user="hello"} 1069300
telemt_user_unique_ips_current{user="hello"} 10
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 3759.1 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1508
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1371
telemt_upstream_connect_success_total 1371
telemt_upstream_connect_attempts_per_request{bucket="1"} 1371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 85
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1369
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 25653250 (24.46 MB)
telemt_user_octets_to_client{user="hello"} 2323349234 (2.16 GB)
telemt_user_msgs_from_client{user="hello"} 46442
telemt_user_msgs_to_client{user="hello"} 730003
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 3757.6 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 536
telemt_upstream_connect_success_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 534
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 7552839 (7.20 MB)
telemt_user_octets_to_client{user="hello"} 275171952 (262.42 MB)
telemt_user_msgs_from_client{user="hello"} 17146
telemt_user_msgs_to_client{user="hello"} 61104
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 3755.3 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1264
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 1167
telemt_upstream_connect_success_total 1167
telemt_upstream_connect_attempts_per_request{bucket="1"} 1167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1165
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 8167209 (7.79 MB)
telemt_user_octets_to_client{user="hello"} 324613006 (309.58 MB)
telemt_user_msgs_from_client{user="hello"} 15901
telemt_user_msgs_to_client{user="hello"} 99894
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 3757.1 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1641
telemt_connections_bad_total 674
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 961
telemt_upstream_connect_success_total 960
telemt_upstream_connect_attempts_per_request{bucket="1"} 959
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 958
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 18342447 (17.49 MB)
telemt_user_octets_to_client{user="hello"} 2598101242 (2.42 GB)
telemt_user_msgs_from_client{user="hello"} 41284
telemt_user_msgs_to_client{user="hello"} 479384
telemt_user_unique_ips_current{user="hello"} 2
```