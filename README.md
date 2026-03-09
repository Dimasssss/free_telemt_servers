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

# Server Metrics 2026-03-09 06:16:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 24989.1 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24857
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 563
telemt_upstream_connect_attempt_total 22857
telemt_upstream_connect_success_total 22849
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 22856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22845
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 212434208 (202.59 MB)
telemt_user_octets_to_client{user="hello"} 13028150110 (12.13 GB)
telemt_user_msgs_from_client{user="hello"} 429508
telemt_user_msgs_to_client{user="hello"} 649394
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 24987.2 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3287
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 3090
telemt_upstream_connect_success_total 3090
telemt_upstream_connect_attempts_per_request{bucket="1"} 3090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 220
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3086
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 48006667 (45.78 MB)
telemt_user_octets_to_client{user="hello"} 3002279801 (2.80 GB)
telemt_user_msgs_from_client{user="hello"} 104378
telemt_user_msgs_to_client{user="hello"} 573528
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 24987.8 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1755
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1633
telemt_upstream_connect_success_total 1633
telemt_upstream_connect_attempts_per_request{bucket="1"} 1633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1629
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 907418828 (865.38 MB)
telemt_user_octets_to_client{user="hello"} 1120768575 (1.04 GB)
telemt_user_msgs_from_client{user="hello"} 348483
telemt_user_msgs_to_client{user="hello"} 222755
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 24982.5 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3885
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 3311
telemt_upstream_connect_success_total 3309
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3305
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 127906507 (121.98 MB)
telemt_user_octets_to_client{user="hello"} 2689100251 (2.50 GB)
telemt_user_msgs_from_client{user="hello"} 77107
telemt_user_msgs_to_client{user="hello"} 583405
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 24988.0 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8799
telemt_connections_bad_total 4975
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 3610
telemt_upstream_connect_success_total 3610
telemt_upstream_connect_attempts_per_request{bucket="1"} 3610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3606
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 48022162 (45.80 MB)
telemt_user_octets_to_client{user="hello"} 2760766248 (2.57 GB)
telemt_user_msgs_from_client{user="hello"} 76980
telemt_user_msgs_to_client{user="hello"} 371734
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```