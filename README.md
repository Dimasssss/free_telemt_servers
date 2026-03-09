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

# Server Metrics 2026-03-09 23:59:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 88753.5 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166987
telemt_connections_bad_total 2324
telemt_handshake_timeouts_total 1700
telemt_upstream_connect_attempt_total 156311
telemt_upstream_connect_success_total 156261
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 156311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 143784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 156251
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 4818146749 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 94148229154 (87.68 GB)
telemt_user_msgs_from_client{user="hello"} 4262918
telemt_user_msgs_to_client{user="hello"} 6046818
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 88752.5 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51697
telemt_connections_bad_total 3034
telemt_handshake_timeouts_total 726
telemt_upstream_connect_attempt_total 45296
telemt_upstream_connect_success_total 45255
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 45296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45245
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 2116099875 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 22376738498 (20.84 GB)
telemt_user_msgs_from_client{user="hello"} 1491089
telemt_user_msgs_to_client{user="hello"} 6404953
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 88753.0 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62169
telemt_connections_bad_total 825
telemt_handshake_timeouts_total 3649
telemt_upstream_connect_attempt_total 49017
telemt_upstream_connect_success_total 49015
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 49017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49007
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 5981720280 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 53771322169 (50.08 GB)
telemt_user_msgs_from_client{user="hello"} 3126706
telemt_user_msgs_to_client{user="hello"} 7633517
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 88747.8 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67876
telemt_connections_bad_total 345
telemt_handshake_timeouts_total 1031
telemt_upstream_connect_attempt_total 62603
telemt_upstream_connect_success_total 62445
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 62603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62435
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 2260805062 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 45570784595 (42.44 GB)
telemt_user_msgs_from_client{user="hello"} 1801082
telemt_user_msgs_to_client{user="hello"} 11000666
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 88753.2 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112523
telemt_connections_bad_total 20020
telemt_handshake_timeouts_total 3000
telemt_upstream_connect_attempt_total 84618
telemt_upstream_connect_success_total 84609
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 84618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84599
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 1420725763 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 82881823106 (77.19 GB)
telemt_user_msgs_from_client{user="hello"} 1984391
telemt_user_msgs_to_client{user="hello"} 10682850
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```