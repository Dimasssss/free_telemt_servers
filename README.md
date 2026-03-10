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

# Server Metrics 2026-03-10 18:14:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13713.7 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54992
telemt_connections_bad_total 1506
telemt_handshake_timeouts_total 1439
telemt_upstream_connect_attempt_total 49271
telemt_upstream_connect_success_total 49259
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 49270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49257
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 1444116922 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 37108124922 (34.56 GB)
telemt_user_msgs_from_client{user="hello"} 1380082
telemt_user_msgs_to_client{user="hello"} 2776793
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 13712.8 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19882
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 344
telemt_upstream_connect_attempt_total 18182
telemt_upstream_connect_success_total 18178
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 18182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18176
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 548689080 (523.27 MB)
telemt_user_octets_to_client{user="hello"} 9519236497 (8.87 GB)
telemt_user_msgs_from_client{user="hello"} 537530
telemt_user_msgs_to_client{user="hello"} 3002546
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 13712.5 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30731
telemt_connections_bad_total 90
telemt_handshake_timeouts_total 2699
telemt_upstream_connect_attempt_total 26079
telemt_upstream_connect_success_total 26079
telemt_upstream_connect_attempts_per_request{bucket="1"} 26079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26077
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 341215528 (325.41 MB)
telemt_user_octets_to_client{user="hello"} 24759414965 (23.06 GB)
telemt_user_msgs_from_client{user="hello"} 551052
telemt_user_msgs_to_client{user="hello"} 3860073
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 13711.4 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30123
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 28788
telemt_upstream_connect_success_total 28701
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 28788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28699
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 389279118 (371.25 MB)
telemt_user_octets_to_client{user="hello"} 26511472631 (24.69 GB)
telemt_user_msgs_from_client{user="hello"} 579673
telemt_user_msgs_to_client{user="hello"} 4631911
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13712.8 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42534
telemt_connections_bad_total 3892
telemt_handshake_timeouts_total 829
telemt_upstream_connect_attempt_total 36191
telemt_upstream_connect_success_total 35954
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 36191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35952
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 1356706064 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 22881427381 (21.31 GB)
telemt_user_msgs_from_client{user="hello"} 1059967
telemt_user_msgs_to_client{user="hello"} 3428569
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 24
```