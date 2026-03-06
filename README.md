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

# Server Metrics 2026-03-06 17:39:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 26225.9 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61221
telemt_connections_bad_total 3258
telemt_handshake_timeouts_total 254
telemt_upstream_connect_attempt_total 53713
telemt_upstream_connect_success_total 53700
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 53713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53696
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 2741303025 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 35759879131 (33.30 GB)
telemt_user_msgs_from_client{user="hello"} 1889272
telemt_user_msgs_to_client{user="hello"} 5637156
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 26226.0 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11870
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 102
telemt_upstream_connect_attempt_total 11297
telemt_upstream_connect_success_total 11278
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 11297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11274
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 147104414 (140.29 MB)
telemt_user_octets_to_client{user="hello"} 6142837438 (5.72 GB)
telemt_user_msgs_from_client{user="hello"} 237702
telemt_user_msgs_to_client{user="hello"} 1896733
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 26225.0 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9418
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 9080
telemt_upstream_connect_success_total 9078
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9076
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 130234587 (124.20 MB)
telemt_user_octets_to_client{user="hello"} 5366937109 (5.00 GB)
telemt_user_msgs_from_client{user="hello"} 205094
telemt_user_msgs_to_client{user="hello"} 1269443
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 26224.3 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13290
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 12373
telemt_upstream_connect_success_total 12332
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 12373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 832
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12328
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 176920309 (168.72 MB)
telemt_user_octets_to_client{user="hello"} 5247609775 (4.89 GB)
telemt_user_msgs_from_client{user="hello"} 223300
telemt_user_msgs_to_client{user="hello"} 1246489
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 26225.6 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18777
telemt_connections_bad_total 6275
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 11600
telemt_upstream_connect_success_total 11600
telemt_upstream_connect_attempts_per_request{bucket="1"} 11600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11596
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 261705721 (249.58 MB)
telemt_user_octets_to_client{user="hello"} 24333548466 (22.66 GB)
telemt_user_msgs_from_client{user="hello"} 450040
telemt_user_msgs_to_client{user="hello"} 4421591
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```