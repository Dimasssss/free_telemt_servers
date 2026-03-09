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

# Server Metrics 2026-03-09 05:40:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 22847.9 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21882
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 19954
telemt_upstream_connect_success_total 19948
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19946
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 186530890 (177.89 MB)
telemt_user_octets_to_client{user="hello"} 11236683857 (10.46 GB)
telemt_user_msgs_from_client{user="hello"} 368156
telemt_user_msgs_to_client{user="hello"} 545440
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 22846.6 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2891
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 2707
telemt_upstream_connect_success_total 2707
telemt_upstream_connect_attempts_per_request{bucket="1"} 2707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2703
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 44087052 (42.04 MB)
telemt_user_octets_to_client{user="hello"} 2746600800 (2.56 GB)
telemt_user_msgs_from_client{user="hello"} 95290
telemt_user_msgs_to_client{user="hello"} 521623
telemt_user_unique_ips_current{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 22847.0 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1594
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1488
telemt_upstream_connect_success_total 1488
telemt_upstream_connect_attempts_per_request{bucket="1"} 1488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1484
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 906990753 (864.97 MB)
telemt_user_octets_to_client{user="hello"} 1109295690 (1.03 GB)
telemt_user_msgs_from_client{user="hello"} 347236
telemt_user_msgs_to_client{user="hello"} 218485
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 22841.8 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3089
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 2556
telemt_upstream_connect_success_total 2556
telemt_upstream_connect_attempts_per_request{bucket="1"} 2556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 557
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2552
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 20624961 (19.67 MB)
telemt_user_octets_to_client{user="hello"} 1809037389 (1.68 GB)
telemt_user_msgs_from_client{user="hello"} 52518
telemt_user_msgs_to_client{user="hello"} 414328
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 22847.3 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7614
telemt_connections_bad_total 4594
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 2831
telemt_upstream_connect_success_total 2831
telemt_upstream_connect_attempts_per_request{bucket="1"} 2831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2829
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 29506286 (28.14 MB)
telemt_user_octets_to_client{user="hello"} 2475625245 (2.31 GB)
telemt_user_msgs_from_client{user="hello"} 57659
telemt_user_msgs_to_client{user="hello"} 304205
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 6
```