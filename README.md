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

# Server Metrics 2026-03-12 00:40:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10527.2 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20196
telemt_connections_bad_total 1805
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 17625
telemt_upstream_connect_success_total 17620
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17618
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 198885086 (189.67 MB)
telemt_user_octets_to_client{user="hello"} 6730311070 (6.27 GB)
telemt_user_msgs_from_client{user="hello"} 346796
telemt_user_msgs_to_client{user="hello"} 898575
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 10515.4 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8206
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 7871
telemt_upstream_connect_success_total 7871
telemt_upstream_connect_attempts_per_request{bucket="1"} 7871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1046
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7869
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 54081845 (51.58 MB)
telemt_user_octets_to_client{user="hello"} 2873994540 (2.68 GB)
telemt_user_msgs_from_client{user="hello"} 135038
telemt_user_msgs_to_client{user="hello"} 919103
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 10489.1 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13738
telemt_connections_bad_total 279
telemt_handshake_timeouts_total 784
telemt_upstream_connect_attempt_total 11190
telemt_upstream_connect_success_total 11190
telemt_upstream_connect_attempts_per_request{bucket="1"} 11190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11188
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 69013696 (65.82 MB)
telemt_user_octets_to_client{user="hello"} 6096292106 (5.68 GB)
telemt_user_msgs_from_client{user="hello"} 217040
telemt_user_msgs_to_client{user="hello"} 1426075
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 10514.5 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12622
telemt_connections_bad_total 2212
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 9771
telemt_upstream_connect_success_total 9760
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 9771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9758
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 70033836 (66.79 MB)
telemt_user_octets_to_client{user="hello"} 4162351581 (3.88 GB)
telemt_user_msgs_from_client{user="hello"} 149639
telemt_user_msgs_to_client{user="hello"} 1515883
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 10515.3 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10577
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 9418
telemt_upstream_connect_success_total 9418
telemt_upstream_connect_attempts_per_request{bucket="1"} 9418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9416
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 126179990 (120.33 MB)
telemt_user_octets_to_client{user="hello"} 16962515723 (15.80 GB)
telemt_user_msgs_from_client{user="hello"} 263985
telemt_user_msgs_to_client{user="hello"} 1529432
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```