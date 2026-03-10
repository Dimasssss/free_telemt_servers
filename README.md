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

# Server Metrics 2026-03-10 19:51:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 19544.3 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73973
telemt_connections_bad_total 2524
telemt_handshake_timeouts_total 2062
telemt_upstream_connect_attempt_total 65926
telemt_upstream_connect_success_total 65913
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 65926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65911
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 2101598795 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 49067940134 (45.70 GB)
telemt_user_msgs_from_client{user="hello"} 1940583
telemt_user_msgs_to_client{user="hello"} 3589348
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 19543.5 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28877
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 462
telemt_upstream_connect_attempt_total 26458
telemt_upstream_connect_success_total 26451
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26449
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 861726693 (821.81 MB)
telemt_user_octets_to_client{user="hello"} 21019268287 (19.58 GB)
telemt_user_msgs_from_client{user="hello"} 882289
telemt_user_msgs_to_client{user="hello"} 6412462
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 19543.4 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45228
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 3613
telemt_upstream_connect_attempt_total 38807
telemt_upstream_connect_success_total 38806
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 38807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38804
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 611820549 (583.48 MB)
telemt_user_octets_to_client{user="hello"} 37485005051 (34.91 GB)
telemt_user_msgs_from_client{user="hello"} 843399
telemt_user_msgs_to_client{user="hello"} 5601520
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 19542.1 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41042
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 39390
telemt_upstream_connect_success_total 39274
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 39390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39272
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 641292297 (611.58 MB)
telemt_user_octets_to_client{user="hello"} 30976420647 (28.85 GB)
telemt_user_msgs_from_client{user="hello"} 840485
telemt_user_msgs_to_client{user="hello"} 5789146
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 19543.3 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59849
telemt_connections_bad_total 5282
telemt_handshake_timeouts_total 1266
telemt_upstream_connect_attempt_total 50822
telemt_upstream_connect_success_total 50578
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 50822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50576
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 1526689094 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 38658450248 (36.00 GB)
telemt_user_msgs_from_client{user="hello"} 1405614
telemt_user_msgs_to_client{user="hello"} 5457834
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 22
```