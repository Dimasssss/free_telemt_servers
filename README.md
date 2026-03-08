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

# Server Metrics 2026-03-08 20:44:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 48950.9 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109849
telemt_connections_bad_total 5128
telemt_handshake_timeouts_total 1276
telemt_upstream_connect_attempt_total 99716
telemt_upstream_connect_success_total 99680
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 99716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99674
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 2329898852 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 62247921514 (57.97 GB)
telemt_user_msgs_from_client{user="hello"} 2409510
telemt_user_msgs_to_client{user="hello"} 3378466
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 48949.9 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25598
telemt_connections_bad_total 274
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 24755
telemt_upstream_connect_success_total 24748
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 24755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24742
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 830368034 (791.90 MB)
telemt_user_octets_to_client{user="hello"} 22417655632 (20.88 GB)
telemt_user_msgs_from_client{user="hello"} 958745
telemt_user_msgs_to_client{user="hello"} 6063898
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 48949.8 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14883
telemt_connections_bad_total 228
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13483
telemt_upstream_connect_success_total 13407
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1013
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13401
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 1414314269 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 5608608559 (5.22 GB)
telemt_user_msgs_from_client{user="hello"} 644469
telemt_user_msgs_to_client{user="hello"} 955430
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 48949.7 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19488
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 18661
telemt_upstream_connect_success_total 18623
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 18661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18617
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 1060055317 (1010.95 MB)
telemt_user_octets_to_client{user="hello"} 6389656318 (5.95 GB)
telemt_user_msgs_from_client{user="hello"} 563569
telemt_user_msgs_to_client{user="hello"} 1442573
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 48949.9 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28791
telemt_connections_bad_total 9336
telemt_handshake_timeouts_total 238
telemt_upstream_connect_attempt_total 18754
telemt_upstream_connect_success_total 18747
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18741
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 345477487 (329.47 MB)
telemt_user_octets_to_client{user="hello"} 15603246584 (14.53 GB)
telemt_user_msgs_from_client{user="hello"} 481240
telemt_user_msgs_to_client{user="hello"} 2050245
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```