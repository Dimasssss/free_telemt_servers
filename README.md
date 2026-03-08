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

# Server Metrics 2026-03-08 21:05:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 50183.1 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111558
telemt_connections_bad_total 5494
telemt_handshake_timeouts_total 1279
telemt_upstream_connect_attempt_total 101034
telemt_upstream_connect_success_total 100998
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 101034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100992
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 2432768378 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 63293509377 (58.95 GB)
telemt_user_msgs_from_client{user="hello"} 2478638
telemt_user_msgs_to_client{user="hello"} 3430451
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 50182.4 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26083
telemt_connections_bad_total 276
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 25229
telemt_upstream_connect_success_total 25222
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 25229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25216
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 833025242 (794.43 MB)
telemt_user_octets_to_client{user="hello"} 22548441802 (21.00 GB)
telemt_user_msgs_from_client{user="hello"} 966267
telemt_user_msgs_to_client{user="hello"} 6108808
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 50182.1 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15029
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13627
telemt_upstream_connect_success_total 13551
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13545
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1414996571 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 5650713135 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 646276
telemt_user_msgs_to_client{user="hello"} 965098
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 50182.0 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19979
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 19132
telemt_upstream_connect_success_total 19093
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 19132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19087
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1064620404 (1015.30 MB)
telemt_user_octets_to_client{user="hello"} 6456177206 (6.01 GB)
telemt_user_msgs_from_client{user="hello"} 567518
telemt_user_msgs_to_client{user="hello"} 1459131
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 50182.3 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29450
telemt_connections_bad_total 9558
telemt_handshake_timeouts_total 239
telemt_upstream_connect_attempt_total 19181
telemt_upstream_connect_success_total 19174
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19168
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 358911053 (342.28 MB)
telemt_user_octets_to_client{user="hello"} 16489093099 (15.36 GB)
telemt_user_msgs_from_client{user="hello"} 500065
telemt_user_msgs_to_client{user="hello"} 2134937
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```