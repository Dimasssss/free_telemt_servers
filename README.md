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

# Server Metrics 2026-03-04 19:04:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 27483.2 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44394
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 1285
telemt_upstream_connect_attempt_total 42057
telemt_upstream_connect_success_total 42047
telemt_upstream_connect_attempts_per_request{bucket="1"} 42037
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42043
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 1424198109 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 33631812384 (31.32 GB)
telemt_user_msgs_from_client{user="hello"} 1318278
telemt_user_msgs_to_client{user="hello"} 5308792
telemt_user_unique_ips_current{user="hello"} 15
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 27486.2 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9969
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 9366
telemt_upstream_connect_success_total 9364
telemt_upstream_connect_attempts_per_request{bucket="1"} 9362
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9360
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 845924440 (806.74 MB)
telemt_user_octets_to_client{user="hello"} 10521891359 (9.80 GB)
telemt_user_msgs_from_client{user="hello"} 539487
telemt_user_msgs_to_client{user="hello"} 3553434
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 27484.3 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5715
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 5536
telemt_upstream_connect_success_total 5536
telemt_upstream_connect_attempts_per_request{bucket="1"} 5536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5532
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 233628959 (222.81 MB)
telemt_user_octets_to_client{user="hello"} 4165782829 (3.88 GB)
telemt_user_msgs_from_client{user="hello"} 208453
telemt_user_msgs_to_client{user="hello"} 896555
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 27482.1 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9316
telemt_connections_bad_total 431
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 8341
telemt_upstream_connect_success_total 8337
telemt_upstream_connect_attempts_per_request{bucket="1"} 8333
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8333
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 131313318 (125.23 MB)
telemt_user_octets_to_client{user="hello"} 4353351027 (4.05 GB)
telemt_user_msgs_from_client{user="hello"} 157143
telemt_user_msgs_to_client{user="hello"} 1053227
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 27483.9 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11185
telemt_connections_bad_total 4879
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 6083
telemt_upstream_connect_success_total 6080
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6079
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6076
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 176071855 (167.92 MB)
telemt_user_octets_to_client{user="hello"} 11602791583 (10.81 GB)
telemt_user_msgs_from_client{user="hello"} 275226
telemt_user_msgs_to_client{user="hello"} 2215348
telemt_user_unique_ips_current{user="hello"} 2
```