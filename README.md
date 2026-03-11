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

# Server Metrics 2026-03-11 14:41:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 87349.0 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290140
telemt_connections_bad_total 3681
telemt_handshake_timeouts_total 4816
telemt_upstream_connect_attempt_total 268589
telemt_upstream_connect_success_total 268511
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 268589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 245674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 268501
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 5066400596 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 135134448348 (125.85 GB)
telemt_user_msgs_from_client{user="hello"} 5878050
telemt_user_msgs_to_client{user="hello"} 10750856
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 87348.5 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114832
telemt_connections_bad_total 922
telemt_handshake_timeouts_total 3371
telemt_upstream_connect_attempt_total 105532
telemt_upstream_connect_success_total 105511
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 105532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 464
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105501
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 5965804768 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 68497772089 (63.79 GB)
telemt_user_msgs_from_client{user="hello"} 3942107
telemt_user_msgs_to_client{user="hello"} 19669114
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 87348.2 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159686
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 6996
telemt_upstream_connect_attempt_total 142502
telemt_upstream_connect_success_total 142488
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 142502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 126693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 142478
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 12693373974 (11.82 GB)
telemt_user_octets_to_client{user="hello"} 128157283852 (119.36 GB)
telemt_user_msgs_from_client{user="hello"} 6736287
telemt_user_msgs_to_client{user="hello"} 28632018
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 87347.1 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177088
telemt_connections_bad_total 7453
telemt_handshake_timeouts_total 1979
telemt_upstream_connect_attempt_total 160577
telemt_upstream_connect_success_total 160187
telemt_upstream_connect_fail_total 390
telemt_upstream_connect_attempts_per_request{bucket="1"} 160577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 139261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 90
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 390
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 160177
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 9609894309 (8.95 GB)
telemt_user_octets_to_client{user="hello"} 111676841598 (104.01 GB)
telemt_user_msgs_from_client{user="hello"} 5707932
telemt_user_msgs_to_client{user="hello"} 33187162
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 87348.3 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252988
telemt_connections_bad_total 19286
telemt_handshake_timeouts_total 6311
telemt_upstream_connect_attempt_total 205540
telemt_upstream_connect_success_total 205036
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 205540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 177541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 205028
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 5022844391 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 166498728391 (155.06 GB)
telemt_user_msgs_from_client{user="hello"} 4850620
telemt_user_msgs_to_client{user="hello"} 22909196
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 66317.9 (18h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454
telemt_connections_bad_total 432
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```