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

# Server Metrics 2026-03-12 06:34:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 31808.1 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86668
telemt_connections_bad_total 2118
telemt_handshake_timeouts_total 2309
telemt_upstream_connect_attempt_total 78447
telemt_upstream_connect_success_total 78368
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 78447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78364
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 806179305 (768.83 MB)
telemt_user_octets_to_client{user="hello"} 23047445913 (21.46 GB)
telemt_user_msgs_from_client{user="hello"} 1179121
telemt_user_msgs_to_client{user="hello"} 2673895
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 31796.3 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35316
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 535
telemt_upstream_connect_attempt_total 33316
telemt_upstream_connect_success_total 33296
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 33316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33292
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 302349423 (288.34 MB)
telemt_user_octets_to_client{user="hello"} 15728977481 (14.65 GB)
telemt_user_msgs_from_client{user="hello"} 595792
telemt_user_msgs_to_client{user="hello"} 4982767
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 31769.7 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52752
telemt_connections_bad_total 676
telemt_handshake_timeouts_total 1116
telemt_upstream_connect_attempt_total 47598
telemt_upstream_connect_success_total 47574
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 47597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47570
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 5428052414 (5.06 GB)
telemt_user_octets_to_client{user="hello"} 28645945593 (26.68 GB)
telemt_user_msgs_from_client{user="hello"} 2694245
telemt_user_msgs_to_client{user="hello"} 5107459
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 31795.1 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57876
telemt_connections_bad_total 13010
telemt_handshake_timeouts_total 881
telemt_upstream_connect_attempt_total 41678
telemt_upstream_connect_success_total 39944
telemt_upstream_connect_fail_total 1734
telemt_upstream_connect_attempts_per_request{bucket="1"} 41678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1734
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39940
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 1385200681 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 28641149797 (26.67 GB)
telemt_user_msgs_from_client{user="hello"} 1091700
telemt_user_msgs_to_client{user="hello"} 11850079
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1987.4 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2953
telemt_connections_bad_total 355
telemt_handshake_timeouts_total 79
telemt_upstream_connect_attempt_total 2416
telemt_upstream_connect_success_total 2400
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2398
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 114052544 (108.77 MB)
telemt_user_octets_to_client{user="hello"} 2821522049 (2.63 GB)
telemt_user_msgs_from_client{user="hello"} 83436
telemt_user_msgs_to_client{user="hello"} 332911
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 31795.8 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54084
telemt_connections_bad_total 767
telemt_handshake_timeouts_total 323
telemt_upstream_connect_attempt_total 50523
telemt_upstream_connect_success_total 50481
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 50523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50477
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 888753952 (847.58 MB)
telemt_user_octets_to_client{user="hello"} 47852497895 (44.57 GB)
telemt_user_msgs_from_client{user="hello"} 1300451
telemt_user_msgs_to_client{user="hello"} 6114484
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 21
```