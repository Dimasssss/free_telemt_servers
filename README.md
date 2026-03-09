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

# Server Metrics 2026-03-09 15:53:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 59607.4 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107905
telemt_connections_bad_total 1655
telemt_handshake_timeouts_total 965
telemt_upstream_connect_attempt_total 100803
telemt_upstream_connect_success_total 100764
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 100803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100758
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 2592410614 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 52622753806 (49.01 GB)
telemt_user_msgs_from_client{user="hello"} 2440758
telemt_user_msgs_to_client{user="hello"} 3497595
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 59606.3 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27585
telemt_connections_bad_total 216
telemt_handshake_timeouts_total 331
telemt_upstream_connect_attempt_total 25972
telemt_upstream_connect_success_total 25955
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 25972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25949
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 830480492 (792.01 MB)
telemt_user_octets_to_client{user="hello"} 14892150636 (13.87 GB)
telemt_user_msgs_from_client{user="hello"} 744773
telemt_user_msgs_to_client{user="hello"} 4074273
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 59607.4 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34925
telemt_connections_bad_total 644
telemt_handshake_timeouts_total 1614
telemt_upstream_connect_attempt_total 25900
telemt_upstream_connect_success_total 25900
telemt_upstream_connect_attempts_per_request{bucket="1"} 25900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25894
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 4398773010 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 16355005483 (15.23 GB)
telemt_user_msgs_from_client{user="hello"} 1907385
telemt_user_msgs_to_client{user="hello"} 2203377
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 59601.7 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38956
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 841
telemt_upstream_connect_attempt_total 35812
telemt_upstream_connect_success_total 35720
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 35812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35714
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 1899998692 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 28563218733 (26.60 GB)
telemt_user_msgs_from_client{user="hello"} 1205317
telemt_user_msgs_to_client{user="hello"} 7365695
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 59607.1 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66445
telemt_connections_bad_total 14311
telemt_handshake_timeouts_total 1567
telemt_upstream_connect_attempt_total 47459
telemt_upstream_connect_success_total 47457
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 47459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47451
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 803017868 (765.82 MB)
telemt_user_octets_to_client{user="hello"} 49331375719 (45.94 GB)
telemt_user_msgs_from_client{user="hello"} 1093940
telemt_user_msgs_to_client{user="hello"} 6049880
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 10
```