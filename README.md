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

# Server Metrics 2026-03-08 21:10:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 50490.9 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111830
telemt_connections_bad_total 5494
telemt_handshake_timeouts_total 1279
telemt_upstream_connect_attempt_total 101303
telemt_upstream_connect_success_total 101267
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 101303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101261
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 2436292547 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 63612213511 (59.24 GB)
telemt_user_msgs_from_client{user="hello"} 2487339
telemt_user_msgs_to_client{user="hello"} 3442492
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 50490.2 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26258
telemt_connections_bad_total 283
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 25391
telemt_upstream_connect_success_total 25384
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 25391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25378
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 834128806 (795.49 MB)
telemt_user_octets_to_client{user="hello"} 22590586481 (21.04 GB)
telemt_user_msgs_from_client{user="hello"} 969094
telemt_user_msgs_to_client{user="hello"} 6121471
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 50489.8 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15063
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13660
telemt_upstream_connect_success_total 13584
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13578
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1415042096 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 5650920054 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 646425
telemt_user_msgs_to_client{user="hello"} 965269
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 50489.6 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20078
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 19230
telemt_upstream_connect_success_total 19191
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 19230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19185
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 1064815919 (1015.49 MB)
telemt_user_octets_to_client{user="hello"} 6465637435 (6.02 GB)
telemt_user_msgs_from_client{user="hello"} 568106
telemt_user_msgs_to_client{user="hello"} 1462708
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 50489.9 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29642
telemt_connections_bad_total 9613
telemt_handshake_timeouts_total 239
telemt_upstream_connect_attempt_total 19314
telemt_upstream_connect_success_total 19307
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19301
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 360125877 (343.44 MB)
telemt_user_octets_to_client{user="hello"} 16526513971 (15.39 GB)
telemt_user_msgs_from_client{user="hello"} 502418
telemt_user_msgs_to_client{user="hello"} 2141522
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```