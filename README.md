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

# Server Metrics 2026-03-06 06:47:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 30710.0 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85099
telemt_connections_bad_total 51943
telemt_handshake_timeouts_total 2475
telemt_upstream_connect_attempt_total 28845
telemt_upstream_connect_success_total 28841
telemt_upstream_connect_attempts_per_request{bucket="1"} 28837
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28837
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 406599237 (387.76 MB)
telemt_user_octets_to_client{user="hello"} 24493787564 (22.81 GB)
telemt_user_msgs_from_client{user="hello"} 714095
telemt_user_msgs_to_client{user="hello"} 3715351
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 30707.8 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3801
telemt_connections_bad_total 158
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 3577
telemt_upstream_connect_success_total 3576
telemt_upstream_connect_attempts_per_request{bucket="1"} 3575
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3572
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 72168630 (68.83 MB)
telemt_user_octets_to_client{user="hello"} 1534167035 (1.43 GB)
telemt_user_msgs_from_client{user="hello"} 102546
telemt_user_msgs_to_client{user="hello"} 487714
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 30708.7 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3232
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 2952
telemt_upstream_connect_success_total 2952
telemt_upstream_connect_attempts_per_request{bucket="1"} 2952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 270
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2948
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 61518601 (58.67 MB)
telemt_user_octets_to_client{user="hello"} 2801913688 (2.61 GB)
telemt_user_msgs_from_client{user="hello"} 92128
telemt_user_msgs_to_client{user="hello"} 604038
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 30710.9 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5948
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 313
telemt_upstream_connect_attempt_total 5167
telemt_upstream_connect_success_total 5166
telemt_upstream_connect_attempts_per_request{bucket="1"} 5165
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5162
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 113081161 (107.84 MB)
telemt_user_octets_to_client{user="hello"} 8125937954 (7.57 GB)
telemt_user_msgs_from_client{user="hello"} 181230
telemt_user_msgs_to_client{user="hello"} 1714566
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 30710.7 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10469
telemt_connections_bad_total 5614
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 4566
telemt_upstream_connect_success_total 4566
telemt_upstream_connect_attempts_per_request{bucket="1"} 4566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4562
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 110237266 (105.13 MB)
telemt_user_octets_to_client{user="hello"} 21710711681 (20.22 GB)
telemt_user_msgs_from_client{user="hello"} 268831
telemt_user_msgs_to_client{user="hello"} 4046331
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```