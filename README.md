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

# Server Metrics 2026-03-08 16:27:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 33544.9 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80971
telemt_connections_bad_total 5039
telemt_handshake_timeouts_total 1081
telemt_upstream_connect_attempt_total 72099
telemt_upstream_connect_success_total 72076
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 72099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72072
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 1874999610 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 38719944462 (36.06 GB)
telemt_user_msgs_from_client{user="hello"} 1712902
telemt_user_msgs_to_client{user="hello"} 2344919
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 33544.1 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17327
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 16756
telemt_upstream_connect_success_total 16754
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16750
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 622202685 (593.38 MB)
telemt_user_octets_to_client{user="hello"} 17053827439 (15.88 GB)
telemt_user_msgs_from_client{user="hello"} 675650
telemt_user_msgs_to_client{user="hello"} 4603433
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 33543.8 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10723
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 10088
telemt_upstream_connect_success_total 10012
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 10088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10008
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 222491491 (212.18 MB)
telemt_user_octets_to_client{user="hello"} 3556014005 (3.31 GB)
telemt_user_msgs_from_client{user="hello"} 174438
telemt_user_msgs_to_client{user="hello"} 617456
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 33543.7 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14411
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 13729
telemt_upstream_connect_success_total 13699
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13695
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 998981992 (952.70 MB)
telemt_user_octets_to_client{user="hello"} 5014159182 (4.67 GB)
telemt_user_msgs_from_client{user="hello"} 499499
telemt_user_msgs_to_client{user="hello"} 1135258
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 33543.9 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18943
telemt_connections_bad_total 6157
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 12362
telemt_upstream_connect_success_total 12358
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 12362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12354
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 246111308 (234.71 MB)
telemt_user_octets_to_client{user="hello"} 10667686366 (9.94 GB)
telemt_user_msgs_from_client{user="hello"} 316156
telemt_user_msgs_to_client{user="hello"} 1380065
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```