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

# Server Metrics 2026-03-08 20:24:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 47718.7 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107880
telemt_connections_bad_total 5085
telemt_handshake_timeouts_total 1274
telemt_upstream_connect_attempt_total 98110
telemt_upstream_connect_success_total 98076
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 98110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98070
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 2310950193 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 61576623995 (57.35 GB)
telemt_user_msgs_from_client{user="hello"} 2369093
telemt_user_msgs_to_client{user="hello"} 3325966
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 47717.7 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25068
telemt_connections_bad_total 274
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 24230
telemt_upstream_connect_success_total 24223
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 24230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24217
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 805137649 (767.84 MB)
telemt_user_octets_to_client{user="hello"} 21726375429 (20.23 GB)
telemt_user_msgs_from_client{user="hello"} 931029
telemt_user_msgs_to_client{user="hello"} 5900109
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 47717.5 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14704
telemt_connections_bad_total 184
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13350
telemt_upstream_connect_success_total 13274
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13268
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 1384396200 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 5565879163 (5.18 GB)
telemt_user_msgs_from_client{user="hello"} 631368
telemt_user_msgs_to_client{user="hello"} 938767
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 47717.3 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19186
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 18360
telemt_upstream_connect_success_total 18323
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 18360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18319
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 1059133916 (1010.07 MB)
telemt_user_octets_to_client{user="hello"} 6352196696 (5.92 GB)
telemt_user_msgs_from_client{user="hello"} 561192
telemt_user_msgs_to_client{user="hello"} 1431094
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 47717.7 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28150
telemt_connections_bad_total 9102
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 18370
telemt_upstream_connect_success_total 18363
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18357
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 341945482 (326.10 MB)
telemt_user_octets_to_client{user="hello"} 15530559610 (14.46 GB)
telemt_user_msgs_from_client{user="hello"} 475374
telemt_user_msgs_to_client{user="hello"} 2037022
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```