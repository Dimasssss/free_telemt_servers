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

# Server Metrics 2026-03-04 15:03:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 12994.5 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21086
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 554
telemt_upstream_connect_attempt_total 20016
telemt_upstream_connect_success_total 20013
telemt_upstream_connect_attempts_per_request{bucket="1"} 20010
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20011
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 874837954 (834.31 MB)
telemt_user_octets_to_client{user="hello"} 15615078650 (14.54 GB)
telemt_user_msgs_from_client{user="hello"} 699905
telemt_user_msgs_to_client{user="hello"} 2486054
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 12997.2 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5172
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 4711
telemt_upstream_connect_success_total 4710
telemt_upstream_connect_attempts_per_request{bucket="1"} 4709
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4708
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 314152559 (299.60 MB)
telemt_user_octets_to_client{user="hello"} 6086134336 (5.67 GB)
telemt_user_msgs_from_client{user="hello"} 229172
telemt_user_msgs_to_client{user="hello"} 1969840
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 12995.2 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2475
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 2388
telemt_upstream_connect_success_total 2388
telemt_upstream_connect_attempts_per_request{bucket="1"} 2388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2386
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 81695989 (77.91 MB)
telemt_user_octets_to_client{user="hello"} 887871890 (846.74 MB)
telemt_user_msgs_from_client{user="hello"} 74485
telemt_user_msgs_to_client{user="hello"} 227627
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 12993.2 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5519
telemt_connections_bad_total 338
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 4745
telemt_upstream_connect_success_total 4743
telemt_upstream_connect_attempts_per_request{bucket="1"} 4741
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 334
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4741
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 38529810 (36.74 MB)
telemt_user_octets_to_client{user="hello"} 3244550607 (3.02 GB)
telemt_user_msgs_from_client{user="hello"} 78986
telemt_user_msgs_to_client{user="hello"} 725159
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 12995.0 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5455
telemt_connections_bad_total 2346
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2957
telemt_upstream_connect_success_total 2956
telemt_upstream_connect_attempts_per_request{bucket="1"} 2955
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2954
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 76154529 (72.63 MB)
telemt_user_octets_to_client{user="hello"} 7180301842 (6.69 GB)
telemt_user_msgs_from_client{user="hello"} 135822
telemt_user_msgs_to_client{user="hello"} 1324526
telemt_user_unique_ips_current{user="hello"} 5
```