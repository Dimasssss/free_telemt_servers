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

# Server Metrics 2026-03-11 15:33:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 90420.5 (25h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306532
telemt_connections_bad_total 4957
telemt_handshake_timeouts_total 5180
telemt_upstream_connect_attempt_total 282781
telemt_upstream_connect_success_total 282700
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 282780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 258466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 282690
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 5323405978 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 138815017375 (129.28 GB)
telemt_user_msgs_from_client{user="hello"} 6137959
telemt_user_msgs_to_client{user="hello"} 11175393
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 90419.9 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121465
telemt_connections_bad_total 971
telemt_handshake_timeouts_total 3409
telemt_upstream_connect_attempt_total 111893
telemt_upstream_connect_success_total 111868
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 111889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111858
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 6055669237 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 69799553441 (65.01 GB)
telemt_user_msgs_from_client{user="hello"} 4053524
telemt_user_msgs_to_client{user="hello"} 20288508
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 90419.7 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166669
telemt_connections_bad_total 1435
telemt_handshake_timeouts_total 7210
telemt_upstream_connect_attempt_total 148788
telemt_upstream_connect_success_total 148774
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 148788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 148764
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 12741201354 (11.87 GB)
telemt_user_octets_to_client{user="hello"} 131692438428 (122.65 GB)
telemt_user_msgs_from_client{user="hello"} 6862558
telemt_user_msgs_to_client{user="hello"} 29570328
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 90418.8 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186151
telemt_connections_bad_total 8645
telemt_handshake_timeouts_total 2293
telemt_upstream_connect_attempt_total 167767
telemt_upstream_connect_success_total 167357
telemt_upstream_connect_fail_total 410
telemt_upstream_connect_attempts_per_request{bucket="1"} 167767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 93
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 452
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 410
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 167347
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 9914855212 (9.23 GB)
telemt_user_octets_to_client{user="hello"} 115451909118 (107.52 GB)
telemt_user_msgs_from_client{user="hello"} 5911899
telemt_user_msgs_to_client{user="hello"} 34566136
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 90420.0 (25h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263199
telemt_connections_bad_total 19872
telemt_handshake_timeouts_total 6342
telemt_upstream_connect_attempt_total 214802
telemt_upstream_connect_success_total 214297
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 214801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 185641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 214289
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 5120656089 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 173990670319 (162.04 GB)
telemt_user_msgs_from_client{user="hello"} 5053780
telemt_user_msgs_to_client{user="hello"} 24283074
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 69389.4 (19h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```