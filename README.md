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

# Server Metrics 2026-03-08 21:20:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 51106.1 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112570
telemt_connections_bad_total 5494
telemt_handshake_timeouts_total 1279
telemt_upstream_connect_attempt_total 102034
telemt_upstream_connect_success_total 101998
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 102034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101992
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 2466255666 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 64042304222 (59.64 GB)
telemt_user_msgs_from_client{user="hello"} 2513417
telemt_user_msgs_to_client{user="hello"} 3465744
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 51105.6 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26547
telemt_connections_bad_total 284
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 25667
telemt_upstream_connect_success_total 25660
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 25667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25654
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 836995912 (798.22 MB)
telemt_user_octets_to_client{user="hello"} 22619223396 (21.07 GB)
telemt_user_msgs_from_client{user="hello"} 972618
telemt_user_msgs_to_client{user="hello"} 6133284
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 51105.0 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15117
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13713
telemt_upstream_connect_success_total 13637
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13631
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 1553770515 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 5651786523 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 695419
telemt_user_msgs_to_client{user="hello"} 966888
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 51105.0 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20373
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 19522
telemt_upstream_connect_success_total 19482
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 19522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19476
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 1065459074 (1016.10 MB)
telemt_user_octets_to_client{user="hello"} 6471611761 (6.03 GB)
telemt_user_msgs_from_client{user="hello"} 569910
telemt_user_msgs_to_client{user="hello"} 1467166
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 51105.3 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29942
telemt_connections_bad_total 9723
telemt_handshake_timeouts_total 239
telemt_upstream_connect_attempt_total 19502
telemt_upstream_connect_success_total 19495
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19489
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 362636645 (345.84 MB)
telemt_user_octets_to_client{user="hello"} 16788931141 (15.64 GB)
telemt_user_msgs_from_client{user="hello"} 509799
telemt_user_msgs_to_client{user="hello"} 2169427
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```