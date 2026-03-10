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

# Server Metrics 2026-03-10 17:18:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10341.0 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42847
telemt_connections_bad_total 496
telemt_handshake_timeouts_total 1345
telemt_upstream_connect_attempt_total 38588
telemt_upstream_connect_success_total 38578
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 38588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38576
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 1177899127 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 27341185851 (25.46 GB)
telemt_user_msgs_from_client{user="hello"} 1092798
telemt_user_msgs_to_client{user="hello"} 1952715
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 10340.3 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14967
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 315
telemt_upstream_connect_attempt_total 13552
telemt_upstream_connect_success_total 13550
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 13552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13548
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 418512029 (399.12 MB)
telemt_user_octets_to_client{user="hello"} 7648658923 (7.12 GB)
telemt_user_msgs_from_client{user="hello"} 406979
telemt_user_msgs_to_client{user="hello"} 2389448
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 10340.1 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23780
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 2027
telemt_upstream_connect_attempt_total 20298
telemt_upstream_connect_success_total 20298
telemt_upstream_connect_attempts_per_request{bucket="1"} 20298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20296
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 181392335 (172.99 MB)
telemt_user_octets_to_client{user="hello"} 9873679169 (9.20 GB)
telemt_user_msgs_from_client{user="hello"} 394945
telemt_user_msgs_to_client{user="hello"} 2127407
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 10338.9 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23241
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 226
telemt_upstream_connect_attempt_total 22139
telemt_upstream_connect_success_total 22076
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 22139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22074
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 320438093 (305.59 MB)
telemt_user_octets_to_client{user="hello"} 22963971555 (21.39 GB)
telemt_user_msgs_from_client{user="hello"} 472157
telemt_user_msgs_to_client{user="hello"} 3995204
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10340.2 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31898
telemt_connections_bad_total 2097
telemt_handshake_timeouts_total 562
telemt_upstream_connect_attempt_total 27939
telemt_upstream_connect_success_total 27702
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 27939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27700
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 1257093275 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 18091287517 (16.85 GB)
telemt_user_msgs_from_client{user="hello"} 869522
telemt_user_msgs_to_client{user="hello"} 2647022
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 22
```