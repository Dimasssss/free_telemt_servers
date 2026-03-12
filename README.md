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

# Server Metrics 2026-03-12 05:10:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 26738.5 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64501
telemt_connections_bad_total 2102
telemt_handshake_timeouts_total 1756
telemt_upstream_connect_attempt_total 57799
telemt_upstream_connect_success_total 57780
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 57797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57776
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 594239300 (566.71 MB)
telemt_user_octets_to_client{user="hello"} 19335885540 (18.01 GB)
telemt_user_msgs_from_client{user="hello"} 896895
telemt_user_msgs_to_client{user="hello"} 2192792
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 26726.7 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24377
telemt_connections_bad_total 166
telemt_handshake_timeouts_total 138
telemt_upstream_connect_attempt_total 23186
telemt_upstream_connect_success_total 23182
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 23186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23178
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 207022258 (197.43 MB)
telemt_user_octets_to_client{user="hello"} 12831095474 (11.95 GB)
telemt_user_msgs_from_client{user="hello"} 434247
telemt_user_msgs_to_client{user="hello"} 3590474
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 26700.3 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39899
telemt_connections_bad_total 542
telemt_handshake_timeouts_total 1009
telemt_upstream_connect_attempt_total 35603
telemt_upstream_connect_success_total 35602
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 35603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35598
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 5321962046 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 22300730792 (20.77 GB)
telemt_user_msgs_from_client{user="hello"} 2479102
telemt_user_msgs_to_client{user="hello"} 4003581
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 26725.6 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43148
telemt_connections_bad_total 10552
telemt_handshake_timeouts_total 782
telemt_upstream_connect_attempt_total 30293
telemt_upstream_connect_success_total 28593
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 30293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28589
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 270768699 (258.23 MB)
telemt_user_octets_to_client{user="hello"} 21522904198 (20.04 GB)
telemt_user_msgs_from_client{user="hello"} 532900
telemt_user_msgs_to_client{user="hello"} 8925702
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 26726.4 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37634
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 194
telemt_upstream_connect_attempt_total 34655
telemt_upstream_connect_success_total 34654
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 34655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34650
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 667510297 (636.59 MB)
telemt_user_octets_to_client{user="hello"} 34506006075 (32.14 GB)
telemt_user_msgs_from_client{user="hello"} 935959
telemt_user_msgs_to_client{user="hello"} 4667482
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 23
```