# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

# Server Metrics 2026-03-10 19:41:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18931.0 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72234
telemt_connections_bad_total 2417
telemt_handshake_timeouts_total 1932
telemt_upstream_connect_attempt_total 64473
telemt_upstream_connect_success_total 64460
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 64473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64458
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 2043406481 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 47770847204 (44.49 GB)
telemt_user_msgs_from_client{user="hello"} 1895183
telemt_user_msgs_to_client{user="hello"} 3531961
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 18930.3 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27795
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 454
telemt_upstream_connect_attempt_total 25466
telemt_upstream_connect_success_total 25459
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 25466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25457
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 837170734 (798.39 MB)
telemt_user_octets_to_client{user="hello"} 19221534472 (17.90 GB)
telemt_user_msgs_from_client{user="hello"} 837169
telemt_user_msgs_to_client{user="hello"} 5855420
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 18929.7 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43383
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 3585
telemt_upstream_connect_attempt_total 37077
telemt_upstream_connect_success_total 37076
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 37077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37074
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 594127784 (566.60 MB)
telemt_user_octets_to_client{user="hello"} 35876270092 (33.41 GB)
telemt_user_msgs_from_client{user="hello"} 811826
telemt_user_msgs_to_client{user="hello"} 5363435
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 18928.9 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40056
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 38427
telemt_upstream_connect_success_total 38315
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 38427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38313
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 632680634 (603.37 MB)
telemt_user_octets_to_client{user="hello"} 30338437779 (28.25 GB)
telemt_user_msgs_from_client{user="hello"} 819956
telemt_user_msgs_to_client{user="hello"} 5678988
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18930.2 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58583
telemt_connections_bad_total 5150
telemt_handshake_timeouts_total 1261
telemt_upstream_connect_attempt_total 49783
telemt_upstream_connect_success_total 49540
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 49783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49538
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 1510250872 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 38222701732 (35.60 GB)
telemt_user_msgs_from_client{user="hello"} 1379087
telemt_user_msgs_to_client{user="hello"} 5401099
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```