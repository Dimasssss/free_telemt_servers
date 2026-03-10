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

# Server Metrics 2026-03-10 18:40:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15248.6 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60377
telemt_connections_bad_total 1766
telemt_handshake_timeouts_total 1480
telemt_upstream_connect_attempt_total 54194
telemt_upstream_connect_success_total 54182
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 54194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54180
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 1776118417 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 40994901206 (38.18 GB)
telemt_user_msgs_from_client{user="hello"} 1599197
telemt_user_msgs_to_client{user="hello"} 3099159
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 15248.3 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22335
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 372
telemt_upstream_connect_attempt_total 20438
telemt_upstream_connect_success_total 20432
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20430
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 657746234 (627.28 MB)
telemt_user_octets_to_client{user="hello"} 10471010827 (9.75 GB)
telemt_user_msgs_from_client{user="hello"} 617159
telemt_user_msgs_to_client{user="hello"} 3307844
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 15247.9 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34436
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 2935
telemt_upstream_connect_attempt_total 29211
telemt_upstream_connect_success_total 29211
telemt_upstream_connect_attempts_per_request{bucket="1"} 29211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29209
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 430574723 (410.63 MB)
telemt_user_octets_to_client{user="hello"} 30794556760 (28.68 GB)
telemt_user_msgs_from_client{user="hello"} 635154
telemt_user_msgs_to_client{user="hello"} 4548841
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 15246.9 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32883
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 31436
telemt_upstream_connect_success_total 31343
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 31436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31341
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 438205923 (417.91 MB)
telemt_user_octets_to_client{user="hello"} 27006426453 (25.15 GB)
telemt_user_msgs_from_client{user="hello"} 627287
telemt_user_msgs_to_client{user="hello"} 4792505
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15248.1 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47599
telemt_connections_bad_total 4439
telemt_handshake_timeouts_total 1033
telemt_upstream_connect_attempt_total 40317
telemt_upstream_connect_success_total 40079
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 40317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40077
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 1401244905 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 25567524612 (23.81 GB)
telemt_user_msgs_from_client{user="hello"} 1147740
telemt_user_msgs_to_client{user="hello"} 3888555
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 25
```