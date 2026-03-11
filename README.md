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

# Server Metrics 2026-03-11 17:42:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2506.5 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10696
telemt_connections_bad_total 584
telemt_handshake_timeouts_total 61
telemt_upstream_connect_attempt_total 9621
telemt_upstream_connect_success_total 9618
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 9621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9616
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 205067170 (195.57 MB)
telemt_user_octets_to_client{user="hello"} 6828459571 (6.36 GB)
telemt_user_msgs_from_client{user="hello"} 215099
telemt_user_msgs_to_client{user="hello"} 482733
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2494.8 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5805
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 5263
telemt_upstream_connect_success_total 5262
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5260
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 68286182 (65.12 MB)
telemt_user_octets_to_client{user="hello"} 3560903999 (3.32 GB)
telemt_user_msgs_from_client{user="hello"} 115694
telemt_user_msgs_to_client{user="hello"} 1423434
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 2514.3 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6093
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 5642
telemt_upstream_connect_success_total 5641
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 618
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5639
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 44475557 (42.42 MB)
telemt_user_octets_to_client{user="hello"} 2230767179 (2.08 GB)
telemt_user_msgs_from_client{user="hello"} 110814
telemt_user_msgs_to_client{user="hello"} 670368
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2510.0 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5623
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 5233
telemt_upstream_connect_success_total 5219
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5217
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 246269490 (234.86 MB)
telemt_user_octets_to_client{user="hello"} 2374288254 (2.21 GB)
telemt_user_msgs_from_client{user="hello"} 157169
telemt_user_msgs_to_client{user="hello"} 567694
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2518.2 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6498
telemt_connections_bad_total 554
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 5744
telemt_upstream_connect_success_total 5744
telemt_upstream_connect_attempts_per_request{bucket="1"} 5744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5742
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 36459231 (34.77 MB)
telemt_user_octets_to_client{user="hello"} 787318069 (750.85 MB)
telemt_user_msgs_from_client{user="hello"} 76792
telemt_user_msgs_to_client{user="hello"} 271136
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 77124.5 (21h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495
telemt_connections_bad_total 471
telemt_handshake_timeouts_total 14
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