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

# Server Metrics 2026-03-07 23:30:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 24329.7 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35292
telemt_connections_bad_total 224
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 33914
telemt_upstream_connect_success_total 33910
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 33914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33908
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 2164294849 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 25380836461 (23.64 GB)
telemt_user_msgs_from_client{user="hello"} 1228953
telemt_user_msgs_to_client{user="hello"} 3928297
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 24328.9 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6406
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 6087
telemt_upstream_connect_success_total 6080
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 6087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6076
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 133795488 (127.60 MB)
telemt_user_octets_to_client{user="hello"} 6273038490 (5.84 GB)
telemt_user_msgs_from_client{user="hello"} 223585
telemt_user_msgs_to_client{user="hello"} 1607395
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 24328.7 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3942
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3738
telemt_upstream_connect_success_total 3738
telemt_upstream_connect_attempts_per_request{bucket="1"} 3738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3736
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 108314560 (103.30 MB)
telemt_user_octets_to_client{user="hello"} 11718796346 (10.91 GB)
telemt_user_msgs_from_client{user="hello"} 183752
telemt_user_msgs_to_client{user="hello"} 2484890
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 24156.9 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10428
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 10020
telemt_upstream_connect_success_total 9996
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 10020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9992
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 211498016 (201.70 MB)
telemt_user_octets_to_client{user="hello"} 9429178571 (8.78 GB)
telemt_user_msgs_from_client{user="hello"} 268023
telemt_user_msgs_to_client{user="hello"} 2786828
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 24328.9 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11726
telemt_connections_bad_total 4495
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 7020
telemt_upstream_connect_success_total 7012
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7008
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 1613204469 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 7451471218 (6.94 GB)
telemt_user_msgs_from_client{user="hello"} 787718
telemt_user_msgs_to_client{user="hello"} 1649908
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```