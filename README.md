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

# Server Metrics 2026-03-07 07:35:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 1674.2 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2113
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 2029
telemt_upstream_connect_success_total 2029
telemt_upstream_connect_attempts_per_request{bucket="1"} 2029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2027
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 30159639 (28.76 MB)
telemt_user_octets_to_client{user="hello"} 2979301667 (2.77 GB)
telemt_user_msgs_from_client{user="hello"} 52945
telemt_user_msgs_to_client{user="hello"} 582263
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 1673.5 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 506
telemt_upstream_connect_success_total 505
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 503
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 3042500 (2.90 MB)
telemt_user_octets_to_client{user="hello"} 167241652 (159.49 MB)
telemt_user_msgs_from_client{user="hello"} 6728
telemt_user_msgs_to_client{user="hello"} 47574
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 1673.1 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 440
telemt_upstream_connect_success_total 440
telemt_upstream_connect_attempts_per_request{bucket="1"} 440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 438
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 10247583 (9.77 MB)
telemt_user_octets_to_client{user="hello"} 150749977 (143.77 MB)
telemt_user_msgs_from_client{user="hello"} 8073
telemt_user_msgs_to_client{user="hello"} 37384
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 1673.1 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 653
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 628
telemt_upstream_connect_success_total 627
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 625
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 5423113 (5.17 MB)
telemt_user_octets_to_client{user="hello"} 144421513 (137.73 MB)
telemt_user_msgs_from_client{user="hello"} 9648
telemt_user_msgs_to_client{user="hello"} 41254
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 1673.7 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1220
telemt_connections_bad_total 301
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 837
telemt_upstream_connect_success_total 837
telemt_upstream_connect_attempts_per_request{bucket="1"} 837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 165
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 835
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 16729481 (15.95 MB)
telemt_user_octets_to_client{user="hello"} 1876896007 (1.75 GB)
telemt_user_msgs_from_client{user="hello"} 20477
telemt_user_msgs_to_client{user="hello"} 332963
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```