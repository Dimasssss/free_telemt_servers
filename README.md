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

# Server Metrics 2026-03-08 11:29:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 15643.2 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33039
telemt_connections_bad_total 2571
telemt_handshake_timeouts_total 200
telemt_upstream_connect_attempt_total 28958
telemt_upstream_connect_success_total 28940
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 28958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28938
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 997629609 (951.41 MB)
telemt_user_octets_to_client{user="hello"} 16431747216 (15.30 GB)
telemt_user_msgs_from_client{user="hello"} 791492
telemt_user_msgs_to_client{user="hello"} 953006
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 15642.4 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8191
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 7831
telemt_upstream_connect_success_total 7831
telemt_upstream_connect_attempts_per_request{bucket="1"} 7831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7829
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 114752663 (109.44 MB)
telemt_user_octets_to_client{user="hello"} 5392588930 (5.02 GB)
telemt_user_msgs_from_client{user="hello"} 207625
telemt_user_msgs_to_client{user="hello"} 1387887
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 15642.1 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5134
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 5001
telemt_upstream_connect_success_total 5001
telemt_upstream_connect_attempts_per_request{bucket="1"} 5001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4999
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 118863500 (113.36 MB)
telemt_user_octets_to_client{user="hello"} 1400345877 (1.30 GB)
telemt_user_msgs_from_client{user="hello"} 82855
telemt_user_msgs_to_client{user="hello"} 243037
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 15642.0 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7321
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 6994
telemt_upstream_connect_success_total 6981
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 6994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 447
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6979
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 881969242 (841.11 MB)
telemt_user_octets_to_client{user="hello"} 2848986628 (2.65 GB)
telemt_user_msgs_from_client{user="hello"} 374739
telemt_user_msgs_to_client{user="hello"} 622861
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 15642.2 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9763
telemt_connections_bad_total 2914
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 6696
telemt_upstream_connect_success_total 6695
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6693
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 109210767 (104.15 MB)
telemt_user_octets_to_client{user="hello"} 5102943806 (4.75 GB)
telemt_user_msgs_from_client{user="hello"} 161619
telemt_user_msgs_to_client{user="hello"} 717231
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```