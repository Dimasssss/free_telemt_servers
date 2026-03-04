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

# Server Metrics 2026-03-04 10:31:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 7704.6 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13187
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 192
telemt_upstream_connect_attempt_total 11951
telemt_upstream_connect_success_total 11950
telemt_upstream_connect_attempts_per_request{bucket="1"} 11949
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11948
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 158945811 (151.58 MB)
telemt_user_octets_to_client{user="hello"} 5839110606 (5.44 GB)
telemt_user_msgs_from_client{user="hello"} 261415
telemt_user_msgs_to_client{user="hello"} 982579
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 7716.2 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1778
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 1638
telemt_upstream_connect_success_total 1636
telemt_upstream_connect_attempts_per_request{bucket="1"} 1634
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1634
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 61726676 (58.87 MB)
telemt_user_octets_to_client{user="hello"} 797395702 (760.46 MB)
telemt_user_msgs_from_client{user="hello"} 57042
telemt_user_msgs_to_client{user="hello"} 247449
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 7700.9 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1585
telemt_connections_bad_total 78
telemt_upstream_connect_attempt_total 1482
telemt_upstream_connect_success_total 1482
telemt_upstream_connect_attempts_per_request{bucket="1"} 1482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 185
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1480
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 41421706 (39.50 MB)
telemt_user_octets_to_client{user="hello"} 3212264843 (2.99 GB)
telemt_user_msgs_from_client{user="hello"} 88283
telemt_user_msgs_to_client{user="hello"} 601983
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 7691.2 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2803
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 2509
telemt_upstream_connect_success_total 2508
telemt_upstream_connect_attempts_per_request{bucket="1"} 2507
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 65
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2506
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 16693761 (15.92 MB)
telemt_user_octets_to_client{user="hello"} 483658719 (461.25 MB)
telemt_user_msgs_from_client{user="hello"} 26619
telemt_user_msgs_to_client{user="hello"} 135381
telemt_user_unique_ips_current{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 7702.6 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2694
telemt_connections_bad_total 1384
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1247
telemt_upstream_connect_success_total 1247
telemt_upstream_connect_attempts_per_request{bucket="1"} 1247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1245
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 19776201 (18.86 MB)
telemt_user_octets_to_client{user="hello"} 712516002 (679.51 MB)
telemt_user_msgs_from_client{user="hello"} 39890
telemt_user_msgs_to_client{user="hello"} 176762
telemt_user_unique_ips_current{user="hello"} 2
```