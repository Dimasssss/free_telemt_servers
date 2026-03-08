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

# Server Metrics 2026-03-08 17:39:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 37859.1 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90018
telemt_connections_bad_total 5045
telemt_handshake_timeouts_total 1238
telemt_upstream_connect_attempt_total 80708
telemt_upstream_connect_success_total 80680
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 80708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80674
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 1997818464 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 48936558848 (45.58 GB)
telemt_user_msgs_from_client{user="hello"} 1937456
telemt_user_msgs_to_client{user="hello"} 2736391
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 37858.2 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19804
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 19150
telemt_upstream_connect_success_total 19146
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 19150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19142
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 698500927 (666.14 MB)
telemt_user_octets_to_client{user="hello"} 18709142683 (17.42 GB)
telemt_user_msgs_from_client{user="hello"} 771331
telemt_user_msgs_to_client{user="hello"} 5105385
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 37858.0 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12154
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 161
telemt_upstream_connect_attempt_total 11307
telemt_upstream_connect_success_total 11231
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11227
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 230247717 (219.58 MB)
telemt_user_octets_to_client{user="hello"} 4001031130 (3.73 GB)
telemt_user_msgs_from_client{user="hello"} 193479
telemt_user_msgs_to_client{user="hello"} 706476
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 37857.7 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15848
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 15134
telemt_upstream_connect_success_total 15101
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 15134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15097
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 1016731440 (969.63 MB)
telemt_user_octets_to_client{user="hello"} 5669762807 (5.28 GB)
telemt_user_msgs_from_client{user="hello"} 524082
telemt_user_msgs_to_client{user="hello"} 1272480
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 37858.0 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21711
telemt_connections_bad_total 6990
telemt_handshake_timeouts_total 228
telemt_upstream_connect_attempt_total 14173
telemt_upstream_connect_success_total 14169
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14165
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 262256245 (250.11 MB)
telemt_user_octets_to_client{user="hello"} 11360549476 (10.58 GB)
telemt_user_msgs_from_client{user="hello"} 349336
telemt_user_msgs_to_client{user="hello"} 1495344
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```