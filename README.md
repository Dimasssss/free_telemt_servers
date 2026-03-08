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

# Server Metrics 2026-03-08 11:03:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 14104.1 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28971
telemt_connections_bad_total 2560
telemt_handshake_timeouts_total 187
telemt_upstream_connect_attempt_total 25117
telemt_upstream_connect_success_total 25102
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 25117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25100
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 889518245 (848.31 MB)
telemt_user_octets_to_client{user="hello"} 14625215141 (13.62 GB)
telemt_user_msgs_from_client{user="hello"} 717731
telemt_user_msgs_to_client{user="hello"} 829103
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 14103.4 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7390
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 7038
telemt_upstream_connect_success_total 7038
telemt_upstream_connect_attempts_per_request{bucket="1"} 7038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7036
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 103468756 (98.68 MB)
telemt_user_octets_to_client{user="hello"} 4707811447 (4.38 GB)
telemt_user_msgs_from_client{user="hello"} 184472
telemt_user_msgs_to_client{user="hello"} 1224462
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 14103.2 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4837
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 4725
telemt_upstream_connect_success_total 4725
telemt_upstream_connect_attempts_per_request{bucket="1"} 4725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4723
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 109109578 (104.06 MB)
telemt_user_octets_to_client{user="hello"} 1343875482 (1.25 GB)
telemt_user_msgs_from_client{user="hello"} 75883
telemt_user_msgs_to_client{user="hello"} 230855
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 14102.8 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6640
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 6336
telemt_upstream_connect_success_total 6326
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 6336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6324
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 877314999 (836.67 MB)
telemt_user_octets_to_client{user="hello"} 2671477307 (2.49 GB)
telemt_user_msgs_from_client{user="hello"} 364608
telemt_user_msgs_to_client{user="hello"} 579516
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 14103.2 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8799
telemt_connections_bad_total 2629
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 6026
telemt_upstream_connect_success_total 6025
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6023
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 100235556 (95.59 MB)
telemt_user_octets_to_client{user="hello"} 4261735344 (3.97 GB)
telemt_user_msgs_from_client{user="hello"} 140215
telemt_user_msgs_to_client{user="hello"} 600842
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 6
```