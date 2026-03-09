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

# Server Metrics 2026-03-09 04:29:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 18568.0 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16089
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 417
telemt_upstream_connect_attempt_total 14450
telemt_upstream_connect_success_total 14445
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14443
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 145058350 (138.34 MB)
telemt_user_octets_to_client{user="hello"} 9309062924 (8.67 GB)
telemt_user_msgs_from_client{user="hello"} 280320
telemt_user_msgs_to_client{user="hello"} 423881
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 18566.2 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1736
telemt_connections_bad_total 62
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 1590
telemt_upstream_connect_success_total 1590
telemt_upstream_connect_attempts_per_request{bucket="1"} 1590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1588
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 29799440 (28.42 MB)
telemt_user_octets_to_client{user="hello"} 1378162602 (1.28 GB)
telemt_user_msgs_from_client{user="hello"} 60071
telemt_user_msgs_to_client{user="hello"} 269401
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 18566.8 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1229
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1129
telemt_upstream_connect_success_total 1129
telemt_upstream_connect_attempts_per_request{bucket="1"} 1129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1127
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 423909420 (404.27 MB)
telemt_user_octets_to_client{user="hello"} 955330011 (911.07 MB)
telemt_user_msgs_from_client{user="hello"} 171956
telemt_user_msgs_to_client{user="hello"} 183752
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 18561.6 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2448
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 1959
telemt_upstream_connect_success_total 1959
telemt_upstream_connect_attempts_per_request{bucket="1"} 1959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1957
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 15783738 (15.05 MB)
telemt_user_octets_to_client{user="hello"} 1251437339 (1.17 GB)
telemt_user_msgs_from_client{user="hello"} 40785
telemt_user_msgs_to_client{user="hello"} 310623
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 18567.2 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5112
telemt_connections_bad_total 3376
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1703
telemt_upstream_connect_success_total 1703
telemt_upstream_connect_attempts_per_request{bucket="1"} 1703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 206
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1701
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 12683147 (12.10 MB)
telemt_user_octets_to_client{user="hello"} 1660015667 (1.55 GB)
telemt_user_msgs_from_client{user="hello"} 32695
telemt_user_msgs_to_client{user="hello"} 207767
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```