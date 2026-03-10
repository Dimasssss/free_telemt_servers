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

# Server Metrics 2026-03-10 18:35:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14939.4 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59370
telemt_connections_bad_total 1727
telemt_handshake_timeouts_total 1468
telemt_upstream_connect_attempt_total 53263
telemt_upstream_connect_success_total 53251
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 53263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53249
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 1669143071 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 40536851420 (37.75 GB)
telemt_user_msgs_from_client{user="hello"} 1543516
telemt_user_msgs_to_client{user="hello"} 3046696
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 14938.9 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21879
telemt_connections_bad_total 206
telemt_handshake_timeouts_total 370
telemt_upstream_connect_attempt_total 20009
telemt_upstream_connect_success_total 20003
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20001
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 601266278 (573.41 MB)
telemt_user_octets_to_client{user="hello"} 10166499999 (9.47 GB)
telemt_user_msgs_from_client{user="hello"} 589403
telemt_user_msgs_to_client{user="hello"} 3226157
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 14938.7 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33576
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 2858
telemt_upstream_connect_attempt_total 28487
telemt_upstream_connect_success_total 28487
telemt_upstream_connect_attempts_per_request{bucket="1"} 28487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28485
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 360708652 (344.00 MB)
telemt_user_octets_to_client{user="hello"} 29648016653 (27.61 GB)
telemt_user_msgs_from_client{user="hello"} 602297
telemt_user_msgs_to_client{user="hello"} 4423017
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 14937.5 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32230
telemt_connections_bad_total 45
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 30817
telemt_upstream_connect_success_total 30725
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 30817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30723
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 409754995 (390.77 MB)
telemt_user_octets_to_client{user="hello"} 26864121062 (25.02 GB)
telemt_user_msgs_from_client{user="hello"} 610139
telemt_user_msgs_to_client{user="hello"} 4757657
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14938.9 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46678
telemt_connections_bad_total 4310
telemt_handshake_timeouts_total 1030
telemt_upstream_connect_attempt_total 39563
telemt_upstream_connect_success_total 39325
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 39563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39323
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 1392276754 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 24406669169 (22.73 GB)
telemt_user_msgs_from_client{user="hello"} 1124665
telemt_user_msgs_to_client{user="hello"} 3702612
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 24
```