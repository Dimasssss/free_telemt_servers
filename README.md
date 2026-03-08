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

# Server Metrics 2026-03-08 16:12:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 32620.3 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79658
telemt_connections_bad_total 5039
telemt_handshake_timeouts_total 1067
telemt_upstream_connect_attempt_total 70823
telemt_upstream_connect_success_total 70800
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 70823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70796
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 1762733082 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 37943403406 (35.34 GB)
telemt_user_msgs_from_client{user="hello"} 1648295
telemt_user_msgs_to_client{user="hello"} 2297539
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 32619.0 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16898
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 121
telemt_upstream_connect_attempt_total 16329
telemt_upstream_connect_success_total 16328
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16324
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 614301731 (585.84 MB)
telemt_user_octets_to_client{user="hello"} 16546946192 (15.41 GB)
telemt_user_msgs_from_client{user="hello"} 655832
telemt_user_msgs_to_client{user="hello"} 4444624
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 32618.9 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10550
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9915
telemt_upstream_connect_success_total 9839
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9835
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 219999321 (209.81 MB)
telemt_user_octets_to_client{user="hello"} 3344880754 (3.12 GB)
telemt_user_msgs_from_client{user="hello"} 167512
telemt_user_msgs_to_client{user="hello"} 577081
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 32618.7 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14008
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 13348
telemt_upstream_connect_success_total 13318
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13314
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 963454349 (918.82 MB)
telemt_user_octets_to_client{user="hello"} 4900945748 (4.56 GB)
telemt_user_msgs_from_client{user="hello"} 482788
telemt_user_msgs_to_client{user="hello"} 1107508
telemt_user_unique_ips_current{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 32619.1 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18506
telemt_connections_bad_total 5992
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 12116
telemt_upstream_connect_success_total 12112
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 12116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12108
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 243704382 (232.41 MB)
telemt_user_octets_to_client{user="hello"} 10441076376 (9.72 GB)
telemt_user_msgs_from_client{user="hello"} 310051
telemt_user_msgs_to_client{user="hello"} 1356292
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```