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

# Server Metrics 2026-03-12 02:28:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17011.5 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33451
telemt_connections_bad_total 1907
telemt_handshake_timeouts_total 274
telemt_upstream_connect_attempt_total 29766
telemt_upstream_connect_success_total 29759
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 29766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29757
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 288359278 (275.00 MB)
telemt_user_octets_to_client{user="hello"} 9670810206 (9.01 GB)
telemt_user_msgs_from_client{user="hello"} 495934
telemt_user_msgs_to_client{user="hello"} 1213529
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16999.8 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14075
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 13472
telemt_upstream_connect_success_total 13472
telemt_upstream_connect_attempts_per_request{bucket="1"} 13472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13470
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 94275721 (89.91 MB)
telemt_user_octets_to_client{user="hello"} 6023365891 (5.61 GB)
telemt_user_msgs_from_client{user="hello"} 230678
telemt_user_msgs_to_client{user="hello"} 1729851
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 16973.3 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23260
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 892
telemt_upstream_connect_attempt_total 19979
telemt_upstream_connect_success_total 19979
telemt_upstream_connect_attempts_per_request{bucket="1"} 19979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19977
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 5077314714 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 12379158203 (11.53 GB)
telemt_user_msgs_from_client{user="hello"} 2112487
telemt_user_msgs_to_client{user="hello"} 2488268
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16998.8 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25436
telemt_connections_bad_total 8429
telemt_handshake_timeouts_total 700
telemt_upstream_connect_attempt_total 15580
telemt_upstream_connect_success_total 15540
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 15580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2144
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15536
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 128500580 (122.55 MB)
telemt_user_octets_to_client{user="hello"} 8409396148 (7.83 GB)
telemt_user_msgs_from_client{user="hello"} 260089
telemt_user_msgs_to_client{user="hello"} 3181156
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 16999.6 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18486
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 16964
telemt_upstream_connect_success_total 16964
telemt_upstream_connect_attempts_per_request{bucket="1"} 16964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16962
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 420987433 (401.48 MB)
telemt_user_octets_to_client{user="hello"} 22275241385 (20.75 GB)
telemt_user_msgs_from_client{user="hello"} 534066
telemt_user_msgs_to_client{user="hello"} 2537732
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```