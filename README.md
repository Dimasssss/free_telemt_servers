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

# Server Metrics 2026-03-08 17:44:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 38167.1 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90486
telemt_connections_bad_total 5045
telemt_handshake_timeouts_total 1238
telemt_upstream_connect_attempt_total 81165
telemt_upstream_connect_success_total 81137
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 81165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81131
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2003755741 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 49632970645 (46.22 GB)
telemt_user_msgs_from_client{user="hello"} 1950653
telemt_user_msgs_to_client{user="hello"} 2761201
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 38166.4 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19922
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 19266
telemt_upstream_connect_success_total 19262
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 19266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19258
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 709057272 (676.21 MB)
telemt_user_octets_to_client{user="hello"} 18822981940 (17.53 GB)
telemt_user_msgs_from_client{user="hello"} 804710
telemt_user_msgs_to_client{user="hello"} 5166633
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 38166.1 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12703
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 670
telemt_upstream_connect_attempt_total 11404
telemt_upstream_connect_success_total 11328
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11324
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 233897870 (223.06 MB)
telemt_user_octets_to_client{user="hello"} 4087721530 (3.81 GB)
telemt_user_msgs_from_client{user="hello"} 197686
telemt_user_msgs_to_client{user="hello"} 720242
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 38166.0 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15932
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 15214
telemt_upstream_connect_success_total 15181
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 15214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1105
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15177
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 1017103435 (969.99 MB)
telemt_user_octets_to_client{user="hello"} 5685116453 (5.29 GB)
telemt_user_msgs_from_client{user="hello"} 525018
telemt_user_msgs_to_client{user="hello"} 1277210
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 38166.2 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22111
telemt_connections_bad_total 7144
telemt_handshake_timeouts_total 228
telemt_upstream_connect_attempt_total 14402
telemt_upstream_connect_success_total 14398
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14394
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 263278715 (251.08 MB)
telemt_user_octets_to_client{user="hello"} 11376522565 (10.60 GB)
telemt_user_msgs_from_client{user="hello"} 351486
telemt_user_msgs_to_client{user="hello"} 1500433
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```