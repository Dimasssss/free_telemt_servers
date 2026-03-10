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

# Server Metrics 2026-03-10 23:48:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 33746.5 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100205
telemt_connections_bad_total 3323
telemt_handshake_timeouts_total 2305
telemt_upstream_connect_attempt_total 90112
telemt_upstream_connect_success_total 90080
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 90112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90076
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 2627778573 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 73685660970 (68.63 GB)
telemt_user_msgs_from_client{user="hello"} 2618115
telemt_user_msgs_to_client{user="hello"} 5028216
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 33745.9 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39145
telemt_connections_bad_total 337
telemt_handshake_timeouts_total 925
telemt_upstream_connect_attempt_total 35578
telemt_upstream_connect_success_total 35569
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 35578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35565
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 1989652172 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 38102285592 (35.49 GB)
telemt_user_msgs_from_client{user="hello"} 1556964
telemt_user_msgs_to_client{user="hello"} 9383695
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 33745.8 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61992
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 4083
telemt_upstream_connect_attempt_total 53899
telemt_upstream_connect_success_total 53897
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 53899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53893
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 1083604037 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 56014104875 (52.17 GB)
telemt_user_msgs_from_client{user="hello"} 1261473
telemt_user_msgs_to_client{user="hello"} 8245802
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 33744.6 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58286
telemt_connections_bad_total 90
telemt_handshake_timeouts_total 514
telemt_upstream_connect_attempt_total 55791
telemt_upstream_connect_success_total 55639
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 55791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55635
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 837024158 (798.25 MB)
telemt_user_octets_to_client{user="hello"} 37666666815 (35.08 GB)
telemt_user_msgs_from_client{user="hello"} 1152486
telemt_user_msgs_to_client{user="hello"} 7243177
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 33745.8 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84720
telemt_connections_bad_total 8102
telemt_handshake_timeouts_total 1468
telemt_upstream_connect_attempt_total 71933
telemt_upstream_connect_success_total 71685
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 71933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71681
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 2086982897 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 57406223441 (53.46 GB)
telemt_user_msgs_from_client{user="hello"} 1989820
telemt_user_msgs_to_client{user="hello"} 8349720
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 12715.2 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```