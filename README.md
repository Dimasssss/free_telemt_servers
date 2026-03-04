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

# Server Metrics 2026-03-04 10:57:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 9243.4 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15735
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 200
telemt_upstream_connect_attempt_total 14388
telemt_upstream_connect_success_total 14387
telemt_upstream_connect_attempts_per_request{bucket="1"} 14386
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14385
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 265320273 (253.03 MB)
telemt_user_octets_to_client{user="hello"} 7194454180 (6.70 GB)
telemt_user_msgs_from_client{user="hello"} 341672
telemt_user_msgs_to_client{user="hello"} 1200901
telemt_user_unique_ips_current{user="hello"} 11
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 9254.8 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2078
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 1915
telemt_upstream_connect_success_total 1913
telemt_upstream_connect_attempts_per_request{bucket="1"} 1911
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1911
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 74571832 (71.12 MB)
telemt_user_octets_to_client{user="hello"} 849402090 (810.05 MB)
telemt_user_msgs_from_client{user="hello"} 65738
telemt_user_msgs_to_client{user="hello"} 266043
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 9239.4 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1821
telemt_connections_bad_total 78
telemt_upstream_connect_attempt_total 1714
telemt_upstream_connect_success_total 1714
telemt_upstream_connect_attempts_per_request{bucket="1"} 1714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 201
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1712
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 43510975 (41.50 MB)
telemt_user_octets_to_client{user="hello"} 3310632928 (3.08 GB)
telemt_user_msgs_from_client{user="hello"} 93989
telemt_user_msgs_to_client{user="hello"} 626213
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 9230.0 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3352
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 3032
telemt_upstream_connect_success_total 3031
telemt_upstream_connect_attempts_per_request{bucket="1"} 3030
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 82
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3029
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 22339932 (21.31 MB)
telemt_user_octets_to_client{user="hello"} 1202579565 (1.12 GB)
telemt_user_msgs_from_client{user="hello"} 37987
telemt_user_msgs_to_client{user="hello"} 330415
telemt_user_unique_ips_current{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 9241.3 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3195
telemt_connections_bad_total 1651
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1477
telemt_upstream_connect_success_total 1477
telemt_upstream_connect_attempts_per_request{bucket="1"} 1477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1475
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 21787017 (20.78 MB)
telemt_user_octets_to_client{user="hello"} 799952501 (762.89 MB)
telemt_user_msgs_from_client{user="hello"} 43787
telemt_user_msgs_to_client{user="hello"} 200565
```