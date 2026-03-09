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

# Server Metrics 2026-03-09 20:09:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 74948.8 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144942
telemt_connections_bad_total 2121
telemt_handshake_timeouts_total 1529
telemt_upstream_connect_attempt_total 135316
telemt_upstream_connect_success_total 135271
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 135316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 135263
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 4297184033 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 77041352089 (71.75 GB)
telemt_user_msgs_from_client{user="hello"} 3686674
telemt_user_msgs_to_client{user="hello"} 4971792
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 74947.7 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42847
telemt_connections_bad_total 242
telemt_handshake_timeouts_total 543
telemt_upstream_connect_attempt_total 40190
telemt_upstream_connect_success_total 40169
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40161
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 1194537539 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 20672435581 (19.25 GB)
telemt_user_msgs_from_client{user="hello"} 1101854
telemt_user_msgs_to_client{user="hello"} 5876984
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 74948.2 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54149
telemt_connections_bad_total 706
telemt_handshake_timeouts_total 3012
telemt_upstream_connect_attempt_total 42237
telemt_upstream_connect_success_total 42235
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 42237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42227
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 4763010408 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 29756165654 (27.71 GB)
telemt_user_msgs_from_client{user="hello"} 2509217
telemt_user_msgs_to_client{user="hello"} 4459453
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 74943.0 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59562
telemt_connections_bad_total 266
telemt_handshake_timeouts_total 947
telemt_upstream_connect_attempt_total 54683
telemt_upstream_connect_success_total 54537
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 54683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7021
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54529
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2166075116 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 41192221576 (38.36 GB)
telemt_user_msgs_from_client{user="hello"} 1609311
telemt_user_msgs_to_client{user="hello"} 10006257
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 74948.4 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97175
telemt_connections_bad_total 17410
telemt_handshake_timeouts_total 2457
telemt_upstream_connect_attempt_total 73142
telemt_upstream_connect_success_total 73134
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 73142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73126
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 1240750305 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 65259634412 (60.78 GB)
telemt_user_msgs_from_client{user="hello"} 1675108
telemt_user_msgs_to_client{user="hello"} 8690142
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```