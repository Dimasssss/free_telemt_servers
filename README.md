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

# Server Metrics 2026-03-06 14:44:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 15752.5 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38412
telemt_connections_bad_total 3071
telemt_handshake_timeouts_total 161
telemt_upstream_connect_attempt_total 31909
telemt_upstream_connect_success_total 31901
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31899
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 1934367918 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 21138219495 (19.69 GB)
telemt_user_msgs_from_client{user="hello"} 1229700
telemt_user_msgs_to_client{user="hello"} 3323419
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 15752.0 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6765
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 87
telemt_upstream_connect_attempt_total 6376
telemt_upstream_connect_success_total 6374
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6372
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 69329225 (66.12 MB)
telemt_user_octets_to_client{user="hello"} 2693431801 (2.51 GB)
telemt_user_msgs_from_client{user="hello"} 128208
telemt_user_msgs_to_client{user="hello"} 833445
telemt_user_unique_ips_current{user="hello"} 7
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 15751.1 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6156
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 5953
telemt_upstream_connect_success_total 5953
telemt_upstream_connect_attempts_per_request{bucket="1"} 5953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5951
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 92056739 (87.79 MB)
telemt_user_octets_to_client{user="hello"} 3810368638 (3.55 GB)
telemt_user_msgs_from_client{user="hello"} 133665
telemt_user_msgs_to_client{user="hello"} 893404
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 15750.5 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8769
telemt_connections_bad_total 102
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 8168
telemt_upstream_connect_success_total 8143
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 8168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 451
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8141
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 129388951 (123.39 MB)
telemt_user_octets_to_client{user="hello"} 2555503349 (2.38 GB)
telemt_user_msgs_from_client{user="hello"} 143502
telemt_user_msgs_to_client{user="hello"} 675080
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 15751.8 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11899
telemt_connections_bad_total 4286
telemt_handshake_timeouts_total 533
telemt_upstream_connect_attempt_total 6891
telemt_upstream_connect_success_total 6891
telemt_upstream_connect_attempts_per_request{bucket="1"} 6891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6889
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 198023341 (188.85 MB)
telemt_user_octets_to_client{user="hello"} 18617670063 (17.34 GB)
telemt_user_msgs_from_client{user="hello"} 308842
telemt_user_msgs_to_client{user="hello"} 3290660
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```