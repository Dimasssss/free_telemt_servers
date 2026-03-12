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

# Server Metrics 2026-03-12 04:11:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 23172.5 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49327
telemt_connections_bad_total 1982
telemt_handshake_timeouts_total 365
telemt_upstream_connect_attempt_total 44823
telemt_upstream_connect_success_total 44809
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 44823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44805
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 494756488 (471.84 MB)
telemt_user_octets_to_client{user="hello"} 14453300081 (13.46 GB)
telemt_user_msgs_from_client{user="hello"} 726040
telemt_user_msgs_to_client{user="hello"} 1745756
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 23160.6 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19511
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 18569
telemt_upstream_connect_success_total 18567
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 18569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18563
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 167863401 (160.09 MB)
telemt_user_octets_to_client{user="hello"} 10885657625 (10.14 GB)
telemt_user_msgs_from_client{user="hello"} 352722
telemt_user_msgs_to_client{user="hello"} 2883377
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 23134.4 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33356
telemt_connections_bad_total 406
telemt_handshake_timeouts_total 926
telemt_upstream_connect_attempt_total 29560
telemt_upstream_connect_success_total 29560
telemt_upstream_connect_attempts_per_request{bucket="1"} 29560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29556
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 5270736385 (4.91 GB)
telemt_user_octets_to_client{user="hello"} 19555412135 (18.21 GB)
telemt_user_msgs_from_client{user="hello"} 2367530
telemt_user_msgs_to_client{user="hello"} 3647973
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 23159.5 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34507
telemt_connections_bad_total 8655
telemt_handshake_timeouts_total 736
telemt_upstream_connect_attempt_total 24060
telemt_upstream_connect_success_total 22361
telemt_upstream_connect_fail_total 1699
telemt_upstream_connect_attempts_per_request{bucket="1"} 24060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1699
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22357
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 206227260 (196.67 MB)
telemt_user_octets_to_client{user="hello"} 19030815462 (17.72 GB)
telemt_user_msgs_from_client{user="hello"} 430047
telemt_user_msgs_to_client{user="hello"} 7999169
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 23160.4 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28994
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 26955
telemt_upstream_connect_success_total 26954
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 26955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26952
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 600849527 (573.01 MB)
telemt_user_octets_to_client{user="hello"} 31637127924 (29.46 GB)
telemt_user_msgs_from_client{user="hello"} 817430
telemt_user_msgs_to_client{user="hello"} 4075054
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 22
```