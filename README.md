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

# Server Metrics 2026-03-12 00:18:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9230.6 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17572
telemt_connections_bad_total 1801
telemt_handshake_timeouts_total 88
telemt_upstream_connect_attempt_total 15201
telemt_upstream_connect_success_total 15196
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15194
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 185754455 (177.15 MB)
telemt_user_octets_to_client{user="hello"} 6147178848 (5.73 GB)
telemt_user_msgs_from_client{user="hello"} 320508
telemt_user_msgs_to_client{user="hello"} 822145
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 9218.8 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7020
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 6723
telemt_upstream_connect_success_total 6723
telemt_upstream_connect_attempts_per_request{bucket="1"} 6723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 849
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6721
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 36577942 (34.88 MB)
telemt_user_octets_to_client{user="hello"} 1307735765 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 89729
telemt_user_msgs_to_client{user="hello"} 519198
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 9193.2 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11901
telemt_connections_bad_total 272
telemt_handshake_timeouts_total 775
telemt_upstream_connect_attempt_total 9434
telemt_upstream_connect_success_total 9434
telemt_upstream_connect_attempts_per_request{bucket="1"} 9434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1324
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9432
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 60960564 (58.14 MB)
telemt_user_octets_to_client{user="hello"} 5961379071 (5.55 GB)
telemt_user_msgs_from_client{user="hello"} 191916
telemt_user_msgs_to_client{user="hello"} 1375058
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 9217.7 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11168
telemt_connections_bad_total 2211
telemt_handshake_timeouts_total 245
telemt_upstream_connect_attempt_total 8379
telemt_upstream_connect_success_total 8368
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 8379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8366
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 62147070 (59.27 MB)
telemt_user_octets_to_client{user="hello"} 3698362854 (3.44 GB)
telemt_user_msgs_from_client{user="hello"} 129165
telemt_user_msgs_to_client{user="hello"} 1316478
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 9218.5 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9064
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 8011
telemt_upstream_connect_success_total 8011
telemt_upstream_connect_attempts_per_request{bucket="1"} 8011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8009
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 117053349 (111.63 MB)
telemt_user_octets_to_client{user="hello"} 16695508542 (15.55 GB)
telemt_user_msgs_from_client{user="hello"} 242155
telemt_user_msgs_to_client{user="hello"} 1474118
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 13
```