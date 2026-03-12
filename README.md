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

# Server Metrics 2026-03-12 02:55:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18633.1 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37274
telemt_connections_bad_total 1923
telemt_handshake_timeouts_total 301
telemt_upstream_connect_attempt_total 33386
telemt_upstream_connect_success_total 33379
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 33386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33377
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 314676092 (300.10 MB)
telemt_user_octets_to_client{user="hello"} 10384392115 (9.67 GB)
telemt_user_msgs_from_client{user="hello"} 535502
telemt_user_msgs_to_client{user="hello"} 1309131
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 18621.5 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15386
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 14721
telemt_upstream_connect_success_total 14721
telemt_upstream_connect_attempts_per_request{bucket="1"} 14721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14719
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 125453385 (119.64 MB)
telemt_user_octets_to_client{user="hello"} 8251407077 (7.68 GB)
telemt_user_msgs_from_client{user="hello"} 272689
telemt_user_msgs_to_client{user="hello"} 2233178
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 18595.0 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25996
telemt_connections_bad_total 365
telemt_handshake_timeouts_total 906
telemt_upstream_connect_attempt_total 22580
telemt_upstream_connect_success_total 22580
telemt_upstream_connect_attempts_per_request{bucket="1"} 22580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22576
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 5213017098 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 12756715911 (11.88 GB)
telemt_user_msgs_from_client{user="hello"} 2197556
telemt_user_msgs_to_client{user="hello"} 2650526
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 18620.4 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28676
telemt_connections_bad_total 8512
telemt_handshake_timeouts_total 703
telemt_upstream_connect_attempt_total 18657
telemt_upstream_connect_success_total 16959
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 18657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16955
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 146401511 (139.62 MB)
telemt_user_octets_to_client{user="hello"} 12008130174 (11.18 GB)
telemt_user_msgs_from_client{user="hello"} 309740
telemt_user_msgs_to_client{user="hello"} 4830785
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 18621.1 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20568
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 140
telemt_upstream_connect_attempt_total 18944
telemt_upstream_connect_success_total 18944
telemt_upstream_connect_attempts_per_request{bucket="1"} 18944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18942
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 457088665 (435.91 MB)
telemt_user_octets_to_client{user="hello"} 25732714348 (23.97 GB)
telemt_user_msgs_from_client{user="hello"} 604571
telemt_user_msgs_to_client{user="hello"} 3185151
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```