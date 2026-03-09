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

# Server Metrics 2026-03-09 14:57:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 56240.1 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100098
telemt_connections_bad_total 1649
telemt_handshake_timeouts_total 944
telemt_upstream_connect_attempt_total 93190
telemt_upstream_connect_success_total 93152
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 93190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93146
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 2456517997 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 47728843329 (44.45 GB)
telemt_user_msgs_from_client{user="hello"} 2272264
telemt_user_msgs_to_client{user="hello"} 3176830
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 56238.7 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24591
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 291
telemt_upstream_connect_attempt_total 23107
telemt_upstream_connect_success_total 23090
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 23107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23084
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 810733152 (773.18 MB)
telemt_user_octets_to_client{user="hello"} 13117159887 (12.22 GB)
telemt_user_msgs_from_client{user="hello"} 693520
telemt_user_msgs_to_client{user="hello"} 3560069
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 56239.6 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30915
telemt_connections_bad_total 642
telemt_handshake_timeouts_total 1525
telemt_upstream_connect_attempt_total 22197
telemt_upstream_connect_success_total 22197
telemt_upstream_connect_attempts_per_request{bucket="1"} 22197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22191
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 4347543458 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 13089556089 (12.19 GB)
telemt_user_msgs_from_client{user="hello"} 1836680
telemt_user_msgs_to_client{user="hello"} 1804672
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 56234.0 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33196
telemt_connections_bad_total 185
telemt_handshake_timeouts_total 809
telemt_upstream_connect_attempt_total 30461
telemt_upstream_connect_success_total 30380
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 30459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30374
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 1822381330 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 22338310469 (20.80 GB)
telemt_user_msgs_from_client{user="hello"} 1067354
telemt_user_msgs_to_client{user="hello"} 5500596
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 56239.4 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60301
telemt_connections_bad_total 13625
telemt_handshake_timeouts_total 1499
telemt_upstream_connect_attempt_total 42294
telemt_upstream_connect_success_total 42292
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 42294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42286
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 715337865 (682.20 MB)
telemt_user_octets_to_client{user="hello"} 39777851340 (37.05 GB)
telemt_user_msgs_from_client{user="hello"} 923486
telemt_user_msgs_to_client{user="hello"} 4934634
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 17
```