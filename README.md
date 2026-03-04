# Информация

Покупаю сервера у разных хостингов для тестов и запуска прокси для Telegram

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
```tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

# Server Metrics 2026-03-04 07:30:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.6

telemt_uptime_seconds 37170.7 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52240
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 595
telemt_upstream_connect_attempt_total 23341
telemt_upstream_connect_success_total 23334
telemt_upstream_connect_attempts_per_request{bucket="1"} 23327
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23330
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 331770011 (316.40 MB)
telemt_user_octets_to_client{user="hello"} 21018658966 (19.58 GB)
telemt_user_msgs_from_client{user="hello"} 594557
telemt_user_msgs_to_client{user="hello"} 3153924
telemt_user_unique_ips_current{user="hello"} 7
```

## psb.hosting

```
telemt 3.1.6

telemt_uptime_seconds 37173.8 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3604
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 3354
telemt_upstream_connect_success_total 3351
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3350
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3347
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 47569029 (45.37 MB)
telemt_user_octets_to_client{user="hello"} 2764044123 (2.57 GB)
telemt_user_msgs_from_client{user="hello"} 96318
telemt_user_msgs_to_client{user="hello"} 738121
```

## koara.io

```
telemt 3.1.6

telemt_uptime_seconds 37170.0 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2402
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2185
telemt_upstream_connect_success_total 2185
telemt_upstream_connect_attempts_per_request{bucket="1"} 2185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2181
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 33694862 (32.13 MB)
telemt_user_octets_to_client{user="hello"} 2498472890 (2.33 GB)
telemt_user_msgs_from_client{user="hello"} 70752
telemt_user_msgs_to_client{user="hello"} 541193
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.1.6

telemt_uptime_seconds 37171.8 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7731
telemt_connections_bad_total 133
telemt_handshake_timeouts_total 2837
telemt_upstream_connect_attempt_total 4648
telemt_upstream_connect_success_total 4646
telemt_upstream_connect_attempts_per_request{bucket="1"} 4644
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4642
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 60699958 (57.89 MB)
telemt_user_octets_to_client{user="hello"} 2617793906 (2.44 GB)
telemt_user_msgs_from_client{user="hello"} 67724
telemt_user_msgs_to_client{user="hello"} 578986
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.1.6

telemt_uptime_seconds 37171.6 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9176
telemt_connections_bad_total 6754
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 2367
telemt_upstream_connect_success_total 2366
telemt_upstream_connect_attempts_per_request{bucket="1"} 2365
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2362
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 78172791 (74.55 MB)
telemt_user_octets_to_client{user="hello"} 10268432273 (9.56 GB)
telemt_user_msgs_from_client{user="hello"} 145208
telemt_user_msgs_to_client{user="hello"} 1848270
```