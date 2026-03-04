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

# Server Metrics 2026-03-04 23:33:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 43584.2 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66504
telemt_connections_bad_total 126
telemt_handshake_timeouts_total 1552
telemt_upstream_connect_attempt_total 59980
telemt_upstream_connect_success_total 59965
telemt_upstream_connect_attempts_per_request{bucket="1"} 59950
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59961
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 2326156173 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 46863249634 (43.64 GB)
telemt_user_msgs_from_client{user="hello"} 1978799
telemt_user_msgs_to_client{user="hello"} 7463807
telemt_user_unique_ips_current{user="hello"} 13
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 43586.9 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12199
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 11367
telemt_upstream_connect_success_total 11365
telemt_upstream_connect_attempts_per_request{bucket="1"} 11363
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11361
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 1055372238 (1006.48 MB)
telemt_user_octets_to_client{user="hello"} 11045179525 (10.29 GB)
telemt_user_msgs_from_client{user="hello"} 647549
telemt_user_msgs_to_client{user="hello"} 3725446
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 43585.1 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11179
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 7290
telemt_upstream_connect_success_total 7290
telemt_upstream_connect_attempts_per_request{bucket="1"} 7290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7286
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 308000001 (293.73 MB)
telemt_user_octets_to_client{user="hello"} 5253127159 (4.89 GB)
telemt_user_msgs_from_client{user="hello"} 268331
telemt_user_msgs_to_client{user="hello"} 1133181
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 43583.1 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14977
telemt_connections_bad_total 681
telemt_handshake_timeouts_total 74
telemt_upstream_connect_attempt_total 13075
telemt_upstream_connect_success_total 13070
telemt_upstream_connect_attempts_per_request{bucket="1"} 13065
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1067
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13066
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 391913552 (373.76 MB)
telemt_user_octets_to_client{user="hello"} 5573131702 (5.19 GB)
telemt_user_msgs_from_client{user="hello"} 301902
telemt_user_msgs_to_client{user="hello"} 1388663
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 43584.8 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17351
telemt_connections_bad_total 7833
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9162
telemt_upstream_connect_success_total 9158
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9156
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9152
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 512676112 (488.93 MB)
telemt_user_octets_to_client{user="hello"} 21162697587 (19.71 GB)
telemt_user_msgs_from_client{user="hello"} 542192
telemt_user_msgs_to_client{user="hello"} 4003027
telemt_user_unique_ips_current{user="hello"} 1
```