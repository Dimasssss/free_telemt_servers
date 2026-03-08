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

# Server Metrics 2026-03-08 10:12:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 11017.4 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22886
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 148
telemt_upstream_connect_attempt_total 19274
telemt_upstream_connect_success_total 19260
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 19274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19258
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 675863484 (644.55 MB)
telemt_user_octets_to_client{user="hello"} 11622610578 (10.82 GB)
telemt_user_msgs_from_client{user="hello"} 550657
telemt_user_msgs_to_client{user="hello"} 628163
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 11016.3 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5352
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 5028
telemt_upstream_connect_success_total 5028
telemt_upstream_connect_attempts_per_request{bucket="1"} 5028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5026
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 72625696 (69.26 MB)
telemt_user_octets_to_client{user="hello"} 3489313128 (3.25 GB)
telemt_user_msgs_from_client{user="hello"} 127971
telemt_user_msgs_to_client{user="hello"} 912090
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 11016.0 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4028
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3945
telemt_upstream_connect_success_total 3945
telemt_upstream_connect_attempts_per_request{bucket="1"} 3945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3943
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 35782878 (34.13 MB)
telemt_user_octets_to_client{user="hello"} 1206740353 (1.12 GB)
telemt_user_msgs_from_client{user="hello"} 41846
telemt_user_msgs_to_client{user="hello"} 197642
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 11015.9 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4989
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 4783
telemt_upstream_connect_success_total 4776
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4774
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 163409622 (155.84 MB)
telemt_user_octets_to_client{user="hello"} 2242336256 (2.09 GB)
telemt_user_msgs_from_client{user="hello"} 98628
telemt_user_msgs_to_client{user="hello"} 479694
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 11016.2 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6608
telemt_connections_bad_total 2072
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 4463
telemt_upstream_connect_success_total 4463
telemt_upstream_connect_attempts_per_request{bucket="1"} 4463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4461
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 55159096 (52.60 MB)
telemt_user_octets_to_client{user="hello"} 3747199418 (3.49 GB)
telemt_user_msgs_from_client{user="hello"} 104851
telemt_user_msgs_to_client{user="hello"} 483773
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```