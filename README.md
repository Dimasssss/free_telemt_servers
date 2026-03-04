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

# Server Metrics 2026-03-04 23:53:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 44815.7 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67217
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1557
telemt_upstream_connect_attempt_total 60634
telemt_upstream_connect_success_total 60619
telemt_upstream_connect_attempts_per_request{bucket="1"} 60604
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60613
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 2335963429 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 46989247389 (43.76 GB)
telemt_user_msgs_from_client{user="hello"} 1990828
telemt_user_msgs_to_client{user="hello"} 7490730
telemt_user_unique_ips_current{user="hello"} 13
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 44817.8 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12620
telemt_connections_bad_total 250
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 11407
telemt_upstream_connect_success_total 11405
telemt_upstream_connect_attempts_per_request{bucket="1"} 11403
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11401
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 1056272632 (1007.34 MB)
telemt_user_octets_to_client{user="hello"} 11090873053 (10.33 GB)
telemt_user_msgs_from_client{user="hello"} 649520
telemt_user_msgs_to_client{user="hello"} 3736395
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 44816.4 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11206
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 7317
telemt_upstream_connect_success_total 7317
telemt_upstream_connect_attempts_per_request{bucket="1"} 7317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7311
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 308092596 (293.82 MB)
telemt_user_octets_to_client{user="hello"} 5253888327 (4.89 GB)
telemt_user_msgs_from_client{user="hello"} 268623
telemt_user_msgs_to_client{user="hello"} 1133700
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 44813.9 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15060
telemt_connections_bad_total 686
telemt_handshake_timeouts_total 75
telemt_upstream_connect_attempt_total 13136
telemt_upstream_connect_success_total 13131
telemt_upstream_connect_attempts_per_request{bucket="1"} 13126
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1076
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13125
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 392075750 (373.91 MB)
telemt_user_octets_to_client{user="hello"} 5578768065 (5.20 GB)
telemt_user_msgs_from_client{user="hello"} 302265
telemt_user_msgs_to_client{user="hello"} 1390139
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 44816.0 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17623
telemt_connections_bad_total 8055
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9211
telemt_upstream_connect_success_total 9207
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9205
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9201
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 512843767 (489.09 MB)
telemt_user_octets_to_client{user="hello"} 21170679389 (19.72 GB)
telemt_user_msgs_from_client{user="hello"} 542625
telemt_user_msgs_to_client{user="hello"} 4004998
```