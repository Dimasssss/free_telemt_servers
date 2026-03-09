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

# Server Metrics 2026-03-09 00:45:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 5113.1 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4332
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 170
telemt_upstream_connect_attempt_total 3813
telemt_upstream_connect_success_total 3812
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3810
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 45584178 (43.47 MB)
telemt_user_octets_to_client{user="hello"} 6052473057 (5.64 GB)
telemt_user_msgs_from_client{user="hello"} 112307
telemt_user_msgs_to_client{user="hello"} 197233
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 5111.0 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 308
telemt_upstream_connect_success_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 306
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 1952740 (1.86 MB)
telemt_user_octets_to_client{user="hello"} 46779599 (44.61 MB)
telemt_user_msgs_from_client{user="hello"} 5626
telemt_user_msgs_to_client{user="hello"} 15091
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 5111.6 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 327
telemt_upstream_connect_success_total 327
telemt_upstream_connect_attempts_per_request{bucket="1"} 327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 325
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 16159212 (15.41 MB)
telemt_user_octets_to_client{user="hello"} 47781863 (45.57 MB)
telemt_user_msgs_from_client{user="hello"} 9477
telemt_user_msgs_to_client{user="hello"} 13099
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 5106.3 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 606
telemt_upstream_connect_success_total 606
telemt_upstream_connect_attempts_per_request{bucket="1"} 606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 95
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 604
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 3917348 (3.74 MB)
telemt_user_octets_to_client{user="hello"} 182783743 (174.32 MB)
telemt_user_msgs_from_client{user="hello"} 9703
telemt_user_msgs_to_client{user="hello"} 36670
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 5111.9 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1576
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 647
telemt_upstream_connect_success_total 647
telemt_upstream_connect_attempts_per_request{bucket="1"} 647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 645
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 6353578 (6.06 MB)
telemt_user_octets_to_client{user="hello"} 1264171728 (1.18 GB)
telemt_user_msgs_from_client{user="hello"} 17888
telemt_user_msgs_to_client{user="hello"} 153837
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```