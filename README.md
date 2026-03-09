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

# Server Metrics 2026-03-09 14:46:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 55628.1 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98814
telemt_connections_bad_total 1649
telemt_handshake_timeouts_total 943
telemt_upstream_connect_attempt_total 91935
telemt_upstream_connect_success_total 91897
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 91935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91891
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 2432275040 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 46487881406 (43.30 GB)
telemt_user_msgs_from_client{user="hello"} 2242545
telemt_user_msgs_to_client{user="hello"} 3094351
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 55626.4 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23832
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 291
telemt_upstream_connect_attempt_total 22513
telemt_upstream_connect_success_total 22496
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 22513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22490
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 806912501 (769.53 MB)
telemt_user_octets_to_client{user="hello"} 12691018595 (11.82 GB)
telemt_user_msgs_from_client{user="hello"} 683403
telemt_user_msgs_to_client{user="hello"} 3424834
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 55627.5 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30214
telemt_connections_bad_total 641
telemt_handshake_timeouts_total 1512
telemt_upstream_connect_attempt_total 21537
telemt_upstream_connect_success_total 21537
telemt_upstream_connect_attempts_per_request{bucket="1"} 21537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21531
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 4334745953 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 12270065320 (11.43 GB)
telemt_user_msgs_from_client{user="hello"} 1822599
telemt_user_msgs_to_client{user="hello"} 1722545
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 55622.0 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32200
telemt_connections_bad_total 184
telemt_handshake_timeouts_total 809
telemt_upstream_connect_attempt_total 29505
telemt_upstream_connect_success_total 29430
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 29505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3555
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29424
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 1805855122 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 20817763152 (19.39 GB)
telemt_user_msgs_from_client{user="hello"} 1039692
telemt_user_msgs_to_client{user="hello"} 5030016
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 55627.4 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58483
telemt_connections_bad_total 13511
telemt_handshake_timeouts_total 1448
telemt_upstream_connect_attempt_total 40698
telemt_upstream_connect_success_total 40696
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 40698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40690
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 709132085 (676.28 MB)
telemt_user_octets_to_client{user="hello"} 39417536353 (36.71 GB)
telemt_user_msgs_from_client{user="hello"} 907397
telemt_user_msgs_to_client{user="hello"} 4884369
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 19
```