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

# Server Metrics 2026-03-09 07:17:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 28659.3 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30345
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 578
telemt_upstream_connect_attempt_total 28082
telemt_upstream_connect_success_total 28074
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 28082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28070
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 268588121 (256.15 MB)
telemt_user_octets_to_client{user="hello"} 15365779713 (14.31 GB)
telemt_user_msgs_from_client{user="hello"} 542386
telemt_user_msgs_to_client{user="hello"} 813018
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 28657.4 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5030
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 4712
telemt_upstream_connect_success_total 4711
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 307
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4707
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 61327396 (58.49 MB)
telemt_user_octets_to_client{user="hello"} 3968960801 (3.70 GB)
telemt_user_msgs_from_client{user="hello"} 133762
telemt_user_msgs_to_client{user="hello"} 772738
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 28658.0 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2447
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2299
telemt_upstream_connect_success_total 2299
telemt_upstream_connect_attempts_per_request{bucket="1"} 2299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2295
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 913620940 (871.30 MB)
telemt_user_octets_to_client{user="hello"} 1447823530 (1.35 GB)
telemt_user_msgs_from_client{user="hello"} 358231
telemt_user_msgs_to_client{user="hello"} 278080
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 28652.9 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5205
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 353
telemt_upstream_connect_attempt_total 4272
telemt_upstream_connect_success_total 4269
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 747
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4265
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 138156417 (131.76 MB)
telemt_user_octets_to_client{user="hello"} 5022267881 (4.68 GB)
telemt_user_msgs_from_client{user="hello"} 103672
telemt_user_msgs_to_client{user="hello"} 1232907
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 28658.3 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11520
telemt_connections_bad_total 6189
telemt_handshake_timeouts_total 29
telemt_upstream_connect_attempt_total 4966
telemt_upstream_connect_success_total 4966
telemt_upstream_connect_attempts_per_request{bucket="1"} 4966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4962
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 63291883 (60.36 MB)
telemt_user_octets_to_client{user="hello"} 3143131435 (2.93 GB)
telemt_user_msgs_from_client{user="hello"} 98075
telemt_user_msgs_to_client{user="hello"} 436126
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 6
```