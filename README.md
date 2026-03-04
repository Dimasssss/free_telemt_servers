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

# Server Metrics 2026-03-04 10:36:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 8012.6 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13618
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 192
telemt_upstream_connect_attempt_total 12380
telemt_upstream_connect_success_total 12379
telemt_upstream_connect_attempts_per_request{bucket="1"} 12378
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12377
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 162707694 (155.17 MB)
telemt_user_octets_to_client{user="hello"} 5949086120 (5.54 GB)
telemt_user_msgs_from_client{user="hello"} 268688
telemt_user_msgs_to_client{user="hello"} 1003201
telemt_user_unique_ips_current{user="hello"} 11
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 8023.9 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1853
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 1690
telemt_upstream_connect_success_total 1688
telemt_upstream_connect_attempts_per_request{bucket="1"} 1686
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1686
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 70784155 (67.51 MB)
telemt_user_octets_to_client{user="hello"} 809782123 (772.27 MB)
telemt_user_msgs_from_client{user="hello"} 61055
telemt_user_msgs_to_client{user="hello"} 251450
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 8008.4 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1612
telemt_connections_bad_total 78
telemt_upstream_connect_attempt_total 1507
telemt_upstream_connect_success_total 1507
telemt_upstream_connect_attempts_per_request{bucket="1"} 1507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 185
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1505
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 41760065 (39.83 MB)
telemt_user_octets_to_client{user="hello"} 3233446365 (3.01 GB)
telemt_user_msgs_from_client{user="hello"} 89253
telemt_user_msgs_to_client{user="hello"} 606447
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 7999.1 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2966
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 2654
telemt_upstream_connect_success_total 2653
telemt_upstream_connect_attempts_per_request{bucket="1"} 2652
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 69
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2651
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 17315475 (16.51 MB)
telemt_user_octets_to_client{user="hello"} 518861753 (494.83 MB)
telemt_user_msgs_from_client{user="hello"} 28296
telemt_user_msgs_to_client{user="hello"} 145622
telemt_user_unique_ips_current{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 8010.4 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2772
telemt_connections_bad_total 1436
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1272
telemt_upstream_connect_success_total 1272
telemt_upstream_connect_attempts_per_request{bucket="1"} 1272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1270
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 20043899 (19.12 MB)
telemt_user_octets_to_client{user="hello"} 722819532 (689.33 MB)
telemt_user_msgs_from_client{user="hello"} 40360
telemt_user_msgs_to_client{user="hello"} 180028
telemt_user_unique_ips_current{user="hello"} 4
```