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

# Server Metrics 2026-03-12 00:13:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8906.0 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16818
telemt_connections_bad_total 1762
telemt_handshake_timeouts_total 85
telemt_upstream_connect_attempt_total 14500
telemt_upstream_connect_success_total 14495
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14493
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 181749612 (173.33 MB)
telemt_user_octets_to_client{user="hello"} 5980726008 (5.57 GB)
telemt_user_msgs_from_client{user="hello"} 311732
telemt_user_msgs_to_client{user="hello"} 799407
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 8894.4 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6699
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 6425
telemt_upstream_connect_success_total 6425
telemt_upstream_connect_attempts_per_request{bucket="1"} 6425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 820
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6423
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 33495562 (31.94 MB)
telemt_user_octets_to_client{user="hello"} 1082338776 (1.01 GB)
telemt_user_msgs_from_client{user="hello"} 81216
telemt_user_msgs_to_client{user="hello"} 461764
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 8868.0 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11508
telemt_connections_bad_total 272
telemt_handshake_timeouts_total 770
telemt_upstream_connect_attempt_total 9059
telemt_upstream_connect_success_total 9059
telemt_upstream_connect_attempts_per_request{bucket="1"} 9059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1262
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9057
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 59128411 (56.39 MB)
telemt_user_octets_to_client{user="hello"} 5949447098 (5.54 GB)
telemt_user_msgs_from_client{user="hello"} 186182
telemt_user_msgs_to_client{user="hello"} 1366945
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 8893.4 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10824
telemt_connections_bad_total 2168
telemt_handshake_timeouts_total 240
telemt_upstream_connect_attempt_total 8113
telemt_upstream_connect_success_total 8102
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 8113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8100
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 60086173 (57.30 MB)
telemt_user_octets_to_client{user="hello"} 3518448595 (3.28 GB)
telemt_user_msgs_from_client{user="hello"} 123978
telemt_user_msgs_to_client{user="hello"} 1240116
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 8894.3 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8730
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 7688
telemt_upstream_connect_success_total 7688
telemt_upstream_connect_attempts_per_request{bucket="1"} 7688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7686
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 112463426 (107.25 MB)
telemt_user_octets_to_client{user="hello"} 15683553848 (14.61 GB)
telemt_user_msgs_from_client{user="hello"} 229476
telemt_user_msgs_to_client{user="hello"} 1386828
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```