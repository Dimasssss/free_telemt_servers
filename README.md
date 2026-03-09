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

# Server Metrics 2026-03-09 16:44:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 62670.8 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115771
telemt_connections_bad_total 1656
telemt_handshake_timeouts_total 978
telemt_upstream_connect_attempt_total 108408
telemt_upstream_connect_success_total 108369
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 108408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108363
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 2932764049 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 56549439387 (52.67 GB)
telemt_user_msgs_from_client{user="hello"} 2694247
telemt_user_msgs_to_client{user="hello"} 3774442
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 62669.5 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30898
telemt_connections_bad_total 222
telemt_handshake_timeouts_total 355
telemt_upstream_connect_attempt_total 29149
telemt_upstream_connect_success_total 29131
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 29149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29125
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 1002201681 (955.77 MB)
telemt_user_octets_to_client{user="hello"} 15795951061 (14.71 GB)
telemt_user_msgs_from_client{user="hello"} 847523
telemt_user_msgs_to_client{user="hello"} 4367462
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 62670.1 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38881
telemt_connections_bad_total 656
telemt_handshake_timeouts_total 1727
telemt_upstream_connect_attempt_total 29502
telemt_upstream_connect_success_total 29502
telemt_upstream_connect_attempts_per_request{bucket="1"} 29502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29496
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 4459262853 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 18383079069 (17.12 GB)
telemt_user_msgs_from_client{user="hello"} 1978405
telemt_user_msgs_to_client{user="hello"} 2418429
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 62664.9 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44818
telemt_connections_bad_total 198
telemt_handshake_timeouts_total 877
telemt_upstream_connect_attempt_total 40970
telemt_upstream_connect_success_total 40871
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 40970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40863
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 1952721775 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 31159647211 (29.02 GB)
telemt_user_msgs_from_client{user="hello"} 1281407
telemt_user_msgs_to_client{user="hello"} 7878769
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 62670.5 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73135
telemt_connections_bad_total 15198
telemt_handshake_timeouts_total 1660
telemt_upstream_connect_attempt_total 52901
telemt_upstream_connect_success_total 52899
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 52901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52893
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 892215703 (850.88 MB)
telemt_user_octets_to_client{user="hello"} 55250808876 (51.46 GB)
telemt_user_msgs_from_client{user="hello"} 1224463
telemt_user_msgs_to_client{user="hello"} 6745570
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 20
```