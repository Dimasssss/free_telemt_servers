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

# Server Metrics 2026-03-12 02:01:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15389.4 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29597
telemt_connections_bad_total 1905
telemt_handshake_timeouts_total 199
telemt_upstream_connect_attempt_total 26339
telemt_upstream_connect_success_total 26332
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26330
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 265887608 (253.57 MB)
telemt_user_octets_to_client{user="hello"} 9070191530 (8.45 GB)
telemt_user_msgs_from_client{user="hello"} 460760
telemt_user_msgs_to_client{user="hello"} 1120122
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 15377.4 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12448
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 11946
telemt_upstream_connect_success_total 11946
telemt_upstream_connect_attempts_per_request{bucket="1"} 11946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11944
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 80084186 (76.37 MB)
telemt_user_octets_to_client{user="hello"} 4461938054 (4.16 GB)
telemt_user_msgs_from_client{user="hello"} 197298
telemt_user_msgs_to_client{user="hello"} 1399895
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 15351.4 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20852
telemt_connections_bad_total 305
telemt_handshake_timeouts_total 876
telemt_upstream_connect_attempt_total 17723
telemt_upstream_connect_success_total 17723
telemt_upstream_connect_attempts_per_request{bucket="1"} 17723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17721
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 3966902874 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 10310782571 (9.60 GB)
telemt_user_msgs_from_client{user="hello"} 1690765
telemt_user_msgs_to_client{user="hello"} 2082354
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 15376.3 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23474
telemt_connections_bad_total 7935
telemt_handshake_timeouts_total 694
telemt_upstream_connect_attempt_total 14162
telemt_upstream_connect_success_total 14123
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 14162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1881
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14119
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 116001979 (110.63 MB)
telemt_user_octets_to_client{user="hello"} 6654214510 (6.20 GB)
telemt_user_msgs_from_client{user="hello"} 226105
telemt_user_msgs_to_client{user="hello"} 2532613
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 15377.2 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16749
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 128
telemt_upstream_connect_attempt_total 15274
telemt_upstream_connect_success_total 15274
telemt_upstream_connect_attempts_per_request{bucket="1"} 15274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15272
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 401141076 (382.56 MB)
telemt_user_octets_to_client{user="hello"} 21029381743 (19.59 GB)
telemt_user_msgs_from_client{user="hello"} 491596
telemt_user_msgs_to_client{user="hello"} 2169464
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```