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

# Server Metrics 2026-03-06 18:04:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 27766.2 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65525
telemt_connections_bad_total 3311
telemt_handshake_timeouts_total 316
telemt_upstream_connect_attempt_total 57618
telemt_upstream_connect_success_total 57604
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 57618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57600
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 2815961164 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 37633762932 (35.05 GB)
telemt_user_msgs_from_client{user="hello"} 1959586
telemt_user_msgs_to_client{user="hello"} 5948691
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 27766.5 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13063
telemt_connections_bad_total 324
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 12357
telemt_upstream_connect_success_total 12338
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 12357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12334
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 154335075 (147.19 MB)
telemt_user_octets_to_client{user="hello"} 6525721115 (6.08 GB)
telemt_user_msgs_from_client{user="hello"} 254992
telemt_user_msgs_to_client{user="hello"} 2005265
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 27765.6 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9880
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 9534
telemt_upstream_connect_success_total 9532
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9528
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 134796051 (128.55 MB)
telemt_user_octets_to_client{user="hello"} 5564962886 (5.18 GB)
telemt_user_msgs_from_client{user="hello"} 214982
telemt_user_msgs_to_client{user="hello"} 1314086
telemt_user_unique_ips_current{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 27764.9 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14147
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 13140
telemt_upstream_connect_success_total 13095
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 13140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 922
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13091
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 191494104 (182.62 MB)
telemt_user_octets_to_client{user="hello"} 5771952649 (5.38 GB)
telemt_user_msgs_from_client{user="hello"} 241591
telemt_user_msgs_to_client{user="hello"} 1369223
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 27766.2 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19512
telemt_connections_bad_total 6553
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 12052
telemt_upstream_connect_success_total 12052
telemt_upstream_connect_attempts_per_request{bucket="1"} 12052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12048
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 266209290 (253.88 MB)
telemt_user_octets_to_client{user="hello"} 24567706538 (22.88 GB)
telemt_user_msgs_from_client{user="hello"} 460773
telemt_user_msgs_to_client{user="hello"} 4476069
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```