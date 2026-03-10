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

# Server Metrics 2026-03-10 01:51:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 95502.5 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175200
telemt_connections_bad_total 2334
telemt_handshake_timeouts_total 1743
telemt_upstream_connect_attempt_total 164296
telemt_upstream_connect_success_total 164245
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 164296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 151066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 164235
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 4904324425 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 101777346461 (94.79 GB)
telemt_user_msgs_from_client{user="hello"} 4420599
telemt_user_msgs_to_client{user="hello"} 6427019
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 95501.5 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54574
telemt_connections_bad_total 3059
telemt_handshake_timeouts_total 795
telemt_upstream_connect_attempt_total 47920
telemt_upstream_connect_success_total 47879
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 47920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47869
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 2134729544 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 23464344368 (21.85 GB)
telemt_user_msgs_from_client{user="hello"} 1539937
telemt_user_msgs_to_client{user="hello"} 6745275
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 95502.0 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65126
telemt_connections_bad_total 840
telemt_handshake_timeouts_total 3727
telemt_upstream_connect_attempt_total 51455
telemt_upstream_connect_success_total 51453
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 51455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51443
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 6020703177 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 54500209910 (50.76 GB)
telemt_user_msgs_from_client{user="hello"} 3313746
telemt_user_msgs_to_client{user="hello"} 7930387
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 95497.0 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72108
telemt_connections_bad_total 380
telemt_handshake_timeouts_total 1046
telemt_upstream_connect_attempt_total 66651
telemt_upstream_connect_success_total 66490
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 66651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66480
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 2286891232 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 47008516071 (43.78 GB)
telemt_user_msgs_from_client{user="hello"} 1851252
telemt_user_msgs_to_client{user="hello"} 11274414
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 95502.2 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119712
telemt_connections_bad_total 21382
telemt_handshake_timeouts_total 3010
telemt_upstream_connect_attempt_total 90279
telemt_upstream_connect_success_total 90267
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 90279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13106
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90257
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 1554504701 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 83578808206 (77.84 GB)
telemt_user_msgs_from_client{user="hello"} 2072104
telemt_user_msgs_to_client{user="hello"} 10857959
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 13
```