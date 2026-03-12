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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-12 06:55:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 33039.7 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92679
telemt_connections_bad_total 2120
telemt_handshake_timeouts_total 2389
telemt_upstream_connect_attempt_total 84207
telemt_upstream_connect_success_total 84040
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 84207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84036
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 851621723 (812.17 MB)
telemt_user_octets_to_client{user="hello"} 25110165232 (23.39 GB)
telemt_user_msgs_from_client{user="hello"} 1254111
telemt_user_msgs_to_client{user="hello"} 2854617
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 33027.5 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37890
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 554
telemt_upstream_connect_attempt_total 35791
telemt_upstream_connect_success_total 35749
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 35791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35745
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 314568915 (300.00 MB)
telemt_user_octets_to_client{user="hello"} 16152697605 (15.04 GB)
telemt_user_msgs_from_client{user="hello"} 623151
telemt_user_msgs_to_client{user="hello"} 5148116
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 33001.1 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56287
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 1139
telemt_upstream_connect_attempt_total 50693
telemt_upstream_connect_success_total 50657
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 50693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50653
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 5462717477 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 30732322267 (28.62 GB)
telemt_user_msgs_from_client{user="hello"} 2753070
telemt_user_msgs_to_client{user="hello"} 5465285
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 33026.4 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61708
telemt_connections_bad_total 13097
telemt_handshake_timeouts_total 904
telemt_upstream_connect_attempt_total 45117
telemt_upstream_connect_success_total 43357
telemt_upstream_connect_fail_total 1760
telemt_upstream_connect_attempts_per_request{bucket="1"} 45117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7365
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1760
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43353
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 1420053490 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 34295717399 (31.94 GB)
telemt_user_msgs_from_client{user="hello"} 1177218
telemt_user_msgs_to_client{user="hello"} 13767025
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3218.8 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4767
telemt_connections_bad_total 577
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 3909
telemt_upstream_connect_success_total 3875
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 3909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3873
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 132969479 (126.81 MB)
telemt_user_octets_to_client{user="hello"} 4645265263 (4.33 GB)
telemt_user_msgs_from_client{user="hello"} 134425
telemt_user_msgs_to_client{user="hello"} 667440
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 33027.2 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58928
telemt_connections_bad_total 918
telemt_handshake_timeouts_total 331
telemt_upstream_connect_attempt_total 55084
telemt_upstream_connect_success_total 55002
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 55084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9076
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54998
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 985992967 (940.32 MB)
telemt_user_octets_to_client{user="hello"} 50527823814 (47.06 GB)
telemt_user_msgs_from_client{user="hello"} 1402051
telemt_user_msgs_to_client{user="hello"} 6459519
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 31
```