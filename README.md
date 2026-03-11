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

# Server Metrics 2026-03-11 18:53:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6814.5 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27741
telemt_connections_bad_total 1533
telemt_handshake_timeouts_total 125
telemt_upstream_connect_attempt_total 24972
telemt_upstream_connect_success_total 24966
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 24972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24964
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 663448838 (632.71 MB)
telemt_user_octets_to_client{user="hello"} 15841028694 (14.75 GB)
telemt_user_msgs_from_client{user="hello"} 623792
telemt_user_msgs_to_client{user="hello"} 1182929
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 6802.8 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13228
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 234
telemt_upstream_connect_attempt_total 11917
telemt_upstream_connect_success_total 11916
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 262
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11914
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 181508516 (173.10 MB)
telemt_user_octets_to_client{user="hello"} 7565487789 (7.05 GB)
telemt_user_msgs_from_client{user="hello"} 279676
telemt_user_msgs_to_client{user="hello"} 2845809
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 6822.2 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15236
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 113
telemt_upstream_connect_attempt_total 14248
telemt_upstream_connect_success_total 14246
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 14248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14244
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 149933421 (142.99 MB)
telemt_user_octets_to_client{user="hello"} 5676386706 (5.29 GB)
telemt_user_msgs_from_client{user="hello"} 292381
telemt_user_msgs_to_client{user="hello"} 1635341
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 6817.9 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15361
telemt_connections_bad_total 994
telemt_handshake_timeouts_total 218
telemt_upstream_connect_attempt_total 13589
telemt_upstream_connect_success_total 13552
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 13589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13550
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 498591968 (475.49 MB)
telemt_user_octets_to_client{user="hello"} 8696001126 (8.10 GB)
telemt_user_msgs_from_client{user="hello"} 363774
telemt_user_msgs_to_client{user="hello"} 2019591
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 6826.1 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16757
telemt_connections_bad_total 1350
telemt_handshake_timeouts_total 85
telemt_upstream_connect_attempt_total 14831
telemt_upstream_connect_success_total 14830
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14828
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 267613922 (255.22 MB)
telemt_user_octets_to_client{user="hello"} 3924975000 (3.66 GB)
telemt_user_msgs_from_client{user="hello"} 303395
telemt_user_msgs_to_client{user="hello"} 1159400
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 81432.6 (22h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 514
telemt_connections_bad_total 488
telemt_handshake_timeouts_total 16
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