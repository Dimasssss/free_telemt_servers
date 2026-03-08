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

# Server Metrics 2026-03-08 20:54:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 49567.1 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110844
telemt_connections_bad_total 5491
telemt_handshake_timeouts_total 1276
telemt_upstream_connect_attempt_total 100335
telemt_upstream_connect_success_total 100299
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 100335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100293
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 2392546053 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 62712640012 (58.41 GB)
telemt_user_msgs_from_client{user="hello"} 2447925
telemt_user_msgs_to_client{user="hello"} 3404734
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 49566.2 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25895
telemt_connections_bad_total 275
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 25043
telemt_upstream_connect_success_total 25036
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 25043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25030
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 831651023 (793.12 MB)
telemt_user_octets_to_client{user="hello"} 22488719998 (20.94 GB)
telemt_user_msgs_from_client{user="hello"} 962289
telemt_user_msgs_to_client{user="hello"} 6084487
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 49566.0 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14972
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13570
telemt_upstream_connect_success_total 13494
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13488
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1414880702 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 5649730979 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 645959
telemt_user_msgs_to_client{user="hello"} 964558
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 49565.9 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19669
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 18827
telemt_upstream_connect_success_total 18788
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 18827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18782
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 1060479107 (1011.35 MB)
telemt_user_octets_to_client{user="hello"} 6402321142 (5.96 GB)
telemt_user_msgs_from_client{user="hello"} 564646
telemt_user_msgs_to_client{user="hello"} 1446670
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 49566.2 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29098
telemt_connections_bad_total 9448
telemt_handshake_timeouts_total 239
telemt_upstream_connect_attempt_total 18946
telemt_upstream_connect_success_total 18939
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18933
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 350191627 (333.97 MB)
telemt_user_octets_to_client{user="hello"} 16454938536 (15.32 GB)
telemt_user_msgs_from_client{user="hello"} 492149
telemt_user_msgs_to_client{user="hello"} 2125163
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```