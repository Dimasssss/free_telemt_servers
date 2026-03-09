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

# Server Metrics 2026-03-09 01:15:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 6947.6 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5848
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 5244
telemt_upstream_connect_success_total 5242
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5240
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 60090184 (57.31 MB)
telemt_user_octets_to_client{user="hello"} 6822397800 (6.35 GB)
telemt_user_msgs_from_client{user="hello"} 143191
telemt_user_msgs_to_client{user="hello"} 243276
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 6945.8 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 399
telemt_upstream_connect_success_total 399
telemt_upstream_connect_attempts_per_request{bucket="1"} 399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 397
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 6347997 (6.05 MB)
telemt_user_octets_to_client{user="hello"} 421340064 (401.82 MB)
telemt_user_msgs_from_client{user="hello"} 17714
telemt_user_msgs_to_client{user="hello"} 81003
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 6946.2 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 465
telemt_upstream_connect_success_total 465
telemt_upstream_connect_attempts_per_request{bucket="1"} 465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 463
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 29559199 (28.19 MB)
telemt_user_octets_to_client{user="hello"} 75897753 (72.38 MB)
telemt_user_msgs_from_client{user="hello"} 15739
telemt_user_msgs_to_client{user="hello"} 24508
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 6941.1 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 827
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 814
telemt_upstream_connect_success_total 814
telemt_upstream_connect_attempts_per_request{bucket="1"} 814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 812
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 6530189 (6.23 MB)
telemt_user_octets_to_client{user="hello"} 356898053 (340.36 MB)
telemt_user_msgs_from_client{user="hello"} 16816
telemt_user_msgs_to_client{user="hello"} 96565
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 6946.6 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2041
telemt_connections_bad_total 1248
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 778
telemt_upstream_connect_success_total 778
telemt_upstream_connect_attempts_per_request{bucket="1"} 778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 776
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 6822450 (6.51 MB)
telemt_user_octets_to_client{user="hello"} 1284869833 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 19039
telemt_user_msgs_to_client{user="hello"} 158686
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```