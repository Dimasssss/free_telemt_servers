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

# Server Metrics 2026-03-07 20:30:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 13548.6 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23125
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 22246
telemt_upstream_connect_success_total 22243
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 22246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22241
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 1820018814 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 16626547753 (15.48 GB)
telemt_user_msgs_from_client{user="hello"} 849513
telemt_user_msgs_to_client{user="hello"} 2566947
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 13547.5 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4974
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 4727
telemt_upstream_connect_success_total 4722
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 4727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4720
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 75589293 (72.09 MB)
telemt_user_octets_to_client{user="hello"} 3041371536 (2.83 GB)
telemt_user_msgs_from_client{user="hello"} 122884
telemt_user_msgs_to_client{user="hello"} 873623
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 13547.2 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2608
telemt_connections_bad_total 102
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 2463
telemt_upstream_connect_success_total 2463
telemt_upstream_connect_attempts_per_request{bucket="1"} 2463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 231
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2461
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 75519059 (72.02 MB)
telemt_user_octets_to_client{user="hello"} 3583885812 (3.34 GB)
telemt_user_msgs_from_client{user="hello"} 90591
telemt_user_msgs_to_client{user="hello"} 744203
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 13375.5 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5797
telemt_connections_bad_total 91
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 5555
telemt_upstream_connect_success_total 5542
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 5555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5540
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 84321210 (80.41 MB)
telemt_user_octets_to_client{user="hello"} 5813210845 (5.41 GB)
telemt_user_msgs_from_client{user="hello"} 146042
telemt_user_msgs_to_client{user="hello"} 1756648
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 13547.4 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7701
telemt_connections_bad_total 2488
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 5067
telemt_upstream_connect_success_total 5060
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5058
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 1569289291 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 3275416896 (3.05 GB)
telemt_user_msgs_from_client{user="hello"} 670506
telemt_user_msgs_to_client{user="hello"} 766719
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```