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

# Server Metrics 2026-03-10 12:16:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 132982.7 (36h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293658
telemt_connections_bad_total 3464
telemt_handshake_timeouts_total 3080
telemt_upstream_connect_attempt_total 274811
telemt_upstream_connect_success_total 274659
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 274811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 253858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 274647
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 6510439324 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 182042317094 (169.54 GB)
telemt_user_msgs_from_client{user="hello"} 6657937
telemt_user_msgs_to_client{user="hello"} 10788931
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 132982.5 (36h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89791
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 1265
telemt_upstream_connect_attempt_total 80580
telemt_upstream_connect_success_total 80536
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 80580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7584
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80522
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 2767039960 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 34873503571 (32.48 GB)
telemt_user_msgs_from_client{user="hello"} 2182967
telemt_user_msgs_to_client{user="hello"} 10047911
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 132982.9 (36h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127647
telemt_connections_bad_total 1215
telemt_handshake_timeouts_total 6282
telemt_upstream_connect_attempt_total 93645
telemt_upstream_connect_success_total 93643
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 93645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93631
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 6598196143 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 66658816788 (62.08 GB)
telemt_user_msgs_from_client{user="hello"} 4360468
telemt_user_msgs_to_client{user="hello"} 11074490
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 132977.9 (36h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132828
telemt_connections_bad_total 1041
telemt_handshake_timeouts_total 2903
telemt_upstream_connect_attempt_total 122337
telemt_upstream_connect_success_total 122075
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 122336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13270
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 78
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 313
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 122061
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 3867438645 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 85121360298 (79.28 GB)
telemt_user_msgs_from_client{user="hello"} 3264940
telemt_user_msgs_to_client{user="hello"} 19373118
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 132983.0 (36h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197217
telemt_connections_bad_total 28870
telemt_handshake_timeouts_total 5290
telemt_upstream_connect_attempt_total 154733
telemt_upstream_connect_success_total 153772
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 154733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 153758
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 3408588468 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 114540848394 (106.67 GB)
telemt_user_msgs_from_client{user="hello"} 3565301
telemt_user_msgs_to_client{user="hello"} 15581247
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 25
```