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

# Server Metrics 2026-03-04 21:50:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 37427.0 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62083
telemt_connections_bad_total 88
telemt_handshake_timeouts_total 1544
telemt_upstream_connect_attempt_total 55695
telemt_upstream_connect_success_total 55681
telemt_upstream_connect_attempts_per_request{bucket="1"} 55667
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55677
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 2265202941 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 43341851108 (40.37 GB)
telemt_user_msgs_from_client{user="hello"} 1860383
telemt_user_msgs_to_client{user="hello"} 6905054
telemt_user_unique_ips_current{user="hello"} 11
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 37429.8 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11763
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 11122
telemt_upstream_connect_success_total 11120
telemt_upstream_connect_attempts_per_request{bucket="1"} 11118
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11116
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 1053654608 (1004.84 MB)
telemt_user_octets_to_client{user="hello"} 11025345324 (10.27 GB)
telemt_user_msgs_from_client{user="hello"} 642838
telemt_user_msgs_to_client{user="hello"} 3715522
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 37427.9 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7312
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 6979
telemt_upstream_connect_success_total 6979
telemt_upstream_connect_attempts_per_request{bucket="1"} 6979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6975
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 305950682 (291.78 MB)
telemt_user_octets_to_client{user="hello"} 5107868260 (4.76 GB)
telemt_user_msgs_from_client{user="hello"} 262544
telemt_user_msgs_to_client{user="hello"} 1095820
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 37426.0 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12699
telemt_connections_bad_total 624
telemt_handshake_timeouts_total 61
telemt_upstream_connect_attempt_total 11107
telemt_upstream_connect_success_total 11103
telemt_upstream_connect_attempts_per_request{bucket="1"} 11099
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11099
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 352644564 (336.31 MB)
telemt_user_octets_to_client{user="hello"} 4927023811 (4.59 GB)
telemt_user_msgs_from_client{user="hello"} 272726
telemt_user_msgs_to_client{user="hello"} 1236824
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 37427.6 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15414
telemt_connections_bad_total 6706
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 8415
telemt_upstream_connect_success_total 8411
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8409
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8407
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 496753717 (473.74 MB)
telemt_user_octets_to_client{user="hello"} 17894692961 (16.67 GB)
telemt_user_msgs_from_client{user="hello"} 502885
telemt_user_msgs_to_client{user="hello"} 3430928
telemt_user_unique_ips_current{user="hello"} 4
```