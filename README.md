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

# Server Metrics 2026-03-11 21:32:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16324.4 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53548
telemt_connections_bad_total 2597
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 48585
telemt_upstream_connect_success_total 48572
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 48585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48570
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 1498623109 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 28202076148 (26.27 GB)
telemt_user_msgs_from_client{user="hello"} 1321206
telemt_user_msgs_to_client{user="hello"} 2758451
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16312.4 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24788
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 263
telemt_upstream_connect_attempt_total 22977
telemt_upstream_connect_success_total 22937
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 22977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22935
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 269482085 (257.00 MB)
telemt_user_octets_to_client{user="hello"} 11680357857 (10.88 GB)
telemt_user_msgs_from_client{user="hello"} 474691
telemt_user_msgs_to_client{user="hello"} 4775445
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 16332.3 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30564
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 28673
telemt_upstream_connect_success_total 28671
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 28673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28669
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 331407857 (316.06 MB)
telemt_user_octets_to_client{user="hello"} 11481607077 (10.69 GB)
telemt_user_msgs_from_client{user="hello"} 563492
telemt_user_msgs_to_client{user="hello"} 2813546
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16327.7 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32493
telemt_connections_bad_total 1815
telemt_handshake_timeouts_total 482
telemt_upstream_connect_attempt_total 28782
telemt_upstream_connect_success_total 28699
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 28782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28697
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 728627240 (694.87 MB)
telemt_user_octets_to_client{user="hello"} 18246897511 (16.99 GB)
telemt_user_msgs_from_client{user="hello"} 678463
telemt_user_msgs_to_client{user="hello"} 5887828
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16335.9 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35886
telemt_connections_bad_total 3129
telemt_handshake_timeouts_total 186
telemt_upstream_connect_attempt_total 31537
telemt_upstream_connect_success_total 31478
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 31532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31476
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 549174220 (523.73 MB)
telemt_user_octets_to_client{user="hello"} 11505624236 (10.72 GB)
telemt_user_msgs_from_client{user="hello"} 693817
telemt_user_msgs_to_client{user="hello"} 4195115
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 90942.3 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3775
telemt_connections_bad_total 644
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 3029
telemt_upstream_connect_success_total 3029
telemt_upstream_connect_attempts_per_request{bucket="1"} 3029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 454
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3019
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 30713385 (29.29 MB)
telemt_user_octets_to_client{user="hello"} 2657889394 (2.48 GB)
telemt_user_msgs_from_client{user="hello"} 81575
telemt_user_msgs_to_client{user="hello"} 327286
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 11
```