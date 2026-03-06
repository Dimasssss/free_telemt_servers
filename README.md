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

# Server Metrics 2026-03-06 06:42:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 30401.9 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84539
telemt_connections_bad_total 51943
telemt_handshake_timeouts_total 2475
telemt_upstream_connect_attempt_total 28290
telemt_upstream_connect_success_total 28286
telemt_upstream_connect_attempts_per_request{bucket="1"} 28282
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28282
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 400855460 (382.29 MB)
telemt_user_octets_to_client{user="hello"} 23732279088 (22.10 GB)
telemt_user_msgs_from_client{user="hello"} 700259
telemt_user_msgs_to_client{user="hello"} 3609077
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 30399.7 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3718
telemt_connections_bad_total 158
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 3494
telemt_upstream_connect_success_total 3493
telemt_upstream_connect_attempts_per_request{bucket="1"} 3492
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3489
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 71438567 (68.13 MB)
telemt_user_octets_to_client{user="hello"} 1504190787 (1.40 GB)
telemt_user_msgs_from_client{user="hello"} 101121
telemt_user_msgs_to_client{user="hello"} 479773
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 30400.3 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3128
telemt_connections_bad_total 228
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 2854
telemt_upstream_connect_success_total 2854
telemt_upstream_connect_attempts_per_request{bucket="1"} 2854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 265
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2850
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 61044485 (58.22 MB)
telemt_user_octets_to_client{user="hello"} 2787047013 (2.60 GB)
telemt_user_msgs_from_client{user="hello"} 90776
telemt_user_msgs_to_client{user="hello"} 599794
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 30402.8 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5784
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 313
telemt_upstream_connect_attempt_total 5019
telemt_upstream_connect_success_total 5018
telemt_upstream_connect_attempts_per_request{bucket="1"} 5017
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5014
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 112536078 (107.32 MB)
telemt_user_octets_to_client{user="hello"} 8104590285 (7.55 GB)
telemt_user_msgs_from_client{user="hello"} 179686
telemt_user_msgs_to_client{user="hello"} 1707959
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 30402.5 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10383
telemt_connections_bad_total 5559
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 4535
telemt_upstream_connect_success_total 4535
telemt_upstream_connect_attempts_per_request{bucket="1"} 4535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4531
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 108835623 (103.79 MB)
telemt_user_octets_to_client{user="hello"} 21370971942 (19.90 GB)
telemt_user_msgs_from_client{user="hello"} 265016
telemt_user_msgs_to_client{user="hello"} 3986924
telemt_user_unique_ips_current{user="hello"} 2
```