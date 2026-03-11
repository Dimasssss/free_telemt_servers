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

# Server Metrics 2026-03-11 23:30:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6312.1 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10359
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 9903
telemt_upstream_connect_success_total 9899
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 9903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9897
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 146510672 (139.72 MB)
telemt_user_octets_to_client{user="hello"} 4930539958 (4.59 GB)
telemt_user_msgs_from_client{user="hello"} 246170
telemt_user_msgs_to_client{user="hello"} 661332
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 6300.3 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4370
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 4197
telemt_upstream_connect_success_total 4197
telemt_upstream_connect_attempts_per_request{bucket="1"} 4197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 545
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4195
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 19607451 (18.70 MB)
telemt_user_octets_to_client{user="hello"} 514113970 (490.30 MB)
telemt_user_msgs_from_client{user="hello"} 47205
telemt_user_msgs_to_client{user="hello"} 226624
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 6274.0 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7819
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 557
telemt_upstream_connect_attempt_total 6224
telemt_upstream_connect_success_total 6224
telemt_upstream_connect_attempts_per_request{bucket="1"} 6224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 785
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6222
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 41586148 (39.66 MB)
telemt_user_octets_to_client{user="hello"} 4038652587 (3.76 GB)
telemt_user_msgs_from_client{user="hello"} 129400
telemt_user_msgs_to_client{user="hello"} 991896
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 6299.3 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5933
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 57
telemt_upstream_connect_attempt_total 5693
telemt_upstream_connect_success_total 5686
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 705
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5684
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 44347134 (42.29 MB)
telemt_user_octets_to_client{user="hello"} 2189959625 (2.04 GB)
telemt_user_msgs_from_client{user="hello"} 87758
telemt_user_msgs_to_client{user="hello"} 822697
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 6300.3 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6106
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 5289
telemt_upstream_connect_success_total 5289
telemt_upstream_connect_attempts_per_request{bucket="1"} 5289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 846
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5287
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 88906697 (84.79 MB)
telemt_user_octets_to_client{user="hello"} 11746784580 (10.94 GB)
telemt_user_msgs_from_client{user="hello"} 165483
telemt_user_msgs_to_client{user="hello"} 889837
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 6
```