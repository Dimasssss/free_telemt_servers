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

# Server Metrics 2026-03-04 09:35:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 4318.7 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8083
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 7066
telemt_upstream_connect_success_total 7066
telemt_upstream_connect_attempts_per_request{bucket="1"} 7066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7064
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 95422591 (91.00 MB)
telemt_user_octets_to_client{user="hello"} 3431089210 (3.20 GB)
telemt_user_msgs_from_client{user="hello"} 150390
telemt_user_msgs_to_client{user="hello"} 587629
telemt_user_unique_ips_current{user="hello"} 10
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 4329.8 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 746
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 660
telemt_upstream_connect_success_total 660
telemt_upstream_connect_attempts_per_request{bucket="1"} 660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 658
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 22285307 (21.25 MB)
telemt_user_octets_to_client{user="hello"} 260056643 (248.01 MB)
telemt_user_msgs_from_client{user="hello"} 22820
telemt_user_msgs_to_client{user="hello"} 81919
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 4314.4 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 707
telemt_connections_bad_total 59
telemt_upstream_connect_attempt_total 629
telemt_upstream_connect_success_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 627
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 10602397 (10.11 MB)
telemt_user_octets_to_client{user="hello"} 1289726351 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 29933
telemt_user_msgs_to_client{user="hello"} 220345
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 4305.0 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1293
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1153
telemt_upstream_connect_success_total 1153
telemt_upstream_connect_attempts_per_request{bucket="1"} 1153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1151
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 5383116 (5.13 MB)
telemt_user_octets_to_client{user="hello"} 189024858 (180.27 MB)
telemt_user_msgs_from_client{user="hello"} 10841
telemt_user_msgs_to_client{user="hello"} 59805
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 4316.5 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1624
telemt_connections_bad_total 757
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 817
telemt_upstream_connect_success_total 817
telemt_upstream_connect_attempts_per_request{bucket="1"} 817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 815
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 11224338 (10.70 MB)
telemt_user_octets_to_client{user="hello"} 396895898 (378.51 MB)
telemt_user_msgs_from_client{user="hello"} 25272
telemt_user_msgs_to_client{user="hello"} 104300
telemt_user_unique_ips_current{user="hello"} 2
```