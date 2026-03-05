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

# Server Metrics 2026-03-05 00:14:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 46046.3 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67678
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1557
telemt_upstream_connect_attempt_total 61092
telemt_upstream_connect_success_total 61077
telemt_upstream_connect_attempts_per_request{bucket="1"} 61062
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61071
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 2338570617 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 47052875662 (43.82 GB)
telemt_user_msgs_from_client{user="hello"} 1998684
telemt_user_msgs_to_client{user="hello"} 7509530
telemt_user_unique_ips_current{user="hello"} 8
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 46049.3 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15924
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 11415
telemt_upstream_connect_success_total 11413
telemt_upstream_connect_attempts_per_request{bucket="1"} 11411
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11409
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 1056351582 (1007.42 MB)
telemt_user_octets_to_client{user="hello"} 11091303100 (10.33 GB)
telemt_user_msgs_from_client{user="hello"} 649815
telemt_user_msgs_to_client{user="hello"} 3736741
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 46047.5 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11245
telemt_connections_bad_total 175
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 7351
telemt_upstream_connect_success_total 7351
telemt_upstream_connect_attempts_per_request{bucket="1"} 7351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7345
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 308171310 (293.90 MB)
telemt_user_octets_to_client{user="hello"} 5254581270 (4.89 GB)
telemt_user_msgs_from_client{user="hello"} 268887
telemt_user_msgs_to_client{user="hello"} 1134175
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 46045.4 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15165
telemt_connections_bad_total 686
telemt_handshake_timeouts_total 75
telemt_upstream_connect_attempt_total 13234
telemt_upstream_connect_success_total 13229
telemt_upstream_connect_attempts_per_request{bucket="1"} 13224
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1083
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13223
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 392390637 (374.21 MB)
telemt_user_octets_to_client{user="hello"} 5587405098 (5.20 GB)
telemt_user_msgs_from_client{user="hello"} 303092
telemt_user_msgs_to_client{user="hello"} 1393503
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 46047.1 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17864
telemt_connections_bad_total 8280
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9227
telemt_upstream_connect_success_total 9223
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9221
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9217
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 512875536 (489.12 MB)
telemt_user_octets_to_client{user="hello"} 21170834204 (19.72 GB)
telemt_user_msgs_from_client{user="hello"} 542725
telemt_user_msgs_to_client{user="hello"} 4005111
```