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

# Server Metrics 2026-03-08 05:14:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 44965.4 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64487
telemt_connections_bad_total 6038
telemt_handshake_timeouts_total 469
telemt_upstream_connect_attempt_total 54693
telemt_upstream_connect_success_total 54684
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 54693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54678
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 2461221363 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 35859561412 (33.40 GB)
telemt_user_msgs_from_client{user="hello"} 1654886
telemt_user_msgs_to_client{user="hello"} 5615100
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 44964.8 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8931
telemt_connections_bad_total 370
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 8408
telemt_upstream_connect_success_total 8400
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 8408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8394
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 215383784 (205.41 MB)
telemt_user_octets_to_client{user="hello"} 12291019818 (11.45 GB)
telemt_user_msgs_from_client{user="hello"} 396782
telemt_user_msgs_to_client{user="hello"} 2879691
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 44964.4 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5509
telemt_connections_bad_total 286
telemt_handshake_timeouts_total 207
telemt_upstream_connect_attempt_total 4930
telemt_upstream_connect_success_total 4930
telemt_upstream_connect_attempts_per_request{bucket="1"} 4930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4926
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 127976097 (122.05 MB)
telemt_user_octets_to_client{user="hello"} 14554011666 (13.55 GB)
telemt_user_msgs_from_client{user="hello"} 232433
telemt_user_msgs_to_client{user="hello"} 3097038
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 44792.6 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14362
telemt_connections_bad_total 228
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 13774
telemt_upstream_connect_success_total 13748
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 13774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2168
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13744
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 358298402 (341.70 MB)
telemt_user_octets_to_client{user="hello"} 12843480276 (11.96 GB)
telemt_user_msgs_from_client{user="hello"} 398004
telemt_user_msgs_to_client{user="hello"} 3611358
telemt_user_unique_ips_current{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 44964.5 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18124
telemt_connections_bad_total 8346
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 9513
telemt_upstream_connect_success_total 9505
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 9513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9501
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 1641271855 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 10018498625 (9.33 GB)
telemt_user_msgs_from_client{user="hello"} 855319
telemt_user_msgs_to_client{user="hello"} 2163604
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 4
```