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

# Server Metrics 2026-03-11 22:23:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2323.9 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3824
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 47
telemt_upstream_connect_attempt_total 3688
telemt_upstream_connect_success_total 3687
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 426
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3685
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 39961705 (38.11 MB)
telemt_user_octets_to_client{user="hello"} 2083913622 (1.94 GB)
telemt_user_msgs_from_client{user="hello"} 90796
telemt_user_msgs_to_client{user="hello"} 317886
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2312.5 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1583
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1520
telemt_upstream_connect_success_total 1520
telemt_upstream_connect_attempts_per_request{bucket="1"} 1520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1518
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 8965451 (8.55 MB)
telemt_user_octets_to_client{user="hello"} 228209443 (217.64 MB)
telemt_user_msgs_from_client{user="hello"} 21721
telemt_user_msgs_to_client{user="hello"} 98669
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 2286.0 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3752
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 2846
telemt_upstream_connect_success_total 2846
telemt_upstream_connect_attempts_per_request{bucket="1"} 2846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 334
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2844
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 16547310 (15.78 MB)
telemt_user_octets_to_client{user="hello"} 1409626580 (1.31 GB)
telemt_user_msgs_from_client{user="hello"} 51355
telemt_user_msgs_to_client{user="hello"} 438613
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2311.3 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2505
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 2362
telemt_upstream_connect_success_total 2359
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2357
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 24573807 (23.44 MB)
telemt_user_octets_to_client{user="hello"} 753053772 (718.17 MB)
telemt_user_msgs_from_client{user="hello"} 36937
telemt_user_msgs_to_client{user="hello"} 291087
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2312.7 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2462
telemt_connections_bad_total 449
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1978
telemt_upstream_connect_success_total 1978
telemt_upstream_connect_attempts_per_request{bucket="1"} 1978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1976
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 19421339 (18.52 MB)
telemt_user_octets_to_client{user="hello"} 1072782805 (1023.09 MB)
telemt_user_msgs_from_client{user="hello"} 28223
telemt_user_msgs_to_client{user="hello"} 192088
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 2312.2 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2336
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 2115
telemt_upstream_connect_success_total 2115
telemt_upstream_connect_attempts_per_request{bucket="1"} 2115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 375
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2113
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 49548909 (47.25 MB)
telemt_user_octets_to_client{user="hello"} 6105955999 (5.69 GB)
telemt_user_msgs_from_client{user="hello"} 70302
telemt_user_msgs_to_client{user="hello"} 323019
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 8
```