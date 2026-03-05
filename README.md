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

# Server Metrics 2026-03-05 12:23:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 89778.4 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132001
telemt_connections_bad_total 532
telemt_handshake_timeouts_total 4218
telemt_upstream_connect_attempt_total 116695
telemt_upstream_connect_success_total 116666
telemt_upstream_connect_attempts_per_request{bucket="1"} 116637
telemt_upstream_connect_attempts_per_request{bucket="2"} 29
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116656
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 3350941803 (3.12 GB)
telemt_user_octets_to_client{user="hello"} 80948843324 (75.39 GB)
telemt_user_msgs_from_client{user="hello"} 3339724
telemt_user_msgs_to_client{user="hello"} 13195971
telemt_user_unique_ips_current{user="hello"} 12
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 89781.2 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24083
telemt_connections_bad_total 488
telemt_handshake_timeouts_total 74
telemt_upstream_connect_attempt_total 19182
telemt_upstream_connect_success_total 19178
telemt_upstream_connect_attempts_per_request{bucket="1"} 19174
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19168
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 1187693513 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 15458104544 (14.40 GB)
telemt_user_msgs_from_client{user="hello"} 854293
telemt_user_msgs_to_client{user="hello"} 4940810
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 89779.6 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20490
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 16179
telemt_upstream_connect_success_total 16179
telemt_upstream_connect_attempts_per_request{bucket="1"} 16179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16169
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 454929403 (433.85 MB)
telemt_user_octets_to_client{user="hello"} 9939943875 (9.26 GB)
telemt_user_msgs_from_client{user="hello"} 468799
telemt_user_msgs_to_client{user="hello"} 2130602
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 89777.3 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35227
telemt_connections_bad_total 1012
telemt_handshake_timeouts_total 639
telemt_upstream_connect_attempt_total 31079
telemt_upstream_connect_success_total 31066
telemt_upstream_connect_attempts_per_request{bucket="1"} 31053
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31056
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 528374424 (503.90 MB)
telemt_user_octets_to_client{user="hello"} 19001174142 (17.70 GB)
telemt_user_msgs_from_client{user="hello"} 587167
telemt_user_msgs_to_client{user="hello"} 4236018
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 89779.0 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35095
telemt_connections_bad_total 16212
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 18286
telemt_upstream_connect_success_total 18281
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18278
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18271
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 665677648 (634.84 MB)
telemt_user_octets_to_client{user="hello"} 28929933019 (26.94 GB)
telemt_user_msgs_from_client{user="hello"} 777623
telemt_user_msgs_to_client{user="hello"} 5551574
telemt_user_unique_ips_current{user="hello"} 2
```