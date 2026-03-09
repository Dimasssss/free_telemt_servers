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

# Server Metrics 2026-03-09 06:01:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 24071.3 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23526
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 560
telemt_upstream_connect_attempt_total 21555
telemt_upstream_connect_success_total 21548
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 21555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21546
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 200150113 (190.88 MB)
telemt_user_octets_to_client{user="hello"} 12189224117 (11.35 GB)
telemt_user_msgs_from_client{user="hello"} 400508
telemt_user_msgs_to_client{user="hello"} 598139
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 24069.7 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3002
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 2818
telemt_upstream_connect_success_total 2818
telemt_upstream_connect_attempts_per_request{bucket="1"} 2818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2814
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 46032979 (43.90 MB)
telemt_user_octets_to_client{user="hello"} 2921744571 (2.72 GB)
telemt_user_msgs_from_client{user="hello"} 99745
telemt_user_msgs_to_client{user="hello"} 551998
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 24070.1 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1700
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1580
telemt_upstream_connect_success_total 1580
telemt_upstream_connect_attempts_per_request{bucket="1"} 1580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1576
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 907179634 (865.15 MB)
telemt_user_octets_to_client{user="hello"} 1113163158 (1.04 GB)
telemt_user_msgs_from_client{user="hello"} 347801
telemt_user_msgs_to_client{user="hello"} 220214
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 24064.9 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3499
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 2946
telemt_upstream_connect_success_total 2944
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 602
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2940
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 124064243 (118.32 MB)
telemt_user_octets_to_client{user="hello"} 2178692494 (2.03 GB)
telemt_user_msgs_from_client{user="hello"} 68033
telemt_user_msgs_to_client{user="hello"} 474804
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 24070.4 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8298
telemt_connections_bad_total 4811
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 3279
telemt_upstream_connect_success_total 3279
telemt_upstream_connect_attempts_per_request{bucket="1"} 3279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3277
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 41977522 (40.03 MB)
telemt_user_octets_to_client{user="hello"} 2611715379 (2.43 GB)
telemt_user_msgs_from_client{user="hello"} 68400
telemt_user_msgs_to_client{user="hello"} 338048
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```