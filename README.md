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

# Server Metrics 2026-03-07 01:46:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 27515.8 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34161
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 31900
telemt_upstream_connect_success_total 31892
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31888
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 2085836414 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 33160590372 (30.88 GB)
telemt_user_msgs_from_client{user="hello"} 1390145
telemt_user_msgs_to_client{user="hello"} 5233253
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 27514.6 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6730
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 6297
telemt_upstream_connect_success_total 6294
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6290
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 215526264 (205.54 MB)
telemt_user_octets_to_client{user="hello"} 3898058545 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 202459
telemt_user_msgs_to_client{user="hello"} 1090765
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 27514.6 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3250
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 2958
telemt_upstream_connect_success_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 2958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 267
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2954
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 65415858 (62.39 MB)
telemt_user_octets_to_client{user="hello"} 1871935825 (1.74 GB)
telemt_user_msgs_from_client{user="hello"} 64909
telemt_user_msgs_to_client{user="hello"} 397644
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 27514.7 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4532
telemt_connections_bad_total 130
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4330
telemt_upstream_connect_success_total 4323
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4319
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 101061293 (96.38 MB)
telemt_user_octets_to_client{user="hello"} 1375091843 (1.28 GB)
telemt_user_msgs_from_client{user="hello"} 86745
telemt_user_msgs_to_client{user="hello"} 355772
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 27515.0 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12943
telemt_connections_bad_total 5898
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6883
telemt_upstream_connect_success_total 6882
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6878
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 229845835 (219.20 MB)
telemt_user_octets_to_client{user="hello"} 7750632876 (7.22 GB)
telemt_user_msgs_from_client{user="hello"} 220007
telemt_user_msgs_to_client{user="hello"} 1588065
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 2
```