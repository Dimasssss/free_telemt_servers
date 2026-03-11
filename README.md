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

# Server Metrics 2026-03-11 03:12:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 45966.7 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119524
telemt_connections_bad_total 3363
telemt_handshake_timeouts_total 2583
telemt_upstream_connect_attempt_total 108118
telemt_upstream_connect_success_total 108079
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 108118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108073
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 2930537811 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 82138723010 (76.50 GB)
telemt_user_msgs_from_client{user="hello"} 2975856
telemt_user_msgs_to_client{user="hello"} 5684398
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 45966.0 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49863
telemt_connections_bad_total 388
telemt_handshake_timeouts_total 2921
telemt_upstream_connect_attempt_total 43895
telemt_upstream_connect_success_total 43886
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43882
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 2288926818 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 42280050008 (39.38 GB)
telemt_user_msgs_from_client{user="hello"} 1771771
telemt_user_msgs_to_client{user="hello"} 10225193
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 45965.7 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70198
telemt_connections_bad_total 660
telemt_handshake_timeouts_total 4207
telemt_upstream_connect_attempt_total 61419
telemt_upstream_connect_success_total 61417
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 61419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6871
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61411
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 11744340602 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70051053676 (65.24 GB)
telemt_user_msgs_from_client{user="hello"} 5133317
telemt_user_msgs_to_client{user="hello"} 13148173
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 45964.7 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69929
telemt_connections_bad_total 149
telemt_handshake_timeouts_total 551
telemt_upstream_connect_attempt_total 66907
telemt_upstream_connect_success_total 66750
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 66907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8445
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66744
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 1766807398 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 42720829890 (39.79 GB)
telemt_user_msgs_from_client{user="hello"} 1603202
telemt_user_msgs_to_client{user="hello"} 8394764
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 45966.1 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107658
telemt_connections_bad_total 10525
telemt_handshake_timeouts_total 1531
telemt_upstream_connect_attempt_total 91634
telemt_upstream_connect_success_total 91386
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 91634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91382
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 2222821415 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 82150244158 (76.51 GB)
telemt_user_msgs_from_client{user="hello"} 2310657
telemt_user_msgs_to_client{user="hello"} 11092164
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 24935.5 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```