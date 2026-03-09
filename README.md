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

# Server Metrics 2026-03-09 14:36:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 55015.6 (15h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97091
telemt_connections_bad_total 1616
telemt_handshake_timeouts_total 941
telemt_upstream_connect_attempt_total 90269
telemt_upstream_connect_success_total 90231
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 90269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90225
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 2377445025 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 45440118671 (42.32 GB)
telemt_user_msgs_from_client{user="hello"} 2196182
telemt_user_msgs_to_client{user="hello"} 3034798
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 55014.1 (15h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23330
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 288
telemt_upstream_connect_attempt_total 22027
telemt_upstream_connect_success_total 22010
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 22027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22004
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 802823364 (765.63 MB)
telemt_user_octets_to_client{user="hello"} 12414782925 (11.56 GB)
telemt_user_msgs_from_client{user="hello"} 673273
telemt_user_msgs_to_client{user="hello"} 3329398
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 55015.1 (15h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28980
telemt_connections_bad_total 190
telemt_handshake_timeouts_total 1490
telemt_upstream_connect_attempt_total 20932
telemt_upstream_connect_success_total 20932
telemt_upstream_connect_attempts_per_request{bucket="1"} 20932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20926
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 4327123068 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 11155777877 (10.39 GB)
telemt_user_msgs_from_client{user="hello"} 1804597
telemt_user_msgs_to_client{user="hello"} 1600022
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 55009.5 (15h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30705
telemt_connections_bad_total 184
telemt_handshake_timeouts_total 620
telemt_upstream_connect_attempt_total 28300
telemt_upstream_connect_success_total 28230
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 28300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28224
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 1776920009 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 20079056561 (18.70 GB)
telemt_user_msgs_from_client{user="hello"} 1015468
telemt_user_msgs_to_client{user="hello"} 4839417
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 55014.9 (15h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56932
telemt_connections_bad_total 13393
telemt_handshake_timeouts_total 1438
telemt_upstream_connect_attempt_total 39340
telemt_upstream_connect_success_total 39338
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 39340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39332
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 695842624 (663.61 MB)
telemt_user_octets_to_client{user="hello"} 39174652916 (36.48 GB)
telemt_user_msgs_from_client{user="hello"} 891386
telemt_user_msgs_to_client{user="hello"} 4821659
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```