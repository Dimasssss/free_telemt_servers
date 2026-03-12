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

# Server Metrics 2026-03-12 05:16:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 27062.9 (7h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65683
telemt_connections_bad_total 2104
telemt_handshake_timeouts_total 1798
telemt_upstream_connect_attempt_total 58911
telemt_upstream_connect_success_total 58894
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 58911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58890
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 606841174 (578.73 MB)
telemt_user_octets_to_client{user="hello"} 19629016651 (18.28 GB)
telemt_user_msgs_from_client{user="hello"} 911178
telemt_user_msgs_to_client{user="hello"} 2219272
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 27051.0 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25137
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 143
telemt_upstream_connect_attempt_total 23883
telemt_upstream_connect_success_total 23878
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23874
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 218851607 (208.71 MB)
telemt_user_octets_to_client{user="hello"} 13083310126 (12.18 GB)
telemt_user_msgs_from_client{user="hello"} 447292
telemt_user_msgs_to_client{user="hello"} 3700952
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 27024.6 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40597
telemt_connections_bad_total 546
telemt_handshake_timeouts_total 1017
telemt_upstream_connect_attempt_total 36270
telemt_upstream_connect_success_total 36269
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 36270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36265
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 5325772375 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 22597476102 (21.05 GB)
telemt_user_msgs_from_client{user="hello"} 2490280
telemt_user_msgs_to_client{user="hello"} 4058589
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 27050.0 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44495
telemt_connections_bad_total 10938
telemt_handshake_timeouts_total 795
telemt_upstream_connect_attempt_total 31148
telemt_upstream_connect_success_total 29448
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 31148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4803
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29444
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 275216324 (262.47 MB)
telemt_user_octets_to_client{user="hello"} 21756285554 (20.26 GB)
telemt_user_msgs_from_client{user="hello"} 543738
telemt_user_msgs_to_client{user="hello"} 9008409
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 27050.6 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38511
telemt_connections_bad_total 760
telemt_handshake_timeouts_total 195
telemt_upstream_connect_attempt_total 35500
telemt_upstream_connect_success_total 35499
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 35500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35495
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 672050680 (640.92 MB)
telemt_user_octets_to_client{user="hello"} 34658219954 (32.28 GB)
telemt_user_msgs_from_client{user="hello"} 946980
telemt_user_msgs_to_client{user="hello"} 4695517
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```