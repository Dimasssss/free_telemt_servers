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

# Server Metrics 2026-03-08 08:39:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 5471.8 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11511
telemt_connections_bad_total 1782
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 9211
telemt_upstream_connect_success_total 9206
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9204
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 256052636 (244.19 MB)
telemt_user_octets_to_client{user="hello"} 5906078493 (5.50 GB)
telemt_user_msgs_from_client{user="hello"} 219673
telemt_user_msgs_to_client{user="hello"} 291740
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 5470.9 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2461
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2337
telemt_upstream_connect_success_total 2337
telemt_upstream_connect_attempts_per_request{bucket="1"} 2337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2335
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 31767659 (30.30 MB)
telemt_user_octets_to_client{user="hello"} 1695042022 (1.58 GB)
telemt_user_msgs_from_client{user="hello"} 57181
telemt_user_msgs_to_client{user="hello"} 412686
telemt_user_unique_ips_current{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 5470.5 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2157
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2109
telemt_upstream_connect_success_total 2109
telemt_upstream_connect_attempts_per_request{bucket="1"} 2109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2107
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 25336951 (24.16 MB)
telemt_user_octets_to_client{user="hello"} 462369278 (440.95 MB)
telemt_user_msgs_from_client{user="hello"} 19859
telemt_user_msgs_to_client{user="hello"} 84387
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 5470.4 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2055
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 1962
telemt_upstream_connect_success_total 1958
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1956
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 45725417 (43.61 MB)
telemt_user_octets_to_client{user="hello"} 496335449 (473.34 MB)
telemt_user_msgs_from_client{user="hello"} 30494
telemt_user_msgs_to_client{user="hello"} 143015
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 5470.8 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3480
telemt_connections_bad_total 981
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2468
telemt_upstream_connect_success_total 2468
telemt_upstream_connect_attempts_per_request{bucket="1"} 2468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2466
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 25605168 (24.42 MB)
telemt_user_octets_to_client{user="hello"} 942957616 (899.27 MB)
telemt_user_msgs_from_client{user="hello"} 41390
telemt_user_msgs_to_client{user="hello"} 145364
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 6
```