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

# Server Metrics 2026-03-12 00:56:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11499.7 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21837
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 137
telemt_upstream_connect_attempt_total 19204
telemt_upstream_connect_success_total 19198
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19196
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 209699542 (199.99 MB)
telemt_user_octets_to_client{user="hello"} 6965759126 (6.49 GB)
telemt_user_msgs_from_client{user="hello"} 364328
telemt_user_msgs_to_client{user="hello"} 940756
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 11487.9 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8693
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 8335
telemt_upstream_connect_success_total 8335
telemt_upstream_connect_attempts_per_request{bucket="1"} 8335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8333
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 58548699 (55.84 MB)
telemt_user_octets_to_client{user="hello"} 3140230425 (2.92 GB)
telemt_user_msgs_from_client{user="hello"} 147312
telemt_user_msgs_to_client{user="hello"} 986730
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 11461.4 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15198
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 842
telemt_upstream_connect_attempt_total 12539
telemt_upstream_connect_success_total 12539
telemt_upstream_connect_attempts_per_request{bucket="1"} 12539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1859
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12537
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 82424180 (78.61 MB)
telemt_user_octets_to_client{user="hello"} 7161699249 (6.67 GB)
telemt_user_msgs_from_client{user="hello"} 246505
telemt_user_msgs_to_client{user="hello"} 1615283
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 11486.8 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14528
telemt_connections_bad_total 2653
telemt_handshake_timeouts_total 684
telemt_upstream_connect_attempt_total 10639
telemt_upstream_connect_success_total 10628
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 10639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10626
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 83433283 (79.57 MB)
telemt_user_octets_to_client{user="hello"} 4942077890 (4.60 GB)
telemt_user_msgs_from_client{user="hello"} 167458
telemt_user_msgs_to_client{user="hello"} 1842152
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 11487.6 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11702
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 118
telemt_upstream_connect_attempt_total 10502
telemt_upstream_connect_success_total 10502
telemt_upstream_connect_attempts_per_request{bucket="1"} 10502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10500
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 158515870 (151.17 MB)
telemt_user_octets_to_client{user="hello"} 17253594424 (16.07 GB)
telemt_user_msgs_from_client{user="hello"} 286259
telemt_user_msgs_to_client{user="hello"} 1561895
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```