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

# Server Metrics 2026-03-08 03:57:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 40346.8 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57193
telemt_connections_bad_total 5991
telemt_handshake_timeouts_total 407
telemt_upstream_connect_attempt_total 48369
telemt_upstream_connect_success_total 48362
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 48369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48358
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 2370848124 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 32735154628 (30.49 GB)
telemt_user_msgs_from_client{user="hello"} 1520095
telemt_user_msgs_to_client{user="hello"} 5115714
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 40346.2 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7949
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 7447
telemt_upstream_connect_success_total 7439
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7433
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 180309174 (171.96 MB)
telemt_user_octets_to_client{user="hello"} 10722214482 (9.99 GB)
telemt_user_msgs_from_client{user="hello"} 340020
telemt_user_msgs_to_client{user="hello"} 2504655
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 40345.8 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4870
telemt_connections_bad_total 250
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 4534
telemt_upstream_connect_success_total 4534
telemt_upstream_connect_attempts_per_request{bucket="1"} 4534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4530
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 123025146 (117.33 MB)
telemt_user_octets_to_client{user="hello"} 14242410403 (13.26 GB)
telemt_user_msgs_from_client{user="hello"} 222865
telemt_user_msgs_to_client{user="hello"} 3010621
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 40174.2 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13470
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 12919
telemt_upstream_connect_success_total 12893
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 12919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2042
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12889
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 347988311 (331.87 MB)
telemt_user_octets_to_client{user="hello"} 11380577214 (10.60 GB)
telemt_user_msgs_from_client{user="hello"} 371508
telemt_user_msgs_to_client{user="hello"} 3301327
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 40346.1 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15996
telemt_connections_bad_total 7413
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 8335
telemt_upstream_connect_success_total 8327
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 8335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8323
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 1621852490 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 7776768212 (7.24 GB)
telemt_user_msgs_from_client{user="hello"} 807942
telemt_user_msgs_to_client{user="hello"} 1747954
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```