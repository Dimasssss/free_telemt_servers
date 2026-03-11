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

# Server Metrics 2026-03-11 17:31:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1891.9 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7906
telemt_connections_bad_total 440
telemt_handshake_timeouts_total 44
telemt_upstream_connect_attempt_total 7150
telemt_upstream_connect_success_total 7148
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7146
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 156909926 (149.64 MB)
telemt_user_octets_to_client{user="hello"} 4241344770 (3.95 GB)
telemt_user_msgs_from_client{user="hello"} 160494
telemt_user_msgs_to_client{user="hello"} 320561
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 1880.3 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4327
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 87
telemt_upstream_connect_attempt_total 3903
telemt_upstream_connect_success_total 3902
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3900
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 30656869 (29.24 MB)
telemt_user_octets_to_client{user="hello"} 2751013166 (2.56 GB)
telemt_user_msgs_from_client{user="hello"} 77364
telemt_user_msgs_to_client{user="hello"} 1085254
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 1899.7 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4373
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 4168
telemt_upstream_connect_success_total 4168
telemt_upstream_connect_attempts_per_request{bucket="1"} 4168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 435
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4166
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 31117477 (29.68 MB)
telemt_user_octets_to_client{user="hello"} 1238344987 (1.15 GB)
telemt_user_msgs_from_client{user="hello"} 75877
telemt_user_msgs_to_client{user="hello"} 397752
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 1895.4 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4424
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 4078
telemt_upstream_connect_success_total 4066
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 4078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4064
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 162728595 (155.19 MB)
telemt_user_octets_to_client{user="hello"} 1646131018 (1.53 GB)
telemt_user_msgs_from_client{user="hello"} 110928
telemt_user_msgs_to_client{user="hello"} 419632
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1903.6 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5049
telemt_connections_bad_total 440
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 4448
telemt_upstream_connect_success_total 4448
telemt_upstream_connect_attempts_per_request{bucket="1"} 4448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4446
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 27454334 (26.18 MB)
telemt_user_octets_to_client{user="hello"} 553876109 (528.22 MB)
telemt_user_msgs_from_client{user="hello"} 55254
telemt_user_msgs_to_client{user="hello"} 203013
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 76510.0 (21h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494
telemt_connections_bad_total 470
telemt_handshake_timeouts_total 13
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