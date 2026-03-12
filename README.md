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

# Server Metrics 2026-03-12 05:05:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 26413.8 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62964
telemt_connections_bad_total 2102
telemt_handshake_timeouts_total 1603
telemt_upstream_connect_attempt_total 56458
telemt_upstream_connect_success_total 56442
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 56458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56438
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 588081734 (560.84 MB)
telemt_user_octets_to_client{user="hello"} 19104328026 (17.79 GB)
telemt_user_msgs_from_client{user="hello"} 882705
telemt_user_msgs_to_client{user="hello"} 2156408
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 26402.4 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23719
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 22557
telemt_upstream_connect_success_total 22553
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 22557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22549
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 200674223 (191.38 MB)
telemt_user_octets_to_client{user="hello"} 12169474333 (11.33 GB)
telemt_user_msgs_from_client{user="hello"} 423281
telemt_user_msgs_to_client{user="hello"} 3488923
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 26375.8 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39158
telemt_connections_bad_total 542
telemt_handshake_timeouts_total 979
telemt_upstream_connect_attempt_total 34929
telemt_upstream_connect_success_total 34928
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 34929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34924
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 5318073310 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 21891704344 (20.39 GB)
telemt_user_msgs_from_client{user="hello"} 2467311
telemt_user_msgs_to_client{user="hello"} 3961241
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 26401.2 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41882
telemt_connections_bad_total 10178
telemt_handshake_timeouts_total 778
telemt_upstream_connect_attempt_total 29484
telemt_upstream_connect_success_total 27784
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 29484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4563
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27780
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 263847728 (251.62 MB)
telemt_user_octets_to_client{user="hello"} 21087700419 (19.64 GB)
telemt_user_msgs_from_client{user="hello"} 517161
telemt_user_msgs_to_client{user="hello"} 8763466
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 26402.0 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37017
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 182
telemt_upstream_connect_attempt_total 34071
telemt_upstream_connect_success_total 34070
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 34071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34066
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 663764817 (633.02 MB)
telemt_user_octets_to_client{user="hello"} 34445748740 (32.08 GB)
telemt_user_msgs_from_client{user="hello"} 927762
telemt_user_msgs_to_client{user="hello"} 4653616
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 19
```