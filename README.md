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

# Server Metrics 2026-03-06 06:36:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 30094.1 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84147
telemt_connections_bad_total 51943
telemt_handshake_timeouts_total 2472
telemt_upstream_connect_attempt_total 27903
telemt_upstream_connect_success_total 27899
telemt_upstream_connect_attempts_per_request{bucket="1"} 27895
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27895
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 394876921 (376.58 MB)
telemt_user_octets_to_client{user="hello"} 23339528001 (21.74 GB)
telemt_user_msgs_from_client{user="hello"} 689936
telemt_user_msgs_to_client{user="hello"} 3550821
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 30091.9 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3661
telemt_connections_bad_total 151
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 3444
telemt_upstream_connect_success_total 3443
telemt_upstream_connect_attempts_per_request{bucket="1"} 3442
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3439
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 71183876 (67.89 MB)
telemt_user_octets_to_client{user="hello"} 1491053720 (1.39 GB)
telemt_user_msgs_from_client{user="hello"} 100453
telemt_user_msgs_to_client{user="hello"} 475122
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 30092.7 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3005
telemt_connections_bad_total 228
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 2734
telemt_upstream_connect_success_total 2734
telemt_upstream_connect_attempts_per_request{bucket="1"} 2734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 255
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2730
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 60115905 (57.33 MB)
telemt_user_octets_to_client{user="hello"} 2736218059 (2.55 GB)
telemt_user_msgs_from_client{user="hello"} 88248
telemt_user_msgs_to_client{user="hello"} 588382
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 30095.1 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5612
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 312
telemt_upstream_connect_attempt_total 4868
telemt_upstream_connect_success_total 4867
telemt_upstream_connect_attempts_per_request{bucket="1"} 4866
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4863
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 111068690 (105.92 MB)
telemt_user_octets_to_client{user="hello"} 7735241249 (7.20 GB)
telemt_user_msgs_from_client{user="hello"} 175277
telemt_user_msgs_to_client{user="hello"} 1640684
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 30094.8 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10311
telemt_connections_bad_total 5504
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 4518
telemt_upstream_connect_success_total 4518
telemt_upstream_connect_attempts_per_request{bucket="1"} 4518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4514
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 101934236 (97.21 MB)
telemt_user_octets_to_client{user="hello"} 20875555240 (19.44 GB)
telemt_user_msgs_from_client{user="hello"} 258312
telemt_user_msgs_to_client{user="hello"} 3902224
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```